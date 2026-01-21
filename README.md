# 🚀 Ronald Gaba | Portfolio Website
<div align="center">
![Portfolio Preview](https://img.shields.io/badge/Portfolio-Live-4F46E5?style=for-the-badge&logo=vercel&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
**A modern, animated, and fully responsive portfolio website showcasing my work as a Frontend Developer & React Native Specialist.**
[🌐 Live Demo](#) • [📧 Contact Me](mailto:ronaldrg.rr@gmail.com) • [💼 LinkedIn](#) • [🐙 GitHub](https://github.com/Rontoge)
</div>
---
## 📸 Preview
<div align="center">
| Light Mode | Dark Mode |
|:----------:|:---------:|
| ![Light Mode](https://via.placeholder.com/400x250/F8FAFC/4F46E5?text=Light+Mode) | ![Dark Mode](https://via.placeholder.com/400x250/020617/6366F1?text=Dark+Mode) |
</div>
---
## ✨ Features
### 🎨 Design & UI
- **Premium Indigo Color Palette** - Carefully crafted light & dark themes
- **Glassmorphism Effects** - Modern frosted glass navbar
- **Animated Gradient Text** - Eye-catching headings
- **Particle Background** - Dynamic floating particles
- **Custom Cursor** - Interactive cursor follower (desktop)
### 🚀 Animations
- **Fade-in Animations** - Smooth text and element reveals
- **Scroll Animations** - Sections animate into view
- **Floating Elements** - Tech icons float around profile
- **Hover Effects** - Interactive buttons and cards
- **Page Transitions** - Seamless navigation between pages
- **Counter Animation** - Stats count up on load
### 📱 Responsive
- **Mobile-First Design** - Optimized for all screen sizes
- **Touch-Friendly** - Large tap targets for mobile
- **Hamburger Menu** - Animated mobile navigation
- **Adaptive Layout** - Grid adjusts to screen width
### ⚡ Functionality
- **Dark/Light Mode Toggle** - Saved to localStorage
- **Working Contact Form** - Powered by Web3Forms
- **Downloadable Resume** - One-click CV download
- **Smooth Scrolling** - Seamless navigation
- **Loading Screen** - Professional page load experience
---
## 🛠️ Tech Stack
| Category | Technology |
|----------|------------|
| **Structure** | HTML5 |
| **Styling** | Tailwind CSS v4, Custom CSS |
| **Interactivity** | Vanilla JavaScript |
| **Icons** | Font Awesome 6 |
| **Fonts** | Google Fonts (Inter, Fira Code) |
| **Form Backend** | Web3Forms API |
| **Deployment** | Vercel / GitHub Pages |
---
## 📁 Project Structure
```
portfolio/
├── index.html          # Main HTML file (single-page app)
├── README.md           # Project documentation
└── assets/             # (Optional) Images and assets
    ├── images/
    └── resume/
        └── Ronald_Gaba_Resume.pdf
```
---
## 🚀 Getting Started
### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A code editor (VS Code recommended)
- Git installed on your machine
### Installation
1. **Clone the repository**
   ```bash
   git clone https://github.com/Rontoge/portfolio.git
   cd portfolio
   ```
2. **Open in browser**
   ```bash
   # Simply open index.html in your browser
   # Or use a local server:
   npx serve .
   # Or with Python:
   python -m http.server 8000
   ```
3. **View the site**
   ```
   Open http://localhost:8000 in your browser
   ```
---
## ⚙️ Configuration
### 📧 Setting Up the Contact Form
The contact form uses [Web3Forms](https://web3forms.com) - a free email API service.
1. **Get your access key:**
   - Go to [web3forms.com](https://web3forms.com)
   - Enter your email address
   - Click "Create Access Key"
   - Check your email for the key
2. **Add the key to your code:**
   ```html
   <!-- Find this line in index.html -->
   <input type="hidden" name="access_key" value="YOUR_ACCESS_KEY_HERE">
   
   <!-- Replace with your actual key -->
   <input type="hidden" name="access_key" value="your-actual-key-12345">
   ```
3. **Test the form** - Submit a test message!
### 🎨 Customizing Colors
The color palette is defined in the CSS variables:
```css
:root {
    --bg-light: #F8FAFC;
    --text-primary-light: #0F172A;
    --text-secondary-light: #475569;
    --accent: #4F46E5;           /* Primary Indigo */
    --accent-hover: #4338CA;      /* Darker Indigo */
    --accent-soft: #A5B4FC;       /* Light Indigo */
    
    /* Dark Mode */
    --bg-dark: #020617;
    --text-dark: #E5E7EB;
    --accent-dark: #6366F1;
}
```
### 📝 Updating Content
All content is in `index.html`. Key sections to update:
| Section | What to Update |
|---------|----------------|
| Hero | Name, title, description, stats |
| About | Career summary, education, skills |
| Portfolio | Project cards, GitHub links |
| Contact | Email, phone, location |
| Footer | Social links, copyright year |
---
## 🌐 Deployment
### Deploy to Vercel (Recommended)
1. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```
2. **Deploy on Vercel**
   - Go to [vercel.com](https://vercel.com)
   - Click "Import Project"
   - Select your GitHub repository
   - Click "Deploy"
   - Done! 🎉
### Deploy to GitHub Pages
1. **Enable GitHub Pages**
   - Go to repository Settings
   - Navigate to "Pages" section
   - Select "main" branch
   - Click Save
2. **Access your site**
   ```
   https://rontoge.github.io/portfolio
   ```
### Deploy to Netlify
1. Drag and drop your project folder to [netlify.com/drop](https://netlify.com/drop)
2. Or connect your GitHub repository for continuous deployment
---
## 📊 Performance
| Metric | Score |
|--------|-------|
| Performance | 95+ |
| Accessibility | 95+ |
| Best Practices | 100 |
| SEO | 100 |
*Tested with Google Lighthouse*
---
## 🔮 Future Enhancements
- [ ] Add blog section
- [ ] Implement project filtering
- [ ] Add more project details pages
- [ ] Integrate with headless CMS
- [ ] Add multi-language support
- [ ] Implement analytics dashboard
---
## 🤝 Contributing
Contributions are welcome! Feel free to:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
---
## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```
MIT License
Copyright (c) 2026 Ronald Gaba
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```
---
## 📬 Contact
**Ronald Gaba** - Frontend Developer & React Native Specialist
<div align="center">
[![Email](https://img.shields.io/badge/Email-ronaldrg.rr%40gmail.com-4F46E5?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ronaldrg.rr@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](#)
[![GitHub](https://img.shields.io/badge/GitHub-Rontoge-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Rontoge)
</div>
---
<div align="center">
### ⭐ Star this repo if you found it helpful!
Made with ❤️ and ☕ by **Ronald Gaba**
</div>
