# ALiAS Website Source

Here you'll find the source code of [lucknow.asetalias.in](lucknow.asetalias.in).

## 🚀 Project Overview

Within this project, you'll find the following folders and files:

```bash
.
├── README.md
├── index.html
├── package.json
├── pnpm-lock.yaml
├── public
│   ├── assets
│   │   ├── icons
│   │   └── images
│   └── data
│       ├── about.json
│       ├── alumni.json
│       ├── events.json
│       ├── members.json
│       └── socials.json
├── src
│   ├── App.css
│   ├── App.jsx
│   ├── components
│   │   ├── AboutUs
│   │   ├── Alumni
│   │   ├── Community
│   │   ├── Contact
│   │   ├── Events
│   │   ├── Hero
│   │   ├── Navbar
│   │   ├── Reusables
│   │   └── Team
│   ├── index.css
│   ├── main.jsx
│   ├── pages
│   │   └── Home
│   └── variables.css
└── vite.config.js
```

The public/data directory contains various JSON files for adding events, volunteers, and alumni.

## 🛠️ Contribution and Local Development

To contribute to this project or run it locally, follow these instructions:

### Installation

1. Navigate to the project's root directory using your terminal.

2. Run the following command to install the necessary dependencies:

   ```bash
   pnpm install
   ```
   /- If pnpm install does not work, or pnpm is termed as a non recognized command then install pnpm

3. To install pnpm, you can use the package manager that you currently have on your system. Below are instructions for different package managers:
      
   1- npm:
         If you have npm installed, you can use it to install pnpm globally. Open your terminal and run:

   ```bash
   npm install -g pnpm
   ```
   This command installs pnpm globally, allowing you to use it from any directory.

   2- Yarn:
         If you prefer using yarn, you can install pnpm globally with:

   ```bash
   yarn global add pnpm
   ```
   This command installs pnpm globally using yarn.
   
   3. npx:
      If you don't want to install pnpm globally, you can use npx to run pnpm without installation:

   ```bash
   npx pnpm install
   ```
   This command runs pnpm for the current project without the need for a global installation.

After installation, you should be able to use pnpm commands globally or within your project.

**#Verify Installation:**

To verify that pnpm has been installed successfully, you can run the following command:

   ```bash
   pnpm --version
   ```
This should print the installed version of pnpm to the console.
Now you are ready to use pnpm for managing your project's dependencies.
      
### Local Development

1. After installing the dependencies, start the local development server by running:

   ```bash
   pnpm dev
   ```

   This will launch the server, and you can access the site at [`localhost:5173`](https://localhost:5173) in your browser.

2. Make your desired changes to the project files.

3. If you want to contribute, please fork the repository, create a branch for your changes, and submit a pull request.

### Questions or Discussions

Join our [Discord server](https://discord.gg/jKhDqHBbMy) for any questions, discussions, or further assistance.


### We would be happy to invite everyone to make new commits and show their creativity on this website
