# Mark Finley - Portfolio Website

A modern, responsive portfolio website showcasing my skills, projects, and experience as a Full Stack Developer.

🌐 **Live Website**: [https://hyiaman.github.io](https://hyiaman.github.io)

## ✨ Features

- **Modern Design**: Clean, professional interface with beautiful gradients and animations
- **Responsive Layout**: Optimized for all devices (desktop, tablet, mobile)
- **Advanced Theme System**: Three-state theme toggle (System Default, Light Mode, Dark Mode)
- **Smooth Navigation**: Fixed side navigation with mobile-friendly bottom navigation
- **Interactive Elements**: Hover effects, smooth scrolling, and engaging animations
- **Performance Optimized**: Fast loading times with optimized assets
- **Accessibility**: Keyboard navigation support and proper focus states

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3 (Custom Properties), Vanilla JavaScript
- **Design**: Modern CSS Grid, Flexbox, CSS Animations
- **Icons**: Emoji-based icons for universal compatibility
- **Deployment**: GitHub Pages
- **Version Control**: Git

## 📋 Sections

1. **Header**: Professional introduction with call-to-action buttons
2. **About**: Personal introduction and downloadable resume
3. **Skills**: Categorized technical skills (Frontend, Backend, Database & Tools)
4. **Projects**: Featured project showcase with live demos and source code links
5. **Contact**: Multiple ways to get in touch

## 🎨 Design Features

### Theme System
- **System Default**: Automatically adapts to user's OS preference
- **Light Mode**: Clean, bright interface
- **Dark Mode**: Modern dark theme with proper contrast
- Persistent theme selection with localStorage

### Navigation
- **Desktop**: Fixed side navigation with tooltips
- **Mobile**: Bottom navigation bar for easy thumb access
- **Smooth Scrolling**: Seamless transitions between sections
- **Active States**: Visual indicators for current section

### Animations
- CSS-based animations for better performance
- Scroll-triggered reveals
- Hover effects on interactive elements
- Loading states and transitions

## 📱 Responsive Design

The website is fully responsive with breakpoints at:
- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## 🚀 Quick Start

1. **Clone the repository**:
   ```bash
   git clone https://github.com/hyiaman/hyiaman.github.io.git
   cd hyiaman.github.io
   ```

2. **Open locally**:
   - Simply open `index.html` in your web browser
   - Or use a local server for development:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js
     npx serve .
     ```

3. **View the website**:
   - Local: `http://localhost:8000`
   - Live: `https://hyiaman.github.io`

## 📂 Project Structure

```
portfolio/
├── index.html          # Main portfolio page
├── profile_pic.jpg     # Profile image
├── resume.pdf          # Downloadable resume
├── README.md           # Project documentation
└── CNAME              # Custom domain configuration
```

## 🔧 Customization

To customize this portfolio for your own use:

1. **Personal Information**:
   - Update name, title, and bio in the HTML
   - Replace `profile_pic.jpg` with your photo
   - Update `resume.pdf` with your resume

2. **Contact Information**:
   - Update email, LinkedIn, and GitHub links
   - Modify contact section as needed

3. **Skills & Projects**:
   - Update the skills sections with your technologies
   - Replace project information with your own work
   - Add links to your live demos and repositories

4. **Styling**:
   - Modify CSS custom properties for colors and themes
   - Adjust animations and transitions as desired
   - Update typography and spacing

## 🌟 Key Highlights

- **Single File Architecture**: Everything contained in one HTML file for simplicity
- **No Dependencies**: Pure HTML, CSS, and JavaScript - no frameworks required
- **GitHub Pages Ready**: Optimized for easy deployment on GitHub Pages
- **SEO Friendly**: Proper meta tags and semantic HTML structure
- **Fast Loading**: Minimal external dependencies and optimized assets

## � Contact Form Setup

To enable the contact form functionality:

1. **Create EmailJS Account**: Sign up at [EmailJS](https://www.emailjs.com/)
2. **Set up Service**: Configure your email service (Gmail, Outlook, etc.)
3. **Create Template**: Set up an email template in EmailJS
4. **Configure Credentials**: 
   - Copy `config.template.js` to `config.js`
   - Add your EmailJS credentials:
   ```javascript
   window.emailConfig = {
       publicKey: 'your_public_key',
       serviceId: 'your_service_id', 
       templateId: 'your_template_id'
   };
   ```

**⚠️ Security Note**: Never commit `config.js` to version control as it contains API credentials. The file is already added to `.gitignore`.

## �📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 About

Created by **Mark Finley** - Full Stack Developer

- 📧 Email: [oseimarkfinley@gmail.com](mailto:oseimarkfinley@gmail.com)
- 💼 LinkedIn: [linkedin.com/in/markfinley](https://linkedin.com/in/markfinley)
- 🔗 GitHub: [github.com/Mark-Finley](https://github.com/Mark-Finley)
- 🌐 Portfolio: [hyiaman.github.io](https://hyiaman.github.io)

---

⭐ **If you like this portfolio template, please give it a star!**