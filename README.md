# Text Deformatter

A simple, clean web app that strips unwanted formatting from text copied from Microsoft Word and other word processors, making it ready to paste into HTML editors and WYSIWYG editors.

## Features

This tool removes all the annoying formatting issues that come from copying text from Word:

- **Extra spaces** at the end of lines and paragraphs
- **Multiple consecutive spaces** (reduced to single spaces)
- **Non-breaking spaces** and special Unicode spaces
- **Excessive line breaks** (more than 2 consecutive)
- **Tabs** (converted to spaces)
- **Carriage returns** (normalized to line feeds)
- **Zero-width characters** and other invisible formatting
- **Smart quotes** (converted to regular quotes)
- **Em dashes and en dashes** (converted to regular hyphens)
- **Special bullet points** (converted to asterisks)

## How to Use

1. **Open** `index.html` in any web browser
2. **Paste** your text from Word into the left textarea
3. The text is **automatically cleaned** in real-time
4. **Copy** the cleaned text using the "Copy Cleaned Text" button
5. **Paste** into your HTML editor or any other destination

## Usage

### Local Usage
Simply open the `index.html` file in your web browser. No server or installation required!

### Deploy to Web
You can deploy this to any static hosting service:
- GitHub Pages
- Netlify
- Vercel
- Any web server

## Technical Details

The app uses vanilla JavaScript to perform text cleaning operations including:
- Unicode character normalization
- Whitespace cleanup
- Special character conversion
- Line ending normalization

All processing happens in the browser - no data is sent to any server.

## Browser Support

Works in all modern browsers:
- Chrome/Edge
- Firefox
- Safari
- Opera

## License

Free to use and modify as needed.
