# Kindle Clippings Viewer

A lightweight, single-page web application to parse, organize, and explore your Amazon Kindle highlights. This tool runs entirely in your browser using a single HTML file—no server, build steps, or installation required.

## 🚀 Features

-   **Instant Parsing:** Drag and drop or select your `My Clippings.txt` file to instantly organize thousands of highlights.
    
-   **Smart Organization:** Group highlights by Book and Author.
    
-   **Duplicate Removal:** Automatically detects and merges overlapping highlights (common when re-highlighting to expand a selection).
    
-   **Sticky Headers:** Book titles remain visible at the top of the screen while you scroll through their highlights.
    
-   **Privacy Focused:** 100% Client-side processing. Your personal reading data never leaves your device.
    
-   **Export Tools:**
    
    -   **Copy to Clipboard:** Copy formatted highlights for a specific book with one click.
        
    -   **Download:** Export individual books as clean text files.
        

## ⌨️ Keyboard Shortcuts

Navigate your library efficiently without touching the mouse:

* **Arrow Down** - Move to next highlight (auto-expands book if needed)

* **Arrow Up** - Move to previous highlight

* **Page Down** - Jump to next book title

* **Page Up** - Jump to previous book title

* **Enter** - Expand/Collapse the currently selected book

* **Home** - Scroll to the very top

* **End** - Scroll to the very bottom

## 🛠️ Tech Stack

-   **HTML5 & Vanilla JavaScript:** Core logic and structure.
    
-   **Tailwind CSS (CDN):** Utility-first styling for a clean, responsive UI.
    
-   **Lucide Icons (CDN):** Beautiful, consistent iconography.
    

## 📋 How to Use

1.  **Connect** your Kindle to your computer via USB.
    
2.  **Navigate** to the `documents` folder on the Kindle drive.
    
3.  **Copy** the `My Clippings.txt` file to your computer.
    
4.  **Open** `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari).
    
5.  **Click** "Select File" and choose your `My Clippings.txt`.
    

## 🤝 Contributing

Since this is a single-file application, you can edit `index.html` directly to make changes.

1.  Open `index.html` in a code editor (VS Code, Sublime Text, etc.).
    
2.  Modify the JavaScript logic inside the `<script>` tags or styles in `<style>`.
    
3.  Refresh your browser to see changes.
    

## 📄 License

Distributed under the MIT License.
