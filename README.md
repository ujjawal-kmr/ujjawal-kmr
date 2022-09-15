<style>
.programmer{
font-size:5px; /* Control the size of your element */ 

position : absolute;
left     : 50%;
top      : 50%;
width    : 22em;
height   : 15em;
margin   : -7.5em 0 0 -11em;}

.programmer::before,
.programmer::after{
content : '';
display : block;
width   : 1em;
height  : 1em;
margin  : -1em 0 0 -1em;
}

.programmer::before{/*This is the animated area of the element*/ 
animation: animate 2000ms steps(1) infinite;
}

@keyframes animate {
0%, 100% {box-shadow:8em 5em #070307,8em 4em #070307,6em 4em #070307,6em 5em #070307,4em 4em #070307,4em 5em #070307,4em 8em #303030,4em 9em #303030,4em 10em #303030,4em 11em #303030,4em 12em #303030,4em 13em #303030,5em 13em #303030,6em 13em #303030,7em 13em #303030,5em 9em #303030,5em 10em #303030,5em 11em #303030,5em 12em #303030,6em 12em #303030,6em 11em #303030,5em 8em #303030,6em 8em #303030,7em 8em #303030,8em 8em #303030,8em 9em #303030,7em 9em #303030,6em 9em #303030,6em 10em #303030,7em 10em #303030,8em 10em #303030,8em 11em #303030,7em 11em #303030,7em 12em #303030,8em 12em #303030,8em 13em #303030,8em 14em #303030,7em 14em #303030,6em 14em #303030,5em 14em #303030,4em 14em #303030}
10% {box-shadow:8em 5em #070307,8em 4em #595959,6em 4em #070307,6em 5em #070307,4em 4em #595959,4em 5em #070307,4em 9em #303030,4em 10em #303030,4em 11em #303030,4em 12em #303030,4em 13em #303030,5em 13em #303030,6em 13em #303030,7em 13em #303030,5em 9em #303030,5em 10em #303030,5em 11em #303030,5em 12em #303030,6em 12em #303030,6em 11em #303030,8em 9em #303030,7em 9em #303030,6em 9em #303030,6em 10em #303030,7em 10em #303030,8em 10em #303030,8em 11em #303030,7em 11em #303030,7em 12em #303030,8em 12em #303030,8em 13em #303030,8em 14em #303030,7em 14em #303030,6em 14em #303030,5em 14em #303030,4em 14em #303030,15em 11em #570e57,16em 11em #570e57,18em 11em #570e57,19em 11em #570e57,20em 11em #570e57,17em 11em #570e57,14em 11em #570e57,13em 11em #570e57}
20% {box-shadow:8em 5em #595959,6em 4em #595959,6em 5em #070307,4em 5em #595959,4em 10em #303030,4em 11em #303030,4em 12em #303030,4em 13em #303030,5em 13em #303030,6em 13em #303030,7em 13em #303030,5em 10em #303030,5em 11em #303030,5em 12em #303030,6em 12em #303030,6em 11em #303030,6em 10em #303030,7em 10em #303030,8em 10em #303030,8em 11em #303030,7em 11em #303030,7em 12em #303030,8em 12em #303030,8em 13em #303030,8em 14em #303030,7em 14em #303030,6em 14em #303030,5em 14em #303030,4em 14em #303030,14em 9em #570e57,15em 9em #570e57,16em 9em #570e57,17em 9em #570e57,18em 9em #570e57,19em 9em #570e57,20em 9em #570e57,15em 11em #4e4e9c,16em 11em #4e4e9c,17em 11em #4e4e9c,18em 11em #4e4e9c,19em 11em #4e4e9c,20em 11em #4e4e9c,13em 9em #570e57}
30% {box-shadow:8em 5em #595959,6em 5em #595959,4em 5em #595959,4em 11em #303030,4em 12em #303030,4em 13em #303030,5em 13em #303030,6em 13em #303030,7em 13em #303030,5em 11em #303030,5em 12em #303030,6em 12em #303030,6em 11em #303030,8em 11em #303030,7em 11em #303030,7em 12em #303030,8em 12em #303030,8em 13em #303030,8em 14em #303030,7em 14em #303030,6em 14em #303030,5em 14em #303030,4em 14em #303030,15em 9em #4e4e9c,16em 9em #4e4e9c,17em 9em #4e4e9c,18em 9em #4e4e9c,19em 9em #4e4e9c,20em 9em #4e4e9c,20em 7em #570e57,19em 7em #570e57,18em 7em #570e57,17em 7em #570e57,16em 7em #570e57,15em 7em #570e57,14em 7em #570e57,14em 11em #225c24,15em 11em #225c24,16em 11em #225c24,17em 11em #225c24,18em 11em #225c24,19em 11em #225c24,20em 11em #225c24,13em 11em #225c24,12em 11em #225c24,13em 7em #570e57,6em 3em #070307}
40% {box-shadow:4em 12em #303030,4em 13em #303030,5em 13em #303030,6em 13em #303030,7em 13em #303030,5em 12em #303030,6em 12em #303030,7em 12em #303030,8em 12em #303030,8em 13em #303030,8em 14em #303030,7em 14em #303030,6em 14em #303030,5em 14em #303030,4em 14em #303030,13em 5em #570e57,14em 5em #570e57,15em 5em #570e57,16em 5em #570e57,17em 5em #570e57,18em 5em #570e57,19em 5em #570e57,20em 5em #570e57,20em 7em #4e4e9c,19em 7em #4e4e9c,18em 7em #4e4e9c,17em 7em #4e4e9c,16em 7em #4e4e9c,15em 7em #4e4e9c,20em 9em #225c24,19em 9em #225c24,18em 9em #225c24,17em 9em #225c24,16em 9em #225c24,15em 9em #225c24,14em 9em #225c24,13em 9em #225c24,12em 9em #225c24,20em 11em #000000,18em 11em #000000,16em 11em #000000,14em 11em #000000,12em 11em #000000,6em 3em #070307,6em 4em #070307,6em 5em #070307}
50% {box-shadow:4em 13em #303030,5em 13em #303030,6em 13em #303030,7em 13em #303030,8em 13em #303030,8em 14em #303030,7em 14em #303030,6em 14em #303030,5em 14em #303030,4em 14em #303030,13em 5em #570e57,14em 5em #570e57,15em 5em #570e57,16em 5em #570e57,17em 5em #570e57,18em 5em #570e57,19em 5em #570e57,20em 5em #570e57,20em 7em #4e4e9c,19em 7em #4e4e9c,18em 7em #4e4e9c,17em 7em #4e4e9c,16em 7em #4e4e9c,15em 7em #4e4e9c,20em 9em #225c24,19em 9em #225c24,18em 9em #225c24,17em 9em #225c24,16em 9em #225c24,15em 9em #225c24,14em 9em #225c24,13em 9em #225c24,12em 9em #225c24,11em 11em #000000,13em 11em #000000,15em 11em #000000,17em 11em #000000,19em 11em #000000,6em 3em #070307,6em 4em #070307,6em 5em #070307}
60% {box-shadow:8em 14em #303030,7em 14em #303030,6em 14em #303030,5em 14em #303030,4em 14em #303030,13em 5em #570e57,14em 5em #570e57,15em 5em #570e57,16em 5em #570e57,17em 5em #570e57,18em 5em #570e57,19em 5em #570e57,20em 5em #570e57,20em 7em #4e4e9c,19em 7em #4e4e9c,18em 7em #4e4e9c,17em 7em #4e4e9c,16em 7em #4e4e9c,15em 7em #4e4e9c,20em 9em #225c24,19em 9em #225c24,18em 9em #225c24,17em 9em #225c24,16em 9em #225c24,15em 9em #225c24,14em 9em #225c24,13em 9em #225c24,12em 9em #225c24,12em 11em #000000,14em 11em #000000,16em 11em #000000,18em 11em #000000,20em 11em #000000,6em 3em #070307,6em 4em #070307,6em 5em #070307}
70% {box-shadow:15em 11em #225c24,14em 10em #225c24,13em 9em #225c24,12em 8em #225c24,16em 10em #225c24,17em 9em #225c24,18em 8em #225c24,19em 7em #225c24,20em 6em #225c24,19em 6em #225c24,20em 5em #225c24,18em 7em #225c24,17em 8em #225c24,16em 9em #225c24,15em 10em #225c24,14em 9em #225c24,13em 8em #225c24,6em 3em #070307,6em 4em #070307,6em 5em #070307}
80% {box-shadow:6em 3em #070307,6em 4em #070307,6em 5em #070307}
90% {box-shadow:15em 11em #225c24,14em 10em #225c24,13em 9em #225c24,12em 8em #225c24,16em 10em #225c24,17em 9em #225c24,18em 8em #225c24,19em 7em #225c24,20em 6em #225c24,19em 6em #225c24,20em 5em #225c24,18em 7em #225c24,17em 8em #225c24,16em 9em #225c24,15em 10em #225c24,14em 9em #225c24,13em 8em #225c24,6em 3em #070307,6em 4em #070307,6em 5em #070307}
}

.programmer::after{ /*This is the static area of the element*/ 
box-shadow:3em 7em #000000,3em 8em #070307,3em 10em #070307,3em 11em #070307,3em 12em #070307,6em 1em #070307,7em 1em #070307,8em 1em #070307,9em 1em #070307,10em 1em #070307,1em 9em #070307,1em 10em #070307,1em 11em #070307,1em 12em #070307,9em 14em #070307,3em 14em #000000,11em 1em #070307,12em 1em #070307,13em 1em #070307,14em 1em #070307,15em 1em #070307,16em 1em #070307,17em 1em #070307,18em 1em #070307,19em 1em #070307,20em 1em #070307,21em 1em #070307,22em 1em #070307,22em 2em #070307,22em 3em #070307,22em 4em #070307,22em 5em #070307,22em 6em #070307,22em 7em #070307,22em 8em #070307,22em 9em #070307,22em 10em #070307,22em 11em #070307,22em 12em #000000,6em 2em #070307,18em 3em #070307,19em 3em #070307,20em 3em #070307,14em 3em #070307,1em 13em #070307,2em 13em #070307,3em 15em #070307,4em 15em #070307,5em 15em #070307,6em 15em #070307,7em 15em #070307,8em 15em #070307,9em 15em #070307,11em 13em #000000,9em 13em #000000,9em 12em #000000,9em 11em #000000,9em 10em #000000,9em 9em #000000,9em 8em #000000,9em 7em #000000,8em 7em #000000,7em 7em #000000,6em 7em #000000,5em 7em #000000,4em 7em #000000,2em 9em #000000,3em 9em #000000,3em 13em #000000,22em 13em #000000,21em 13em #000000,20em 13em #000000,19em 13em #000000,18em 13em #000000,17em 13em #000000,16em 13em #000000,15em 13em #000000,14em 13em #000000,13em 13em #000000,12em 13em #000000,15em 3em #000000,16em 3em #000000;
}

body,html{margin:0;background:#7A8CAB}
q{position:absolute;bottom:50px;width:100%;text-align:center;color:#fff;}
</style>

<div class="programmer"></div>




<h1 align="center">Hi 👋, I'm Ujjawal Kumar</h1>
<h3 align="center">Programmer</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=ujjawal-kmr&label=Profile%20views&color=0e75b6&style=flat" alt="ujjawal-kmr" /> </p>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=ujjawal-kmr" alt="ujjawal-kmr" /></a> </p>

- 🌱 I’m currently learning **JavaScript**

- 💬 Ask me about **Algorithms**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://www.linkedin.com/in/ujjawal1/" target="_blank" rel="noopener noreferrer"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/in/ujjawal1/" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://cloud.google.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/google_cloud/google_cloud-icon.svg" alt="gcp" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> <a href="https://www.php.net" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> </p>

<p><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=ujjawal-kmr&show_icons=true&locale=en&layout=compact" alt="ujjawal-kmr" /></p>
