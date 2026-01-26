# 📎 ezClip: Effortless Snippet & Clipboard Manager

| Status | Deploy Link | Deploy Link 2 |
| :---: | :---: | :---: |
| Stable | [https://rustbasic.github.io/](https://rustbasic.github.io/) | [https://rustbasic.github.io/ezclip/](https://rustbasic.github.io/ezclip/) | 

---

## 🚀 Overview

**ezClip** is a fast and persistent desktop/web application built with Rust and Egui, designed to help you manage frequently used text snippets, code blocks, and clipboard content efficiently. Stop repetitive typing and save time by organizing your text clips into customizable categories, ready for instant access and copying.

## ✨ Key Features

*   **Category-Based Organization:** Structure your clips using personalized categories (e.g., Personal, Work, Templates, APIs).
*   **Persistent Storage:** Your categories and items are automatically saved and restored on shutdown, ensuring your data is always safe.
*   **One-Click Copy:** Easily copy any stored item to the clipboard with a single click on the "Copy" button or by double-clicking the text input field.
*   **Flexible UI Layout:** Toggle the category panel between the **Left** and **Right** side using the `L⇔R` button for optimized workflow.
*   **Notepad Mode:** Switch to a dedicated "Notepad Mode" to view and edit all items within the selected category as a single, multi-line text block. This is perfect for bulk editing or importing lists.
*   **Easy Management:** Seamlessly add, delete, and rearrange both categories and individual items using dedicated buttons (`+ Add`, `↑`, `↓`, `🗑`).
*   **Clipboard Monitoring (Desktop):** Display the last copied text in the bottom panel for quick reference.

## 🛠 Built With

*   **Rust:** For performance and reliability.
*   **eframe/egui:** For a responsive, cross-platform graphical user interface.

## 💡 How to Use

1.  **Access:** Open the ezClip Web Application here: [https://rustbasic.github.io/](https://rustbasic.github.io/) or [https://rustbasic.github.io/ezclip/](https://rustbasic.github.io/ezclip/)
2.  **Manage Categories (Side Panel):** Use the left/right panel to create new categories (`+ Add`) or rearrange them. Click on a category name to select it.
3.  **Manage Items (Central Panel):** Once a category is selected, the central panel displays the individual items (snippets). Use the `+ Add` button to add new items.
4.  **Copy:** Double-click any item's text field, or press the dedicated `Copy` button next to it.
5.  **Bulk Edit:** Use the **NotePad Mode** button to transition the items into a single text editor for easy mass modification. When you switch back, the lines are converted back into individual items.
