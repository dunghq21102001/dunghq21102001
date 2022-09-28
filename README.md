- 👋 Hi, I’m @dunghq21102001
- 👀 I’m interested in Web design and web developer
- 🌱 I’m currently learning reactJS, nextJS
<h2 align="center">🛠 Technologies and Tools 🛠</h2>
<br>
<!-- https://simpleicons.org/ -->
<span><img src="https://img.shields.io/badge/JavaScript-282C34?logo=javascript&logoColor=F7DF1E" alt="JavaScript logo" title="JavaScript" height="25" /></span>
&nbsp;
<span><img src="https://img.shields.io/badge/ReactJS-282C34?logo=react&logoColor=61DAFB" alt="ReactJS logo" title="ReactJS" height="25" /></span>
&nbsp;
<span><img src="https://img.shields.io/badge/Redux-282C34?logo=redux&logoColor=764ABC" alt="Redux logo" title="Redux" height="25" /></span>
&nbsp;
<span><img src="https://img.shields.io/badge/Node.js-282C34?logo=node.js&logoColor=00F200" alt="Node.js logo" title="Node.js" height="25" /></span>
&nbsp;
<span><img src="https://img.shields.io/badge/Express-282C34?logo=express&logoColor=FFFFFF" alt="Express.js logo" title="Express.js" height="25" /></span>
&nbsp;
<span><img src="https://img.shields.io/badge/MongoDB-282C34?logo=mongodb&logoColor=47A248" alt="MongoDB logo" title="MongoDB" height="25" /></span>
&nbsp;
<span><img src="https://img.shields.io/badge/Tailwind%20CSS-282C34?logo=tailwind-css&logoColor=38B2AC" alt="TailwindCSS logo" title="TailwindCSS" height="25" /></span>
&nbsp;
<span><img src="https://img.shields.io/badge/HTML5-282C34?logo=html5&logoColor=E34F26" alt="HTML5 logo" title="HTML5" height="25" /></span>
&nbsp;
<span><img src="https://img.shields.io/badge/CSS3-282C34?logo=css3&logoColor=1572B6" alt="CSS3 logo" title="CSS3" height="25" /></span>
&nbsp;
<span><img src="https://img.shields.io/badge/Sass-282C34?logo=sass&logoColor=CC6699" alt="SASS logo" title="SASS" height="25" /></span>
&nbsp;
<span><img src="https://img.shields.io/badge/Bootstrap-282C34?logo=bootstrap&logoColor=7952B3" alt="Bootstrap logo" title="Bootstrap" height="25" /></span>
&nbsp;
<span><img src="https://img.shields.io/badge/ESLint-282C34?logo=eslint&logoColor=4B32C3" alt="ESLint logo" title="ESLint" height="25" /></span>
&nbsp;
<span><img src="https://img.shields.io/badge/git-282C34?logo=git&logoColor=F05032" alt="git logo" title="git" height="25" /></span>
&nbsp;
<span><img src="https://img.shields.io/badge/VS%20Code-282C34?logo=visual-studio-code&logoColor=007ACC" alt="Visual Studio Code logo" title="Visual Studio Code" height="25" /></span>
&nbsp;
<span><img src="https://img.shields.io/badge/Firebase-282C34?logo=firebase&logoColor=FFCA28" alt="Firebase logo" title="Firebase" height="25" /></span>
&nbsp;

<div class="loop-wrapper">
  <div class="mountain"></div>
  <div class="hill"></div>
  <div class="tree"></div>
  <div class="tree"></div>
  <div class="tree"></div>
  <div class="rock"></div>
  <div class="truck"></div>
  <div class="wheels"></div>
