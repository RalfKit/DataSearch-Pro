<h1 align="center">
  <img
    src="./static/favicon.svg"
    width="128"
    alt="DataSearch-Pro Logo"
    style="padding: 5px; border-radius: 8px"
  />
  <br />DataSearch Pro
</h1>

<div align="center">

[![GitHub Issues](https://img.shields.io/github/issues/RalfKit/DataSearch-Pro?style=flat-square)](https://github.com/RalfKit/DataSearch-Pro/issues)
[![GitHub All Releases](https://img.shields.io/github/downloads/RalfKit/DataSearch-Pro/total?style=flat-square)](https://github.com/RalfKit/DataSearch-Pro/releases)
[![GitHub Release (latest SemVer)](https://img.shields.io/github/v/release/RalfKit/DataSearch-Pro?style=flat-square)](https://github.com/RalfKit/DataSearch-Pro/releases)
[![GitHub License](https://img.shields.io/github/license/RalfKit/DataSearch-Pro?style=flat-square)](https://github.com/RalfKit/DataSearch-Pro/blob/main/LICENSE)

</div>

## 📌 Overview

A local-first full-text search and document indexing tool with OCR support, designed for exploring file-based data without relying on cloud services.

DataSearch Pro acts as a lightweight **Document Management System (DMS)** for personal and experimental use cases. It automatically indexes files, extracts content, and enables fast search across both file names and contents.

## 📌 Status

This project is currently not actively developed.

It remains available as a functional prototype demonstrating full-text indexing, OCR integration, and automated file monitoring in a desktop environment.

## 🚀 Key Characteristics

- Full-text search across file contents
- Local-first architecture (no cloud, no server)
- Automatic indexing and folder monitoring
- OCR support for images and embedded content
- Tagging and prioritization system
- Designed for desktop usage (Tauri-based)

## Why DataSearch Pro?

- **Content-Based Search:** Find files by what’s inside, not just by name
- **Automation:** Files are automatically indexed and updated when changed
- **Offline First:** Works completely without internet access
- **Flexible Organization:** Use tags, priorities, and filters
- **Broad Format Support:** Works with documents, images, and structured files

## ✨ Features

- **Tags and Prioritization:** Organize and highlight important files
- **Automatic Indexing:** Detects and processes new or changed files
- **Folder Monitoring:** Continuous tracking of selected directories
- **Parallel Processing:** Faster indexing of large datasets
- **File Filtering:** Control which file types are indexed
- **Database Cleanup:** Remove stale entries automatically
- **Light/Dark Themes**
- **Auto-start indexing and monitoring**
- Optional logging and error tracking

## 🔎 Supported File Formats

### Text

`txt`, `csv`, `tsv`, `log`, `md`, `ini`, `yaml`, `yml`, `json`

### Documents

`pdf`, `docx`, `xlsx`, `pptx`, `odt`, `ods`, `odp`, `docm`, `rtf`

### Images (OCR)

`png`, `jpg`, `jpeg`

### Web / Structured

`html`, `htm`, `xhtml`, `svg`, `xml`

### Notes

- Images are processed using OCR
- OCR can optionally be applied to embedded images (e.g. inside PDFs or Office files)

## 🧱 Architecture

- Desktop application built with Tauri
- Local database for indexed content
- File watcher for automatic updates
- OCR pipeline for image processing

## 📌 Limitations

- Not actively maintained
- No guaranteed stability for large-scale usage
- No distributed or multi-user support
- Index must be rebuilt if configuration changes significantly

## 🤔 When to Use

Use this project if you:

- Need full-text search across local files
- Want an offline, self-contained solution
- Are exploring DMS or indexing concepts
- Work with mixed file types (documents, images, structured data)

## 🚫 When Not to Use

Avoid this project if you:

- Need a production-ready DMS
- Require multi-user or server-based architecture
- Expect continuous updates or long-term support
- Need enterprise-grade reliability

## 🧠 Concept

DataSearch Pro explores the idea of shifting file search from simple filename matching to **content-aware indexing**.

By preprocessing files and extracting their content (including OCR), it enables significantly more powerful search capabilities compared to traditional filesystem search.

## 🛠️ Tech Stack

- Tauri
- SvelteKit
- OCR (image text extraction)
- Local database (indexed content storage)

## 🤝 Notes

This project was created as an experimental prototype to explore full-text indexing, OCR integration, and automated file monitoring in a local-first environment.
