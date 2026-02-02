# Quick Start Guide - Immigration Website

## 🚀 Get Your Website Live in 5 Minutes

### 1. Customize Your Information (2 minutes)

Open `index.html` and replace:
- `Your Name` → Your actual name
- `[Your License #]` → Your RCIC license number
- `[X] years` → Your years of experience
- `your.email@example.com` → Your email
- `+1 (234) 567-890` → Your phone number
- Your address, city, province
- Languages you speak

### 2. Upload to GitHub (2 minutes)

1. Create GitHub account (if you don't have one)
2. Create new repository: `yourname.github.io`
3. Upload these files:
   - index.html
   - styles.css
   - script.js

### 3. Enable GitHub Pages (1 minute)

1. Go to repository Settings
2. Click "Pages" in sidebar
3. Select "main" branch
4. Click Save

**Done!** Your site will be live at: `https://yourname.github.io`

---

## 📧 Make Contact Form Work

### Easiest Method: Formspree (FREE)

1. Go to [formspree.io](https://formspree.io)
2. Sign up (free)
3. Create new form
4. Copy your form endpoint
5. In `script.js`, find line ~150 and add your endpoint:

```javascript
const formspreeEndpoint = 'https://formspree.io/f/YOUR_FORM_ID';
```

---

## 🎨 Customize Colors

In `styles.css`, line 7-10:

```css
--primary-color: #1a2847;      /* Navy blue - change this */
--secondary-color: #c41e3a;    /* Red - change this */
--accent-color: #d4af37;       /* Gold - change this */
```

---

## 🖼️ Add Your Photo

In `index.html`, find the About section (around line 95):

Replace the placeholder div with:
```html
<img src="your-photo.jpg" alt="Your Name" style="width: 100%; border-radius: 20px;">
```

Upload your photo to the same folder as your HTML files.

---

## 🌐 Connect Your Domain

After your site is live on GitHub:

1. Buy domain (e.g., from Namecheap, GoDaddy)
2. Add DNS records (at your domain provider):
   - Type: CNAME
   - Name: www
   - Value: yourname.github.io

3. In GitHub repo Settings → Pages:
   - Enter your domain: www.yourname.com
   - Check "Enforce HTTPS"
   - Save

Wait 24 hours for DNS to update.

---

## ✅ Essential Checklist

Before launching:
- ✅ Replace all placeholder text
- ✅ Add your photo
- ✅ Update RCIC license number
- ✅ Set up Formspree for contact form
- ✅ Test on mobile phone
- ✅ Check all sections for accuracy

---

## 🆘 Need Help?

**Form not working?**
→ Set up Formspree (see above)

**Site not loading?**
→ Wait 10 minutes, GitHub Pages takes time to deploy

**Styles look broken?**
→ Make sure all 3 files (HTML, CSS, JS) are in the same folder

---

## 📱 Test Your Website

After deployment, test on:
- Your phone
- Desktop computer
- Different browsers (Chrome, Safari, Firefox)
- Fill out the contact form to test it works

---

**That's it!** Your professional immigration website is now live. 🎉

For detailed instructions, see the full README.md file.