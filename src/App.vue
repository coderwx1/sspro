<template>
  <div class="app">
    <div class="note-wrapper">
      <ul>
        <li>
          <h2>note 1</h2>
          <p>
            第一、对于减法而言，减数和被减数翻转以后，得到的新的差和原来的差是互为相反数的。与之对应，在除法当中，如果除数和被除数的位置颠倒了，得到的商和原来的商就互为倒数。<br />
            第二、如果一个数字要减去多个数，减数的位置可以任意移动；如果一个数字要连续除以多个数，除数的位置也可以任意移动。<br />
            第三、即使减法和加法混合运算，它们的位置也是可以随意调整的，因为我们可以把减去一个正数看作是加上一个负数。同样，除法有类似的性质。<br />
            在一个加减法混合运算的算式中，如果是减数移动到算式的第一位，那么应该把减数变为它的相反数。同理，一个由乘除法组成的混合算式，如果一个除数移动到算式的第一位，那么除数应该变成自己的倒数。
          </p>
          <hr />
          <div class="source-wrapper">
            <span class="source-text">
              note 1 来源：《学好数学并不难》上册 第七章 减法和除法的独特优势：三个共同点
            </span>
          </div>
        </li>
      </ul>
    </div>
  </div>
</template>

<script setup>
import { ref } from "vue";
</script>

<style scoped>
.app {
  width: 375px;
  height: 100%;
}
.note-wrapper {
  padding: 20px;
  letter-spacing: 1.5px;
  text-align: justify;
}

h2 {
  font-size: 25px;
  color: rgb(247, 17, 93);
  padding: 0 0 6px 0;
  margin-bottom: 10px;
  border-bottom: 1px solid black;
}
p {
  font-size: 16px;
}
hr {
  border: none;
  height: 1px;
  background-color: black;
  margin: 10px 0;
}
.source-wrapper {
  /* text-align: right; */
}
.source-text {
  font-size: 13px;
  /* rgb(255, 0, 179) */
  color: rgb(241, 18, 18);
}
</style>
