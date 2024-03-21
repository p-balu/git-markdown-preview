# Git-Markdown-Preview

## Content

- [What is this?](#what-is-this)
- [Features](#features)
- [Installation](#installation)
- [Installing `package using npm` globally](#installing-package-using-npm-globally)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

# What is this?

GitMarkdownPreview is an open-source and offline command-line interface (CLI) application/package designed for rendering local markdown files before committing them to GitHub.

## Features

- **Offline Conversion:** Convert Markdown files to HTML offline without the need for an internet connection.
- **Watch for Changes:** Automatically update the HTML output when changes are made to the input Markdown file.
- **GitHub Styling:** HTML output mirrors the GitHub Markdown style for consistency.
- **Code Block Highlighting:** Integrated [Starry Night](https://github.com/your-username/starry-night) ensures beautiful and syntax-highlighted code blocks.
- **Flowchart Support:** Display Mermaid flowcharts directly in the HTML output.

## `Installation`

```bash
# Clone the repository
git clone https://github.com/p-balu/git-markdown-preview.git

# Navigate to the project directory
cd git-markdown-preview

# Install dependencies
npm install

#To start the application locally
npm start `your/filepath/README.md`
```

## Installing `package using npm` globally

Install the package globally

```sh
npm i git-markdown-preview -g
```

### Start the application in 2 different ways

If you are already inside the directory where README.md file exists then run

```bash
gmark preview
```

#### or

```sh
gmark preview /path/toyour/README.md
```

## Configuration

You can customize the appearance of the HTML output by modifying the included CSS file (`styles.css`).

## Contributing

Contributions are welcome! Feel free to open issues, submit pull requests, or provide feedback.

## License

This project is licensed under the [MIT License](LICENSE).
