# 👶 ICDS Finance Management System
### ફાઇનાન્સ મેનેજમેન્ટ સિસ્ટમ

> Integrated Child Development Services - Mobile-first Finance Tracking App  
> **Live App + Android Install (PWA) via GitHub Pages**

---

## 🚀 GitHub Pages પર Deploy કેવી રીતે કરવું

### Step 1 — GitHub Account બનાવો
1. [github.com](https://github.com) ખોલો
2. **Sign Up** કરો (free)
3. Email verify કરો

---

### Step 2 — New Repository બનાવો
1. GitHub માં login કરો
2. **"+"** button → **"New repository"** click કરો
3. Repository name: `icds-finance` (અથવા ગમે તે નામ)
4. **Public** select કરો ✅
5. **"Create repository"** click કરો

---

### Step 3 — Files Upload કરો
Repository page પર:
1. **"uploading an existing file"** link click કરો
2. નીચેની **બધી files & folders** drag-and-drop કરો:
   ```
   index.html
   manifest.json
   sw.js
   icons/  (folder સાથે)
   ```
3. **"Commit changes"** click કરો

---

### Step 4 — GitHub Pages Enable કરો
1. Repository → **Settings** tab
2. Left sidebar → **Pages**
3. **Source**: `Deploy from a branch`
4. **Branch**: `main` → folder: `/ (root)`
5. **Save** click કરો
6. 2-3 મિનિટ રાહ જુઓ...

---

### Step 5 — App Link મળશે!
```
https://YOUR-USERNAME.github.io/icds-finance/
```

🎉 **બસ! App live થઈ ગઈ!**

---

## 📱 Android પર Install કેવી રીતે કરવું

### Chrome Browser (Recommended):
1. ઉપરનો link Chrome માં ખોલો
2. **"App Install કરો"** banner આવશે → **Install** tap કરો
3. **OR** Chrome menu (⋮) → **"Add to Home screen"**
4. **"Install"** tap કરો
5. App home screen પર add થઈ જશે! ✅

### Samsung Internet:
1. Link ખોલો
2. Menu → **"Add page to"** → **"Home screen"**

---

## ✨ App Features

| Feature | વર્ણન |
|---------|--------|
| 🏠 Dashboard | Fund overview, filters |
| ➕ Entry | Grant/Expenditure entries |
| 📄 Reports | Filtered data with PDF export |
| 📈 Summary | Head-wise summary report |
| ⚙️ Settings | Head management |
| 🔑 Password | System password change |
| 💾 Backup | JSON backup & restore |
| 📶 Offline | Service Worker caching |

---

## 🔒 Security
- Default Password: **1975**
- Data: Browser `localStorage` (device-local)
- Password change: Settings → 🔑 Password

---

## 📂 File Structure
```
icds-finance/
├── index.html          # Main app
├── manifest.json       # PWA config
├── sw.js               # Service Worker (offline)
└── icons/
    ├── icon-72.png
    ├── icon-96.png
    ├── icon-128.png
    ├── icon-144.png
    ├── icon-152.png
    ├── icon-192.png
    ├── icon-384.png
    └── icon-512.png
```

---

## 🛠 Tech Stack
- Pure HTML + CSS + JavaScript
- PWA (Progressive Web App)
- localStorage for data
- html2pdf.js for PDF export
- No framework, no server needed

---

## 📞 Support
ICDS Finance Management System — Gujarat
