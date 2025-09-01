# 🌿 Stachio — Official Website

> The official landing page for **Stachio**, your trusted Discord safety & moderation bot.  
> Built with **HTML**, **TailwindCSS**, and **GSAP** for a clean, modern, and interactive experience.

![License](https://img.shields.io/badge/license-MIT-aac49b.svg)
![HTML](https://img.shields.io/badge/HTML-5-aac49b.svg)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3-aac49b.svg)
![GSAP](https://img.shields.io/badge/GSAP-3-aac49b.svg)

![Stachio Preview](https://stachio.dk)

---

## ✨ Features

- 🎨 Dual-tone theme powered by **#aac49b** + complementary accent  
- 📱 Fully responsive for desktop & mobile  
- ⚡ Smooth animations with GSAP  
- 🛡️ Safety-focused command categories  
- 🌙 Dark mode with glass blur effects  
- 🔄 Animated loading transitions  
- 📊 Live GitHub stats integration  
- 💫 Modern & minimal design  

---

## 🚀 Quick Start

```bash
# Clone repository
git clone github.com/MilkshakeCollective/stachio-website

# Navigate to directory
cd stachio-website

# Open in browser
open index.html
````

---

## ⚙️ Customization

### 1. Bot Info

Update metadata in `index.html`:

```html
<title>Stachio</title>
<meta name="description" content="Stachio — the ultimate Discord safety and moderation bot.">
```

### 2. Assets

Replace images in the `/images/` folder:

```
/images/
├── logo.png     # Stachio logo
└── user.png     # Testimonial avatars
```

### 3. Theme Colors

Modify gradients in `styles.css`:

```css
.gradient-bg {
  background: linear-gradient(-45deg, #aac49b, #344e41);
}
```

---

## 📝 Command Structure

Commands are configured in `script.js`:

```javascript
const commandsData = {
  safety: {
    icon: "🛡️",
    title: "Safety & Moderation",
    commands: [
      {
        name: "/ban",
        description: "Ban a disruptive user",
        permission: "ADMINISTRATOR"
      },
      {
        name: "/warn",
        description: "Issue a warning to a member",
        permission: "MODERATOR"
      }
    ]
  }
};
```

---

## 🌍 Links

* [Invite Stachio](https://discord.com/oauth2/authorize?client_id=1374870746006032414)
* [Support Server](https://discord.gg/wSAkewmzAM)
* [GitHub Repository](https://github.com/MilkshakeCollective/stachio-website)

---

[![Star Repo](https://img.shields.io/github/stars/MilkshakeCollective/stachio-website?style=social)](https://github.com/MilkshakeCollective/stachio-website)

> 💚 Built with care by the **Milkshake Collective** · Protecting communities with Stachio