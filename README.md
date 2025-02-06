# Figma Plugin Workshop

Welcome to your **Figma Plugin Workshop**! 🎨✨ This guide will help you understand the structure of a Figma plugin, how to set up your development environment, and where to find useful resources. No prior coding experience is required!


## 📌 What is This?

This repository provides a **primer** for building Figma plugins. It includes all the necessary steps and configurations to help you get started. It also includes the code for the sample plugin we used in the workshop.

Figma plugins allow designers to extend Figma’s functionality by adding new features, automating repetitive tasks, and integrating external services.

## 📂 Project Structure

Here's an overview of the key files and what they do:

```
📁 figma-plugin-boilerplate
├── 📄 code.ts             # TypeScript file with the plugin's core logic
├── 📄 code.js             # Auto-generated Javascript based on the typescript
├── 📄 manifest.json       # Metadata for your plugin
├── 📄 package.json        # Manages dependencies, scripts, and metadata for the project
├── 📄 package-lock.json   # Locks the versions of dependencies to ensure consistency
├── 📄 tsconfig.json       # TypeScript configuration
└── 📄 README.md           # Documentation for the plugin
├── 📄 ui.html             # HTML file that defines the user interface
```

### 🗂 File Explanations

- **manifest.json** → This is the most important file! It defines your plugin’s name, permissions, and how it interacts with Figma.
- **code.ts** → This is where the magic happens! It contains the logic for your plugin.
- **ui.html** → The structure of your plugin’s UI (if it has one).
- **package.json** → Manages dependencies for development.

## 🛠 Setting Up Your Local Development Environment

1. **Install Visual Studio Code**
   - [Download VSCode](https://code.visualstudio.com/download)
2. **Install Node.js**:

   - [Download Node.js](https://nodejs.org/en/download)
3. Open the plugin folder in VSCode
4. Open **Terminal** from the top bar
5. **Install TypeScript**

   ```sh
   npm install -g typescript
   ```

6. **Get the latest type definitions for the plugin API** Open your terminal (Mac) or Command Prompt (Windows) in your plugin's directory and run:

   ```sh
   npm install --save-dev @figma/plugin-typings
   ```
7. **Terminal > Build Run Task**
8. Go to Figma and launch plugin

## 🔗 Useful Resources

- [Figma Plugin Quick Start Guide](https://www.figma.com/plugin-docs/plugin-quickstart-guide/)
- [Figma Plugin API Documentation](https://www.figma.com/plugin-docs/)
- [Figma Plugin Examples](https://github.com/figma/plugin-samples)
- [The comprehensive toolkit for developing plugins and widgets for Figma and FigJam](https://yuanqing.github.io/create-figma-plugin/)
