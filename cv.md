<img src="https://user-images.githubusercontent.com/126411404/223386544-09a12f0c-0af6-4aa7-a8d1-3e33010b3ecb.jpg" width="120" height="170">

Robert Krasilnikov

mail: ptenckunicyn@gmail.com
tel: +79114441907
discord: Majin (RobertTe-tech)#7099

I need a web tool to implement my ideas. I am sure that I am able to create a solution algorithm for each task, if there is enough time to think about it.

I know the basic syntax JS, HTML, CSS. Programming in Visual Studio Code.

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

1. CSS Bayan. The first educational project of the school RS. The project was compiled only using HTML and CSS, without using JS. Adaptive arrangement of elements for most devices. Simple and functional design.
https://github.com/RobertTe-tech/cssBayan/pull/1

Secondary complete education (11 grades).

[Pre-intermediate](https://angloved.ru/test/opredelit-uroven-anglijskogo/106fk1009d6ae3bcdfeff9b305a1dd6dc60f5/) in English grammar.
