# PDF Splitter
Minimal web app to extract specific pages from a PDF.
No signup.
No API.
Just clean splitting.

---

## Features
- Extract selected pages from any PDF (max 100MB)
- Drag & drop support
- **Page thumbnails** with visual preview
- **Click to select** individual pages
- **Shift+click** for range selection
- **Select all** with one click (or Cmd/Ctrl+A)
- Custom **file naming**
- Dark/Light **theme toggle**
- Real-time **progress bar**
- **Keyboard shortcuts** (Space to split, ESC to clear)
- No authentication
- No ads
- No watermarks

---

## Tech Stack
- React (Create React App)
- PDF.js (PDF rendering)
- jsPDF (PDF creation)
- Tailwind CSS (Apple-inspired UI)
- Lucide React (icons)
- Vercel (static deploy)

---

## How It Works
1. Upload a PDF (or drag & drop)
2. Everything is processed fully in the browser
3. Click pages to select (shift+click for range)
4. Customize the output filename
5. Press Space or click "Extract" button
6. Download your new PDF with selected pages

> All pages show thumbnails automatically for easy selection.

---

## Keyboard Shortcuts
- **Space** → Extract selected pages
- **ESC** → Clear file
- **Cmd/Ctrl + A** → Select/deselect all pages
- **Shift + Click** → Select range of pages

---

## Privacy
All processing happens **locally in your browser**.
No PDFs are uploaded to a server.
Your files never leave your device.

---

## Installation
```bash
# Clone the repo


# Install dependencies
cd pdf-splitter
npm install

# Run locally
npm start
```

---

## Limits
- Maximum **100 MB** file size
- High quality output (scale: 2, compression: 95%)

---

Built by **[@berkindev](https://instagram.com/berkindev)** as part of **30 Days – 30 Web Apps**.
