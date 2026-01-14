# 🏁 APEX VELOCITY - Free Racing Team Template

## Complete Customization Guide

**Version:** 1.0  
**Last Updated:** January 2025  
**Author:** [Your Name]  
**License:** FREE for personal & commercial use (no resale)

---

## 📦 What's Included

- ✅ 5 Fully Responsive HTML Pages
- ✅ Premium CSS Styling (800+ lines)
- ✅ Vanilla JavaScript Functionality
- ✅ Mobile-First Design
- ✅ Scroll Animations
- ✅ Contact Form with Validation
- ✅ Complete Documentation
- ✅ 100% FREE (no hidden costs)
- ✅ Use for personal & commercial projects

---

## 🚀 Quick Start (5 Minutes)

### Step 1: Extract Files
Unzip the template and upload all files to your web server maintaining the folder structure.

### Step 2: Change Team Name
Open **ALL** HTML files and find/replace:
- `APEX VELOCITY` → `YOUR TEAM NAME`
- `Apex Velocity Racing` → `Your Full Team Name`
- `@apexvelocity.racing` → `@yourteam.com`

### Step 3: Update Colors (Optional)
Open `css/style.css` and modify lines 10-17:
```css
--color-primary: #FF3C00;    /* Your main brand color */
--color-accent: #00E5FF;     /* Your accent color */
```

### Step 4: Add Your Content
Replace placeholder text with your actual team information.

### Step 5: Upload & Launch! 🎉

---

## 🎨 Full Customization Guide

### 1. BRANDING

#### A. Team Name & Logo
**Files to Edit:** All `.html` files

**Current:**
```html
<a href="index.html" class="nav-logo">
  APEX <span>VELOCITY</span>
</a>
```

**How to Change:**
1. Replace "APEX VELOCITY" with your team name
2. To add an image logo instead:
```html
<a href="index.html" class="nav-logo">
  <img src="assets/images/logo.png" alt="Your Team" style="height: 40px;">
</a>
```

#### B. Color Scheme
**File:** `css/style.css` (Lines 10-17)

**Current Colors:**
- Primary: `#FF3C00` (Racing Red)
- Accent: `#00E5FF` (Tech Cyan)
- Dark Backgrounds: `#0A0A0A`, `#141414`, `#1E1E1E`

**Popular Motorsport Color Schemes:**

| Team Style | Primary | Accent | Description |
|------------|---------|--------|-------------|
| Ferrari Inspired | `#DC0000` | `#FFD700` | Classic racing red + gold |
| McLaren Inspired | `#FF8700` | `#47C7FC` | Papaya orange + blue |
| Mercedes Inspired | `#00D2BE` | `#C6C6C6` | Petronas teal + silver |
| Red Bull Inspired | `#0600EF` | `#FCD700` | Racing blue + yellow |
| Lamborghini | `#E0B115` | `#000000` | Gold + black |
| Porsche GT | `#D5001C` | `#FFFFFF` | Guards red + white |

**How to Change:**
```css
:root {
  --color-primary: #YOUR_COLOR;
  --color-primary-dark: #DARKER_SHADE;
  --color-accent: #YOUR_ACCENT;
}
```

#### C. Typography
**Files:** All `.html` files `<head>` section + `css/style.css`

**Current Fonts:**
- Display: Rajdhani (Bold, Technical)
- Body: Space Mono (Monospace, Racing-style)

**How to Change:**

**Step 1:** Replace Google Fonts link in ALL HTML files:
```html
<!-- CURRENT -->
<link href="https://fonts.googleapis.com/css2?family=Rajdhani:wght@400;600;700&family=Space+Mono:wght@400;700&display=swap" rel="stylesheet">

<!-- OPTION 1: Modern Clean -->
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700;900&family=Roboto:wght@400;700&display=swap" rel="stylesheet">

<!-- OPTION 2: Elegant -->
<link href="https://fonts.googleapis.com/css2?family=Oswald:wght@400;600;700&family=Open+Sans:wght@400;700&display=swap" rel="stylesheet">

<!-- OPTION 3: Technical -->
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700;900&family=Exo+2:wght@400;700&display=swap" rel="stylesheet">
```

**Step 2:** Update CSS variables in `css/style.css`:
```css
:root {
  --font-display: 'YourDisplayFont', sans-serif;
  --font-body: 'YourBodyFont', sans-serif;
}
```

---

### 2. CONTENT CUSTOMIZATION

#### A. Homepage (index.html)

**Hero Section** (Lines 45-65):
```html
<p class="hero-label">2025 SEASON</p>  <!-- Change year/season -->
<h1 class="hero-title">
  RACING AT THE<br>
  <span class="text-accent">EDGE OF EXCELLENCE</span>  <!-- Your tagline -->
</h1>
<p class="hero-subtitle">
  Your team description here
</p>
```

