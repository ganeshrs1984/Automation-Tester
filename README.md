# Automation-Tester
Journey to Becoming a Great Automation Tester

Your Journey to Becoming a Great Automation Tester 🚀

If you follow this learning path step by step and practice consistently, you'll build a strong foundation in automation testing.

Let's get started!

Step 1: Choose an Automation Framework

Framework: Playwright

What is Playwright?

Playwright is a modern automation framework used to test web applications. It can automate browsers just like a real user by clicking buttons, entering text, selecting options, uploading files, and validating results.

Why Playwright?
Fast and reliable
Supports Chrome, Edge, Firefox, and Safari
Built-in waiting (less flaky tests)
Supports parallel execution
Excellent debugging tools
Supports JavaScript and TypeScript
Step 2: Choose a Programming Language

Language: TypeScript

Why TypeScript?

TypeScript is JavaScript with additional features such as static typing.

It helps you:

Find errors while writing code instead of during execution.
Write cleaner and more maintainable code.
Get better code suggestions and auto-completion in VS Code.
Build automation frameworks that are easier to understand and maintain.

Most professional Playwright projects use TypeScript.

Software You Need to Install
1. Visual Studio Code (VS Code)
What is VS Code?

Visual Studio Code is a lightweight but powerful code editor developed by Microsoft.

Think of it as your workspace where you write, edit, organize, and debug your code.

Why do we use VS Code?
Write TypeScript code
Run Playwright tests
Debug code easily
Manage project files
Install helpful extensions
Built-in terminal for running commands

In short, VS Code is where you'll spend most of your time as an automation engineer.

2. Node.js
What is Node.js?

Node.js is a JavaScript runtime that allows JavaScript code to run outside a web browser.

Normally, JavaScript runs only inside a browser. Node.js allows you to run JavaScript and TypeScript directly on your computer.

Why do we need Node.js?

Node.js is required to:

Run Playwright
Install packages
Execute TypeScript code
Run automation tests
Manage project dependencies

Without Node.js, Playwright cannot run.

Think of it this way:

JavaScript is the language.
Node.js is the engine that runs the language.
3. npm (Node Package Manager)

When you install Node.js, npm is installed automatically.

What is npm?

npm is a package manager.

It downloads and manages libraries that your project depends on.

For example, you use npm to install:

Playwright
TypeScript
ts-node
Other testing libraries

Example commands:

npm install
npm install playwright
npm install typescript
4. Install TypeScript

Once Node.js is installed, install TypeScript using npm.

npm install -g typescript

or for a project:

npm install --save-dev typescript
How Everything Works Together
                 You
                  │
                  ▼
        Write Code in VS Code
                  │
                  ▼
          TypeScript (.ts)
                  │
                  ▼
      TypeScript Compiler (tsc)
                  │
                  ▼
        JavaScript (.js)
                  │
                  ▼
              Node.js
                  │
                  ▼
             Playwright
                  │
                  ▼
      Controls Chrome / Edge / Firefox
                  │
                  ▼
          Executes Automation Tests
