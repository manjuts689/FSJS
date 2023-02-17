# ** DOM Assignment 4**
>**Note**: You have to completed all the given task

---

## **Task 1**

The user has to change the background and text color of stats in all the cards.

### **After Update**
![Output Image](./Output/DOM%20P1%20SS.png)

### **Project Solution**
```js
let CardBarbarian = document.querySelector(".clash-card__unit-stats--barbarian");
CardBarbarian.style.backgroundColor = "#Ec9b3b";
CardBarbarian.style.color = "#ffffff";
let CardBarbarian1 = document.querySelector(".clash-card__unit-stats--barbarian").querySelectorAll(".one-third");
CardBarbarian1[2].style.color = "#ffffff";

let CardArcher = document.querySelector(".clash-card__unit-stats--archer");
CardArcher.style.backgroundColor = "#ee5487";
CardArcher.style.color = "#ffffff";
let CardArcher1 = document.querySelector(".clash-card__unit-stats--archer").querySelectorAll(".one-third");
CardArcher1[2].style.color = "#ffffff";

let CardGiant = document.querySelector(".clash-card__unit-stats--giant");
CardGiant.style.backgroundColor = "#f6901a";
CardGiant.style.color = "#ffffff";
let CardGiant1 = document.querySelector(".clash-card__unit-stats--giant").querySelectorAll(".one-third");
CardGiant1[2].style.color = "#ffffff";

let CardGoblin = document.querySelector(".clash-card__unit-stats--goblin");
CardGoblin.style.backgroundColor = "#82bb30";
CardGoblin.style.color = "#ffffff";
let CardGoblin1 = document.querySelector(".clash-card__unit-stats--goblin").querySelectorAll(".one-third");
CardGoblin1[2].style.color = "#ffffff";

let CardWizard = document.querySelector(".clash-card__unit-stats--wizard");
CardWizard.style.backgroundColor = "#4facff";
CardWizard.style.color = "#ffffff";
let CardWizard1 = document.querySelector(".clash-card__unit-stats--wizard").querySelectorAll(".one-third");
CardWizard1[2].style.color = "#ffffff";
```
---

