# NullDev Privacy Policies

This repository contains privacy policies for all NullDev apps.

## 🌐 Live Site

Visit: https://hellonulldev.github.io/Policy/

## 📱 Apps

### Indecisive (결정장애 / 優柔不断)
Decision-making helper app

- 🇰🇷 [한국어](https://hellonulldev.github.io/Policy/Indecisive/privacy-policy-ko.html)
- 🇺🇸 [English](https://hellonulldev.github.io/Policy/Indecisive/privacy-policy-en.html)
- 🇯🇵 [日本語](https://hellonulldev.github.io/Policy/Indecisive/privacy-policy-ja.html)

### Three Habits (3개의 습관 / 3つの習慣)
Minimal habit tracker focusing on just 3 habits

- 🇰🇷 [한국어](https://hellonulldev.github.io/Policy/HabitThree/privacy-policy-ko.html)
- 🇺🇸 [English](https://hellonulldev.github.io/Policy/HabitThree/privacy-policy-en.html)
- 🇯🇵 [日本語](https://hellonulldev.github.io/Policy/HabitThree/privacy-policy-ja.html)

## 🌍 Multi-language Support

The main index page now supports three languages:
- 🇺🇸 English
- 🇰🇷 한국어 (Korean)
- 🇯🇵 日本語 (Japanese)

Language preference is automatically detected from browser settings and saved in localStorage.

## 📂 Repository Structure

```
Policy/
├── README.md                      # This file
├── index.html                     # Main page (app list) with multi-language support
├── Indecisive/
│   ├── index.html                 # Language selector
│   ├── privacy-policy-ko.html     # Korean
│   ├── privacy-policy-en.html     # English
│   └── privacy-policy-ja.html     # Japanese
└── HabitThree/
    ├── index.html                 # Language selector
    ├── privacy-policy-ko.html     # Korean
    ├── privacy-policy-en.html     # English
    └── privacy-policy-ja.html     # Japanese
```

## 🔄 How to Update

1. Edit HTML files
2. Commit and push to `main` branch
3. Changes will be live in 1-2 minutes

## 📝 Adding New App Privacy Policy

When adding a new app:

1. Create a new folder with the app name (e.g., `NewApp/`)
2. Create privacy policy files for each language:
   - `privacy-policy-ko.html`
   - `privacy-policy-en.html`
   - `privacy-policy-ja.html`
3. Create an `index.html` for language selection
4. Add the app card to the main `index.html`:

```html
<a href="NewApp/" class="app-card">
    <div class="app-icon">🎯</div>
    <div class="app-name" data-i18n="newapp-name">App Name</div>
    <div class="app-description">
        <span data-i18n="newapp-local">한국어 / 日本語</span><br>
        <span data-i18n="newapp-desc">App description</span>
    </div>
    <div class="app-languages">
        <span class="language-tag">🇰🇷 한국어</span>
        <span class="language-tag">🇺🇸 English</span>
        <span class="language-tag">🇯🇵 日本語</span>
    </div>
</a>
```

5. Add translations to the JavaScript `translations` object

## 📧 Contact

**Developer:** NullDev  
**Email:** hello.nulldev@gmail.com

## 📄 License

All privacy policies are provided as-is for transparency purposes.

---

© 2026 NullDev. All rights reserved.
