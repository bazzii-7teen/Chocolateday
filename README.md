
<div align="center">

# 🍫 Chocolate Day Website

*A romantic, interactive website for your special someone*

[![Made with Love](https://img.shields.io/badge/Made%20with-❤️-ff6b9d)](https://github.com/bazzii-7teen)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

</div>

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🎵 **Music Player** | Embedded YouTube with "I Wanna Be Yours" by Arctic Monkeys |
| 🖼️ **Real Photos** | Pinterest-style chocolate photo gallery |
| ⏰ **Live Countdown** | Updates every second to next Chocolate Day |
| 💝 **Interactive** | Pick gifts, pulse animations, floating hearts |
| 📱 **Mobile First** | Perfect for phone viewing |
| 🎨 **Glass-morphism** | Modern blur effects with pink-purple gradient |

---

## 🚀 Quick Setup

### Step 1: Fork or Download
Click the green **"<> Code"** button above → **Download ZIP**

### Step 2: Open `index.html`
Replace these **5 things** with your own:

#### 1️⃣ **Your Girlfriend's Name** (Line ~45)
```html
<!-- FIND THIS -->
<p class="subtitle">I made this for you, [HER NAME]</p>

<!-- CHANGE TO -->
<p class="subtitle">I made this for you, Sarah</p>
```

2️⃣ Your Name (Line 320)

```html
<!-- FIND THIS -->
<div class="memory-text">Making this for you at midnight... - [YOUR NAME]</div>

<!-- CHANGE TO -->
<div class="memory-text">Making this for you at midnight... - Mike</div>
```

3️⃣ Chocolate Photos (Lines 180-220)
Replace the 5 image URLs with your own:
- Upload photos to [postimg.cc](https://postimg.cc)
- Copy "Direct Link"
- Paste in the `src=""`

```html
<img src="YOUR_DIRECT_LINK_HERE" alt="chocolate">
```

4️⃣ YouTube Song (Line 250)

```html
<!-- Default: Arctic Monkeys - I Wanna Be Yours -->
src="https://www.youtube.com/embed/nyuo9-OjNNg"

<!-- Change to any YouTube video ID -->
src="https://www.youtube.com/embed/YOUR_VIDEO_ID"
```

5️⃣ Countdown Date (Line 450 in JavaScript)

```javascript
// Default: February 9 (Chocolate Day)
const chocolateDay = new Date(`February 9, ${targetYear} 00:00:00`);

// Change to any date:
const chocolateDay = new Date(`December 25, ${targetYear} 00:00:00`);
```

---

🎨 Customization Guide

Change Colors

```css
/* In the CSS section, find :root */
--accent-pink: #ff6b9d;    /* Change to your favorite pink */
--accent-purple: #c44569;  /* Change to your favorite purple */
```

Add More Sections
Copy any `<section>` block and paste before the `</div>` closing tag.

Change Floating Hearts

```javascript
// In the JavaScript, change heart emojis
const heartEmojis = ['💕', '💖', '💗', '💓', '💝'];
// Add your own: ['🌸', '✨', '🎀', '💫']
```

---

📱 Live Demo

🌐 See it live: [https://bazzii-7teen.github.io/Chocolateday/](https://bazzii-7teen.github.io/Chocolateday/)

---

🖼️ Photo Resources

Site	Best For	Link	
Postimg	Hosting your photos	[postimg.cc](https://postimg.cc)	
Unsplash	Free chocolate photos	[unsplash.com](https://unsplash.com/s/photos/chocolate)	
Pexels	Free dessert photos	[pexels.com](https://pexels.com/search/chocolate/)	

---

💝 Tips for Maximum Impact

1. Send at midnight ⏰ - Extra romantic points
2. Text her first 📱 - "Check your messages, I made something"
3. Be ready 😅 - She might cry (happy tears)
4. Have real chocolate ready 🍫 - This website + real chocolate = perfect

---

🛠️ Troubleshooting

Problem	Solution	
Photos not showing	Check Postimg links are "Direct Link"	
Music not playing	YouTube might be blocked, try different video	
Countdown wrong	Check date format: `Month Day, Year`	
Not mobile friendly	Make sure viewport meta tag is present	

---

💌 Made with nervous hands

For that one person who makes everything better

⭐ Star this repo if it helped you!
