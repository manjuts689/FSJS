# ** DOM Assignment 1**
>**Note**: You have to completed all the given task on the home page of the website.

---

## **Task 1**

The user has to append a new element in the navigation menu named **"Hire Me"** after the **Projects**.

### **After Update**
![Output Image](./firstAssignmentImage/task1Output.png)

### **Project Solution**
```js
let ElementLi = document.createElement("li");
ElementLi.innerHTML = "<a>Hire Me</a>";
let Parent = document.querySelector("header nav ul");
Parent.appendChild(ElementLi);
```
---

## **Task 2**

The user needs to change the placeholder message to **"Search My Project"** after the **Search**.

### **After Update**
![Output Image](./firstAssignmentImage/task2Output.png)

### **Project Solution**
```js
let Element = document.querySelector(".search-field input");
Element.placeholder = "Search My Project";
```
---

## **Task 3**

The user has to change **"a Freelancer"** to **"an Employee"** and **"National and International Client"** to **"iNeuron Intelligence Pvt Ltd"**.

### **After Update**
![Output Image](./firstAssignmentImage/task3Output.png)

### **Project Solution**
```js
let Element = document.querySelectorAll(".hero-left-section p span");
Element[1].innerText = "an Employee";
Element[2].innerText = "iNeuron Intelligence Pvt Ltd";
```
---

## **Task 4**

The user has to replace **"Avtar"** image with **"Hitesh Sir"** image.

### **After Update**
![Output Image](./firstAssignmentImage/task4Output.png)

### **Project Solution**
```js
let Element = document.querySelector(".hero-right-section img");
Element.src="./Hitesh.jpeg";
```
---

## **Task 5**

The user has to change **"Support Me"** button and move it beside the **"Chat With Me"** button.

### **After Update**
![Output Image](./firstAssignmentImage/task5Output.png)

### **Project Solution**
```js
let Parent = document.querySelector(".hero-right-section-btns");
let NewBtn = document.createElement("button");
NewBtn.innerText = "Support Me";
Parent.appendChild(NewBtn);
```
---

# ** DOM Assignment 2**
>**Note**: You have to completed all the given task on the About page of the website.

---

## **Task 1**

The user has to change color of all headers to **"#dadaf8"** and display siblings of **"Achievement"** and **"Hobbies"** header elements.

### **After Update**
![Output Image](./secondAssignmentImage/task1Output.png)

### **Project Solution**
```js
let Header = document.querySelectorAll(".accordian h3");
Header.forEach((element)=>{element.style.backgroundColor = "#dadaf8"})
let Para = document.querySelectorAll(".accordian p");
Para[2].style.display = "block";
Para[3].style.display = "block";
```
---

## **Task 2**

The user needs to add new element with Header as **"Skills"** and Paragragh. Change color of all headers to **"#dadaf8"**

### **After Update**
![Output Image](./secondAssignmentImage/task2Output.png)

### **Project Solution**
```js
let Element = document.createElement("div");
Element.className = "accordian";
let Header = document.createElement("h3");
Header.innerText = "Skills";
let Paragraph = document.createElement("p");
Paragraph.innerText = "I posses a very good command over the Full Stack Development technologies like MERN which can be seen in my work over the Github.";
Paragraph.style.display = "block";
Element.appendChild(Header)
Element.appendChild(Paragraph)
Parent = document.querySelector(".accordian-wrapper");
Parent.appendChild(Element)
var Header = document.querySelectorAll(".accordian h3");
Header.forEach((element)=>{element.style.backgroundColor = "#dadaf8"});
```
---

# ** DOM Assignment 3**
>**Note**: You have to completed all the given task on the Contact page of the website.

---

## **Task 1**

The user has to change color of all headers to **"#dadaf8"** and display siblings of **"Achievement"** and **"Hobbies"** header elements.

### **After Update**
![Output Image](./thirdAssignmentImage/task1Output.png)

### **Project Solution**
```js
let MyForm = document.querySelectorAll("form");
MyForm[1].addEventListener("submit",(event)=>{
    event.preventDefault();
    let InputUserName = document.querySelector(".userName");
    let InputEmail = document.querySelector(".userEmail");
    let InputMessage = document.querySelector(".userMessage");
    
    let OutputUserName = document.querySelector(".enterName");
    let OutputEmail = document.querySelector(".enterMail");
    let OutputMessage = document.querySelector(".enterMessage");

    OutputUserName.value = InputUserName.value;
    OutputEmail.value = InputEmail.value;
    OutputMessage.value = InputMessage.value;
})
```
---
