# OrionAI - Advanced HKDSE English Suite

<div align="center">

![OrionAI Logo](https://img.shields.io/badge/OrionAI-8A2BE2?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTAwIDEwMCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48cGF0aCBmaWxsPSIjZmZmIiBkPSJNNTAsNSBBNDUsNDUgMCAxLDEgNTAsOTUgQTQ1LDQ1IDAgMSwxIDUwLDUgTTUwLDE1IEEzNSwzNSAwIDEsMCA1MCw4NSBBMzUsMzUgMCAxLDAgNTAsMTUgWiIvPjxwYXRoIGZpbGw9IiNmZmYiIGQ9Ik00MCwzNSBsMjAsMTUgbC0yMCwxNSBaIi8+PC9zdmc+)

**A comprehensive AI-powered writing assistant for HKDSE English students**

[![GitHub](https://img.shields.io/badge/GitHub-hugow0528-181717?style=flat-square&logo=github)](https://github.com/hugow0528)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

[Features](#features) • [Demo](#demo) • [Installation](#installation) • [Usage](#usage) • [Technologies](#technologies) • [Contributing](#contributing)

</div>

---

## 📖 About

**OrionAI** is an advanced, AI-driven web application designed specifically for Hong Kong Diploma of Secondary Education (HKDSE) English students. It provides a comprehensive suite of tools to help students improve their writing skills, grammar, vocabulary, and text extraction capabilities—all powered by cutting-edge AI technology.

## ✨ Features

### 🎯 Writing Planner
- **Intelligent Genre Detection**: Automatically identifies the writing genre (Argumentative, Narrative, etc.) from your topic
- **Mind Map Generation**: Creates visual conceptual mind maps to organize your ideas
- **Structured Planning**: Provides detailed outlines with Introduction, Body, and Conclusion sections
- **HKDSE-Specific Tips**: Offers practical tips tailored to HKDSE examination requirements
- **Advanced Sentence Structures**: Suggests sophisticated sentence patterns with relevant examples
- **Export Options**: Download your plan as PDF or DOCX

### ✅ Grammar, Typos & Fluency Checker
- **Line-by-Line Analysis**: Reviews your text with examiner-level scrutiny
- **Detailed Feedback**: Identifies grammar errors, typos, punctuation issues, and fluency problems
- **Correction Suggestions**: Provides specific corrections with explanations
- **Educational Approach**: Helps you understand why something is wrong, not just what to fix

### 📚 Vocabulary Enhancer
- **Sentence Sophistication**: Transforms simple sentences into advanced, formal alternatives
- **Multiple Options**: Provides three distinct sophisticated variations
- **Context-Appropriate**: Ensures suggestions maintain the original meaning while elevating language quality

### 🖼️ Image to Text (OCR)
- **Document Scanning**: Extract text from images of documents, notes, or pages
- **Cropping Capability**: Select specific areas of the image to scan
- **Multiple Export Formats**: Save extracted text as PDF, DOCX, or TXT
- **Copy to Clipboard**: Quickly copy all extracted text

## 🚀 Demo

Visit the live application: [OrionAI Demo](https://hugow0528.github.io/OrionAI/) *(if hosted on GitHub Pages)*

## 🛠️ Technologies

OrionAI is built using modern web technologies:

- **Frontend**: 
  - HTML5 for structure
  - CSS3 with custom properties for theming
  - Vanilla JavaScript for interactivity
  
- **AI Integration**:
  - Pollinations.ai API for natural language processing
  
- **Third-Party Libraries**:
  - [jsPDF](https://github.com/parallax/jsPDF) - PDF generation
  - [html2canvas](https://github.com/niklasvh/html2canvas) - Screenshot capability
  - [html-to-docx](https://github.com/evidenceprime/html-to-docx) - DOCX export
  - [Cropper.js](https://github.com/fengyuanchen/cropperjs) - Image cropping

- **Design**:
  - Dark theme with purple accent colors
  - Responsive layout for mobile and desktop
  - Smooth animations and transitions
  - Inter & Roboto Mono fonts from Google Fonts

## 📦 Installation

OrionAI is a static web application that requires no installation. Simply clone and serve:

```bash
# Clone the repository
git clone https://github.com/hugow0528/OrionAI.git

# Navigate to the directory
cd OrionAI

# Open index.html in your browser
# OR serve it with a local server (recommended)
python -m http.server 8000
# Then visit http://localhost:8000
```

### Alternative: GitHub Pages Hosting

You can host OrionAI on GitHub Pages:

1. Fork this repository
2. Go to Settings → Pages
3. Select the branch (usually `main`) and root directory
4. Save and wait for deployment
5. Access your app at `https://yourusername.github.io/OrionAI/`

## 💡 Usage

### Writing Planner
1. Navigate to the "Writing Planner" tab
2. Enter your writing topic or question
3. Click "Generate Plan"
4. Review the AI-generated plan with mind maps, idea points, structure, and tips
5. Export your plan as PDF or DOCX if needed

### Grammar Checker
1. Click on the "Grammar Checker" tab
2. Paste your text into the text area
3. Click "Check Text"
4. Review the line-by-line feedback
5. Apply corrections based on the suggestions

### Vocabulary Enhancer
1. Go to the "Vocab Enhancer" tab
2. Enter a simple sentence
3. Click "Enhance Sentence"
4. Choose from three sophisticated alternatives

### Image to Text
1. Select the "Image to Text" tab
2. Upload an image file
3. Use the cropper to select the text area
4. Click "Scan Cropped Area"
5. Copy or export the extracted text

## 🎨 Customization

The application uses CSS custom properties for easy theming. You can modify colors in the `:root` selector:

```css
:root {
    --color-bg: #0d1117;
    --color-surface: #161b22;
    --color-primary: #8A2BE2;
    --color-primary-light: #a052e8;
    --color-text: #c9d1d9;
    --color-text-muted: #8b949e;
    /* ... and more */
}
```

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Ideas for Contributions
- Add more AI-powered tools for HKDSE preparation
- Improve UI/UX design
- Add support for other languages
- Implement offline mode with cached results
- Add user authentication and history saving
- Create mobile app versions

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Hugo Wong**

- GitHub: [@hugow0528](https://github.com/hugow0528)
- Email: whugo0528@yahoo.com

## 🙏 Acknowledgments

- Thanks to [Pollinations.ai](https://pollinations.ai/) for providing the AI API
- Inspired by the needs of HKDSE English students in Hong Kong
- Built with ❤️ for the education community

## 📧 Support

If you encounter any issues or have questions:

1. Check the [Issues](https://github.com/hugow0528/OrionAI/issues) page
2. Create a new issue if your problem isn't already reported
3. Contact via email: whugo0528@yahoo.com

---

<div align="center">

**Made with 💜 for HKDSE Students**

Copyright © 2025 Hugo Wong. All rights reserved.

</div>