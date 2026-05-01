# Winecalcs

## Avvio locale

Prerequisiti: Node.js 18+

```bash
npm install
npm start
```

Apri `http://localhost:3000`.

## Build locale

```bash
npm run build
```

Genera `dist/index.html`.

## Funzionalità PDF

- Lettura multipagina con parsing testuale ordinato per pagina.
- Fallback OCR (`tesseract.js`) quando il testo nativo non è disponibile.
- Estrazione immagini PDF in ZIP (`pdf_images/page-<n>.png`) con associazione alla pagina.
