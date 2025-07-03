# PurpleGold Cybersecurity Certification Landing Page

A modern, responsive landing page for PurpleGold's affordable cybersecurity certification program.

## 🚀 Features

- **Responsive Design** - Works perfectly on all devices
- **Modern UI/UX** - Clean, professional design with smooth animations
- **SEO Optimized** - Meta tags, structured data, and performance optimized
- **Fast Loading** - Optimized images and efficient CSS/JS
- **Contact Forms** - Ready-to-use enrollment forms
- **Social Proof** - Testimonials and statistics sections

## 📁 Project Structure

```
purple-course/
├── new212.html          # Main landing page
├── styles.css           # All styles and animations
├── script.js            # Interactive functionality
├── images/              # All images and logos
│   ├── hero.png         # Hero section image
│   ├── logo.png         # Main logo
│   └── logo-white.png   # White logo for footer
├── vercel.json          # Vercel deployment config
├── package.json         # Project metadata
└── README.md           # This file
```

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS Grid, Flexbox, and animations
- **JavaScript** - Interactive features and form handling
- **Font Awesome** - Icons
- **Google Fonts** - Inter font family

## 🚀 Deployment to Vercel

### Option 1: Deploy via Vercel CLI

1. **Install Vercel CLI** (if not already installed):
   ```bash
   npm i -g vercel
   ```

2. **Deploy from your project directory**:
   ```bash
   vercel
   ```

3. **Follow the prompts** to connect your GitHub account and configure the project.

### Option 2: Deploy via GitHub Integration

1. **Push your code to GitHub**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/purplegold-landing.git
   git push -u origin main
   ```

2. **Connect to Vercel**:
   - Go to [vercel.com](https://vercel.com)
   - Sign up/Login with GitHub
   - Click "New Project"
   - Import your GitHub repository
   - Deploy!

### Option 3: Drag & Drop Deployment

1. **Zip your project folder**
2. **Go to [vercel.com](https://vercel.com)**
3. **Drag and drop the zip file**
4. **Your site will be deployed instantly!**

## ⚙️ Configuration

### Vercel Settings

The `vercel.json` file includes:
- **Static file serving** for HTML, CSS, JS, and images
- **Security headers** for XSS protection and content type options
- **Caching headers** for optimal performance
- **Route handling** for clean URLs

### Custom Domain

After deployment, you can add a custom domain:
1. Go to your Vercel dashboard
2. Select your project
3. Go to "Settings" → "Domains"
4. Add your custom domain

## 🔧 Local Development

### Prerequisites
- Node.js (v14 or higher)

### Setup
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/purplegold-landing.git
   cd purplegold-landing
   ```

2. **Install dependencies** (optional, for local development):
   ```bash
   npm install
   ```

3. **Run locally**:
   ```bash
   npm run dev
   # or
   npx serve .
   ```

4. **Open in browser**: `http://localhost:3000`

## 📱 Performance Optimizations

- **Image Optimization**: All images are optimized for web
- **CSS Minification**: Styles are optimized for production
- **JavaScript Optimization**: Efficient code with minimal bundle size
- **Caching**: Proper cache headers for static assets
- **CDN**: Vercel's global CDN for fast loading worldwide

## 🔒 Security Features

- **XSS Protection**: Headers configured to prevent XSS attacks
- **Content Type Options**: Prevents MIME type sniffing
- **Frame Options**: Prevents clickjacking attacks
- **HTTPS**: Automatic SSL certificate with Vercel

## 📊 Analytics & Monitoring

After deployment, you can add:
- **Google Analytics** for visitor tracking
- **Vercel Analytics** for performance monitoring
- **Google Search Console** for SEO monitoring

## 🎨 Customization

### Colors
Update the CSS custom properties in `styles.css`:
```css
:root {
  --primary-purple: #6B46C1;
  --secondary-purple: #8B5CF6;
  /* ... other colors */
}
```

### Content
- Update text content in `new212.html`
- Replace images in the `images/` folder
- Modify contact information and social links

### Styling
- All styles are in `styles.css`
- Responsive breakpoints are clearly defined
- Animation timings can be adjusted

## 📞 Support

For deployment issues:
- Check [Vercel Documentation](https://vercel.com/docs)
- Review [Vercel Community](https://github.com/vercel/vercel/discussions)

## 📄 License

MIT License - feel free to use this template for your projects!

---

**Deployed by PurpleGold** 🚀 