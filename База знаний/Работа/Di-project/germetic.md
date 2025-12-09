```
var prevScrollpos = window.pageYOffset;

2window.onscroll = function() {

3 var currentScrollPos = window.pageYOffset;

4 if (prevScrollpos > currentScrollPos) {

5 document.getElementById("navbar").classList.remove("hidden");

6 } else {

7 document.getElementById("navbar").classList.add("hidden");

8 }

9 prevScrollpos = currentScrollPos;

10}
```
Скрытие элемента при скролле
Шапка