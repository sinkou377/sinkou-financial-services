# 🚀 SINKOU Financial Services - GitHub Setup Guide

## Complete Step-by-Step Instructions

### STEP 1: Create GitHub Account (2 minutes)

1. Go to **https://github.com**
2. Click **Sign up**
3. Enter email, password, username
4. Verify email
5. Complete setup

---

### STEP 2: Create Repository (3 minutes)

1. Click **+** icon (top right) → **New repository**
2. **Repository name:** `sinkou-financial-services`
3. **Description:** Professional Financial Services Website
4. **Visibility:** Select **Public** ⭐ (required for free hosting)
5. ☑️ Check "Add a README file"
6. Click **Create repository**

---

### STEP 3: Upload Files (5 minutes)

**Option A: Web Upload (Easiest)**
1. Click **Add file** → **Upload files**
2. Drag & drop all files from the `sinkou-github` folder
3. Keep folder structure intact:
   - ✅ `index.html` (root)
   - ✅ `README.md`
   - ✅ `images/logo.png`
   - ✅ `images/gallery/` (all 12 images)
   - ✅ `images/team-members/` (team photos)
4. Click **Commit changes**

**Option B: Git CLI (For developers)**
```bash
# Clone repository
git clone https://github.com/YOUR-USERNAME/sinkou-financial-services.git
cd sinkou-financial-services

# Copy all files from sinkou-github folder here
cp -r /path/to/sinkou-github/* .

# Upload to GitHub
git add .
git commit -m "Add SINKOU Financial Services website"
git push origin main
```

---

### STEP 4: Enable GitHub Pages (2 minutes)

1. Go to repository **Settings** (top right)
2. Click **Pages** (left sidebar)
3. Under "Build and deployment":
   - **Source:** Select `Deploy from a branch`
   - **Branch:** Select `main` and `/root`
   - Click **Save**
4. Wait 1-2 minutes for deployment

---

### STEP 5: Get Your Live URL (1 minute)

1. Go back to **Settings** → **Pages**
2. You'll see: "Your site is live at: `https://YOUR-USERNAME.github.io/sinkou-financial-services`"
3. **Share this URL with clients!**

---

## 📋 File Checklist

Before uploading, verify you have:

```
sinkou-github/
├── ✅ index.html                    (Main website - 40KB)
├── ✅ README.md                      (Documentation)
├── ✅ .gitignore                     (Git settings)
├── images/
│   ├── ✅ logo.png                   (Company logo)
│   ├── gallery/
│   │   ├── ✅ gallery-1.jpg
│   │   ├── ✅ gallery-2.jpg
│   │   ├── ✅ gallery-3.jpg
│   │   ├── ✅ gallery-4.jpg
│   │   ├── ✅ gallery-5.jpg
│   │   ├── ✅ gallery-6.jpg
│   │   ├── ✅ gallery-7.jpg
│   │   ├── ✅ gallery-8.jpg
│   │   ├── ✅ gallery-9.jpg
│   │   ├── ✅ gallery-10.jpg
│   │   ├── ✅ gallery-11.jpg
│   │   └── ✅ gallery-12.jpg
│   └── team-members/
│       ├── ✅ sindhurao.jpg
│       ├── abhishek.jpg              (Add if available)
│       └── amareesh.jpg              (Add if available)
```

---

## 🎯 After Going Live

### Test Your Website
- [ ] Visit your GitHub Pages URL
- [ ] Check all pages load (Home, Services, Team, Gallery, About, Contact)
- [ ] Test on mobile phone
- [ ] Click gallery images (should open in lightbox)
- [ ] Test contact form
- [ ] Check links work

### Share & Promote
- [ ] Share URL with team members
- [ ] Update Google Business Profile
- [ ] Share on social media
- [ ] Add to email signature
- [ ] Include in marketing materials

### Customize
- [ ] Add more team member photos (drop in `/images/team-members/`)
- [ ] Add more gallery images (drop in `/images/gallery/`, rename sequentially)
- [ ] Update Formspree form ID for emails
- [ ] Add Google Analytics (optional)

---

## 🔧 How to Update Content Later

### To Add New Gallery Images:
1. Add images to `/images/gallery/` folder
2. Name them: `gallery-13.jpg`, `gallery-14.jpg`, etc.
3. Website automatically finds and displays them!

### To Add Team Members:
1. Add photo to `/images/team-members/` folder
2. Open `index.html` and find team section
3. Copy a team member card and modify:
   ```html
   <img src="images/team-members/newperson.jpg" alt="New Person">
   <h3>New Person Name</h3>
   <p>Job Title Here</p>
   ```
4. Save and push to GitHub

### To Change Contact Info:
1. Open `index.html` in any text editor
2. Use Ctrl+F (Find) to search for:
   - `669-249-2281` (phone)
   - `sinkou377@gmail.com` (email)
   - `Sunnyvale, CA` (address)
3. Replace with your information
4. Save and push to GitHub

---

## 📞 Important Links

| Service | Link | Notes |
|---------|------|-------|
| GitHub | https://github.com | Where your site is hosted |
| Pages Setup | https://docs.github.com/pages | GitHub Pages documentation |
| Formspree | https://formspree.io | Contact form backend |
| Custom Domain | https://docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site | (Optional) Buy custom domain |

---

## ❓ Troubleshooting

### Site Not Showing?
- ✅ Verify repository is **Public** (not Private)
- ✅ Check Pages is enabled in Settings
- ✅ Wait 2-3 minutes after first push
- ✅ Clear browser cache (Ctrl+Shift+Delete)

### Images Not Loading?
- ✅ Check file paths are correct
- ✅ Filenames are lowercase
- ✅ Images in correct folders
- ✅ File format supported (jpg, png, gif, webp)

### Contact Form Not Working?
- ✅ Visit https://formspree.io
- ✅ Verify your email address
- ✅ Check form ID in HTML matches Formspree
- ✅ Test in different browser

---

## 🎉 You're Ready!

Follow the 5 steps above and your professional website will be live in **15 minutes!**

Need help? Check the README.md file for detailed documentation.

**Questions?** Visit:
- GitHub Help: https://docs.github.com
- Formspree Support: https://formspree.io/help
- Web Development: https://developer.mozilla.org

---

**✅ Website Status:** Ready for deployment to GitHub Pages 🚀
