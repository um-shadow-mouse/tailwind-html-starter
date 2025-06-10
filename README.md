# Tailwind HTML Starter

A minimal starter project using **Tailwind CSS** with plain HTML. No frameworks or complex tooling—just HTML and Tailwind via the CLI.

## 🚀 Features

- Tailwind CSS v4
- Simple HTML structure
- Easy setup and build
- Watch mode for development

## 🛠️ Setup

1. **Clone the repository** or [download the ZIP](#).
**2. Run the following commands:**
npm install
npm run build

**3.Open index.html in your browser.**

💡 The output CSS file is generated in dist/output.css from src/input.css.
tailwind-html-starter.zip
├──tailwind-html-starter/
├── dist/
│   └── output.css        # Compiled Tailwind CSS
├── src/
│   └── input.css         # Tailwind directives
├── index.html            # Demo HTML page
├── package.json          # Scripts and dependencies
├── tailwind.config.js    # Tailwind config
└── README.md             # You're here**

4. Build Command**
npm run build

5.**📦 Build Command**
npm run build

This runs Tailwind in watch mode:
tailwindcss -i ./src/input.css -o ./dist/output.css --watch

