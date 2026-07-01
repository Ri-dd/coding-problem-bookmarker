# MAANG.in Bookmark Chrome Extension

A lightweight Chrome Extension that enables users to bookmark coding problems directly from MAANG.in for quick access and organized problem tracking. The extension integrates seamlessly with the website, allowing users to save, view, open, and remove bookmarked problems through a simple popup interface.

---

## Features

- 📌 Bookmark coding problems directly from MAANG.in
- 💾 Persist bookmarks using Chrome Storage API
- 📂 View all saved problems from the extension popup
- ▶️ Open bookmarked problems in a new browser tab
- 🗑️ Remove bookmarks with a single click
- 🔄 Supports dynamic page navigation using MutationObserver
- ⚡ Built using Chrome Extension Manifest V3

---

## Tech Stack

- JavaScript (ES6)
- HTML5
- CSS3
- Chrome Extension Manifest V3
- Chrome Storage API
- DOM Manipulation
- MutationObserver

---

## Project Structure

```
.
├── assets/
│   ├── bookmark.png
│   ├── delete.png
│   ├── play.png
│   └── ext-icon.png
├── manifest.json
├── content.js
├── popup.html
├── popup.css
├── popup.js
├── background.js
└── README.md
```

---

## How It Works

1. The extension automatically injects a content script when a MAANG.in problem page is opened.
2. A bookmark button is dynamically added beside the problem interface.
3. Clicking the bookmark button stores the problem name and URL using Chrome Storage.
4. Clicking the extension icon opens a popup displaying all saved bookmarks.
5. Users can open bookmarked problems or remove them from the saved list.

---

## Installation

1. Clone this repository

```bash
git clone https://github.com/<your-username>/<repository-name>.git
```

2. Open Google Chrome.

3. Navigate to

```
chrome://extensions/
```

4. Enable **Developer Mode**.

5. Click **Load unpacked**.

6. Select the cloned project folder.

7. The extension is now ready to use.

---

## Concepts Demonstrated

- Chrome Extension Development (Manifest V3)
- Content Scripts
- Chrome Storage API
- DOM Manipulation
- Event Handling
- MutationObserver
- Dynamic UI Rendering
- Asynchronous JavaScript

---

## Future Improvements

- Search bookmarked problems
- Categorize problems by topic
- Difficulty-based filtering
- Solved/Unsolved status
- Export and import bookmarks
- Sync with external databases

---

## License

This project is licensed under the MIT License.