**Statistics** (Lines 75-95):
Update the numbers to match your team:
```html
<div class="stat-number">12</div>      <!-- Your victories -->
<div class="stat-label">Race Victories</div>

<div class="stat-number">3</div>       <!-- Your championships -->
<div class="stat-label">Championships</div>
```

**Latest News** (Lines 120-170):
Replace with your actual news items:
```html
<p style="...">DECEMBER 18, 2024</p>  <!-- Date -->
<h3>Your News Headline</h3>
<p class="card-text">
  Your news description...
</p>
```

**Sponsors** (Lines 180-200):
Replace sponsor names with your actual partners.

#### B. Team Page (team.html)

**Driver Profiles** (Lines 50-110):
```html
<h3 class="team-member-name">JAMES MORRISON</h3>  <!-- Driver name -->
<p class="team-member-role">Lead Driver</p>       <!-- Position -->
<p class="team-member-bio">
  Driver biography here...
</p>
```

**Add/Remove Team Members:**
To add more drivers, copy this entire block:
```html
<div class="card team-member reveal">
  <div class="team-member-image" style="background: linear-gradient(135deg, var(--color-primary) 0%, var(--color-primary-dark) 100%);"></div>
  <div class="card-content">
    <h3 class="team-member-name">NEW DRIVER NAME</h3>
    <p class="team-member-role">Position</p>
    <p class="team-member-bio">Bio text...</p>
  </div>
</div>
```

#### C. Car Specs (car.html)

**Technical Specifications** (Lines 80-200):
Update all spec tables with your actual car data:
```html
<tr>
  <td>Engine Type</td>
  <td>V8 Naturally Aspirated</td>  <!-- Your engine -->
</tr>
<tr>
  <td>Power Output</td>
  <td>580 HP @ 8,500 RPM</td>      <!-- Your power -->
</tr>
```

#### D. Partners (partners.html)

**Partner Logos:**
Replace sponsor placeholders with actual logos:
```html
<!-- Current placeholder -->
<div class="sponsor-logo">VELOCIS</div>

<!-- With image -->
<div class="sponsor-logo">
  <img src="assets/images/sponsors/velocis.png" alt="Velocis" style="max-width: 80%; max-height: 80%;">
</div>
```

#### E. Contact Page (contact.html)

**Contact Information** (Lines 50-90):
```html
<p style="color: var(--color-gray-light);">
  <a href="mailto:info@apexvelocity.racing">info@yourteam.com</a><br>
  +44 (0) 1234 567890  <!-- Your phone -->
</p>

<!-- Address -->
<p style="color: var(--color-gray-light);">
  Your Team Name<br>
  Your Street Address<br>
  City, State/Region ZIP<br>
  Country
</p>
```

**Contact Form:**
The form is fully functional with JavaScript validation. Email submissions require backend integration (see Advanced Customization).

---

### 3. IMAGES & MEDIA

#### A. Adding Images

**Recommended Image Sizes:**
- Hero Backgrounds: 1920x1080px
- Team Member Photos: 600x800px (portrait)
- Car Images: 1200x675px (landscape)
- Sponsor Logos: 400x200px (maintain aspect ratio)

**File Locations:**
```
assets/
├── images/
│   ├── hero-bg.jpg
│   ├── team/
│   │   ├── driver-1.jpg
│   │   ├── driver-2.jpg
│   ├── car/
│   │   ├── car-main.jpg
│   │   ├── car-detail.jpg
│   └── sponsors/
│       ├── sponsor-1.png
│       └── sponsor-2.png
```

**How to Add Background Images:**
```html
<!-- Current: Gradient placeholder -->
<div class="card-image" style="background: linear-gradient(...);"></div>

<!-- With image -->
<div class="card-image" style="background: url('assets/images/your-image.jpg') center/cover;"></div>
```

**How to Add Team Photos:**
```html
<div class="team-member-image" style="background: url('assets/images/team/driver-1.jpg') center/cover;"></div>
```

#### B. Optimizing Images

**Before uploading:**
1. Resize to recommended dimensions
2. Compress using TinyPNG or similar (aim for <200KB per image)
3. Use .jpg for photos, .png for logos with transparency
4. Use modern formats (.webp) for better performance (optional)

---

### 4. ADVANCED CUSTOMIZATION

#### A. Changing Page Layouts

**Switch from 3-column to 2-column grid:**
```html
<!-- Current -->
<div class="grid grid-3">

<!-- Change to -->
<div class="grid grid-2">
```

