📄 notes/00-introduction.md
# Introduction to TypeScript

## TypeScript kya hai?
TypeScript ek **programming language** hai jo **JavaScript ke upar bana hai**.

Simple words me:
👉 TypeScript = JavaScript + Types

JavaScript me hum types define nahi karte:
```js
let age = 20;
age = "twenty"; // error nahi aata JS me


TypeScript me hum pehle hi bata dete hain:

let age: number = 20;
age = "twenty"; // ❌ error (compile time)

TypeScript kyun use karein?
1. Compile Time Error Detection

TypeScript hume code likhte time hi error bata deta hai, run karne se pehle.

👉 Isse bugs kam hote hain.

2. Better Code Quality

Types hone ki wajah se:

Code readable hota hai

Samajhna easy hota hai

Team ke saath kaam karna easy hota hai

3. Large Projects ke liye Best

JavaScript small projects ke liye theek hai,
lekin React / Node / Backend / Enterprise apps me TypeScript zyada reliable hai.

4. JavaScript ka hi Super Set

TypeScript koi nayi duniya nahi hai.

✔ Jo JavaScript me valid hai
✔ Wo TypeScript me bhi valid hai

Matlab:

console.log("Hello");


Ye TypeScript me bhi chalega 👍

TypeScript kaise kaam karta hai?

TypeScript browser samajh nahi sakta.

Isliye flow hota hai:

TypeScript (.ts) → Compile → JavaScript (.js) → Browser


TypeScript compile hokar JavaScript ban jaata hai.

TypeScript kaha use hota hai?

React (mostly with TS)

Angular (pure TypeScript)

Node.js Backend

Large Scale Web Apps

Enterprise Applications

Industry Reality 💡

Aaj ke time me:

React + TypeScript = Standard

Companies JavaScript se zyada TypeScript prefer karti hain

Isliye TypeScript seekhna optional nahi, almost mandatory ho chuka hai.

Summary

TypeScript = JavaScript + Types

Errors pehle mil jaate hain

Code safe & maintainable hota hai

Industry standard skill hai