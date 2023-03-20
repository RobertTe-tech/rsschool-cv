<p align="center"><img src="https://user-images.githubusercontent.com/126411404/223386544-09a12f0c-0af6-4aa7-a8d1-3e33010b3ecb.jpg" width="180" height="255"></p>

<h1 align="center">Robert Krasilnikov</h1>

<p align="center">
<a href="https://t.me/RobertTetech"><img src="https://img.shields.io/badge/-Telegram-ffffff?style=socialge&logo=telegram&logoColor=26A5E4" alt="Telegram"></a>
<a href="https://discordapp.com/users/818597269548826644/"><img src="https://img.shields.io/badge/-Discord-090909?style=social&logo=discord&logoColor=090909" alt="Discord"></a>
<a href="https://github.com/RobertTe-tech"><img src="https://img.shields.io/badge/-GitHub-090909?style=social&logo=GitHub&logoColor=181717" alt="Discord"></a>
</p>

***

<p align="center">I need a web tool to implement my ideas. I am sure that I am able to create a solution algorithm for each task, if there is enough time to think about it.</p>

<p align="center">I know the basic syntax JS, HTML, CSS. Programming in Visual Studio Code.</p>

```JS
function order(words){
  var s = "";
    var arr = [];
    var type = 0;
    
  for(var i = 0; i < words.length; i++) {
      if(words[i] != ' ') s += words[i];
      if(!isNaN(parseFloat(words[i])) && !isNaN(words[i] - 0)) {
          type = words[i];
      }
      if(words[i] == " " || i == (words.length - 1)) {
          arr[type] = s;
          
          s = "";
      }
  }
  s = "";
  arr.forEach(function (word) {
      if(s.length > 0) s += ' ';
      s += word;
  })
  if(s[s.length - 1] == ' ') console.log(s.slice(-1));
  return s;
}
```

***
<h3 align="center">Educational projects</h3>

* <p align="center"><a href="https://robertte-tech.github.io/cssBayan/cssBayan/index.html">CSS Bayan</a>. The first educational project of the school RS. The project was compiled only using HTML and CSS, without using JS. Adaptive arrangement of elements for most devices. Simple and functional design. <a href="https://github.com/RobertTe-tech/cssBayan/pull/1/files">Sources</a>.</p>

***

<p align="center">Secondary complete education (11 grades).</p>

<p align="center"><a href="https://angloved.ru/test/opredelit-uroven-anglijskogo/106fk1009d6ae3bcdfeff9b305a1dd6dc60f5/">Pre-intermediate</a> in English grammar.</p>
