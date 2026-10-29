# Rgb Generator Colors

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:8E2DE2,100:4A00E0&height=220&section=header&text=Rgb%20Generator%20Colors&fontSize=65&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=Create%20Perfect%20Color%20Palettes%20For%20Your%20Projects&descAlignY=55&descSize=20)

<div align="center">

![Version](https://img.shields.io/badge/version-2.1.0-4A00E0?style=for-the-badge&logo=git&logoColor=white)
![Downloads](https://img.shields.io/badge/downloads-94.2K-8E2DE2?style=for-the-badge&logo=download&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-FF5252?style=for-the-badge&logo=opensourceinitiative&logoColor=white)
![Platform](https://img.shields.io/badge/platform-web%20%7C%20mobile-00C9FF?style=for-the-badge&logo=react&logoColor=white)

</div>

---

## 🎨 The Ultimate Color Toolkit

Color is the most powerful tool in a designer's arsenal. It evokes emotion, establishes hierarchy, and defines brand identity. However, finding the perfect color combination or converting between RGB, HEX, HSL, and CMYK can be a tedious, error-prone process. **Rgb Generator Colors** is a beautifully crafted, open-source web application designed to eliminate that friction.

This repository provides a comprehensive suite of color tools in one sleek, intuitive interface. It is not just a color picker; it is a complete color engine. It features a sophisticated palette generator that uses color theory (complementary, analogous, triadic) to create harmonious combinations. It includes a contrast checker to ensure your text meets WCAG accessibility standards, and a gradient builder for creating stunning CSS backgrounds.

Whether you are a web developer writing CSS, a UI/UX designer creating a design system, or a hobbyist working on a personal project, this tool will become an indispensable part of your workflow. It runs entirely in your browser, requires no installation, and stores your favorite palettes locally for quick access.

<img width="2000" height="2102" alt="nc0i7RlBnH6SA7KnIQUZ9kQBHRs" src="https://github.com/user-attachments/assets/a46bafac-9f0f-49a3-b141-829ecb5a330c" />


---

## ✨ Core Features

| Feature | Description |
|---------|-------------|
| 🎨 **Dynamic Picker** | An interactive, drag-and-drop color wheel with real-time updates |
| 🔄 **Multi-Format Conversion** | Instantly convert between HEX, RGB, HSL, and CMYK |
| 📊 **Palette Generator** | Create complementary, analogous, and triadic color schemes |
| 🛡️ **Contrast Checker** | Test your text/background combinations against WCAG AA and AAA |
| 🌈 **Gradient Builder** | Visually design linear and radial gradients and copy the CSS |
| 📋 **One-Click Copy** | Copy any color code to your clipboard with a single tap |
| 💾 **Local Storage** | Save your favorite palettes directly in your browser |
| 🌓 **Dark Mode** | A stunning, eye-friendly interface for late-night design sessions |

---

## 🎨 How To Master The Color Engine

We have designed this tool to be instantly intuitive, but here is how you can get the most out of it.

### 🖱️ The Interactive Picker
The heart of the app is the interactive color picker. You can drag the cursor across the color spectrum to visually select your base color. The tool instantly updates the HEX, RGB, and HSL values. You can also type a specific code directly into the input field if you already have a brand color in mind.

### 🌈 Building Harmonies
Once you have your base color, click on the "Harmonies" tab. The tool automatically generates a palette based on color theory. If you select "Complementary," it finds the exact opposite color on the wheel. If you select "Analogous," it finds the colors adjacent to your base. You can click on any generated color to make it the new base and continue exploring.

### 🛡️ Accessibility Testing
Accessibility is not optional. In the "Contrast" tab, you can input your text color and background color. The tool calculates the contrast ratio and tells you if it passes WCAG standards. If it fails, it suggests slight adjustments (like darkening the text) to make it accessible without ruining your design.

---

<div align="center">

### 🔗 Ready to find your perfect colors?

[![Get Tool](https://img.shields.io/badge/🎨_GET_TOOL-8E2DE2?style=for-the-badge&logoColor=white)](https://share.google/x87uVAIj13rvzZcjz)

</div>

---

## 🧠 Under The Hood: The Math Of Color

Converting between color spaces is not as simple as it seems. While HEX and RGB are relatively easy to convert (HEX is just a base-16 representation of RGB), converting to HSL (Hue, Saturation, Lightness) requires complex mathematical formulas.

For example, to convert RGB to HSL, the algorithm first normalizes the RGB values to a range of 0 to 1. It then finds the maximum and minimum values to calculate the "Lightness." The "Saturation" is calculated based on the difference between the max and min. The "Hue" is calculated using a series of conditional statements based on which color channel (Red, Green, or Blue) is the maximum.

This tool handles all of these calculations instantly using highly optimized JavaScript functions. It also uses the `color-convert` library under the hood for edge-case accuracy, ensuring that your CMYK values are print-ready.

---

<div align="center">

### ⚙️ Need a detailed configuration guide?

[![Setup Guide](https://img.shields.io/badge/📖_VIEW_SETUP_GUIDE-4A00E0?style=for-the-badge&logoColor=white)](https://share.google/x87uVAIj13rvzZcjz)

</div>

---

## 🛠️ Tech Stack

<div align="center">

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Color Convert](https://img.shields.io/badge/Color_Convert-FF5252?style=flat-square&logo=javascript&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

## 🤝 Community & Contributing

Color is a universal language, and we want this tool to be accessible to everyone. If you have ideas for new features, found a bug, or want to help translate the UI into other languages, we welcome your contributions!

1. **Fork** the repository.
2. **Create** your feature branch (`git checkout -b feature/new-palette`).
3. **Commit** your changes (`git commit -m 'Add new palette'`).
4. **Push** to the branch (`git push origin feature/new-palette`).
5. **Open** a Pull Request.

Please read our `CONTRIBUTING.md` for detailed coding standards and testing requirements. We also have an active Discord server where you can share your favorite color palettes, ask for help with accessibility, and discuss the latest trends in web design.

---

## 📬 Contact & Support

- 💬 **Discussions:** Join the conversation in the GitHub Discussions tab.
- 🐛 **Issues:** Found a bug? Let us know via the Issues tracker.
- 📧 **Email:** Reach out directly at support@rgb-generator.dev.

---

<div align="center">

### ⭐ If this tool helps your designs shine, give it a star! ⭐

[![Star](https://img.shields.io/badge/⭐_STAR_THIS_REPO-FF5252?style=for-the-badge&logo=github&logoColor=white)](https://github.com/your-username/rgb-generator-colors)

---

### 🚀 Start generating colors today

[![Get Started](https://img.shields.io/badge/🚀_GET_STARTED_GUIDE-00C9FF?style=for-the-badge&logoColor=white)](https://share.google/x87uVAIj13rvzZcjz)

<sub>Crafted with precision and ❤️ by the Rgb Generator Colors community</sub>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:4A00E0,100:8E2DE2&height=120&section=footer)

</div>
