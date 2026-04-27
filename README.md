# Old Man's Whiteboard (老人的白板)

A lightweight, smooth, and powerful web-based digital whiteboard tool. Developed with native HTML5 Canvas and JavaScript, and styled with Tailwind CSS for a modern interface, it aims to provide an extremely simple yet feature-rich creative experience.

## 🚀 Live Demo

**[Try it now: https://eledgetw.github.io/whiteboard/](https://eledgetw.github.io/whiteboard/)**

## 🌟 Core Features

* **Fully Offline & Private**: Runs as a single HTML file. All drawing data is stored in the browser's local cache (LocalStorage), ensuring your privacy.
* **Powerful Graphic Editing**:
    * **Free Rotation & Scaling**: Objects can be rotated 360 degrees after selection. Images and shapes support free scaling.
    * **Lasso Tool**: Select multiple objects within an area for easy group movement or batch deletion.
    * **Layer Management**: Built-in "Bring to Front/Send to Back" and "Forward/Backward" functions to precisely control object overlapping.
* **Advanced Text System**:
    * Supports **Bullet Points (•)** and **Automatic Numbered Lists (1.)**.
    * Supports multi-level indentation (using the **Tab** key) with automatic list number recalculation.
    * Supports text alignment (Left, Center, Right) and dynamic font size adjustment.
* **Rich Drawing Tools**:
    * **Highlighter**: Translucent brush strokes with automatic color-layering effects.
    * **Laser Pointer**: A dynamic fading trail perfect for presentations and demonstrations.
    * **Smart Shapes**: Rectangles, Diamonds, Ellipses (with rounded corner settings), Arrows, and Lines.
* **Project Saving & Export**:
    * Export as **.json project files** to resume editing later.
    * Export as **.png images**.
    * **Auto-Resume**: After refreshing the page, the canvas content, zoom level, and view position are automatically restored.

## ⌨️ Keyboard Shortcuts (Hotkeys)

This project features an efficient hotkey system for a seamless workflow:

### Tool Switching
* `1`: Select
* `2`: Rectangle
* `3`: Diamond
* `4`: Ellipse
* `A`: Arrow
* `S`: Line
* `D`: Pencil
* `H`: Highlighter
* `T`: Text
* `L`: Lasso
* `F`: Laser Pointer
* `E`: Eraser

### Object Properties & Operations
* **Line Width**: `Q` (Thinnest) / `W` (Medium).
* **Quick Color Select**: `R` (Red) / `G` (Green) / `B` (Blue) / `Y` (Yellow).
* **Quick Duplicate**: Hold `Ctrl` / `Cmd` while dragging an object.
* **Axis Locking**: Hold `Shift` while drawing lines or moving objects to lock to horizontal/vertical directions.
* **Delete Object**: `Delete` or `Backspace`.

### Canvas Navigation
* **Pan Canvas**: Hold `Space`, use the `Scroll Wheel`, or `Right-click` and drag.
* **Zoom Canvas**: Hold `Ctrl` / `Cmd` and use the scroll wheel, or use two-finger pinch on tablets.
* **Undo/Redo**: `Ctrl+Z` / `Ctrl+Y`.

## 🚀 Interaction Tips

1.  **Paste Assets**: Paste images or text directly from your clipboard using `Ctrl+V`; the system will automatically optimize the display size.
2.  **Context Menu**: Long-press on the canvas (mobile) or right-click to bring up the menu for the paste function.
3.  **List Indentation**: In text editing mode, use `Tab` to increase indentation and `Shift+Tab` to decrease it; the system will automatically convert bullet points.

## 🛠️ Technical Details

* **Frontend Framework**: Tailwind CSS
* **Rendering Engine**: HTML5 Canvas API
* **Local Storage**: LocalStorage API
* **Compatibility**: Supports all modern browsers and touch operations on mobile devices.

## Support This Project
✨ Do you like this project? ✨
If this tool has saved you time ⏱️ or inspired your research 💡,
🧋 click the icon to buy me a pearl milk tea! 🧋

[![Buy me a Boba](https://s3.ap-southeast-1.amazonaws.com/media.anyonelab.com/images/boba/boba-embed-icon.png)](https://eledgetw.bobaboba.me) [![Buy me a Boba](https://s3.ap-southeast-1.amazonaws.com/media.anyonelab.com/images/boba/boba-embed-icon.png)](https://eledgetw.bobaboba.me) [![Buy me a Boba](https://s3.ap-southeast-1.amazonaws.com/media.anyonelab.com/images/boba/boba-embed-icon.png)](https://eledgetw.bobaboba.me)
←←(Click the Boba icon to support the author)

## 📝 Disclaimer

This project is a personal development tool designed to provide a convenient drawing experience for "Digital Twin" workflows. This software does not collect any user information; all drawing data remains locally on the user's device.
