# Portfolio - Hariharan Selvaraj

Personal portfolio website showcasing my work as a Product Engineer specializing in TypeScript, React, Next.js, and AI-powered applications.

![Portfolio Preview](https://img.shields.io/badge/Status-Live-success)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## ✨ Features

- **Modern Design**: Clean, technical aesthetic with animated gradients and smooth transitions
- **Fully Responsive**: Optimized for all devices from mobile to desktop
- **Performance Optimized**: Pure HTML/CSS/JS with no build step required
- **Smooth Animations**: Scroll-triggered animations and interactive hover effects
- **SEO Ready**: Proper meta tags and semantic HTML structure

## 🚀 Quick Start

### View Live

Visit the live portfolio at: `https://hari2309s.github.io/portfolio`

### Run Locally

1. Clone the repository:
```bash
git clone https://github.com/hari2309s/portfolio.git
cd portfolio
```

2. Open `index.html` in your browser:
```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

Or use a local server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js http-server
npx http-server
```

Then navigate to `http://localhost:8000`

## 📦 Deployment to GitHub Pages

### Option 1: Using the GitHub Web Interface

1. Create a new repository named `portfolio` (or any name you prefer)
2. Upload `index.html` to the repository
3. Go to **Settings** → **Pages**
4. Under "Source", select **main** branch
5. Click **Save**
6. Your site will be live at `https://<username>.github.io/portfolio`

### Option 2: Using Git Commands

```bash
# Initialize git repository
git init
git add .
git commit -m "Initial commit: Portfolio website"

# Add remote repository
git remote add origin https://github.com/<username>/portfolio.git

# Push to GitHub
git branch -M main
git push -u origin main
```

Then enable GitHub Pages in repository settings as described above.

### Option 3: Deploy to username.github.io

For a portfolio at the root domain (`https://<username>.github.io`):

1. Create a repository named `<username>.github.io`
2. Push your code to the `main` branch
3. GitHub Pages will automatically serve `index.html`
4. Your site will be live at `https://<username>.github.io`

## 🎨 Customization

### Colors

Edit the CSS variables in the `<style>` section:

```css
:root {
    --color-bg: #0a0a0f;           /* Background color */
    --color-surface: #15151f;      /* Card backgrounds */
    --color-accent: #00d9ff;       /* Primary accent (cyan) */
    --color-purple: #a855f7;       /* Secondary accent */
    --color-pink: #ec4899;         /* Tertiary accent */
}
```

### Content

Update the following sections in `index.html`:

- **Hero Section**: Update name, title, and description
- **Skills**: Add or remove skill categories and tags
- **Projects**: Add your projects with descriptions and links
- **Experience**: Update work history with companies and achievements
- **Education**: Update degree information
- **Contact**: Update email and social media links

### Fonts

The portfolio uses:
- **JetBrains Mono** for monospace/code aesthetic
- **Crimson Pro** for elegant serif headings

To change fonts, update the Google Fonts link in the `<head>`:

```html
<link href="https://fonts.googleapis.com/css2?family=Your+Font&display=swap" rel="stylesheet">
```

## 📱 Responsive Breakpoints

- **Desktop**: > 968px
- **Tablet**: 640px - 968px
- **Mobile**: < 640px

## 🛠️ Technologies Used

- HTML5
- CSS3 (Custom Properties, Grid, Flexbox, Animations)
- Vanilla JavaScript (Intersection Observer API)
- Google Fonts

## 📄 License

MIT License - feel free to use this template for your own portfolio!

## 🤝 Connect

- **Email**: hariharan.2309.s@icloud.com
- **LinkedIn**: [linkedin.com/in/hariharan-selvaraj](https://linkedin.com/in/hariharan-selvaraj)
- **GitHub**: [github.com/hari2309s](https://github.com/hari2309s)

---

Built with ❤️ and clean code
