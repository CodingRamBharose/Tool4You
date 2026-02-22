# Tool4You 🛠️

![Tool4You Logo](/public/logowhite.png)

> **Tool4You** is a comprehensive collection of free, privacy-focused online tools for developers, students, and creative professionals. Built with performance and user experience in mind.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Next.js](https://img.shields.io/badge/Next.js-14-black)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.0-38b2ac)

## ✨ Features

- **40+ Tools**: A wide range of utilities for text, images, code, math, and more.
- **Privacy First**: Most tools run entirely client-side. Your data never leaves your browser.
- **No Ads**: Clean, distraction-free interface.
- **Dark Mode**: Built-in dark mode support for better readability.
- **Responsive**: Fully optimized for mobile, tablet, and desktop devices.
- **Fast**: Built on Next.js for blazing fast performance.

## 🧰 Tool Categories

### 📝 Text Tools
- Case Converter, Word Counter, Lorem Ipsum Generator
- Markdown Editor, Text Diff, String Manipulation

### 🖼️ Image Tools
- Image Compression (JPEG, PNG, WebP)
- Resize, Crop, and Format Conversion
- Color Picker & Palette Generator

### 💻 Developer Tools
- JSON Formatter/Validator, JWT Decoder
- SQL Formatter, Base64 Encoder/Decoder
- HTML/CSS Minifiers

### 🔢 Math & Calculators
- Scientific Calculator, Unit Converters
- Percentage, Date/Time Calculators
- Number Base Converter (Binary, Hex, Decimal)

### 📊 Data & Visualization
- Chart Generators (Pie, Bar, Line)
- CSV/JSON Converters
- Data formatters

### 🛡️ Security
- Password Generator, Hash Generator (MD5, SHA)
- Password Strength Checker

## 🚀 Tech Stack

- **Framework**: [Next.js 14](https://nextjs.org/) (App Router)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **UI Components**: [Shadcn/ui](https://ui.shadcn.com/)
- **Icons**: [Lucide React](https://lucide.dev/)
- **Theming**: [next-themes](https://github.com/pacocoursey/next-themes)

## 🛠️ Getting Started

Follow these steps to run the project locally.

### Prerequisites

- Node.js 18+ installed
- npm, yarn, or pnpm

### Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/RamAvtar75Way/ToolSite.git
    cd ToolSite
    ```

2.  **Install dependencies:**

    ```bash
    npm install
    # or
    yarn install
    ```

3.  **Run the development server:**

    ```bash
    npm run dev
    ```

4.  **Open in Browser:**
    Navigate to `http://localhost:3000` to see the application running.

## 🚀 Deploy on Render

This project is a **Next.js server app**, so deploy it as a **Web Service** on Render (not Static Site).

- Build command: `npm install && npm run build`
- Start command: `npm run start`
- Node version: `20`

If you use Render Blueprint, this repo already includes `render.yaml` with the correct settings.

> `Publish directory out does not exist` means Render is currently configured as a static site. Switch to **Web Service** or re-create the service as Web Service.

## 📂 Project Structure

```bash
├── src/
│   ├── app/              # Next.js App Router pages
│   ├── components/       # Reusable UI components
│   │   ├── common/       # Header, Footer, etc.
│   │   ├── tools/        # Individual tool components
│   │   └── ui/           # Shadcn base components
│   ├── data/             # Static data and tool configs
│   ├── lib/              # Utility functions
│   └── hooks/            # Custom React hooks
├── public/               # Static assets (images, icons)
└── ...config files
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1.  Fork the project
2.  Create your feature branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Built with ❤️ by the Tool4You Team.
