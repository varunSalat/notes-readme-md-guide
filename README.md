# 📝 How to create README.md file beautifully?

## Introduction

This project is designed to help developers create beautiful and well-structured `README.md` files. A well-crafted README is essential for any project as it provides clear instructions, usage guidelines, and essential information to collaborators and users. This guide will walk you through the best practices for writing a comprehensive and visually appealing README, ensuring your project is easily understood and accessible to anyone who interacts with it.

### Aim

The aim of this project is to:

- Provide a simple, yet thorough guide on how to structure a `README.md` file.
- Showcase best practices for organizing project documentation effectively.
- Help developers, especially beginners, understand how to present their project in a clear and professional manner.
- Encourage better collaboration and easier onboarding for contributors and users.

### How to preview README.md file in VSCode?

- Press **`Ctrl + Shift + V`**

## **1. Titles of the Project**

Use the `#` symbol to define the main title of the project.

```markdown
# Project Title Name
```

We have six type of different headers with sizes

## secondary header (`##`)

### tertiary header (`###`)

#### fourth header (`####`)

##### fifth header (`#####`)

###### sixth header (`######`)

## 2. How to create list?

- to create like view we use `-` sign.

### Exa:

- this is list one
- this is list two

## 3. If you add tab after the header it will add tab in readme.md file as well

- this is parent list

  - this is child list one
  - this is child list two

## 4. How to create badges?

1. **Visit the following link:**  
   `https://shields.io/badges/crates-io-license`

2. **Create a Badge** by selecting the desired options on the website.

3. **Copy the Badge Code** provided on the site.

4. **Paste the Badge Code** into your `README.md` file, like so:

   ### Markup:

   ```
   ![Crates.io License](https://img.shields.io/crates/l/mit)
   ![Endpoint Badge](https://img.shields.io/endpoint?url=endpoint-badge)
   ```

   ### Preview:

   ![Crates.io License](https://img.shields.io/crates/l/mit)
   ![Endpoint Badge](https://img.shields.io/endpoint?url=endpoint-badge)

## 5. How to provide a table of content

- It is just like adding context or summary

### Exa:

### Markup:

```
## Table of Content

- [Features](#features)
- [Setup & Installation](#setup--installation)
- [Folder Structure](#folder-structure)
- [Usage](#usage)
- [APIs](#apis)
- [Contribution](#contribution)
- [License](#license)
```

### Preview:

## Table of Content

- [Features](#features)
- [Setup & Installation](#setup--installation)
- [Folder Structure](#folder-structure)
- [Usage](#usage)
- [APIs](#apis)
- [Contribution](#contribution)
- [License](#license)

## 6. Project Folder Structure

- Use **backticks** (`` ` ``) to create a code block.
- Use **slashes** (`/`) to indicate directories.
- Use **indentation** to show nested files/folders (for example, using 2 spaces or 1 tab).
- Use **`├──`** and **`└──`** to indicate folder/file structure.

### Markup & Preview:

```

project-name/
├── src/
│ ├── index.js
│ ├── app.js
│ └── components/
│ └── header.js
├── public/
│ ├── index.html
│ └── style.css
├── package.json
└── README.md

```

## 7. Installation Guide

- Include **step-by-step installation** to setup a project.

### Exa:

### Pre-requisites

- Node.js (v14 or later)
- npm (v6 or later)
- Git

### How to start a project?

    1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/your-project.git
    ```

    2. **Install Dependencies**

    ```bash
    npm i
    ```

    3. **Navigate to the project**

    ```bash
    cd projectName
    ```

    4. **Run the project**

    ```bash
    npm run dev
    ```

### Note:

- When we are showing only code use ```

- when we are showing bash code we have to add **bash** after the first(initial) three tilt sign. ```bash
- just like this we can define while language code it is by adding landing name after first title sign.

- exa:

  ```typescript
  console.log("this is ts code);
  ```

## 8. How to add features of a project

### Markup:

```
## Features:

- Feature 1: Brief description.
- Feature 2: Brief description.
- Feature 3: Brief description.
```

### Preview:

## Features:

- Feature 1: Brief description.
- Feature 2: Brief description.
- Feature 3: Brief description.

## 8. How to create a table?

### Markup:

```
| Column 1      | Column 2      | Column 3      |
|---------------|---------------|---------------|
| Row 1, Cell 1 | Row 1, Cell 2 | Row 1, Cell 3 |
| Row 2, Cell 1 | Row 2, Cell 2 | Row 2, Cell 3 |
| Row 3, Cell 1 | Row 3, Cell 2 | Row 3, Cell 3 |

```

### Preview:

| Column 1      | Column 2      | Column 3      |
| ------------- | ------------- | ------------- |
| Row 1, Cell 1 | Row 1, Cell 2 | Row 1, Cell 3 |
| Row 2, Cell 1 | Row 2, Cell 2 | Row 2, Cell 3 |
| Row 3, Cell 1 | Row 3, Cell 2 | Row 3, Cell 3 |

## 9. APIs or Services

If your project calls APIs or has backend services, explain them here.

### Markup:

```md
## APIs

| Endpoint         | Method | Description                                         |
| ---------------- | ------ | --------------------------------------------------- |
| `/api/users`     | GET    | Get all users                                       |
| `/api/users/:id` | GET    | Get user by ID                                      |
| `/api/users`     | POST   | Create a new user                                   |
| `/api/users`     | POST   | Create a new user ma ke this as much long as needed |
```

### Preview:

## APIs

| Endpoint         | Method | Description                                         |
| ---------------- | ------ | --------------------------------------------------- |
| `/api/users`     | GET    | Get all users                                       |
| `/api/users/:id` | GET    | Get user by ID                                      |
| `/api/users`     | POST   | Create a new user                                   |
| `/api/users`     | POST   | Create a new user ma ke this as much long as needed |

## 10. How to add screenshot or gif?

- We can copy image and just paste it in readme.md file.
- It will automatically add image in your file.
- **It will add Image with it's default height and width**

- to add image with custom height and width we use **img tag**

### markup:

```
<img src="coffee.jpg" alt="alt text" width="200" height="300">
```

### Preview:

<img src="coffee.jpg" alt="alt text" width="200" height="300">

## 10. Useful websites:

- `https://readme.so`
- `https://www.makeareadme.com/`

## Contribution 😉

Contributions are welcome! Here's how you can contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m "Add a new feature"`).
4. Push to your branch (`git push origin feature-branch`).
5. Open a Pull Request.

## Last Words:

**Thank you for checking out this project!** 😊

Made with ❤️ by [Varun Salat](https://varun-salat.vercel.app)
