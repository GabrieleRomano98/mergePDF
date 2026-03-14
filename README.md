# mergePDF

A lightweight, client-side PDF merge tool. Select multiple PDF files, reorder or remove them as needed, and download a single merged document.

## How it works

All processing happens in the browser using [pdf-lib](https://pdf-lib.js.org/). No files are uploaded to any server.

## Usage

Visit the hosted version at [gabrieleromano98.github.io/mergePDF](https://gabrieleromano98.github.io/mergePDF/), or open `index.html` locally in any modern browser.

1. Click "Select PDF files" and choose one or more PDFs.
2. Remove any files you don't need by clicking the X next to them.
3. Click "Download" to merge and save the result as `merged.pdf`.

## Deployment

The app is deployed automatically to GitHub Pages on every push to `main` via GitHub Actions.
