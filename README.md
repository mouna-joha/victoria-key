# Victoria Key — Pocket Perfume Store
**v1.0 · First Release**

## GitHub Pages Setup Guide

### 📁 Folder Structure
```
or direct link or file 
victoria-key/
├── index.html          ← the website (1 file)
├── README.md           ← this guide
└── images/             ← PUT ALL YOUR PHOTOS HERE
    ├── group.jpg        ← hero + gallery big slot (all 5 together)
    ├── group2.jpg       ← 62+59+71 group photo
    ├── no68.jpg         ← No.68 purple
    ├── no62a.jpg        ← No.62 orange (first photo)
    ├── no62b.jpg        ← No.62 orange (second photo)
    ├── no40.jpg         ← No.40 pink
    ├── no59.jpg         ← No.59 blue
    ├── no71.jpg         ← No.71 red
    ├── lifestyle.jpg    ← any mood/lifestyle shot
    ├── detail1.jpg      ← extra (optional)
    └── detail2.jpg      ← extra (optional)
```

### ✏️ Before Publishing — Edit in index.html

Search for `const CFG = {` and edit:
```js
const CFG = {
  whatsapp : '310000000000',   // your number (no + or spaces)
  paypalMe : 'YourRealName',  // your PayPal.me username
  iban     : 'NL91 ABNA 0417 1643 00', // your IBAN
  email    : 'you@email.com',
};
```

Also edit prices if needed (search for `14.95`):
```js
sizes:{'48ml':14.95}  // change to your selling price in EUR
```

### 🚀 Publish on GitHub Pages (Free)

1. Go to https://github.com → Sign up or login
2. Click "New repository" → name it `victoria-key`
3. Upload all files (index.html + images/ folder)
4. Go to Settings → Pages → Source: main branch → Save
5. Your site: `https://yourusername.github.io/victoria-key`

### 💡 Tips
- Photos: minimum 800×800px, JPG format, under 1MB each
- Prices shown in EUR by default, auto-convert for 7 currencies
- Languages: EN, Arabic, NL, DE, FR — auto switches direction for Arabic
- Cart saves in browser (localStorage), no server needed
- WhatsApp button creates a ready-made order message automatically