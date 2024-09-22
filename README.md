# Full-Text Search Application

This Full-Text Search (FTS) application allows you to index and search the content of PDF, EPUB, and DOCX files in a folder or individually. The application also displays book cover previews for EPUB and PDF files. It uses a full-text search engine with SQLite's FTS5 for fast and efficient searching.

## Features
- **Index PDF, EPUB, and DOCX files** and search their contents.
- **Preview search results** with text snippets.
- **Display book covers** for EPUB and PDF files.
- **Progress tracking** for file indexing, with real-time status in the app.
- **Backup and restore index** using JSON.

## Requirements
- Python 3.7 or later
- PyQt5
- PyPDF2
- EbookLib
- Pillow
- python-docx
- PyMuPDF

## Installation and Setup

### 1. Clone the Repository
Clone this repository to your local machine or download the project files.

```bash
git clone https://github.com/your-username/full-text-search-app.git
cd full-text-search-app
