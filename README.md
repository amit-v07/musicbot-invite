# Music Bot Landing Page 🎵

A beautiful, modern landing page for your Discord Music Bot!

## 🌟 Preview

The landing page features:
- **Gradient Background** (Purple to Pink)
- **Hero Section** with floating animation
- **6 Feature Cards** with hover effects
- **Quick Commands** section
- **Prominent Invite Button**
- **Fully Responsive** (Mobile & Desktop)
- **Modern Glassmorphism** design

## 🚀 Deployment Options

### Option 1: GitHub Pages (Free & Easy)

1. **Create a GitHub repository:**
   ```bash
   # Navigate to landing-page folder
   cd "landing-page"
   
   # Initialize git
   git init
   git add index.html README.md
   git commit -m "Initial commit: Music Bot landing page"
   ```

2. **Push to GitHub:**
   ```bash
   # Create a new repo on GitHub named "musicbot-invite"
   git remote add origin https://github.com/YOUR_USERNAME/musicbot-invite.git
   git branch -M main
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to repository Settings
   - Scroll to "Pages"
   - Source: Deploy from a branch
   - Branch: `main` / `/(root)`
   - Save

4. **Your URL:** `https://YOUR_USERNAME.github.io/musicbot-invite`

### Option 2: Vercel (Free with Custom Domain)

1. Install Vercel CLI:
   ```bash
   npm install -g vercel
   ```

2. Deploy:
   ```bash
   cd landing-page
   vercel
   ```

3. Follow prompts, get instant URL: `https://musicbot-invite.vercel.app`

### Option 3: Netlify Drop (Drag & Drop)

1. Go to https://app.netlify.com/drop
2. Drag the `landing-page` folder
3. Instant deployment!
4. Optional: Add custom domain

### Option 4: Local Preview

1. Open `index.html` in your browser:
   ```bash
   # On Windows
   start index.html
   
   # Or just double-click the file
   ```

## 🎨 Customization

### Change Colors

Edit the CSS gradients in `index.html`:

```css
/* Hero Background */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Button Gradient */
background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
```

### Update Bot Name/Info

Find and replace in `index.html`:
- "Music Bot" → Your bot name
- Features text
- Footer credits

### Change Invite Link

Replace this URL (appears twice):
```
https://discord.com/oauth2/authorize?client_id=1397919621473894470&permissions=45214784&integration_type=0&scope=bot
```

## 🔗 Custom Domain Setup

### GitHub Pages + Custom Domain

1. Buy a domain (e.g., `musicbot.com`)
2. Add CNAME file to repo:
   ```
   musicbot.com
   ```
3. In domain DNS settings, add:
   - Type: `CNAME`
   - Name: `@` or `www`
   - Value: `YOUR_USERNAME.github.io`
4. In GitHub repo settings → Pages → Custom domain: `musicbot.com`

### URL Shortener Alternative

Use **Bitly** for instant custom short link:
1. Go to https://bitly.com
2. Paste your GitHub Pages URL
3. Customize: `bit.ly/musicbot-invite`
4. Done!

## 📱 Mobile Responsive

The page automatically adapts to:
- Mobile phones (< 768px)
- Tablets (768px - 1024px)
- Desktops (> 1024px)

## ✨ Features

- ✅ Pure HTML/CSS (no dependencies)
- ✅ Fast loading (< 50KB)
- ✅ Smooth animations
- ✅ Glassmorphism effects
- ✅ SEO optimized
- ✅ No JavaScript required

## 🎯 Analytics (Optional)

Add Google Analytics by inserting before `</head>`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 📊 Track Invite Clicks

Use UTM parameters in your invite link:

```
https://discord.com/oauth2/authorize?client_id=1397919621473894470&permissions=45214784&integration_type=0&scope=bot&utm_source=landingpage&utm_medium=website
```

Then track in Discord bot logs when users join from this link.

## 🤝 Support

Questions? Contact:
- GitHub: [Your GitHub]
- Discord: [Your Server]
- Email: [Your Email]

---

Made with ❤️ by Amit Kumar | Music Bot 2026 Edition
