# ** DOM Assignment 5**
>**Note**: You have to completed all the given task

---

## **Task 1**

The user has to new button **"Pro Subscription"** in nav bar, add new tag **"Chinese (7)"** in tags container and add new card template in recipe gallery.

### **After Update**
![Output Image](./Output/DOM%20P2%20SS.png)

### **Project Solution**
```js
//Add new button in nav bar
let NavElement = document.querySelectorAll(".nav-center div");
let Child = document.createElement("a");
Child.className="btn";
Child.innerText="Pro Subscription"
Child.href="index.html";
NavElement[2].appendChild(Child)

//Create new tag in Tags container
let tagElement = document.querySelector(".tags-container div");
let Child1 = document.createElement("a");
Child1.innerText="Chinese (7)"
Child1.href="#";
tagElement.appendChild(Child1)

//Add new card template in recipe-gallery
let RecipeContainer = document.querySelector(".recipe-gallery");
let NewCard = document.createElement("div");
NewCard.className = "card";
NewCard.innerHTML = '<a href="#" style="font-size: 20px;color:black;"><b>add 6th card here</b></a>'
RecipeContainer.appendChild(NewCard);
```
---

