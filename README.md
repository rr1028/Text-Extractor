# Text Extraction and Image Enhancement Tool

## Overview
This project is a Python-based tool designed to extract text from images and PDF documents while enhancing image quality. The tool uses Optical Character Recognition (OCR) for text extraction and provides image enhancement features to improve clarity and accuracy. It aims to make the process of extracting information from various document formats easier and more effective.

## Features

### 1. Text Extraction
- **Image Files**: Extracts text from `.png`, `.jpg`, and `.jpeg` formats using `pytesseract`.
- **PDF Files**: Extracts text from PDF documents using the `pypdf` library.

### 2. Image Enhancement
- Enhances image quality using the `Wand` library, which performs auto-level correction and other image enhancement techniques to improve readability.
- Allows saving of enhanced images for future use.

### 3. User Interface
- Built with `Tkinter`, providing a simple, user-friendly layout.
- Users can upload images or PDFs and view extracted text in a scrollable window.
- Option to apply image enhancement before text extraction for better results.

## Use Cases
This tool can be applied in scenarios that require automated text extraction and image processing, such as:
- Digital document management
- Data digitization and archival

## Technologies and Libraries

### 1. Text Extraction from Images
- **Algorithm**: Optical Character Recognition (OCR)
- **Libraries**: `pytesseract`, `PIL` (Python Imaging Library)

### 2. Text Extraction from PDFs
- **Algorithm**: PDF text parsing
- **Library**: `pypdf`

### 3. Image Enhancement
- **Library**: `Wand` (for image processing)

## Getting Started

### Prerequisites
- **Python 3.x**
- **Libraries**:
  - `pytesseract`
  - `pypdf`
  - `Pillow` (PIL)
  - `Wand`
  - `Tkinter` (for GUI)

You may install these libraries using the following commands:

```bash
pip install pytesseract pypdf Pillow Wand
