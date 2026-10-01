# 🧭 YatraGuide – Tourist Guide & Booking Website

Ek simple tourist guide website jisme tourist places aur guides dhoondh kar booking kar sakte hain, aur admin sab kuch manage karta hai.

## Features
- **Tourist Login:** places/guides browse (search + city/category filter), booking, My Bookings (status ke saath)
- **Admin Login:** saari bookings dekhna (Confirm / Cancel), places aur guides add/delete, sample data load
- Responsive design + dark mode

## Project structure
```
yatraguide/
├── index.html   # poori website (HTML + CSS + JS ek hi file mein)
└── README.md
```

## GitHub par upload karne ke steps
1. github.com par naya repository banao (jaise `yatraguide`), **Public** rakho.
2. **Add file → Upload files** par jao, `index.html` aur `README.md` drag-drop karo, **Commit changes** dabao.
3. Repository ke **Settings → Pages** mein jao.
4. **Source:** `Deploy from a branch` → Branch: `main` / folder: `/ (root)` → **Save**.
5. 1–2 minute baad link milega: `https://<your-username>.github.io/yatraguide/`

## Login details (GitHub Pages / demo mode)
- **Tourist:** naam daalo, "Tourist Login" dabao
- **Admin:** password `admin123`, "Admin Login" dabao
- Admin ke baad pehli baar "Load sample places & guides" dabao.

## ⚠️ Data storage ke baare mein
GitHub Pages sirf static hosting hai (server/database nahi). Isliye yahan data **browser ke localStorage** mein save hota hai:
- Data usi browser/device mein rehta hai, doosre users ko nahi dikhta.
- Tourist ki booking admin ke device par nahi dikhegi.
- Admin password code mein likha hai, isliye ye sirf demo/portfolio ke liye hai.

Real multi-user data ke liye backend chahiye (Firebase / Supabase / Node + MySQL).
