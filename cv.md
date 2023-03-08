<img src="https://user-images.githubusercontent.com/126411404/223386544-09a12f0c-0af6-4aa7-a8d1-3e33010b3ecb.jpg" width="120" height="170">

Robert Krasilnikov

mail: ptenckunicyn@gmail.com
tel: +79114441907
discord: Majin (RobertTe-tech)#7099

Стремлюсь стать с web на ты, используя данный инструмент на максимум. Уверен, что для каждой задачи способен составить алгоритм решения, если будет достаточно времени на обдумывание. 

Знаю базовый синтаксис JS, HTML, CSS. Программирую в Visual Studio Code.

```JS
function Bor() {
    this.arr = [];
    this.get = function() {
        for(let i = 97; i < 97 + 26; i++) {
            if(this.arr[String.fromCharCode(i)] != undefined)
                return String.fromCharCode(i) + this.arr[String.fromCharCode(i)].get();
        }
        return "";
    };
    this.setWord = function(word) {
        if(ind >= word.length) ind = 0;
        else {
            this.arr[word[ind]] = new Bor();
            this.arr[word[ind++]].setWord(word);
        }
    };
};
let ind = 0; // static var for Bor
function check(word) { // correct input [a-zA-Z]
    let s = "", a1 = false, a2 = false, c = '';
    for(let i = 0; i < word.length; i++) {
        c = word[i];
        a1 = c >= "a" && c <="z";
        a2 = c >= "A" && c <="Z";
        if(a1) {
            s += c;
        } else if(a2) {
            s += c.toLowerCase();
        } else {
            return s;
        }
    }
    return s;
}

var bor = new Bor();
bor.setWord(check("hello"));
console.log(bor.get());
```

<!--Опыт работы. Junior Dev может перечислить учебные проекты с указанием использованных навыков и ссылками на исходный код.-->

Среднее полное образование (11 классов).

[Pre-intermediate](https://angloved.ru/test/opredelit-uroven-anglijskogo/106fk1009d6ae3bcdfeff9b305a1dd6dc60f5/) in English grammar.
