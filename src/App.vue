<template>
  <div class="home">
    <div class="btns">
      <div class="eml-cell">
        <van-cell-group>
          <van-field
            v-model="eml"
            label="邮箱"
            size="large"
            placeholder="请输入邮箱"
          />
        </van-cell-group>
      </div>
      <div class="btn">
        <van-button type="primary " size="large" @click="sendCode">
          发送验证码
        </van-button>
      </div>
      <div class="captcha-cell">
        <van-cell-group>
          <van-field
            v-model="captcha"
            label="验证码"
            size="large"
            placeholder="请输入验证码"
          />
        </van-cell-group>
      </div>
      <div class="btn">
        <van-button type="primary" size="large" @click="register">
          注册
        </van-button>
      </div>
      <div class="btn">
        <van-button type="primary" size="large" @click="login">
          登陆
        </van-button>
      </div>
      <div class="btn">
        <van-button type="danger" size="large" @click="killUser">
          删除用户
        </van-button>
      </div>
      <div class="btn">
        <van-button type="primary" size="large" @click="buy"> 购买 </van-button>
      </div>
    </div>
    <div class="res-Text">{{ resText }}</div>
  </div>
</template>

<script setup>
import { ref } from "vue";

const BASEURL = `https://vercel-python-sepia-tau.vercel.app`;
let resText = ref("");
let eml = ref("freedomweb@yeah.net");
let captcha = ref("");

function sendCode() {
  if (!eml.value) return;
  const url = `${BASEURL}/send_captcha/${eml.value}`;
  fetch(url)
    .then((response) => response.json())
    .then((data) => {
      console.log(data);
      resText.value = data.msg;
    });
}

function register() {
  if (!eml.value) return;
  const url = `${BASEURL}/register/${eml.value}/${captcha.value}`;
  fetch(url)
    .then((response) => response.json())
    .then((data) => {
      resText.value = data.msg;
      console.log(data);
    });
}

function login() {
  if (!eml.value) return;
  const url = `${BASEURL}/login/${eml.value}`;
  fetch(url)
    .then((response) => response.json())
    .then((data) => {
      resText.value = data.msg;
      console.log(data);
    });
}

function killUser() {
  if (!eml.value) return;
  const url = `${BASEURL}/kill_user/${eml.value}`;
  fetch(url)
    .then((response) => response.json())
    .then((data) => {
      resText.value = data.msg;
      console.log(data);
    });
}

function buy() {
  const url = `${BASEURL}/buy`;
  fetch(url)
    .then((response) => response.text())
    .then((data) => {
      resText.value = data;
      console.log(data);
    });
}
</script>

<style scoped>
.home {
  width: 375px;
  height: 100%;
  background-color: #f7f8fa;
}
.btns {
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  padding: 20px 10px;
}
.btn,
.eml-cell,
.captcha-cell {
  padding: 10px 0;
}

.res-Text {
  padding: 0 10px;
  text-align: center;
  word-wrap: break-word;
}
</style>
