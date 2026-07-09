# Your First TypeScript Program

This guide will help you create and execute your first TypeScript program using **VS Code**, **Node.js**, and **npm**.

---

# Prerequisites

Make sure you have installed the following tools before starting:

- **VS Code**
  ```bash
  code --version
  ```

- **Node.js**
  ```bash
  node --version
  ```

- **npm** (comes with Node.js)
  ```bash
  npm --version
  ```

- **TypeScript**
  ```bash
  tsc --version
  ```

---

# Step 1: Create a Project Folder

Open VS Code and create a new folder.

Example:

```text
typescript-demo
```

Open this folder in VS Code.

---

# Step 2: Initialize npm

Run:

```bash
npm init -y
```

This creates a `package.json` file.

Project structure:

```text
typescript-demo
│
└── package.json
```

---

# Step 3: Install TypeScript

Run:

```bash
npm install typescript --save-dev
```

This installs TypeScript locally in your project.

---

# Step 4: Create a TypeScript Configuration

Run:

```bash
npx tsc --init
```

This creates:

```text
tsconfig.json
```

Your project now looks like:

```text
typescript-demo
│
├── node_modules
├── package.json
├── package-lock.json
└── tsconfig.json
```

---

# Step 5: Create Your First TypeScript File

Create a file named:

```text
app.ts
```

Add the following code:

```typescript
let name: string = "Ganesh";

console.log("Hello " + name);
```

---

# Step 6: Compile TypeScript

Run:

```bash
npx tsc app.ts
```

TypeScript compiles the code and creates:

```text
app.js
```

Project structure:

```text
typescript-demo
│
├── app.ts
├── app.js
├── node_modules
├── package.json
├── package-lock.json
└── tsconfig.json
```

---

# Step 7: Execute the Program

Run:

```bash
node app.js
```

Output:

```text
Hello Ganesh
```

🎉 Congratulations! You have successfully written and executed your first TypeScript program.

---

# What Just Happened?

```text
TypeScript (.ts)
        │
        ▼
TypeScript Compiler (tsc)
        │
        ▼
JavaScript (.js)
        │
        ▼
Node.js Executes It
```

**Key Point:**

- TypeScript cannot be executed directly by Node.js.
- The TypeScript compiler (`tsc`) converts `.ts` files into `.js` files.
- Node.js executes the generated JavaScript.

---

# Bonus: Compile Automatically

Instead of compiling every time, run:

```bash
npx tsc --watch
```

Now, every time you save your `.ts` file, TypeScript automatically recompiles it.

Simply run:

```bash
node app.js
```

to execute the latest version.

---

# Next Step

Once you're comfortable with the basics, you can install **ts-node**, which allows you to execute TypeScript files directly without manually compiling them first.

```bash
npm install --save-dev ts-node
```

Run your program with:

```bash
npx ts-node app.ts
```

> **Learning Tip:** Start by using the **compile (`tsc`) → execute (`node`)** workflow. Understanding that TypeScript is compiled into JavaScript is one of the most important concepts for every beginner.
