# FileConvert Pro

A professional file conversion website with an iOS-style glassmorphism dark theme.

## 📁 Project Structure

```
fileconvert-pro/
├── index.html          → Everything in one file (HTML + CSS + JS)
├── .gitignore
└── README.md
```

> All styles and logic are inlined inside `index.html` so the site works by simply opening the single file — no server or build step needed.

## 🚀 How to Run

1. Clone the repo
   ```bash
   git clone <your-repo-url>
   cd fileconvert-pro
   ```

2. Open `index.html` directly in your browser. That's it.

## ✨ Features

- **Drag & drop** or click-to-browse file upload
- **6 format options** — PDF, DOCX, JPG, PNG, WebP, GIF
- **Animated progress bar** during conversion
- **Auto-download** of the converted file to your device
- **Toast notification** on successful download
- **Fully responsive** for desktop and mobile
- **Pure black theme** with animated glassmorphism orbs

## 📝 Notes

The current implementation downloads the original file with the new extension. To add real format conversion, integrate libraries such as:

- **pdf-lib** — create / manipulate PDFs
- **docx** — generate Word documents
- **sharp / canvas** — image format conversion

## 📜 License

MIT
