# 📱 QR Code Generator

A modern, responsive QR code generator built with pure HTML, CSS, and JavaScript. Generate QR codes instantly for URLs, text content, and contact information with a beautiful, user-friendly interface.

## ✨ Features

### 🎯 **Multiple QR Code Types**
- **URL Generation** - Create QR codes for websites with automatic protocol detection
- **Text Content** - Generate codes for any text content or messages  
- **Contact Information** - Create vCard QR codes with complete contact details

### 🎨 **Modern Design**
- **Responsive Layout** - Works perfectly on desktop, tablet, and mobile devices
- **Beautiful UI** - Clean, modern interface with gradient backgrounds and smooth animations
- **Tab Navigation** - Intuitive switching between different QR code types
- **Real-time Generation** - QR codes update instantly as you type

### 🔧 **Robust Functionality**
- **Multiple Generation Methods** - Primary QRious library with fallback to online APIs
- **Download Support** - Save QR codes as PNG images
- **Copy to Clipboard** - Quick copying of QR code data
- **Form Validation** - Smart URL formatting and input validation
- **Cross-browser Compatible** - Works on all modern browsers

## 🚀 Live Demo

> **[View Live Demo](https://mrutyunjay-patil.github.io/qr-gen/)**

## 🛠️ Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling with Flexbox/Grid layouts
- **Vanilla JavaScript** - Pure JS without frameworks
- **QRious Library** - Primary QR code generation
- **Tailwind CSS** - Utility-first CSS framework (CDN)
- **External APIs** - Fallback QR generation services

## 📁 Project Structure

```
qr-code-generator/
│
├── index.html          # Main application file (self-contained)
└── README.md           # Project documentation
```

## 🚀 Quick Start

### Option 1: Direct Download
1. Download the `index.html` file
2. Open it in any modern web browser
3. Start generating QR codes instantly!

### Option 2: GitHub Pages Deployment
1. **Fork this repository**
   ```bash
   git clone https://github.com/Mrutyunjay-Patil/qr-gen.git
   cd qr-gen
   ```

2. **Enable GitHub Pages**
   - Go to repository Settings
   - Navigate to Pages section
   - Set source to "Deploy from a branch"
   - Select "main" branch
   - Save settings

3. **Access your live site**
   - Your QR generator will be available at: `https://your-github-username.github.io/qr-gen/`

### Option 3: Local Development
```bash
# Clone the repository
git clone https://github.com/Mrutyunjay-Patil/qr-gen.git

# Navigate to project directory
cd qr-gen

# Open in browser (no build process required!)
open index.html
```

## 💡 Usage Instructions

### 🔗 **Creating URL QR Codes**
1. Click the "URL" tab
2. Enter any website URL (http:// is optional)
3. QR code generates automatically
4. Download or copy the data as needed

### 📝 **Creating Text QR Codes**  
1. Switch to "Text" tab
2. Enter any text content in the textarea
3. QR code updates in real-time
4. Perfect for messages, notes, or instructions

### 👤 **Creating Contact QR Codes**
1. Select "Contact" tab
2. Fill in contact information fields:
   - First Name & Last Name
   - Phone Number
   - Email Address  
   - Organization
   - Website URL
3. Generates vCard format QR code
4. Scannable by any contact app

### 📥 **Download & Share**
- **Download**: Click download button to save as PNG
- **Copy Data**: Copy underlying QR code data to clipboard
- **Clear**: Reset all fields with one click

## 🌟 Key Features Explained

### Smart URL Handling
- Automatically adds `https://` if protocol is missing
- Validates URL format before generation
- Supports all standard URL formats

### vCard Generation
- Creates industry-standard vCard format
- Compatible with all contact management apps
- Supports multiple contact fields

### Responsive Design
- Mobile-first approach
- Smooth animations and transitions
- Touch-friendly interface

### Fallback Support
- Primary: QRious library for high-quality generation
- Fallback: Online API services if library fails
- Ensures QR codes always generate successfully

## 🔧 Customization

The application is built with modular CSS and JavaScript, making it easy to customize:

### Changing Colors
```css
/* Update gradient colors in the CSS section */
.gradient-bg {
    background: linear-gradient(135deg, your-color-1, your-color-2);
}
```

### Adding New QR Types
```javascript
// Add new tab in the HTML
// Extend the switchTab() function
// Add generation logic in generateQRCode()
```

### Modifying Styling
- All styles are contained in the `<style>` section
- Uses CSS custom properties for easy theming
- Tailwind classes can be replaced with custom CSS

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Make your changes**
4. **Commit your changes**
   ```bash
   git commit -m 'Add some amazing feature'
   ```
5. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
6. **Open a Pull Request**

### 🐛 Bug Reports
Found a bug? Please open an issue with:
- Description of the problem
- Steps to reproduce
- Expected vs actual behavior
- Browser/device information

### 💡 Feature Requests
Have an idea? Open an issue tagged "enhancement" with:
- Clear description of the proposed feature
- Use case/problem it solves
- Any implementation ideas

## 📋 Browser Support

| Browser | Version | Status |
|---------|---------|--------|
| Chrome  | 60+     | ✅ Full Support |
| Firefox | 55+     | ✅ Full Support |
| Safari  | 11+     | ✅ Full Support |
| Edge    | 79+     | ✅ Full Support |
| Opera   | 47+     | ✅ Full Support |

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

```
MIT License

Copyright (c) 2024 Mrutyunjay Patil

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

## 👨‍💻 Author

**Mrutyunjay Patil**
- Email: [patilmrutyunjay2@gmail.com](mailto:patilmrutyunjay2@gmail.com)
- GitHub: [@Mrutyunjay-Patil](https://github.com/Mrutyunjay-Patil)

## 🙏 Acknowledgments

- [QRious](https://github.com/neocotic/qrious) - Primary QR code generation library
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [QR Server API](https://goqr.me/api/) - Fallback QR code generation service
- Design inspiration from modern web applications

---

⭐ **Star this repository if you found it helpful!**

🔗 **Share it with others who might need a simple QR code generator!**

📢 **Follow for more open source projects!**
