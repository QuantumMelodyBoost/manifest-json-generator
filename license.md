# Manifest Json Generator

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:FF416C,100:FF4B2B&height=220&section=header&text=Manifest%20Json%20Generator&fontSize=60&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=Create%20Perfect%20Web%20App%20Manifests%20In%20Seconds&descAlignY=55&descSize=20)

<div align="center">

![Version](https://img.shields.io/badge/version-2.1.0-FF4B2B?style=for-the-badge&logo=git&logoColor=white)
![Downloads](https://img.shields.io/badge/downloads-91.4K-FF416C?style=for-the-badge&logo=download&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-00E676?style=for-the-badge&logo=opensourceinitiative&logoColor=white)
![Platform](https://img.shields.io/badge/platform-web%20%7C%20vscode-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

</div>

---

## 🚀 The Fastest Way To Build PWA Manifests

Progressive Web Apps (PWAs) are the future of the web. They offer the speed of a website with the functionality of a native app. However, creating a perfect `manifest.json` file is often a tedious, error-prone process. A single typo in the JSON structure, a missing icon path, or an incorrect theme color can prevent your app from being installable on Android, iOS, or Windows.

**Manifest Json Generator** is a beautifully designed, open-source tool that eliminates this friction. It provides a visual, interactive interface for building your PWA manifest. Instead of writing raw JSON, you simply fill out a form: upload your icons, select your theme colors, choose your display mode, and the tool automatically generates the perfectly formatted JSON code.

This repository is designed for web developers, indie hackers, and agencies. It includes a web-based UI and a powerful VS Code extension. The tool validates your input in real-time, warns you about common pitfalls (like missing `maskable` icons for Android), and even generates the necessary HTML `<link>` tags to include in your `index.html` file.

<img width="1672" height="941" alt="0787b01a-2bb8-46e5-b0bd-a8bdf26f2b55" src="https://github.com/user-attachments/assets/80585a84-0a78-4eea-af05-e14b40585b62" />


---

## ✨ Core Features

| Feature | Description |
|---------|-------------|
| 🎨 **Visual Editor** | A sleek UI to configure every aspect of your manifest |
| 🖼️ **Icon Generator** | Automatically resize your source image into all required PWA sizes |
| 🛡️ **Maskable Icons** | Specialized preview to ensure your icons look great on Android |
| 🎯 **Real-Time Validation** | Instantly catches errors like missing required fields or bad hex codes |
| 📋 **One-Click Copy** | Copy the generated JSON and HTML tags directly to your clipboard |
| 🧩 **VS Code Extension** | Generate manifests directly within your IDE |
| 🌓 **Dark/Light Mode** | A stunning interface that adapts to your environment |
| 📦 **Presets** | Quick-start templates for common app types (e-commerce, blog, tool) |

---

## 🚀 Quick Setup

You can use the web version immediately, or run it locally. You will need Node.js 18+ installed on your machine.

```bash
# Clone the repository
git clone https://github.com/your-username/manifest-json-generator.git

# Navigate into the directory
cd manifest-json-generator

# Install the required dependencies
npm install

# Start the local development server
npm run dev
```

Once the server is running, open your browser and navigate to `http://localhost:3000`. You will be greeted by the intuitive dashboard. Start by uploading your high-resolution logo, and the tool will automatically generate all the icon variants. Then, use the color pickers to set your theme and background colors.

---

<div align="center">

### 🔗 Ready to build your manifest?

[![Get Tool](https://img.shields.io/badge/🚀_GET_TOOL-FF416C?style=for-the-badge&logoColor=white)](https://share.google/xzBJwYwlPwS98mzKM)

</div>

---

## 🧠 Under The Hood: Why Manifests Matter

A Web App Manifest is a simple JSON file that tells the browser how your app should behave when installed on a user's device. It defines the app's name, icons, start URL, and display mode. If this file is missing or malformed, the browser will not prompt the user to install your app.

The most common issue developers face is **icon compatibility**. Android requires a 512x512 icon and a separate "maskable" icon that allows the OS to crop it into a circle or squircle without cutting off important content. iOS requires a 180x180 `apple-touch-icon`. Our generator handles all of this automatically.

The tool is built with React and uses `sharp` (via an API route) to resize images on the fly. The output JSON is strictly formatted according to the W3C specification, ensuring maximum compatibility across all browsers and operating systems.

---

<div align="center">

### ⚙️ Need a detailed configuration guide?

[![Setup Guide](https://img.shields.io/badge/📖_VIEW_SETUP_GUIDE-FF4B2B?style=for-the-badge&logoColor=white)](https://share.google/xzBJwYwlPwS98mzKM)

</div>

---

## 🛠️ Tech Stack

<div align="center">

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Sharp](https://img.shields.io/badge/Sharp-99CC00?style=flat-square&logo=sharp&logoColor=white)

</div>

---

## 🤝 Community & Contributing

PWA development is a rapidly evolving field. If you have suggestions for new features, bug fixes, or want to add support for a new platform (like Windows PWA packaging), we welcome your contributions!

1. **Fork** the repository.
2. **Create** your feature branch (`git checkout -b feature/new-preset`).
3. **Commit** your changes (`git commit -m 'Add new preset'`).
4. **Push** to the branch (`git push origin feature/new-preset`).
5. **Open** a Pull Request.

Please read our `CONTRIBUTING.md` for detailed coding standards and testing requirements. We also have an active Discord server where you can share your generated manifests, ask for help with PWA caching, and discuss the latest trends in web development.

---

## 📬 Contact & Support

- 💬 **Discussions:** Join the conversation in the GitHub Discussions tab.
- 🐛 **Issues:** Found a bug? Let us know via the Issues tracker.
- 📧 **Email:** Reach out directly at support@manifest-gen.dev.

---

<div align="center">

### ⭐ If this tool saves you time, give it a star! ⭐

[![Star](https://img.shields.io/badge/⭐_STAR_THIS_REPO-00E676?style=for-the-badge&logo=github&logoColor=white)](https://github.com/your-username/manifest-json-generator)

---

### 🚀 Start generating your manifest today

[![Get Started](https://img.shields.io/badge/🚀_GET_STARTED_GUIDE-007ACC?style=for-the-badge&logoColor=white)](https://share.google/xzBJwYwlPwS98mzKM)

<sub>Crafted with precision and ❤️ by the Manifest Json Generator community</sub>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:FF4B2B,100:FF416C&height=120&section=footer)

</div>