**Available grid classes:**
- `grid-2` - 2 columns (responsive to 1 on mobile)
- `grid-3` - 3 columns (responsive to 1 on mobile)
- `grid-4` - 4 columns (responsive to 2 on mobile)

#### B. Adding New Pages

**Step 1:** Duplicate any existing HTML file (e.g., `team.html`)

**Step 2:** Rename it (e.g., `news.html`)

**Step 3:** Update navigation in ALL HTML files:
```html
<ul class="nav-menu">
  <li><a href="index.html" class="nav-link">HOME</a></li>
  <li><a href="team.html" class="nav-link">TEAM</a></li>
  <li><a href="car.html" class="nav-link">CAR</a></li>
  <li><a href="news.html" class="nav-link">NEWS</a></li>  <!-- NEW -->
  <li><a href="partners.html" class="nav-link">PARTNERS</a></li>
  <li><a href="contact.html" class="nav-link">CONTACT</a></li>
</ul>
```

**Step 4:** Update footer links in ALL files

**Step 5:** Customize content in your new page

#### C. Animation Adjustments

**Speed up/slow down animations:**
`css/style.css` - Lines 30-35:
```css
:root {
  --transition-fast: 0.2s ease;   /* Change to 0.1s for faster */
  --transition-base: 0.3s ease;   /* Change to 0.5s for slower */
  --transition-slow: 0.5s ease;   /* Change to 0.8s for slower */
}
```

**Disable scroll animations:**
Remove the `reveal` class from elements in HTML files:
```html
<!-- With animation -->
<div class="card reveal">

<!-- Without animation -->
<div class="card">
```

#### D. Contact Form Backend Integration

The current form has client-side validation only. To actually send emails:

**Option 1: FormSubmit (Free, No Coding)**
```html
<form action="https://formsubmit.co/your@email.com" method="POST">
  <!-- Keep existing form fields -->
  <!-- Add these hidden fields: -->
  <input type="hidden" name="_subject" value="New Contact Form Submission">
  <input type="hidden" name="_captcha" value="false">
  <input type="text" name="_honey" style="display:none">
  <!-- Keep submit button -->
</form>
```

**Option 2: Formspree (Free/Paid)**
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
  <!-- Keep existing fields -->
</form>
```

**Option 3: Custom Backend**
Modify `js/main.js` to send AJAX requests to your server endpoint.

#### E. SEO Optimization

**Update meta tags in ALL HTML files:**
```html
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
  <!-- UPDATE THESE -->
  <meta name="description" content="Your team description for search engines">
  <meta name="keywords" content="your, keywords, here, racing, motorsport">
  <title>Your Page Title | Your Team Name</title>
  
  <!-- ADD THESE (Optional but recommended) -->
  <meta property="og:title" content="Your Team Name">
  <meta property="og:description" content="Your description">
  <meta property="og:image" content="https://yoursite.com/assets/images/og-image.jpg">
  <meta property="og:url" content="https://yoursite.com">
  <meta name="twitter:card" content="summary_large_image">
