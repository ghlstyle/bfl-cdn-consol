# BFL CDN Console 🚀
This repository hosts static assets for **Brieflyne**. Large files (over 50MB) are served via GitHub Raw, and smaller assets can still use jsDelivr.

## 📂 Folder Structure
- `/assets/client-review/`: Client video testimonials and reviews.
- `/assets/images/`: Logos and UI elements.
- `/assets/js/` & `/assets/css/`: Development scripts and styles.

## 🔗 CDN & Direct Access Links

### 1. Large Files (>50MB) - GitHub Raw
Use this for high-quality videos or large assets:
`https://raw.githubusercontent.com/ghlstyle/bfl-cdn-consol/main/path/to/file`

**Example (Video):**
`https://raw.githubusercontent.com/ghlstyle/bfl-cdn-consol/main/assets/client-review/Brieflyne_Review_1_o7jw90.mp4`

### 2. Small Assets (<50MB) - jsDelivr
Use this for images, CSS, and JS (better caching):
`https://cdn.jsdelivr.net/gh/ghlstyle/bfl-cdn-consol/path/to/file`

---

## 🛠️ Usage in Code

### Video Implementation (HTML5)
```html
<video width="100%" controls preload="metadata">
  <source src="[https://raw.githubusercontent.com/ghlstyle/bfl-cdn-consol/main/assets/client-review/Brieflyne_Review_1_o7jw90.mp4](https://raw.githubusercontent.com/ghlstyle/bfl-cdn-consol/main/assets/client-review/Brieflyne_Review_1_o7jw90.mp4)" type="video/mp4">
  Your browser does not support the video tag.
</video>