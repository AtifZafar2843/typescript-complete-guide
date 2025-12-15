# Introduction to TypeScript

## TypeScript kya hai?
TypeScript ek **programming language** hai jo **JavaScript ke upar build** ki gayi hai.

Simple shabdon me:

> **TypeScript = JavaScript + Types**

JavaScript me variables ka type define nahi hota,  
jabki TypeScript me hum pehle batate hain ki variable kis type ka hoga.

---

## JavaScript vs TypeScript (Basic Example)

### JavaScript
```js
let age = 20;
age = "twenty"; // JavaScript me error nahi aata
```

### TypeScript
```ts
let age: number = 20;
age = "twenty"; // Compile time error
```

👉 TypeScript hume code likhte waqt hi error bata deta hai.

---

### TypeScript kyun use karein?
1. Compile Time Error Detection
TypeScript me errors run hone se pehle mil jaate hain,
jis se bugs kaafi kam ho jaate hain.

2. Better Code Quality
Code zyada readable hota hai
Samajhna easy hota hai
Team ke saath kaam karna easy ho jaata hai

3. Large Projects ke liye Best
Small scripts ke liye JavaScript theek hai,
lekin React, Node, Backend aur large applications ke liye
TypeScript zyada reliable hota hai.

4. JavaScript ka Super Set
TypeScript koi alag language nahi hai jo JavaScript ko replace karti ho.

✔ Jo JavaScript me valid hai
✔ Wo TypeScript me bhi valid hai

### Example:

```js
console.log("Hello World");
```
Ye code TypeScript me bhi bilkul sahi chalega.

### TypeScript kaise kaam karta hai?
Browser directly TypeScript nahi samajhta.

### Flow kuch is tarah hota hai:

```txt
TypeScript (.ts)
        ↓ compile
JavaScript (.js)
        ↓
Browser / Node.js
TypeScript file pehle JavaScript me convert hoti hai,
phir wahi JavaScript run hoti hai.
```

---

### TypeScript kaha use hota hai?
React (mostly TypeScript ke saath)
Angular (pure TypeScript)
Node.js backend
Large scale web applications
Enterprise level software

---

### Industry Reality
Aaj ke time me:
React + TypeScript = Industry Standard
Companies plain JavaScript se zyada TypeScript prefer karti hain
Isliye TypeScript seekhna ek strong career decision hai.

---

### Summary
TypeScript = JavaScript + Types
Compile time errors milte hain
Code zyada safe aur maintainable hota hai
Modern web development ke liye essential skill hai