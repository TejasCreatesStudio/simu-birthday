# 💙 Simu's Birthday Website

A beautiful, interactive birthday webpage with animations, gallery, heartfelt letter, and more.

## ✨ Features

- **Intro Section** - Animated greeting with scroll indicator
- **Photo Gallery** - 5 photos with captions and hover effects
- **Flower Canvas** - Animated blue orchids bouquet
- **Love Letter** - Heartfelt message with elegant typography
- **Birthday Cake** - Interactive canvas with candle blowing animation
- **Message Box** - Space to leave personal notes
- **Background Music** - Toggle-able background audio
- **Navigation Dots** - Quick section navigation
- **Starfield Background** - Animated stars across all sections
- **Responsive Design** - Works on mobile & desktop

## 🚀 Deployment to Netlify

### Step 1: Push to GitHub (Already Done!)
Your code is now in the `simu-birthday` repository.

### Step 2: Deploy on Netlify

1. Go to **[netlify.com](https://netlify.com)**
2. Click **"New site from Git"**
3. Select **GitHub** and authorize
4. Choose the **`simu-birthday`** repository
5. Leave all build settings as default (static site)
6. Click **"Deploy"** 

**Your live site will be ready in seconds!** 🎉

### Step 3: Add Your Photos

Replace placeholder images in `index.html` gallery section (lines ~190-198):
```html
<img src="YOUR_IMAGE_URL_HERE" alt="Photo description">
```

You can:
- Upload images to GitHub and use their raw URLs
- Use Imgur, Cloudinary, or any image hosting
- Upload to your own server

## 📝 How to Customize

### Change Photos & Captions
Edit lines in the gallery section:
```html
<img src="your-image-url" alt="Photo">
<div class="ph-over"><p class="ph-cap">Your caption here ✨</p></div>
```

### Change Music
Replace the audio source (line ~232):
```html
<source src="YOUR_MUSIC_URL" type="audio/mpeg">
```

### Edit the Letter
Modify the text in the letter section (lines ~290-320)

### Change Colors
Edit CSS variables at the top (lines ~16-23):
```css
:root{
  --orchid: #4a90d9;    /* Main blue color */
  --gold: #e8c97a;      /* Gold accents */
  /* ... etc ... */
}
```

## 📱 Preview

The site includes:
- Smooth scroll animations
- Interactive music player
- Responsive mobile design
- Beautiful gradient backgrounds
- Hover effects on gallery

## 🎁 Ready to Deploy!

Your code is production-ready. Just connect it to Netlify and share the link! 💙

---

*Made with love for Simu on May 8th* 🌸✨