</div> 
<style>
.loop-wrapper {
  margin: 0 auto;
  position: relative;
  display: block;
  width: 600px;
  height: 250px;
  overflow: hidden;
  border-bottom: 3px solid #fff;
  color: #fff;
}
.mountain {
  position: absolute;
  right: -900px;
  bottom: -20px;
  width: 2px;
  height: 2px;
  box-shadow: 
    0 0 0 50px #4DB6AC,
    60px 50px 0 70px #4DB6AC,
    90px 90px 0 50px #4DB6AC,
    250px 250px 0 50px #4DB6AC,
    290px 320px 0 50px #4DB6AC,
    320px 400px 0 50px #4DB6AC
    ;
  transform: rotate(130deg);
  animation: mtn 20s linear infinite;
}
.hill {
  position: absolute;
  right: -900px;
  bottom: -50px;
  width: 400px;
  border-radius: 50%;
  height: 20px;
  box-shadow: 
    0 0 0 50px #4DB6AC,
    -20px 0 0 20px #4DB6AC,
    -90px 0 0 50px #4DB6AC,
    250px 0 0 50px #4DB6AC,
    290px 0 0 50px #4DB6AC,
    620px 0 0 50px #4DB6AC;
  animation: hill 4s 2s linear infinite;
}
.tree, .tree:nth-child(2), .tree:nth-child(3) {
  position: absolute;
  height: 100px; 
  width: 35px;
  bottom: 0;
  background: url(https://s3-us-west-2.amazonaws.com/s.cdpn.io/130015/tree.svg) no-repeat;
}
.rock {
  margin-top: -17%;
  height: 2%; 
  width: 2%;
  bottom: -2px;
  border-radius: 20px;
  position: absolute;
  background: #ddd;
}
.truck, .wheels {
  transition: all ease;
  width: 85px;
  margin-right: -60px;
  bottom: 0px;
  right: 50%;
  position: absolute;
  background: #eee;
}
.truck {
  background: url(https://s3-us-west-2.amazonaws.com/s.cdpn.io/130015/truck.svg) no-repeat;
  background-size: contain;
  height: 60px;
}
.truck:before {
  content: " ";
  position: absolute;
  width: 25px;
  box-shadow:
    -30px 28px 0 1.5px #fff,
     -35px 18px 0 1.5px #fff;
}
.wheels {
  background: url(https://s3-us-west-2.amazonaws.com/s.cdpn.io/130015/wheels.svg) no-repeat;
  height: 15px;
  margin-bottom: 0;
}

.tree  { animation: tree 3s 0.000s linear infinite; }
.tree:nth-child(2)  { animation: tree2 2s 0.150s linear infinite; }
.tree:nth-child(3)  { animation: tree3 8s 0.050s linear infinite; }
.rock  { animation: rock 4s   -0.530s linear infinite; }
.truck  { animation: truck 4s   0.080s ease infinite; }
.wheels  { animation: truck 4s   0.001s ease infinite; }
.truck:before { animation: wind 1.5s   0.000s ease infinite; }


@keyframes tree {
  0%   { transform: translate(1350px); }
  50% {}
  100% { transform: translate(-50px); }
}
@keyframes tree2 {
  0%   { transform: translate(650px); }
  50% {}
  100% { transform: translate(-50px); }
}
@keyframes tree3 {
  0%   { transform: translate(2750px); }
  50% {}
  100% { transform: translate(-50px); }
}

@keyframes rock {
  0%   { right: -200px; }
  100% { right: 2000px; }
}
@keyframes truck {
  0%   { }
  6%   { transform: translateY(0px); }
  7%   { transform: translateY(-6px); }
  9%   { transform: translateY(0px); }
  10%   { transform: translateY(-1px); }
  11%   { transform: translateY(0px); }
  100%   { }
}
@keyframes wind {
  0%   {  }
  50%   { transform: translateY(3px) }
  100%   { }
}
@keyframes mtn {
  100% {
    transform: translateX(-2000px) rotate(130deg);
  }
}
@keyframes hill {
  100% {
    transform: translateX(-2000px);
  }
}


</style>


<h2 align="center">🔥 GitHub Stats 🔥</h2>
<br>

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=dunghq21102001&show_icons=true&theme=tokyonight)
&nbsp;
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=dunghq21102001&layout=compact&hide=Less,SCSS)](https://github.com/dunghq21102001/)


<h2 align="center">How to connect with me</h2>
<br>
<div align="center">
  <a href="https://www.facebook.com/dungx.quoc.2125109" target="blank">
    <img src="https://img.icons8.com/bubbles/100/000000/facebook-new.png" alt="dunghq-facebook" />
  </a>
  <a href="https://www.instagram.com/dunghq21/" target="blank">
    <img src="https://img.icons8.com/bubbles/100/000000/instagram.png" alt="dunghq-instagram" />
  </a>
  <a href="https://mail.google.com/mail/u/0/#inbox" target="top">
    <img src="https://img.icons8.com/bubbles/100/000000/apple-mail.png" alt="dunghq-email" />
  </a>
</div>

