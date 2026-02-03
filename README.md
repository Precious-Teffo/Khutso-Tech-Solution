# Khutso-Tech-Solution
A professional single-page website for CodeCraft Solutions showcasing services, projects, and contact details. Features responsive navigation, service cards, project showcases, process timeline, Formspree contact form, clean blue/white design, smooth scrolling, and full mobile responsiveness—ideal for tech service businesses.

![Website Preview](https://img.shields.io/badge/Status-Ready%20to%20Deploy-success)
![Responsive](https://img.shields.io/badge/Responsive-Yes-blue)
![License](https://img.shields.io/badge/License-MIT-green)

## 🌟 Features

- **Fully Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Mobile-First Navigation** - Hamburger menu with smooth slide-in animation for mobile
- **Smooth Scrolling** - Elegant navigation between sections
- **Contact Form Integration** - Ready-to-use Formspree form integration
- **Modern UI/UX** - Clean, professional design with subtle animations
- **Zero Dependencies** - Pure HTML, CSS, and JavaScript (except Google Fonts)
- **Fast Loading** - Optimized single-file structure
- **SEO Friendly** - Semantic HTML structure

## 📋 Sections

1. **Navigation Bar** - Fixed header with responsive mobile menu
2. **Hero Section** - Compelling introduction with call-to-action
3. **Services** - Three service cards showcasing offerings
4. **Projects** - Six project showcases with gradient designs
5. **Process** - Four-step workflow explanation
6. **Contact Form** - Professional contact form with validation
7. **Footer** - Links and copyright information

## 🚀 Quick Start

### Prerequisites

- A text editor (VS Code, Sublime Text, etc.)
- A web browser
- A Formspree account (free) for contact form functionality

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/codecraft-website.git
   cd codecraft-website
   ```

2. **Open the file**
   ```bash
   open index.html
   ```
   Or simply double-click `index.html` to open in your default browser.

3. **Set up Formspree (for contact form)**
   - Go to [formspree.io](https://formspree.io) and create a free account
   - Create a new form
   - Copy your form endpoint (e.g., `https://formspree.io/f/xpzkxxxxx`)
   - Open `index.html` and find line with `action="https://formspree.io/f/YOUR_FORM_ID"`
   - Replace `YOUR_FORM_ID` with your actual Formspree form ID
   - Save the file

## 🎨 Customization

### Change Colors

All colors are defined as CSS variables at the top of the `<style>` section:

```css
:root {
    --primary: #2563eb;        /* Main blue color */
    --primary-dark: #1e40af;   /* Darker blue for hover states */
    --text-dark: #1f2937;      /* Main text color */
    --text-gray: #6b7280;      /* Secondary text color */
    --bg-light: #f9fafb;       /* Light background */
    --white: #ffffff;          /* White */
    --border: #e5e7eb;         /* Border color */
}
```

### Update Company Name

Search for "CodeCraft" in the HTML and replace with your business name:
- Navigation logo
- Footer copyright

### Modify Services

Edit the service cards in the Services section:
- Change icons (emojis)
- Update titles and descriptions
- Modify feature lists

### Add/Remove Projects

The Projects section contains six project cards. You can:
- Add more projects by duplicating a project card
- Remove projects by deleting a card
- Change project details, categories, and tags

### Update Contact Form

Modify form fields in the Contact section:
- Add new fields
- Remove optional fields
- Change dropdown options

## 📱 Responsive Breakpoints

- **Desktop**: > 768px - Full layout with horizontal navigation
- **Tablet**: 481px - 768px - Hamburger menu, 2-column grids
- **Mobile**: ≤ 480px - Hamburger menu, single-column layout

## 🌐 Deployment

### GitHub Pages

1. Push your code to GitHub
2. Go to repository Settings → Pages
3. Select branch (usually `main`) and folder (`/root`)
4. Click Save
5. Your site will be live at `https://yourusername.github.io/repository-name`

### Netlify

1. Create account at [netlify.com](https://netlify.com)
2. Drag and drop your project folder
3. Site goes live instantly with custom domain support

### Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in project directory
3. Follow prompts to deploy

### Traditional Hosting

Upload `index.html` to your web server via:
- FTP/SFTP
- cPanel File Manager
- Hosting provider's dashboard

## 🛠️ Technologies Used

- **HTML5** - Structure and content
- **CSS3** - Styling and responsive design
- **JavaScript (Vanilla)** - Interactivity and form handling
- **Google Fonts** - Poppins font family
- **Formspree** - Contact form backend

## 📦 File Structure

```
codecraft-website/
│
├── index.html              # Main HTML file (contains everything)
├── README.md              # This file
└── WEBSITE_DESCRIPTION.txt # Detailed documentation
```

## ✨ Key Features Explained

### Mobile Hamburger Menu
- Appears on screens ≤ 768px wide
- Smooth slide-in animation
- Closes when clicking links or outside menu
- Animated icon (3 lines → X)

### Smooth Scrolling
- All navigation links scroll smoothly to sections
- Works on both desktop and mobile

### Form Validation
- Client-side validation for required fields
- Email format validation
- Visual feedback on focus
- Success/error messages

### Hover Effects
- Cards lift up with shadow on hover
- Buttons darken on hover
- Links change color on hover
- Smooth transitions throughout

## 🎯 Use Cases

Perfect for:
- Software development companies
- Web development agencies
- Freelance developers
- IT consulting firms
- Digital agencies
- Technology startups
- SaaS businesses

## 🔧 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📈 Performance

- **File Size**: ~52KB (single HTML file)
- **Load Time**: < 1 second on standard connection
- **Lighthouse Score**: 90+ (Performance, Accessibility, Best Practices)

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see below for details:

```
MIT License

Copyright (c) 2026 CodeCraft Solutions

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 💬 Support

Need help? Here are some resources:

- **Issues**: Report bugs or request features in the [Issues](https://github.com/yourusername/codecraft-website/issues) section
- **Discussions**: Ask questions in [Discussions](https://github.com/yourusername/codecraft-website/discussions)
- **Formspree Help**: [Formspree Documentation](https://help.formspree.io/)

## 🙏 Acknowledgments

- [Google Fonts](https://fonts.google.com/) for Poppins font
- [Formspree](https://formspree.io/) for form handling service
- [shields.io](https://shields.io/) for README badges

## 📞 Contact

**Project Maintainer**: Khutso Teffo
- Email: prcsKhutso@gmail.com

## 🗺️ Roadmap

Future enhancements planned:

- [ ] Dark mode toggle
- [ ] Multi-language support
- [ ] Animation on scroll
- [ ] Blog section
- [ ] Client testimonials carousel
- [ ] Live chat integration
- [ ] Portfolio filtering by category

---

**⭐ If you found this project helpful, please consider giving it a star!**

Made with ❤️ by Khutso Tech Solutions
