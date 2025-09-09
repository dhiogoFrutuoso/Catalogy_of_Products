# Catalogy of Products

A simple **Node.js** project for creating and managing a product catalog through basic operations like creating, listing, and searching products.

---

## Table of Contents

- [About](#about)
- [Features](#features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Project](#running-the-project)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)

---

## About

This project was built with **Node.js** and provides a minimal system for product catalog management.  
It supports product creation, listing, and search, making it a good foundation for learning and experimenting with Node.js.

---

## Features

- **Create**: Add new products to the catalog.  
- **List**: Display all products in the catalog.  
- **Search**: Look up products by their details.  
- **Main Control**: Runs the core operations (create, list, search) from a central entry point.  

---

## Project Structure

```text
Catalogy_of_Products/
├── main/
│   ├── menus/
│   │   ├── create.js   # Handles product creation
│   │   ├── list.js     # Handles product listing
│   │   ├── main.js     # Executes create, list, and search
│   │   └── search.js   # Handles product search
│   └── index.js        # Main entry point of the project
├── node_modules/       # Project dependencies (auto-generated)
├── package.json        # Project metadata and dependencies
├── package-lock.json   # Dependency lock file
└── .package-lock.json  # Extra lock file (can be ignored)
Getting Started
Prerequisites
Node.js (version 14 or higher recommended)

npm (comes with Node.js)

Installation
Clone the repository and install dependencies:

bash
Copy code
git clone https://github.com/dhiogoFrutuoso/Catalogy_of_Products.git
cd Catalogy_of_Products
npm install
Running the Project
Start the project with:

bash
Copy code
node main/index.js
This will run the catalog system, allowing you to create, list, and search products from the console.

Contributing
Contributions are welcome!

Fork this repository

Create a new branch (git checkout -b feature/your-feature)

Commit your changes (git commit -m "Add your feature")

Push to the branch (git push origin feature/your-feature)

Open a Pull Request

Acknowledgments
Built with Node.js

Uses open-source libraries like chalk, picocolors, and sisteransi for terminal styling and interaction
