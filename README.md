# Regina Mutinda - Portfolio Website

A modern, responsive personal portfolio website showcasing skills, education, projects, and professional experience. Built with clean HTML5 and CSS, featuring a CSS-only dark mode toggle and smooth animations.

## ✨ Features

### 🎨 **Modern Design**
- Clean, professional layout with card-based components
- Smooth animations and hover effects
- CSS custom properties for easy theming
- Gradient backgrounds and modern shadows

### 🌙 **Dark Mode Support**
- CSS-only dark mode implementation
- Smooth transitions between themes
- Persistent toggle switch in top-right corner
- Accessible design using checkbox input

### 📱 **Fully Responsive**
- Mobile-first approach with progressive enhancement
- Flexible grid layouts for all screen sizes
- Optimized typography scaling
- Touch-friendly navigation and interactions

### 🧭 **Enhanced Navigation**
- Fixed navigation bar with smooth scrolling
- Animated hover effects on navigation links
- Back-to-top button for easy navigation
- Semantic HTML structure for accessibility

### 🎯 **Content Sections**
- **Hero Section**: Profile image, name, title, and social links
- **About**: Professional summary and background
- **Education**: Certifications and academic achievements in card format
- **Interests**: Professional interests with icons
- **Projects**: Portfolio projects with technology tags
- **Contact**: Contact information and functional form

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and modern structure
- **CSS3**: Advanced styling with custom properties, grid, flexbox
- **CSS Animations**: Smooth transitions and hover effects
- **Responsive Design**: Mobile-first approach
- **Accessibility**: ARIA labels, semantic HTML, keyboard navigation

## 📁 File Structure

```
portfolio/
│
├── index.html
├── css/
│   └── style.css
├── resume/
│   └── Regina Mbula CV Portfolio.pdf
├── img/
│   └── babe.jpg

```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of HTML/CSS for customization
- A text editor or IDE for making changes

### Installation

1. **Clone or Download**
   ```bash
   git clone https://github.com/Mutindadev/portfolio.git
   cd portfolio
   ```

2. **Add a Profile Image**
   - Replace the placeholder image URL in the HTML
   - Add your actual profile image as `babe.jpg` in the root directory
   - Update the `src` attribute in the profile image tag

3. **Open in Browser**
   - Open `index.html` in your preferred web browser
   - No server setup required - it's a static website

## ⚙️ Customization Guide

### **Colors and Theming**
Update CSS custom properties in `:root` to change the color scheme:

```css
:root {
  --primary-color: #4A90E2;      /* Main brand color */
  --secondary-color: #F39C12;    /* Accent color */
  --accent-color: #E74C3C;       /* Highlight color */
  --text-color: #2C3E50;         /* Main text color */
  --bg-color: #FFFFFF;           /* Background color */
}
```

### **Content Updates**
1. **Personal Information**: Update name, title, and description in the hero section
2. **About Section**: Replace with your own background and experience
3. **Education**: Add your certifications and educational background
4. **Projects**: Add your own projects with descriptions and links
5. **Contact**: Update with your actual contact information

### **Adding New Sections**
Follow this structure to add new sections:

```html
<section id="new-section" class="section">
  <div class="container">
    <h2 class="section-title">Section Title</h2>
    <!-- Your content here -->
  </div>
</section>
```

### **Social Media Links**
Update the social media links in the hero section:

```html
<div class="social-links">
  <a href="your-github-url" target="_blank" class="social-link">GitHub</a>
  <a href="your-linkedin-url" target="_blank" class="social-link">LinkedIn</a>
  <!-- Add more social links as needed -->
</div>
```

## 🎨 Design System

### **Typography**
- **Primary Font**: Segoe UI, Tahoma, Geneva, Verdana, sans-serif
- **Heading Sizes**: 3rem (hero), 2.5rem (sections), 1.5rem (cards)
- **Body Text**: 1.1rem with 1.6 line height

### **Spacing**
- **Section Padding**: 80px vertical, 20px horizontal
- **Container Max-Width**: 1200px
- **Card Padding**: 2rem
- **Grid Gap**: 2rem

### **Breakpoints**
- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: 320px - 767px

## 🌐 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📋 TODO / Future Enhancements

- [ ] Add more project examples
- [ ] Implement contact form backend
- [ ] Add blog section
- [ ] Include testimonials section
- [ ] Add skill progress bars
- [ ] Implement lazy loading for images
- [ ] Add service worker for offline functionality
- [ ] Include Google Analytics integration

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Create a Pull Request

### **Contribution Guidelines**
- Follow existing code style and formatting
- Test responsiveness on multiple devices
- Ensure accessibility standards are maintained
- Update documentation for any new features

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

**Regina Mutinda**
- 📧 Email: [rmmutinda02@gmail.com](mailto:rmmutinda02@gmail.com)
- 💻 GitHub: [@Mutindadev](https://github.com/Mutindadev)
- 💼 LinkedIn: [Regina Mutinda](https://linkedin.com/in/regina-mutinda-174934292)
- website:(My website)[https:mutindadev.kesug.com]
## 🙏 Acknowledgments

- Design inspiration from modern portfolio websites
- CSS techniques from various web development resources
- Icons and animations using pure CSS
- Color palette inspired by modern UI design trends

---

**⭐ If you found this project helpful, please consider giving it a star on GitHub!**

**🔧 Made with ❤️ by Regina Mutinda**


### References

1. **Exclusive Software Deals for Developers and Startups - Dealsbe**. [http://readme.md](http://readme.md)
2. **About READMEs - GitHub Docs**. [https://docs.github.com](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes)
3. **Make a README**. [https://www.makeareadme.com](https://www.makeareadme.com/)
4. **README.md - haider-shah-video-35-second-viral-link**. [https://huggingface.co](https://huggingface.co/haider-shah-video-35-second-viral-link/NEW.18.VIDEOS.Haider.shah.Viral.Video.Official.Tutorial.viral.on.social.media/blob/main/README.md)
5. **Basic writing and formatting syntax - GitHub Docs**. [https://docs.github.com](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
6. **README.md · orabazes/Flux-Krea-GGUF at main**. [https://huggingface.co](https://huggingface.co/orabazes/Flux-Krea-GGUF/blob/main/README.md)
7. **r/learnprogramming on Reddit: How To Write a README?**. [https://www.reddit.com](https://www.reddit.com/r/learnprogramming/comments/vxfku6/how_to_write_a_readme/)
8. **README.md · black-forest-labs/FLUX.1-Krea-dev at main**. [https://huggingface.co](https://huggingface.co/black-forest-labs/FLUX.1-Krea-dev/blob/main/README.md)
9. **What is README.md File? - GeeksforGeeks**. [https://www.geeksforgeeks.org](https://www.geeksforgeeks.org/git/what-is-readme-md-file/)
10. **README - Wikipedia**. [https://en.wikipedia.org](https://en.wikipedia.org/wiki/README)
