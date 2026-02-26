# ProMark - Professional Image Watermark Tool

A commercial-grade, single-file HTML tool designed to add highly customizable text and grid watermarks to your images. Built with modern web technologies, it features a sleek UI, zero-compression rendering, and a privacy-first local processing workflow.

![ProMark Preview](https://via.placeholder.com/800x450.png?text=ProMark+Interface+Preview) <!-- You can replace this link with an actual screenshot of your tool -->

## ✨ Key Features

*   🎨 **Modern UI Design**: A sleek, Tailwind/MacOS-inspired interface featuring soft shadows, smooth transitions, and custom-styled controls (sliders, toggles, color pickers).
*   🔒 **100% Privacy First**: Pure client-side processing using the HTML5 Canvas API. **No images are ever uploaded to any server.** Your data stays on your device.
*   💎 **Lossless Quality**: While the preview is scaled to fit your screen, the internal Canvas renders at the **exact original resolution** of your uploaded image. Exported images suffer zero quality loss.
*   ⚙️ **Advanced Customization**: 
    *   **Text Watermarks**: Custom text, color, opacity, size, density, and angle. Features a smart *staggered layout* for a natural, secure appearance.
    *   **Grid Watermarks**: Custom color, opacity, line thickness, density, and angle.
*   🛡️ **Edge-to-Edge Coverage**: Utilizes a diagonal-based rendering algorithm to ensure there are **no blind spots or empty corners**, regardless of how you rotate the watermark.
*   📋 **Seamless Workflow**: 
    *   **One-Click Copy**: Uses the native Clipboard API. Instantly copy the watermarked image and paste it directly into Slack, Teams, Word, or WeChat.
    *   **One-Click Export**: Download the full-resolution image as a PNG.

## 🚀 Quick Start

Since ProMark is built as a **Single-File Application**, installation is incredibly simple:

1. Create a new file named `index.html` on your computer.
2. Copy the entire HTML/CSS/JS code from the project and paste it into `index.html`.
3. Double-click the file to open it in any modern web browser (Chrome, Edge, Safari, Firefox).
4. Drag and drop an image into the drop zone and start watermarking!

## 🛠️ Tech Stack & Under the Hood

*   **HTML5 / CSS3**: Vanilla implementation without any external frameworks. Responsive layout using Flexbox.
*   **JavaScript (ES6)**: 
    *   `FileReader API` for local image loading.
    *   `CanvasRenderingContext2D` for high-performance image and watermark manipulation.
    *   `Clipboard API` (`navigator.clipboard.write`) for the one-click copy functionality.

## 🌐 Browser Compatibility

*   **Google Chrome** (Recommended)
*   **Microsoft Edge**
*   **Apple Safari**
*   **Mozilla Firefox**

*Note: The "One-Click Copy to Clipboard" feature requires a secure context (HTTPS or `localhost`) or local file execution (`file:///`) in modern browsers that support the `ClipboardItem` API.*

## 📄 License

This project is open-sourced under the [MIT License](https://opensource.org/licenses/MIT). Feel free to use, modify, and distribute it for both personal and commercial purposes.

---
*Created with ❤️ for a better and safer image sharing experience.*
