# JS QR Code Generator

A simple, client-side QR Code generator built with JavaScript. Generate QR codes directly in the browser — no server or external API calls required.

## Features

- Generate QR codes from any text or URL
- Multiple size options (50x50, 100x100, 150x150, 300x300, 500x500)
- Renders QR codes on an HTML5 Canvas using [qrcode.js](https://github.com/soldair/node-qrcode)
- Fully client-side — no backend or external API needed
- Responsive UI built with Bootstrap 5
- Reset button to clear input and generated QR code

## Project Structure

```
js-qr-code-generator/
├── index.html              # Main application page
├── css/
│   └── bootstrap.min.css   # Bootstrap 5 stylesheet
├── js/
│   ├── bootstrap.min.js    # Bootstrap 5 JavaScript
│   ├── jquery-2.2.4.min.js # jQuery library
│   └── qrcode.min.js       # QR code generation library
├── LICENSE
└── README.md
```

## How to Use

1. **Open the app** — Open `index.html` in any modern web browser. No build step or server required.
2. **Enter text** — Type or paste the text/URL you want to encode into the textarea.
3. **Select size** — Choose a QR code size from the dropdown (default is 500x500).
4. **Generate** — Click the **Generate QR Code** button to render the QR code on the canvas.
5. **Reset** — Click the **Reset** button to clear the input and QR code.

## Technologies Used

- HTML5 Canvas
- JavaScript (ES6)
- [qrcode.js](https://github.com/soldair/node-qrcode) — QR code rendering library
- Bootstrap 5 — UI framework
- jQuery 2.2.4

## License

See [LICENSE](LICENSE) for details.
