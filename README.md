# 📚 EPUB Professional Editor

[![GitHub license](https://img.shields.io/github/license/BR1JM0H4N/Epub-editor?style=for-the-badge)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/BR1JM0H4N/Epub-editor?style=for-the-badge&color=yellow)](https://github.com/BR1JM0H4N/Epub-editor/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/BR1JM0H4N/Epub-editor?style=for-the-badge&color=green)](https://github.com/BR1JM0H4N/Epub-editor/network/members)
[![Demo Live](https://img.shields.io/badge/Demo-Live-brightgreen?style=for-the-badge&logo=vercel)](https://br1jm0h4n.github.io/Epub-editor/)

A powerful, client-side, single-page application (SPA) for professionally editing EPUB files, built entirely with **HTML, CSS (Android 15 Dark Theme), and Vanilla JavaScript**.

The editor allows users to load an EPUB file, perform common fixes and edits, and download the modified file—all without server-side processing.

## ✨ Features

This editor is designed to streamline the EPUB preparation process with a focus on fixing common metadata and structural issues.

| Feature | Description |
| :--- | :--- |
| **Metadata Editing** | Modify core EPUB metadata like **Title**, **Author**, **Language**, and **Publisher**. |
| **Cover Replacement** | Easily replace the cover image, with automatic updates to the OPF manifest (`item` and `<meta name="cover">`). |
| **Cover Structure Fix** | Option to **Ensure cover is the first item in spine order** to correct reading flow. |
| **Front Page Generator** | **Add Front Page** feature to automatically create a simple XHTML wrapper for the cover image and insert it as the first spine item if a proper cover wrapper is missing. |
| **Table of Contents (TOC)** | **Generate/Replace TOC (NCX)** by scanning chapter files using a customizable **CSS Selector** (e.g., `h1, h2, .chapter-title`). |
| **Bulk Find & Replace** | Apply multiple, non-global, or **RegEx** based text replacement rules across *all* chapter (XHTML/HTML) files in the EPUB package. |
| **Client-Side Only** | All processing is done locally in the browser for **speed and privacy**. |
| **Modern UI** | Utilizes an **Android 15 Dark Theme** inspired design for a clean and focused experience. |

## 🛠️ Technology Stack

* **Frontend:** HTML5, CSS3 (Vanilla), JavaScript (Vanilla)
* **Key Library:** **[JSZip](https://stuk.github.io/jszip/)** for reading, modifying, and writing `.zip` files (EPUB format).
* **Styling:** Custom CSS implementing a modern, dark-themed UI.

## 🚀 Getting Started

Since this is a client-side application, you can use it immediately by visiting the demo link or by cloning the repository and opening the `index.html` file in your web browser.

### Using the Live Demo

1.  Navigate to the **[EPUB Professional Editor Demo](https://br1jm0h4n.github.io/Epub-editor/)**.
2.  Click **"Choose File"** and select your `.epub` file.
3.  The metadata fields will populate automatically.
4.  Make your desired edits in the Metadata, Cover, or TOC sections.
5.  Use the **"Open Find & Replace Tool"** to set up bulk text replacement rules.
6.  Click **"Generate & Download EPUB"** to save your modified file.

### Local Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/BR1JM0H4N/Epub-editor.git](https://github.com/BR1JM0H4N/Epub-editor.git)
    cd Epub-editor
    ```
2.  **Open `index.html`** in your browser.

> **Note:** The application uses standard browser APIs and does not require any build tools or local servers.

## 🤝 Contribution

Contributions are welcome! If you have suggestions for new features, bug fixes, or improvements to the styling or core logic, please feel free to open an issue or submit a pull request.

1.  Fork the Project.
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your Changes (`git commit -m 'feat: Add amazing feature'`).
4.  Push to the Branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

## 📄 License

Distributed under the **MIT License**. See `LICENSE` for more information.
