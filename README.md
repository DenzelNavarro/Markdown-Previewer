# Markdown Previewer

This is a **Markdown Previewer** application built using React and JSX. It allows users to type Markdown in a text editor and view the formatted output in real time. This project demonstrates the use of React hooks, specifically `useState`, and utilizes the `react-markdown` library for rendering Markdown content.

## Features

- **Real-Time Preview:** Updates the preview as you type.
- **Markdown Syntax Support:** Supports various Markdown elements, including:
  - Headers
  - Inline and block code
  - Bold and italic text
  - Lists with varying indentation levels
  - Links
  - Blockquotes
  - Images
- **Responsive Design:** The application layout is responsive and adjusts to various screen sizes.

## Usage

1. Enter any Markdown text in the editor box on the left.
2. View the formatted output in the preview area on the right.

## Built With

- **React** - JavaScript library for building user interfaces
- **react-markdown** - Markdown renderer for React

## Code Overview

- **App.js** - Contains the main application logic. It initializes the state for the Markdown text, renders the textarea for input, and uses `react-markdown` to render the preview.
- **defaultMarkdown** - Provides a sample Markdown text with various elements to demonstrate formatting options.

## Example Markdown Syntax

```markdown
# Example Header

## Subheader
Inline code: \`<div></div>\`

\`\`\`
// Code block:
function example() {
  return true;
}
\`\`\`

**Bold Text**
- List item 1
  - Nested item
> Blockquote