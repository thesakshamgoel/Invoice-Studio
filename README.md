# Invoice Studio 🧾✨

**Invoice Studio** is a modern, responsive, Google Workspace / Material 3 inspired professional invoice and agreement generator. Designed for freelancers, creative studios, and independent agencies who need pixel-perfect, print-ready, and PDF invoices with real-time live preview.

Now fully optimized as an **App-like Progressive Web App (PWA)** with native mobile ergonomics, offline support, touch pinch-to-zoom, and 1-tap installation to home screens.

---

## 🌟 Key Features

- 📱 **Mobile & PWA App Experience**: 
  - Installable to home screens (Android, iOS Safari, macOS, Windows) with standalone display mode.
  - Offline capability powered by Service Worker caching.
  - Native mobile bottom navigation bar (`Editor`, `Preview`, `Pages`, `PDF/Print`).
  - Floating Action Button (FAB) for seamless 1-tap switching between forms and live preview.
  - Responsive preview canvas that automatically fits mobile screens with 2-finger touch pinch-to-zoom.
- 🎨 **Material 3 / Google Workspace Dark UI**: Sleek, distraction-free interface with polished micro-interactions and smooth transitions.
- 👁️ **Live Interactive Canvas**: Real-time rendering with zoom, pan, and direct-on-canvas editing.
- 💼 **Multi-Profile Management**: Save and switch business profiles, creator contact info, custom brand logos, and UPI/Payment QR codes.
- 📊 **Dynamic Itemized Billing**: Add, reorder, and configure line items with automated calculations for discounts, subtotals, taxes (GST/VAT), and grand totals.
- 📜 **Custom Terms & Agreements**: Rich terms editor with direct support for custom PDF terms attachments via PDF.js.
- 🖨️ **Print & PDF Ready**: Precision print stylesheets and PDF rendering to ensure standard A4 high-resolution documents without scaling artifacts.
- 🚀 **Zero External Server Dependencies**: Runs completely in the browser as a standalone web application.

---

## 📁 Project Structure

```text
Invoice-Studio/
├── index.html              # Main application entry point (GitHub Pages & PWA ready)
├── invoice_generator.html  # Dedicated generator standalone app
├── manifest.json           # Web App Manifest for mobile/desktop PWA installation
├── sw.js                   # Service Worker for offline caching & fast loading
├── favicon.png             # High-resolution brand favicon & app icon (776x776)
├── favicon.ico             # Fallback browser icon
├── logo.png                # Default studio branding asset
├── qr.jpg                  # Payment QR code asset
├── .gitignore              # Ignored files and local build scripts
└── README.md               # Documentation
```

---

## 🚀 Quick Start

### 1. Run Directly in Browser
Simply clone or download this repository and open `index.html` (or `invoice_generator.html`) in any modern web browser:

```bash
git clone https://github.com/thesakshamgoel/Invoice-Studio.git
cd Invoice-Studio
```

Double click `index.html` or open it with your browser.

### 2. Install as a Mobile / Desktop App (PWA)
- **On Mobile (Chrome/Android)**: Tap the "Install App" button in the app or choose "Add to Home screen" in browser options.
- **On iPhone / iPad (Safari)**: Tap the Share button ⎋ > "Add to Home Screen" ⊕.
- **On Desktop (Chrome / Edge)**: Click the Install icon in the browser address bar.

### 3. Run with Local HTTP Server (Optional)
If you prefer running via a local dev server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .
```
Then navigate to `http://localhost:8000`.

### 4. Deploy to GitHub Pages
1. Go to repository **Settings** > **Pages**.
2. Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
3. Select the `main` branch and `/ (root)` folder.
4. Click **Save**. Your Invoice Studio app will be live on the web instantly!

---

## 🛠️ Built With

- **HTML5 & Vanilla CSS3**: Custom Google Dark / Material 3 Design System.
- **Modern JavaScript (ES6+)**: Zero framework overhead, instantaneous performance.
- **Service Worker & Web Manifest**: Complete PWA offline and install capability.
- **PDF.js**: Client-side high-fidelity rendering for custom PDF terms and agreements.
- **Google Fonts**: Inter, Caveat, and Dancing Script typography.

---

## 👤 Author

**Saksham Goel**
- GitHub: [@thesakshamgoel](https://github.com/thesakshamgoel)
- Email: thesakshamgoel@gmail.com

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
