# Course Curriculum

This course covers a diverse range of topics across five quarters:

## Quarter 1: TypeScript

- Introduction to TypeScript
- Basic syntax and data types
- Functions and classes
- Advanced TypeScript features
- Practical applications and projects

## Quarter 2: Next.js (UI/UX)

- Introduction to Next.js framework
- Building user interfaces with Next.js
- Enhancing user experience with Next.js features
- Styling and responsive design
- Real-world projects and case studies

## Quarter 3: Python

- Introduction to Python programming language
- Basic syntax and data structures
- Object-oriented programming in Python
- Python for data analysis and manipulation
- Practical Python applications and projects

## Quarter 4: Generative AI

- Fundamentals of Generative AI
- Generative Adversarial Networks (GANs)
- Variational Autoencoders (VAEs)
- Applications of Generative AI in art, design, and beyond
- Hands-on projects and experimentation with Generative AI models

## Quarter 5: Cloud AI Engineering

- Introduction to Cloud AI services
- Deployment of AI models on cloud platforms
- Scalability and performance optimization techniques
- Cloud-based AI solutions for various domains
- Capstone project involving the integration of AI with cloud technologies

This curriculum offers a comprehensive exploration of key technologies and concepts, providing students with a well-rounded understanding and practical skills in TypeScript, Next.js, Python, Generative AI, and Cloud AI Engineering.

# Installation and Verification Guide

## Node.js Installation:

- Visit the [Node.js website](https://nodejs.org).
- Click on the LTS version for stability.
- Follow the installation instructions provided for your operating system.

## Check Node.js Version:

- Open Command Prompt (Cmd).
- Type `node -v` and press Enter.

## VS Code Installation:

- Navigate to the [VS Code website](https://code.visualstudio.com/).
- Download the installer using the provided button.
- Install VS Code by following the installation wizard.

## Check VS Code Version:

- Open Command Prompt (Cmd).
- Type `code -v` and press Enter.

## Installing TypeScript

To install TypeScript, follow these steps:

### For Windows Users:

1. Open Command Prompt (Cmd).
2. Type the following command and press Enter:

```bash
 npm install -g typescript
```

### For Mac/Linux Users:

1. Open Terminal.
2. Type the following command and press Enter:

```bash
 sudo npm i -g typescript
```

### What This Command Does:

- `npm install -g typescript`: This command installs TypeScript globally on your system, allowing you to use it from any directory.

### Note:

- For Mac/Linux users, the `sudo` command is used to execute the installation with administrative privileges.
- Make sure you have Node.js and npm (Node Package Manager) installed on your system before running these commands.

By following these steps, you'll have TypeScript installed and ready to use on your machine.

## Verify TypeScript Installation and Version:

- Type `tsc -v` in the command prompt and press Enter.

Make sure you have administrative privileges for installing global packages like TypeScript.

### Versions:

- Node.js Version: 20.11.1
- VS Code Version: 1.87.2
- TypeScript Version: 5.4.2

Ensure your system meets the minimum requirements for each software.

## Changing Terminal from PowerShell to Command Prompt (Cmd) in VS Code

### Using Command Palette:

#### For Windows Users:

1. Open Visual Studio Code.

2. Press `Ctrl + Shift + P` to open the command palette.

3. Type "Terminal: Select Default Profile" and select it from the list.

4. Choose "Command Prompt" or "Command Prompt (Cmd)" from the options provided.

5. Your terminal will switch to Command Prompt as the default.

Now, whenever you open a new terminal in Visual Studio Code, it will default to Command Prompt instead of PowerShell.

#### For Mac/Linux Users:

1. Open Visual Studio Code.

2. Press `Ctrl + Shift + P` to open the command palette.

3. Type "Terminal: Select Default Profile" and select it from the list.

4. Choose "Command Prompt" or "Command Prompt (Cmd)" from the options provided.

5. Your terminal will switch to Command Prompt as the default.

Now, whenever you open a new terminal in Visual Studio Code, it will default to Command Prompt instead of the default shell for your system.

### Using UI:

#### For Windows Users:

1. Open Visual Studio Code.

2. Click on the terminal tab at the top menu.

3. Near the top right corner of the terminal, click on the dropdown arrow.

4. Select "Select Default Shell" from the dropdown menu.

5. Choose "Command Prompt" or "Command Prompt (Cmd)" from the list.

6. Your terminal will switch to Command Prompt as the default.

Now, whenever you open a new terminal in Visual Studio Code, it will default to Command Prompt instead of PowerShell.

#### For Mac/Linux Users:

1. Open Visual Studio Code.

2. Click on the terminal tab at the top menu.

3. Near the top right corner of the terminal, click on the dropdown arrow.

4. Select "Select Default Shell" from the dropdown menu.

5. Choose "Command Prompt" or "Command Prompt (Cmd)" from the list.

6. Your terminal will switch to Command Prompt as the default.

Now, whenever you open a new terminal in Visual Studio Code, it will default to Command Prompt instead of the default shell for your system.

# TypeScript Setup and Compilation Guide

This guide outlines the steps to set up and compile TypeScript files for development.

## Initializing Configuration

To set up project-specific settings for the TypeScript compiler, you can use the following command to create a `tsconfig.json` file:

```bash
npm init tsc --init
```

## Compiling TypeScript Files

To compile TypeScript files (.ts) into JavaScript files (.js), use the tsc command followed by the filename of the TypeScript file you want to compile. Additionally, you can use the -w flag to enable watching for changes and automatic recompilation.

Example:

```bash
tsc filename.ts -w
```

## Running the Compiled Code

Once you've compiled your TypeScript code into JavaScript, you can run the JavaScript file using node.

Example:

```bash
node filename.js
```

Alternatively, you can combine compilation and running the code using the following command:

```bash
tsc filename.ts && node filename.js
```

## Using Nodemon for Development

For development purposes, you can utilize nodemon, a tool that automatically restarts your Node.js application whenever there are changes in the TypeScript files. This saves you time from manually recompiling and restarting the application.

```bash
nodemon node filename.js
```

This guide provides a solid foundation for getting started with TypeScript development.

# TypeScript Projects and Assignments

This repository contains all the classes, Node.js projects, and assignments related to TypeScript.

## Contents

- [Classes](#classes)
- [Node.js Projects](#nodejs-projects)
- [Assignments](#assignments)

## Classes

List the classes or topics covered in your TypeScript course here, along with any relevant information or links.

1. **Class 1:**
   Description: Provide a brief description of the project.
   [](<class01(hello-World)>)

## Node.js Projects

Include descriptions and links to any Node.js projects related to TypeScript that you have worked on. You can provide a brief overview of each project and link to their respective folders or repositories.

1. **Project Name 1:**
   Description: Provide a brief description of the project.
   [](<project1(Simple-Calculator)>)

2. **Project Name 2:**
   Description: Provide a brief description of the project.
   [](<project2(Guess-The-Number-Game)>)

## Assignments

List the assignments related to TypeScript along with any instructions or details.

1. **Assignment 1:**
   Description: Provide a brief description of the assignment.
   [](assignment1/)

