<template>
  <div class="app">
    <div class="note-wrapper">
      <ul>
        <li>
          <h2>Note 1</h2>
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
          <div class="divider-wrapper">
            <div class="divider">
              <i class="note-count">1</i>
            </div>
          </div>

          <div class="source-wrapper">
            <span class="source-content">
              Note 1 来源：《学好数学并不难》上册 第七章 第四节
              减法和除法的独特优势：三个共同点
            </span>
          </div>
        </li>

        <li>
          <h2>Note 2</h2>
          <div>
            <p>
              同底数幂相乘，底数不变，指数相加。<br/>
              <span class="formula">
                公式：\(a^m \ × \ a^n \ = \ a^{m+n} \)
              </span>
            </p>
            <p>
              同底数的幂相除，底数不变，指数相减。<br />
              <span class="formula">
                公式：\(a^m \ ÷ \ a^n \ = \ a^{m-n} \)
              </span>
            </p>
            <p>&nbsp当指数是负数的时候，结果等于正数幂的倒数。</p>
            <p>
              任何数的1次方都等于它自己，而除了0以外的任何数的0次方都等于1。
            </p>
          </div>

          <div class="divider-wrapper">
            <div class="divider">
              <i class="note-count">2</i>
            </div>
          </div>
          <div class="source-wrapper">
            <span class="source-content">
              Note 2 来源：《学好数学并不难》上册 第十章 第二节
              同底数幂的乘除：四个运算规则
            </span>
          </div>
        </li>

        <li>
          <h2>Note 3</h2>
          <div>
            <p>
              同指数的幂相乘，指数不变，底数相乘。<br />
              <span class="formula">
                公式：\(a^n \ × \ b^n \ = \ ( \ ab \ )^n \)
              </span>
              <span class="example">
                由于乘方的结果叫幂，相乘的结果叫积，因此这个口诀也被简称为幂的积等于积的幂，同理，积的幂也等于幂的积。
              </span>
              <br />
              <span class="example">
                例题：\((2x)^4 = ?
                \)，因为2\(x\)是2和\(x\)的乘积，积的幂等于幂的积，因此\((2x)^4 =
                2^4 × x^4 \)，由于2的4次方等于16，因此结果为\(16x^4 \)。
              </span>
            </p>
            <p>
              商的幂等于幂的商。<br />
              <span class="example">
                例题：<i class="fz-19">\( ({3 \over x }) ^2 \)，</i>
                此题处理的是分数的乘方，商的幂等于幂的商，直接把2次方扔到分子分母上，得到:
                <i class="fz-19">
                  \({3^2 \over x^2} = {9 \over x^2} \)
                </i>
              </span>
            </p>
            <p>
              幂的乘方，底数不变，指数相乘。<br />
              <span class="formula">
                公式：\(( \ a^m \ ) \ ^n \ = \ a^{m \ n}\)
              </span>
              <br />
              <span class="example">
                例题：\((4y^2)^3 \ = \ ?
                \)，解决问题的关键是要把系数4搞清楚，要知道 \( \ 4y^2 \ = \ 4 ×
                y × y
                \)，所以y的指数2，这个2是y自我相乘的次数，跟系数4没关系，但是整个算式的3次方，既是4的3次方，也是
                \(y^2\) 的3次方，整个算式符合积的幂的运算法则，因此原式等于\(4^3
                × (y^2)^3 \) ，后者符合幂的乘方法则，指数相乘得到\(4^3 ×
                y^{2×3}\) ，进一步化简，得到\(64y^6\)。
              </span>
            </p>
          </div>

          <div class="divider-wrapper">
            <div class="divider">
              <i class="note-count">3</i>
            </div>
          </div>
          <div class="source-wrapper">
            <span class="source-content">
              Note 3 来源：《学好数学并不难》上册 第十章 第三节
              幂的乘方：商的幂等于幂的商
            </span>
          </div>
        </li>

        <li>
          <h2>Note 4</h2>
          <div>
            <p>
              不等式在左右两边加减任何数字的时候，不等号的方向不变，这个性质对应着不等式的方程移项的功能。
            </p>
            <p>
              不等式左右两边同时乘以或除以一个负数，不等号的方向必须要发生改变。<br />
              <span class="example">
                证明：<i class="example-question">2 > -4</i>
                ，如果不等式两边同时乘以－1会怎么样？左边变成了－2，右边呢，变成了4，－2是小于4的，这时候我们就发现，同乘一个负数，大于号变成了小于号．同样，如果我们把－2＜4这个不等式左右两边同时除以－2，左边就是1，右边是－2，左边就大于右边了。
              </span>
            </p>
          </div>
          <div class="divider-wrapper">
            <div class="divider">
              <i class="note-count">4</i>
            </div>
          </div>
          <div class="source-wrapper">
            <span class="source-content">
              Note 4 来源：《学好数学并不难》上册 第六章 第四节
              不等式的性质：方向的改变
            </span>
          </div>
        </li>

        <li>
          <h2>Note 5</h2>
          <div>
            <p>
              根据幂和指数反推底数的运算，就是乘方的逆运算，叫作开方，开方的结果又叫作方根。
            </p>
            <p>
              当指数是2的时候，可以忽略不写，比如：\(\sqrt{16} \
              \)表示的就是求16的二次方根．要注意的是，16的平方根是有两个的，
              \(\sqrt{16} \
              \)所表示的只是正的那个平方根，它又被称作算术平方根。<br />
            </p>

            <p>
              算术平方根必须是正数或者0。<br />
              <span class="example">
                例题：\(\sqrt{a^2} \ = \ ? \ \) ，这个题目让我们求的是\( \ a^2 \
                \)
                的算术平方根是多少？那我们就要知道根号里面的部分是谁的平方，\( \
                a^2 \ \) 当然就是 a 的平方了，所以这个结果就是a
                ，对不对呢？不对，因为算术平方根必须是正数或者0，而我们根本就不清楚
                a 是正数还是负数或是零。如果这个a
                是小于0的呢？那不就得到负数了吗？所以必须要分情况讨论，要保证它的结果是非负数，开根号的结果就只能是
                a 的绝对值|a|，因此当a ≥ 0的时候，结果是a； 当a ＜
                0呢，结果就是－a ，即\( \sqrt{a^2} =|a| = \begin{cases} a & a
                \ge 0 \\ -a & a &lt 0 \end{cases}\)
              </span>
              <span class="example">
                例题：\(\sqrt{(3-x)^2} \ = \ ? \ \) ，如果3－x ≥
                0，开出来的结果就是3－x ，如果3－x ＜0呢，开出来就是－（3－x
                ），也就是x
                －3，我们需要对以上两个不等式进行化简从而确定x的取值范围。即：<br />
                \(\sqrt{(3-x)^2} \ = \ |3-x| = \begin{cases} 3-x \ge 0,3-x; \\
                3-x &lt 0,x-3. \end{cases}\) <br />
                由 \(3-x \ge 0 \) 得，\(x \le 3 \), <br />
                由 \(3-x &lt 0 \) 得，\(x > 3 \),<br />
                即：<br />
                \( \ \begin{cases} x \le 3 & \sqrt{(3-x)^2}=3-x; \\ x \ge 3 &
                \sqrt{(3-x)^2}=x-3. \end{cases} \)
              </span>
            </p>
          </div>
          <div class="divider-wrapper">
            <div class="divider">
              <i class="note-count">5</i>
            </div>
          </div>
          <div class="source-wrapper">
            <span class="source-content">
              Note 5 来源：《学好数学并不难》上册 第十章 第四节
              乘方的逆运算：六种运算的关系
            </span>
          </div>
        </li>



         <li>
          <h2>Note 6</h2>
          <div>
            <p>
              根号里不能为负数 <br/>
               <span class="example">
                例题：化简<i class="fz-22">\(\sqrt{-{ b^2 \over a}} \)</i>，其中<i class="example-question">b &lt 0</i><br>
                <i style="color:rgb(34, 162, 201);">分析：</i>b 虽然是负数，但是b 经过平方以后，那肯定就是正数了；要想让这个根式有意义，只有a 是负数时，根号里面的内容才可能大于等于0，这个根式才可能成立。因此，我们就得到了a 的取值范围是 <i class="example-question">a &lt 0</i> <br>
                 <i style="color:rgb(233, 105, 0)">解题过程：</i>我们先把分子分母的部分独立拆分出来，得到：<br><i class="fz-22">\(\sqrt{-{ b^2 \over a}}\) = \({\sqrt {b^2} \over {\sqrt {-a}}}  \) </i> <br>再把分子开根号出来，得到：<br><i class="example-question"> | b | </i>，原式 = <i class="fz-22">\( | \ b \ | \over \sqrt {-a} \) </i> <br>
                 为了消去分母上的根号，需要在分子分母同时乘以 <i class="fz-22">\( \sqrt {-a} \)</i> <br> 得到：<br><i class="fz-22"> \(\sqrt{-{ b^2 \over a}} \) = \( -b \sqrt {-a} \over \sqrt {(-a)^2}\) = \( -b \sqrt {-a} \over -a \)</i> <br>消去分子分母的负号，得到：<br><i class="fz-22">\(\sqrt{-{ b^2 \over a}} \) = \( b \sqrt {-a} \over a \)</i>
              </span>
            </p>
          </div>
          <div class="divider-wrapper">
            <div class="divider">
              <i class="note-count">6</i>
            </div>
          </div>
          <div class="source-wrapper">
            <span class="source-content">
              Note 6 来源：《学好数学并不难》上册 第十一章 第三节 根式的运算法则：乘除、乘方及化简方法
            </span>
          </div>
        </li>
      </ul>
    </div>
  </div>
