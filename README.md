# SINKOU Financial Services - Website

Professional financial planning website built with modern web technologies. This repository contains a fully responsive, beautifully designed website for SINKOU Financial Services.

## 📁 Folder Structure

```
sinkou-financial-services/
├── index.html                 # Main website file
├── README.md                  # This file
├── .gitignore                 # Git ignore rules
├── images/
│   ├── logo.png              # Company logo
│   ├── gallery/
│   │   ├── gallery-1.jpg      # Event photo 1
│   │   ├── gallery-2.jpg      # Event photo 2
│   │   ├── ... (gallery-3 to gallery-12)
│   │
│   └── team-members/
│       ├── sindhurao.jpg      # CEO/Founder photo
│       ├── abhishek.jpg       # (Add more team member photos here)
│       └── amareesh.jpg       # (Add more team member photos here)
│
└── .github/
    └── workflows/             # (Optional) CI/CD workflows
```

## 🚀 Quick Start

### Option 1: GitHub Pages (FREE & AUTOMATIC)

1. **Create GitHub Account** (if you don't have one)
   - Go to https://github.com
   - Sign up for free

2. **Create New Repository**
   - Click **"New"** button
   - Repository name: `sinkou-financial-services`
   - Description: "Professional Financial Services Website"
   - Choose **Public** (required for free hosting)
   - Click **"Create repository"**

3. **Upload Files**
   - Click **"Add file"** → **"Upload files"**
   - Drag & drop all files from this folder (maintain folder structure)
   - Or use Git CLI:
     ```bash
     git clone https://github.com/yourusername/sinkou-financial-services.git
     cd sinkou-financial-services
     # Copy all files here
     git add .
     git commit -m "Initial commit: Add website files"
     git push origin main
     ```

4. **Enable GitHub Pages**
   - Go to **Settings** → **Pages**
   - Under "Source", select **main** branch
   - Click **Save**
   - Wait 1-2 minutes for deployment

5. **Your Website is Live!**
   - Access at: `https://yourusername.github.io/sinkou-financial-services`
   - Share this URL with clients

### Option 2: Deploy to Netlify (Alternative)

1. Go to https://netlify.com
2. Sign up (free)
3. Drag & drop the `sinkou-financial-services` folder
4. Your site is live in 10 seconds!
5. Get a custom domain (paid)

## 📸 Adding/Updating Images

### Add Gallery Photos
1. Place images in `/images/gallery/` folder
2. Name them: `gallery-1.jpg`, `gallery-2.jpg`, etc.
3. Supported formats: `.jpg`, `.jpeg`, `.png`, `.gif`, `.webp`
4. Recommended size: 1200x1200px (landscape or square)
5. File size: Keep under 2MB per image for fast loading

### Add Team Member Photos
1. Place images in `/images/team-members/` folder
2. Name them after team members: `sindhurao.jpg`, `abhishek.jpg`, etc.
3. Update the HTML to reference new photos:
   ```html
   <img src="images/team-members/yourname.jpg" alt="Your Name">
   ```

### Update Logo
1. Replace `/images/logo.png` with your new logo
2. Keep filename as `logo.png`
3. Recommended size: 200x200px
4. Format: PNG (supports transparency)

## ✏️ Customizing Content

### Edit Contact Information
Open `index.html` and find these sections:

**Phone Number:**
```html
<a href="tel:669-249-2281" style="...">669-249-2281</a>
```

**Email:**
```html
<a href="mailto:sinkou377@gmail.com" style="...">sinkou377@gmail.com</a>
```

**Address:**
```html
1291 Vicente Dr, Apt 237, Sunnyvale, CA 94086
```

**Office Hours:**
```html
Mon–Sat: 9AM–6PM | Sun: 10AM–2PM
```

### Edit Team Members
Find the team section and update:
- Photo path in `src="images/team-members/..."`
- Name in `<h3>`
- Title in `<p style="color: var(--text-muted);">`

### Update Services
Find the services grid and modify descriptions for:
- Life Insurance
- Retirement Planning
- College Education Planning
- Wealth Management

## 🎨 Design Colors

The website uses a professional navy & green color scheme:

```css
--navy: #0d1f3c              /* Dark navy */
--green: #1a7a4a             /* Forest green */
--green-light: #22a35f       /* Lighter green */
--green-pale: #e6f4ed        /* Pale green background */
--white: #ffffff             /* Pure white */
--off-white: #f7f9fc         /* Soft white background */
```

To change colors, open `index.html` and modify the `:root` CSS variables.

## 📞 Contact Form Integration

The contact form is integrated with **Formspree** (free):

1. **Current Form ID:** `myzgozwj`
   - Submissions go to: `sinkou377@gmail.com`
   - Up to 50 submissions/month (free tier)

2. **To Customize:**
   - Sign up at https://formspree.io (free)
   - Create new form
   - Verify your email
   - Replace `myzgozwj` in the HTML:
     ```html
     <form action="https://formspree.io/f/YOUR_NEW_ID" method="POST">
     ```

3. **Upgrade to Pro:**
   - Unlimited submissions
   - File uploads
   - Custom redirects
   - Cost: $25/month

## 🔧 Technical Details

### Browser Compatibility
- Chrome, Firefox, Safari, Edge (latest versions)
- Mobile-friendly (iOS, Android)
- Responsive design (works on all screen sizes)

### Performance
- Page load: < 2 seconds (with optimized images)
- Mobile-first responsive design
- SEO optimized
- Accessible (WCAG compliant)

### Technologies Used
- HTML5
- CSS3
- Vanilla JavaScript (no frameworks)
- Google Fonts (Playfair Display, DM Sans)
- Formspree (contact form backend)

## 📊 Analytics (Optional)

To track visitors, add Google Analytics:

1. Go to https://analytics.google.com
2. Create free account
3. Add your website
4. Copy tracking ID
5. Add to `index.html` `<head>`:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXX');
</script>
```

## 🎯 SEO Optimization

The website includes:
- ✅ Meta descriptions
- ✅ Open Graph tags (for social media)
- ✅ Mobile viewport settings
- ✅ Semantic HTML
- ✅ Fast load times
- ✅ Mobile-responsive design

To improve further:
1. Submit to Google Search Console
2. Submit XML sitemap
3. Add schema markup for financial services
4. Build backlinks from local directories

## 🆘 Troubleshooting

### Images Not Loading
1. Check file paths match folder structure
2. Ensure image filenames are lowercase
3. File must be in correct folder (`/images/gallery/` or `/images/team-members/`)

### Contact Form Not Working
1. Verify Formspree ID is correct
2. Check email verification with Formspree
3. Test on different browser
4. Check browser console for errors (F12)

### Website Not Showing on GitHub Pages
1. Go to **Settings** → **Pages**
2. Ensure **main** branch is selected
3. Wait 1-2 minutes for deployment
4. Try clearing browser cache (Ctrl+Shift+Del)
5. Check if repository is **Public**

## 📝 Next Steps

1. ✅ Upload all files to GitHub
2. ✅ Enable GitHub Pages
3. ✅ Test website on phone
4. ✅ Share URL with team and clients
5. ✅ Monitor analytics (optional)
6. ✅ Update content as needed (add team photos, new services, etc.)

## 💬 Support

For issues with:
- **GitHub Pages:** https://docs.github.com/pages
- **Formspree:** https://formspree.io/help
- **HTML/CSS:** https://developer.mozilla.org

## 📄 License

Copyright © 2025 SINKOU Financial Services. All rights reserved.

---

**Ready to go live?** Follow the Quick Start steps above! 🚀
