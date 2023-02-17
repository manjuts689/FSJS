# ** DOM Assignment 7**
>**Note**: You have to completed all the given tasks.

---

## **Task 1**

The user has to Remove the languages that have 2.0 in their name(Every alternative language)

### **After Update**
![Output Image](./ass7.1-after.png)

### **Project Solution**
```js
let AnchorElements = document.querySelectorAll(".main__languages a");
AnchorElements.forEach((element)=>{
    if(element.innerText.includes("2.0")){
        element.remove();
    }
})
```
---

## **Task 2**

The user has to write something in the input box and submit the form. This should refresh the page and the languages in the left card should come back

### **After Update**
![Output Image](./ass7.2-after.png)

### **Project Solution**
```js
let InputBoxElement = document.querySelector(".main__form-input");
let SubmitButton = document.querySelector(".main__form-btn");
InputBoxElement.disabled = false;
SubmitButton.disabled = false;
```
---