</template>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Lobster&display=swap");

.app {
  width: 375px;
  height: 100%;
  overflow-y: scroll;
}
.note-wrapper {
  padding: 20px;
  letter-spacing: 1.5px;
  text-align: justify;
}

h2 {
  font-size: 26px;
  /* rgb(247, 17, 93) */
  color: rgb(238, 32, 101);
  padding: 0 0 6px 0;
  margin-bottom: 24px;
  border-bottom: 3px solid rgb(245, 55, 118);
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
.divider-wrapper {
  padding: 20px 0;
  font-size: 20px;
  font-family: "Lobster", cursive;
  color: rgb(235, 38, 159);
}

.divider {
  height: 1px;
  background-color: black;
  position: relative;
}

.note-count {
  position: absolute;
  right: 0;
  top: 0;
  transform: translateY(-100%);
}

.formula {
  display: inline-block;
  width: 100%;
  padding: 15px;
  font-size: 13px;
  color: rgb(66, 185, 131);
  background-color: #f8f8f8;
  margin: 10px 0;
}
.fz-19 {
  font-size: 19px;
}
.fz-20 {
  font-size: 20px;
}.fz-21 {
  font-size: 21px;
}.fz-22 {
  font-size: 22px;
}
.example {
  display: inline-block;
  font-size: 14px;
  vertical-align: middle;
  margin: 10px 0;
}
.example .example-question {
  padding: 2px 7px;
  color: #33a06f;
  border-radius: 4px;
  background-color: #f1f1f1;
}
.example::before {
  content: "";
  display: inline-block;
  width: 5px;
  height: 14px;
  vertical-align: text-top;
  background-color: rgb(255, 0, 0);
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
