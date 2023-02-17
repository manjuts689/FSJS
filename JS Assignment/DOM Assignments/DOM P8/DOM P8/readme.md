# ** DOM Assignment 8**
>**Note**: You have to completed all the given task of the website.

---

## **Task 1**

The user has to add horizontal line, header and paragraph in New section.

### **After Update**
![Output Image](./ass8.1-after.png)

### **Project Solution**
```js
let Parent1 = document.querySelector(".col-lg-4");
let hr1 = document.createElement("hr");
hr1.className = "hr-line";
let header2 = document.createElement("h2");
header2.className = "new-head";
header2.innerText = "This is my custom heading";
let Paragraph = document.createElement("p");
Paragraph.className = "new-p";
Paragraph.innerText = "This sample text used for testing of custom field which is added by the tester";
Parent1.appendChild(hr1);
Parent1.appendChild(header2);
Parent1.appendChild(Paragraph);
```
---

## **Task 2**

The user has to change background colour of main to white.

### **After Update**
![Output Image](./ass8.2-after.png)

### **Project Solution**
```js
let Main1 = document.querySelector(".container-fluid");
Main1.style.backgroundColor = "white";
```
---

## **Task 3**

The user has to change background colour of main to white.

### **After Update**
![Output Image](./ass8.3-after.png)

### **Project Solution**
```js
let Main1 = document.querySelector(".container-fluid");
Main1.style.backgroundColor = "white";
```
---
