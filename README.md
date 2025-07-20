# Convert Scanned Books from TXT/PDF to Markdown
# Markdown Book Sample: *Sapiens – A Brief History of Humankind*

This repository contains a sample conversion of selected pages (pp. 1–9, 301) from the book *Sapiens* by Yuval Noah Harari into Markdown format. The goal is to demonstrate advanced data cleaning and formatting skills when working with unstructured PDF content, particularly scanned or OCR-generated documents.

## 📄 Contents

- `Markdown_Examples_clean_MD.md` – minimal Markdown version with custom anchors and reference links (best for GitHub or Pandoc).
- `Markdown_Examples_HTML_MD.md` – enhanced version with HTML elements for visual alignment and styling (best viewed in Typora or VS Code with Markdown Preview Enhanced).
- `yuval_noah_harari-sapiens_a_brief_histor.pdf` – source document used for conversion (excerpt only).
- Images are embedded via direct links from Dropbox using `dl.dropboxusercontent.com`, and display correctly in most Markdown previewers.

## 🔧 Formatting Approach

### ✅ Used Markdown Features:
- Headings for structured navigation.
- Internal links (anchors) to navigate between TOC and chapters.
- Proper image embedding with captions.
- Lists, block quotes, and emphasis to mirror original formatting.

### 💡 Optional HTML Tags:
Some content uses minimal HTML for precise layout:
- `<center>` for centered copyright blocks.
- `<br>` for spacing where Markdown doesn't support it natively.
- `<a id="...">` for custom anchor linking (e.g. `[See cover](#cover)`).

These do not affect Markdown compatibility if the file is viewed in Typora, MarkText, Obsidian, or exported via Pandoc/Quarto.

## 🔗 Image Hosting

All images are linked using direct access URLs via Dropbox. For example:

```markdown
![Cover](https://dl.dropboxusercontent.com/s/yourfileid/Image_001.jpg)
