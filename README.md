# Markdown Preview Copy Button

A lightweight VS Code extension that adds a **Copy** button to code blocks in the built-in Markdown preview.

## Features

- 📋 One-click copy for any fenced code block
- 🎨 Theme-aware styling (works with light and dark themes)
- ⚡ Lightweight — no dependencies, just CSS and JS injection
- 🤝 Plays nicely with other Markdown extension

## Usage

1. Open any Markdown file
2. Open the built-in Markdown preview (`Cmd+Shift+V` / `Ctrl+Shift+V`)
3. Hover over a code block to reveal the **Copy** button
4. Click to copy the code to your clipboard

## Installation

### From Marketplace

Search for "Markdown Preview Copy Button" in the VS Code Extensions view.

### From VSIX

```bash
code --install-extension markdown-copy-button-0.1.0.vsix
```

## Development

```bash
# Install dependencies
npm install

# Compile TypeScript
npm run compile

# Package extension
npm run package
```

To test locally, press `F5` to open an Extension Development Host.

## License

MIT
