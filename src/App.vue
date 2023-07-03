<template>
  <div class="app">
    <div class="note-wrapper">
      <ul>
        <li>
          <h2>note 1</h2>
          <div>
            <p>
              第一、对于减法而言，减数和被减数翻转以后，得到的新的差和原来的差是互为相反数的。与之对应，在除法当中，如果除数和被除数的位置颠倒了，得到的商和原来的商就互为倒数。<br />
              第二、如果一个数字要减去多个数，减数的位置可以任意移动；如果一个数字要连续除以多个数，除数的位置也可以任意移动。<br />
              第三、即使减法和加法混合运算，它们的位置也是可以随意调整的，因为我们可以把减去一个正数看作是加上一个负数。同样，除法有类似的性质。<br />
            </p>
            <p>
              在一个加减法混合运算的算式中，如果是减数移动到算式的第一位，那么应该把减数变为它的相反数。同理，一个由乘除法组成的混合算式，如果一个除数移动到算式的第一位，那么除数应该变成自己的倒数。
            </p>
          </div>

          <hr />
          <div class="source-wrapper">
            <span class="source-content">
              note 1 来源：《学好数学并不难》上册 第七章
              减法和除法的独特优势：三个共同点
            </span>
          </div>
        </li>

        <li>
          <h2>note 2</h2>
          <div>
            <p>
              同底数幂相乘，底数不变，指数相加。<br />
              <span class="example"> 示例：a^m × a^n ＝a^m ＋ n </span>
            </p>
            <p>
              同底数的幂相除，底数不变，指数相减。<br />
              <span class="example"> 示例：a^m ÷a^n ＝a^m － n </span>
            </p>
            <p>当指数是负数的时候，结果等于正数幂的倒数。</p>
            <p>
              任何数的1次方都等于它自己，而除了0以外的任何数的0次方都等于1。
            </p>
          </div>

          <hr />
          <div class="source-wrapper">
            <span class="source-content">
              note 2 来源：《学好数学并不难》上册 第十章
              同底数幂的乘除：四个运算规则
            </span>
          </div>
        </li>

        <li>
          <h2>note 3</h2>
          <div>
            <p>
              同指数的幂相乘，指数不变，底数相乘。<br />
              <span class="example"> 示例：a^n × b^n ＝（ab ）^n </span> <br />
              由于乘方的结果叫幂，相乘的结果叫积，因此这个口诀也被简称为幂的积等于积的幂，同理，积的幂也等于幂的积。<br />
              比如：（2x）^4 ＝？因为2x
              是2和x的乘积，积的幂等于幂的积，因此（2x）^4 ＝2^4 × x^4
              ，由于2的4次方等于16，因此结果为16x 4。<br />
            </p>
            <p>
              商的幂等于幂的商<br />
              比如（3/x）^2
              此题处理的是分数的乘方，商的幂等于幂的商，直接把2次方扔到分子分母上，得到
              3^2 / x^2 = 9/x^2
            </p>
            <p>
              幂的乘方，底数不变，指数相乘。<br />
              <span class="example"> 示例：（a^m）^n ＝a^mn </span> <br />
              <span>
                题型：（4y^2 ）^3
                ＝？解决问题的关键是要把系数4搞清楚，要知道4y^2 ＝4 × y × y
                ，所以y 的指数2，这个2是y
                自我相乘的次数，跟系数4没关系，但是整个算式的3次方，既是4的3次方，也是y2
                的3次方，整个算式符合积的幂的运算法则，因此原式等于4^3
                ×（y^2）^3 ，后者符合幂的乘方法则，指数相乘得到4^3 × y^2×3
                ，进一步化简，得到64y^6。
              </span>
            </p>
          </div>

          <hr />
          <div class="source-wrapper">
            <span class="source-content">
              note 3 来源：《学好数学并不难》上册 第十章
              幂的乘方：商的幂等于幂的商
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
  height: 100%;
  padding: 20px;
  letter-spacing: 1.5px;
  text-align: justify;
}

h2 {
  font-size: 25px;
  /* rgb(247, 17, 93) */
  color: rgb(238, 32, 101);
  padding: 0 0 6px 0;
  margin-bottom: 10px;
  border-bottom: 1px solid black;
}
p {
  font-size: 16px;
  margin-bottom: 15px;
}

p::before {
  content: "";
  display: inline-block;
  width: 10px;
  height: 10px;

  background-color: black;
  border-radius: 50%;
}
hr {
  border: none;
  height: 1px;
  background-color: black;
  margin: 10px 0;
}

.example {
  display: inline-block;
  width: 100%;
  padding: 15px;
  font-size: 13px;
  color: rgb(66, 185, 131);
  background-color: #f8f8f8;
  margin: 10px 0;
}
.source-wrapper {
  margin-bottom: 20px;
}
.source-content {
  font-size: 13px;
  /* rgb(255, 0, 179) */
  color: #c08b30;
}
</style>
