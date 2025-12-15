
# TypeScript Environment Setup

## Is section me hum kya seekhenge?
Is section me hum step-by-step dekhenge:
TypeScript ka environment kaise setup karein  
Project ka basic structure kaise banayein  
TypeScript code ko compile kaise karein  

## Prerequisites (pehle kya hona chahiye?)

### Node.js Installed hona chahiye

Check karne ke liye terminal me run karo:

```bash
node -v
npm -v
```

Agar version aa raha hai → sab theek
Agar version nahi aa raha → pehle Node.js install karo


## TypeScript Install karna

### Global Install (beginners ke liye recommended)

```bash
npm install -g typescript
```

Installation check karne ke liye:

```bash
tsc -v
```

Agar version aa gaya → TypeScript successfully install ho gaya

## Project Folder Create karna

Terminal me command run karo:

```bash
mkdir typescript-complete-guide
cd typescript-complete-guide
```

## Node Project Initialize karna

```bash
npm init -y
```

Is command se ek `package.json` file create hoti hai
Jo project ki basic information rakhti hai

## TypeScript Config File (tsconfig.json)

TypeScript config file generate karne ke liye:

```bash
tsc --init
```

Isse ek file create hoti hai:

```txt
tsconfig.json
```

Ye file TypeScript compiler ko batati hai:
Kaun si files compile hongi
Output kaha generate hoga
Kaunsa JavaScript version use hoga

## Basic tsconfig.json (Beginner Friendly)

```json
{
  "compilerOptions": {
    "target": "ES6",
    "module": "CommonJS",
    "rootDir": "./src",
    "outDir": "./dist",
    "strict": true
  }
}
```

### Important options ka simple meaning

target → JavaScript ka version
module → import/export system
rootDir → TypeScript files ka folder
outDir → Compiled JavaScript ka folder
strict → strict type checking (recommended)

## Project Folder Structure

```txt
typescript-complete-guide/
│
├── src/
├── dist/
├── notes/
├── tsconfig.json
├── package.json
└── README.md
```

src → TypeScript files
dist → Compiled JavaScript files
notes → Learning notes

## First TypeScript File

`src/index.ts` file create karo:

```ts
let message: string = "Hello TypeScript";
console.log(message);
```

## TypeScript Code Compile karna

Terminal me run karo:

```bash
tsc
```

Compile hone ke baad ye file banegi:

```txt
dist/index.js
```

## JavaScript File Run karna

```bash
node dist/index.js
```

Output:

```txt
Hello TypeScript
```

## Common Beginner Mistakes

TypeScript file ko directly browser me chalana
Compile (`tsc`) karna bhool jaana
strict mode disable rakhna

## Summary

Node.js install hona zaroori hai
TypeScript npm se install hota hai
TypeScript code compile hoke JavaScript banta hai
Proper setup se learning aur development easy ho jaata hai