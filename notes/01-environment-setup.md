# TypeScript Environment Setup

Is section me hum step-by-step dekhenge:
- TypeScript ka environment kaise setup karein
- Project ka structure kaise banayein
- Code ko compile kaise karein

---

## 1. Prerequisites (pehle kya hona chahiye?)

### ✔ Node.js Installed hona chahiye
Check karne ke liye:
```bash
node -v
npm -v
Agar version aa raha hai → sab theek 👍
Nahi aa raha → Node.js install karo.

2. TypeScript Install karna
Global Install (recommended for beginners)
bash
Copy code
npm install -g typescript
Check installation:

bash
Copy code
tsc -v
Agar version aa gaya → TypeScript install ho gaya 🎉

3. Project Folder Create karo
bash
Copy code
mkdir typescript-complete-guide
cd typescript-complete-guide
4. Node Project Initialize karo
bash
Copy code
npm init -y
Isse package.json ban jaayega.

5. TypeScript Config File (tsconfig.json)
bash
Copy code
tsc --init
Ye command ek important file banati hai:

txt
Copy code
tsconfig.json
👉 Ye file batati hai:

Kaun si files compile hongi

Output kaha jayega

Kaunsa JS version use hoga

6. Important tsconfig Options (Beginner Friendly)
json
Copy code
{
  "compilerOptions": {
    "target": "ES6",
    "module": "CommonJS",
    "rootDir": "./src",
    "outDir": "./dist",
    "strict": true
  }
}
Samjho isko 👇
target: JavaScript ka version

module: import/export ka system

rootDir: TypeScript files kaha hongi

outDir: Compiled JavaScript kaha jayegi

strict: strict type checking (recommended)

7. Folder Structure
txt
Copy code
src/     → TypeScript files (.ts)
dist/    → Compiled JavaScript files (.js)
notes/   → Learning notes (Markdown)
8. First TypeScript File
src/index.ts

ts
Copy code
let message: string = "Hello TypeScript";
console.log(message);
9. Compile TypeScript Code
bash
Copy code
tsc
Iske baad:

txt
Copy code
dist/index.js
file generate ho jaayegi.

10. Run JavaScript File
bash
Copy code
node dist/index.js
Output:

txt
Copy code
Hello TypeScript
11. VS Code Extensions (Recommended)
ESLint

Prettier

TypeScript Importer

Ye extensions:

Code clean rakhenge

Errors highlight karenge

Productivity badhayenge

Common Beginner Mistakes ❌
.ts file directly browser me chalana

tsc run karna bhool jaana

strict mode off rakhna

Summary
Node.js install hona chahiye

TypeScript global install karo

tsconfig.json samajhna zaroori hai

TypeScript compile hoke JavaScript banta hai