</head>
```

---

### 5. RESPONSIVE DESIGN

The template is fully responsive with these breakpoints:

- **Mobile:** 320px - 767px
- **Tablet:** 768px - 1023px
- **Desktop:** 1024px+

**Testing Responsiveness:**
1. Open site in Chrome
2. Press F12 (Developer Tools)
3. Click device toggle icon
4. Test different screen sizes

**Common Mobile Issues:**
- If text is too small: Adjust `clamp()` values in CSS
- If layout breaks: Check grid classes are correct
- If images don't load: Verify file paths

---

### 6. BROWSER COMPATIBILITY

**Tested and Supported:**
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

**Not Supported:**
- ❌ Internet Explorer (use Edge instead)

---

### 7. PERFORMANCE OPTIMIZATION

#### A. Speed Tips

1. **Optimize Images:**
   - Use compressed JPGs/PNGs
   - Consider WebP format
   - Lazy load images below fold

2. **Minify Code (Production):**
   - Use CSS minifier: https://cssminifier.com
   - Use JS minifier: https://javascript-minifier.com

3. **Enable Caching:**
   Add to `.htaccess` (Apache) or equivalent:
   ```apache
   <IfModule mod_expires.c>
     ExpiresActive On
     ExpiresByType image/jpg "access plus 1 year"
     ExpiresByType image/jpeg "access plus 1 year"
     ExpiresByType image/png "access plus 1 year"
     ExpiresByType text/css "access plus 1 month"
     ExpiresByType application/javascript "access plus 1 month"
   </IfModule>
   ```

#### B. Loading Speed

Current performance:
- First Paint: ~0.8s
- Fully Loaded: ~1.5s
- Page Size: ~150KB (without images)

---

### 8. DEPLOYMENT

#### A. File Structure for Upload

Upload maintaining this exact structure:
```
your-domain.com/
├── index.html
├── team.html
├── car.html
├── partners.html
├── contact.html
├── css/
│   └── style.css
├── js/
│   └── main.js
├── assets/
│   ├── images/
│   ├── icons/
│   └── fonts/
└── [Optional: .htaccess, robots.txt, sitemap.xml]
```

#### B. Hosting Recommendations

**Beginner-Friendly:**
- Netlify (Free, drag & drop)
- Vercel (Free, git integration)
- GitHub Pages (Free)

**Traditional Hosting:**
- SiteGround
- Bluehost
- HostGator

**Requirements:**
- HTML/CSS/JS support (all hosts)
- No special server requirements
- PHP optional (only for contact form backend)

#### C. Domain Setup

1. Purchase domain from Namecheap, GoDaddy, etc.
2. Point DNS to your hosting
3. Wait 24-48h for propagation
4. Upload files via FTP/cPanel

---

### 9. TROUBLESHOOTING

#### Problem: Styles not loading
**Solution:** Check file paths in HTML `<head>`:
```html
<link rel="stylesheet" href="css/style.css">
```
Ensure `css` folder is in same directory as HTML files.

#### Problem: Navigation not working on mobile
**Solution:** Verify `js/main.js` is loading:
```html
<script src="js/main.js"></script>
```
Check browser console (F12) for errors.

#### Problem: Images not showing
**Solution:** 
- Verify file paths are correct
- Check file extensions (.jpg not .JPG)
- Ensure images are in `assets/images/`

#### Problem: Contact form not submitting
**Solution:** 
- Current form is frontend-only
- See "Contact Form Backend Integration" section
- Check browser console for validation errors

#### Problem: Animation issues
**Solution:**
- Clear browser cache (Ctrl+Shift+Delete)
- Check if JavaScript is enabled
- Verify `reveal` class usage

---

### 10. ADDITIONAL FEATURES

#### A. Add Social Media Links

Update footer in ALL HTML files:
```html
<div class="footer-section">
  <h3>CONNECT</h3>
  <ul class="footer-links">
    <li><a href="https://instagram.com/yourteam" target="_blank">Instagram</a></li>
    <li><a href="https://twitter.com/yourteam" target="_blank">Twitter</a></li>
    <li><a href="https://facebook.com/yourteam" target="_blank">Facebook</a></li>
    <li><a href="https://youtube.com/@yourteam" target="_blank">YouTube</a></li>
  </ul>
</div>
```

#### B. Add Google Analytics

Add before `</head>` in ALL HTML files:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

#### C. Add Cookie Notice

Add before `</body>` in ALL HTML files:
```html
<div id="cookie-notice" style="position: fixed; bottom: 0; left: 0; right: 0; background: var(--color-dark-2); padding: 1rem; text-align: center; border-top: 1px solid var(--color-primary); display: none; z-index: 9999;">
  <p style="margin: 0 0 1rem 0; color: var(--color-gray-light);">This website uses cookies to ensure you get the best experience.</p>
  <button onclick="document.getElementById('cookie-notice').style.display='none'" class="btn btn-primary" style="padding: 0.5rem 2rem;">Accept</button>
</div>
```

---

## 💎 Premium Support

Need help customizing? Email: support@yoursite.com

**Support includes:**
- Installation assistance
- Customization help
- Bug fixes
- Updates

**Response time:** Within 24 hours

---

## 📋 Checklist Before Launch

- [ ] Updated all team names
- [ ] Changed brand colors
- [ ] Updated contact information
- [ ] Replaced all placeholder text
- [ ] Added your images
- [ ] Updated sponsor logos
- [ ] Configured contact form backend
- [ ] Added Google Analytics
- [ ] Updated meta tags for SEO
- [ ] Tested on mobile devices
- [ ] Tested all navigation links
- [ ] Tested contact form
- [ ] Optimized images
- [ ] Spell-checked all content
- [ ] Added social media links
- [ ] Tested in multiple browsers

---

## 🎉 Launch & Beyond

Congratulations on your new website! 

**Post-Launch Tips:**
1. Submit to Google Search Console
2. Create social media accounts
3. Share launch announcement
4. Monitor Google Analytics
5. Update content regularly
6. Keep backup of files

**Need More?**
- Additional page templates
- Advanced features
- Custom development
- Email: custom@yoursite.com

---

**Template Version:** 1.0  
**Last Updated:** January 2025  
**Next Update:** Q2 2025

Thank you for choosing Apex Velocity Template! 🏁
