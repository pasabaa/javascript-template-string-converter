# JavaScript Template String Converter

A lightweight, modern web tool that converts any code into JavaScript template strings with proper escaping of backticks, dollar signs, and backslashes.

![JavaScript Template String Converter](/img/cover.webp?raw=true)

## 🚀 Features

- Convert any code to JavaScript template strings
- Automatically escapes special characters (`\`, `` ` ``, `${}`)
- Customizable variable name
- Clean, modern, and responsive interface
- Copy results to clipboard with one click
- No external dependencies - pure HTML, CSS, and JavaScript

## 🔧 Usage

1. Enter a variable name (default: `code`)
2. Paste your code in the input area
3. Click "Convert to Template String"
4. Copy the resulting JavaScript template string

## 💻 Use Cases

This tool is useful for:

- Creating JavaScript template literals from HTML snippets
- Preparing code for injection into JavaScript files
- Working with multi-line strings in JavaScript
- Embedding code examples in JavaScript documentation

## 🔍 How It Works

The converter automatically handles escaping of special characters that would otherwise break template strings:

- Backslashes (`\`) are escaped to `\\`
- Backticks (`` ` ``) are escaped to ``\` ``
- Template string interpolations (`${...}`) are escaped to `\${...}`

## 🌐 Live Demo

Try it now: [JavaScript Template String Converter](https://javascript-template-string-converter.vercel.app/)

## 🧰 Development

To run this project locally:

1. Clone the repository
   ```
   git clone https://github.com/pasabaa/js-template-string-converter.git
   ```

2. Open `index.html` in your browser

No build steps or server setup required!

## 👨‍💻 Author

Created by [pasabaa](https://github.com/pasabaa)