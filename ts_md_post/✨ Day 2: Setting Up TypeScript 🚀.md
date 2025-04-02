## ✨ Day 2: Setting Up TypeScript 🚀

Welcome back to **Day 2** of our TypeScript journey! Today, we’ll focus on **setting up TypeScript** and getting started with our first TypeScript project. Let’s dive in! 🎉

---

### 🛠️ Installing TypeScript

To start using TypeScript, you need to install it globally on your system. Follow these steps:

1️⃣ Open your terminal and run the following command:

```bash
npm install -g typescript
```

2️⃣ Verify the installation by checking the TypeScript version:

```bash
tsc --version
```

If you see the version number, TypeScript is successfully installed! ✅

---

### 📂 Setting Up a TypeScript Project

Let’s create a new TypeScript project step by step:

#### 1️⃣ Initialize a New Project

Run the following command to create a `package.json` file:

```bash
npm init -y
```

This will create a basic `package.json` file for your project.

---

#### 2️⃣ Install TypeScript Locally

Install TypeScript as a development dependency in your project:

```bash
npm install typescript --save-dev
```

---

#### 3️⃣ Create a `tsconfig.json` File

Run the following command to generate a `tsconfig.json` file:

```bash
npx tsc --init
```

This file contains all the configuration options for your TypeScript project. You can customize it as needed.

---

#### 4️⃣ Write Your First TypeScript File

Create a new file named `index.ts` and add the following code:

```typescript
const greet = (name: string): string => {
  return `Hello, ${name}! Welcome to TypeScript.`;
};

console.log(greet("Developer"));
```

---

#### 5️⃣ Compile TypeScript to JavaScript

Run the following command to compile your TypeScript file:

```bash
npx tsc
```

This will generate a JavaScript file (`index.js`) in the same directory.

---

#### 6️⃣ Run the Compiled JavaScript File

Use Node.js to execute the compiled JavaScript file:

```bash
node index.js
```

You should see the output:  
`Hello, Developer! Welcome to TypeScript.` 🎉

---

#### 🔧 Customizing `tsconfig.json`

Here are some useful options you can enable in your `tsconfig.json` file:

- **`"target"`**: Specify the JavaScript version (e.g., `ES6`).
- **`"strict"`**: Enable strict type checking.
- **`"outDir"`**: Specify the output directory for compiled files.
- **`"rootDir"`**: Specify the root directory for TypeScript files.

Example:

```json
{
  "compilerOptions": {
    "target": "ES6",
    "strict": true,
    "outDir": "./dist",
    "rootDir": "./src"
  }
}
```

---

### 🎯 Conclusion

Congratulations! 🎉 You’ve successfully set up TypeScript and written your first TypeScript program. Setting up TypeScript might seem like a lot at first, but it’s worth it for the type safety and developer experience it provides.
