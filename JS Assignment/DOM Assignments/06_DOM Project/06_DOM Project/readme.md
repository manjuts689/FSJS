# ** DOM Assignment 6**
>**Note**: You have to completed all the given tasks.

---

## **Task 1**

The user has to change the logo image in header section.

### **After Update**
![Output Image](./Output/DOM%20P3%20SS-1.png)

### **Project Solution**
```js
let header = document.querySelector("header img");
header.src="./assets/ineuron-logo.png"
```
---

## **Task 2**

The user has to change the Subscription Amount to **"$10"** and add **"Linkedin"** icon in footer section.

### **After Update**
![Output Image](./Output/DOM%20P3%20SS-2.png)

### **Project Solution**
```js
let AppPriceElement = document.querySelector(".app_price span");
AppPriceElement.innerText = "$10";

let footer1 = document.querySelector(".footer_social");
let SocialMediaElement = document.createElement("div");
SocialMediaElement.className = "footer_social_ico";
let ChildIElement = document.createElement("i");
ChildIElement.className = "fa-brands fa-linkedin";
SocialMediaElement.appendChild(ChildIElement);
footer1.appendChild(SocialMediaElement);
```
---

