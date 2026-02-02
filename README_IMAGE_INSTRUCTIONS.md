# Adding Your Background Image

## How to Add Your Large Background Image

Since your image is very large, we'll use it as a background image for the hero section.

### Step 1: Download Your Image

1. Go to your Google Drive link: https://drive.google.com/file/d/1-9MjBXRn1m1Gcnvrj5gH_GJSjCd6XC2f/view?usp=drive_link
2. Click "Download" 
3. Save it as `background.jpg` in this same folder

### Step 2: Update the CSS

Open `styles.css` and find the `.hero-background` section (around line 25):

```css
.hero-background {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-image: url('background.jpg');  /* ADD THIS LINE */
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    z-index: -1;
}
```

### Step 3: Optimize if Needed

If the image is too large (over 2MB), consider:
- Using a tool like TinyPNG.com to compress it
- Using a lower resolution version for web
- Converting to WebP format for better compression

### Alternative: Use Image URL

If you prefer to host the image elsewhere, you can:
1. Upload to Imgur or another image host
2. Get the direct URL
3. Use that URL in the CSS instead of `background.jpg`

Example:
```css
background-image: url('https://i.imgur.com/your-image-url.jpg');
```

## Current Status

✅ Website customized with your information:
- Name: Khalil Humam  
- Website: Unlock Immigration
- Email: khalil.humam@unlockimmigration.ca
- Phone: +1.236.777.9820
- Address: Brentwood Mall, Burnaby, BC, Canada

✅ Contact form configured (needs Formspree setup)

⏳ Background image: Waiting for you to add it

## Next Steps

1. Add your background image (instructions above)
2. Set up Formspree for the contact form
3. Deploy to GitHub Pages
4. Configure your custom domain
