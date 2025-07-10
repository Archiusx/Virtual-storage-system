# Virtual-storage-system
# 📁 Mobile File Manager (IndexedDB + Folders + Long-Press Menu)

A **mobile-friendly web-based file manager** that mimics a native OS interface using `IndexedDB` for offline storage. Supports folders, context menus, file previews, and common file operations — all optimized for touch devices and mobile browsers.

## 🌟 Features

- 📂 **Folder support** – create and navigate virtual folders.
- 📤 **Upload files** – drag-and-drop or select from your device.
- 👆 **Long-press menu** – context menu for touch devices.
- 👁️ **Preview** – inline preview for images, PDFs, audio, video, text, and HTML.
- 📎 **Clipboard actions** – cut, copy, paste files and folders.
- 💾 **Save** – download files to your device.
- 🗑️ **Delete** – remove items from the virtual file system.
- 🔙 **Back navigation** – return from folders to root.

## 🛠 Technologies Used

- **HTML5**
- **CSS3**
- **Vanilla JavaScript**
- **IndexedDB** (for offline persistent file storage)
- **Base64 encoding** (for file content preview and download)

## 📱 Mobile Optimized

- Responsive layout using CSS grid and media queries.
- Touch support for long-press gestures.
- Minimalist UI inspired by Windows file explorer.

## 🔧 How to Use

1. Open the HTML file in a modern browser (preferably mobile).
2. Use the **Upload** button to add files.
3. Tap **New Folder 📁** to create folders.
4. Long-press (or right-click) on a file to open the context menu.
5. Double-tap (or double-click) a folder to enter it.

## 📦 File Structure

This project is contained entirely in a **single HTML file**, with all UI, logic, and styles embedded.

## 🧪 Known Limitations

- Files are stored **locally** only — no cloud sync unless integrated with Firebase.
- No advanced search or sort features (yet).
- Folder hierarchy is flat (one level deep).
