# ** DOM Assignment 9**
>**Note**: You have to completed all the given task on the home page of the website.

---

## **Task 1**

The user has to change the text color to Red in h1 header under caption class.

### **After Update**
![Output Image](./ass9.1-after.png)

### **Project Solution**
```js
let Parent1 = document.querySelector(".caption h1");
Parent1.style.color = "#e20000";
```
---

## **Task 2**

The user has to change the background color of the button to red when hover on the button.

### **After Update**
![Output Image](./ass9.2-after.png)

### **Project Solution**
```js
let btn = document.querySelector("button");
btn.addEventListener("mouseover",()=>{
btn.style.backgroundColor= "#e20000";
});

btn.addEventListener("mouseout",()=>{
btn.style.backgroundColor= "#3c8067";
});
```
---
