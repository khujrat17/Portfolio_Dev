# 🚀 Khujrat Shaikh - Portfolio Website

A modern, interactive portfolio website showcasing my work as a .NET Full-Stack Developer and official .NET Foundation Member.

## ✨ Features

- **Modern Design**: Futuristic tech aesthetic with glassmorphism and gradient effects
- **Fully Responsive**: Optimized for all devices (desktop, tablet, mobile)
- **Interactive Animations**: Smooth scroll animations, typing effects, and skill progress bars
- **Performance Optimized**: Fast loading with CSS animations and minimal JavaScript
- **Dark Theme**: Eye-friendly dark mode with cosmic background
- **SEO Friendly**: Semantic HTML with proper meta tags

## 🛠️ Tech Stack

- HTML5
- CSS3 (Custom Properties, Flexbox, Grid, Animations)
- Vanilla JavaScript (ES6+)
- Google Fonts (Orbitron, JetBrains Mono)

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles and animations
├── script.js           # JavaScript for interactivity
└── README.md           # This file
```

## 🚀 Deployment Options (100% Free)

### Option 1: GitHub Pages (Recommended)

1. **Create a GitHub Repository**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Portfolio website"
   ```

2. **Push to GitHub**
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git branch -M main
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to your repository settings
   - Navigate to "Pages" section
   - Select "main" branch as source
   - Click "Save"
   - Your site will be live at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

### Option 2: Netlify

1. **Install Netlify CLI** (optional)
   ```bash
   npm install -g netlify-cli
   ```

2. **Deploy via Drag & Drop**
   - Go to [netlify.com](https://www.netlify.com/)
   - Sign up/Login
   - Drag your project folder to the deployment zone
   - Get instant URL!

3. **Deploy via CLI**
   ```bash
   netlify deploy --prod
   ```

### Option 3: Vercel

1. **Install Vercel CLI**
   ```bash
   npm install -g vercel
   ```

2. **Deploy**
   ```bash
   vercel
   ```
   - Follow the prompts
   - Your site will be live instantly!

3. **Deploy via Web Interface**
   - Go to [vercel.com](https://vercel.com/)
   - Import your GitHub repository
   - Automatic deployment on every commit!

### Option 4: Render

1. Go to [render.com](https://render.com/)
2. Connect your GitHub repository
3. Select "Static Site"
4. Deploy with one click!

### Option 5: Cloudflare Pages

1. Go to [pages.cloudflare.com](https://pages.cloudflare.com/)
2. Connect GitHub repository
3. Configure build settings:
   - Build command: (leave empty)
   - Build output directory: `/`
4. Deploy!

## 🎨 Customization

### Update Personal Information

1. **Edit `index.html`**:
   - Update name, title, and contact information
   - Modify project descriptions and links
   - Add/remove sections as needed

2. **Edit `styles.css`**:
   - Change color scheme (CSS variables at top of file)
   - Adjust animations and transitions
   - Modify layouts and spacing

3. **Edit `script.js`**:
   - Update typing animation text array
   - Adjust animation timings
   - Add/remove interactive features

### Color Scheme

Edit CSS variables in `styles.css`:

```css
:root {
    --primary-color: #00d4ff;      /* Cyan */
    --secondary-color: #7c3aed;    /* Purple */
    --accent-color: #ff006e;       /* Pink */
    --bg-dark: #0a0a0f;           /* Dark background */
}
```

### Fonts

Current fonts:
- **Orbitron**: Headers and titles (tech/futuristic feel)
- **JetBrains Mono**: Body text (developer aesthetic)

To change fonts, update the Google Fonts link in `index.html` and CSS font-family rules.

## 📧 Contact Form

The contact form uses `mailto:` link. To use a backend service:

### Option 1: FormSpree
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

### Option 2: Netlify Forms
Add `netlify` attribute to form:
```html
<form netlify>
```

### Option 3: Web3Forms
```html
<form action="https://api.web3forms.com/submit" method="POST">
    <input type="hidden" name="access_key" value="YOUR_ACCESS_KEY">
</form>
```


## 🔧 Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   cd YOUR_REPO_NAME
   ```

2. **Open in browser**
   - Simply open `index.html` in your browser
   - Or use Live Server extension in VS Code

3. **Using Python**
   ```bash
   python -m http.server 8000
   # Visit http://localhost:8000
   ```

4. **Using Node.js**
   ```bash
   npx serve
   # Visit http://localhost:3000
   ```

## 🎯 Performance Tips

- ✅ All images should be optimized (use WebP format)
- ✅ Minify CSS and JS for production
- ✅ Enable caching headers
- ✅ Use CDN for external resources
- ✅ Lazy load images below the fold

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Connect

- **Email**: khujratshaikh1284@gmail.com
- **LinkedIn**: [khujrat-shaikh](https://www.linkedin.com/in/khujrat-shaikh-8823a5203/)
- **GitHub**: [khujrat17](https://github.com/khujrat17)
- **NuGet**: [Khujrat17](https://www.nuget.org/profiles/Khujrat17)

## 🌟 Acknowledgments

- Font: [Google Fonts](https://fonts.google.com/)
- Icons: Custom SVG icons
- Inspiration: Modern web design trends and developer portfolios

---

**Made with 💙 by Khujrat Shaikh**

*⭐ If you like this portfolio, please give it a star on GitHub!*
