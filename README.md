<h1 align="center">
  <strong style="font-size: 2em;">VenSur</strong>
  <img src="https://github.com/user-attachments/assets/40595330-c5e2-4ff5-a777-38c1aafaacbb" width="40" height="40">
</h1>
<p align="center"><em>A modern, Safari-inspired transformation of Firefox — elegant, minimalist, and performance-aware.</em></p>

## 🌟 Overview
**VenSur** is a meticulously enhanced reinterpretation of the WhiteSur theme, built for **seamless compatibility with [ATBC](https://github.com/easonwong-de/Adaptive-Tab-Bar-Colour)**. It blends the visual elegance of Safari with the power and flexibility of Firefox.

### ✨ Highlights:
- 🧭 Safari‑style homepage and toolbar  
- 🖱️ Minimal, intuitive button layout  
- 🎨 Curated color themes  
- ⚙️ Lightweight and deeply customizable  

*For the best results, pair with one of the recommended [color themes](#-themes).*

<p align="center">
  <img width="45%" src="https://github.com/user-attachments/assets/ba54b08b-e259-4de1-8561-83978ee4cf68">
  <img width="45%" src="https://github.com/user-attachments/assets/ac27d055-4959-4285-bf8a-599fcdabf2f5">
</p>

## 🎨 Themes
Choose a theme that complements your setup:

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/4ffd5506-02dd-4124-88ae-dd4ba36ea741" width="280" alt="Light Theme"/><br/>
      <a href="https://addons.mozilla.org/en-US/firefox/addon/safari-15-light-theme/">LIGHT THEME</a>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/25012711-8168-46c5-8375-a34e80606c6b" width="280" alt="Dark Theme 1"/><br/>
      <a href="https://addons.mozilla.org/en-US/firefox/addon/safari-15-dark-theme/">DARK THEME 1</a>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/9b4c862e-cf61-4133-ad16-7f4fdce651fa" width="280" alt="Dark Theme 2"/><br/>
      <a href="https://addons.mozilla.org/en-US/firefox/addon/dark-theme-for-whitesur/">DARK THEME 2</a>
    </td>
  </tr>
</table>

---

## ⚙️ Required Setup (Before Installing)

These steps must be done **regardless of whether you use the manual method or SINE**.

### 1. 🛠️ Configure Firefox (`about:config`)
Visit `about:config` and apply the following settings:

- `toolkit.legacyUserProfileCustomizations.stylesheets` → `true`  
- `svg.context-properties.content.enabled` → `true`  
- `layout.css.color-mix.enabled` → `true`  
- `layout.css.backdrop-filter.force-enabled` → `true` *(optional)*  
- `layout.css.color-mix.color-spaces.enabled` → `true` *(optional)*  

### 2. 🧩 Customize your Toolbar
Modify your toolbar layout to look like this:  
<img width="940" height="79" alt="toolbar layout" src="https://github.com/user-attachments/assets/45b7cc9e-a2bb-4b19-b5a2-f161341038a7" />

### 3. 📦 Install Required Add-on
- [Reload in Address Bar](https://addons.mozilla.org/en-US/firefox/addon/reload-in-address-bar/)

### 4. 🔤 Install SF Pro Fonts
Download and install the **SF Pro** system font to match Safari typography.

---

## 🛠️ Manual Installation

1. Follow the **Required Setup** above.
2. Download the latest version of VenSur.
3. Copy the `chrome` and `configuration` folders into your Firefox profile directory.  
   *(You can locate it by visiting `about:support` and opening the “Profile Folder”)*  
4. Restart Firefox and enjoy your new Safari-like experience!

---

## 🚀 Install with SINE *(Coming Soon)*

A streamlined one-click installer is in the works!

> **Note**: Even when using SINE, you'll still need to complete the [Required Setup](#️required-setup-before-installing).

---
## ⚠️ Optional: Restore Hidden Icons
VenSur removes the Extensions, Hamburger Menu, and Bookmark (Star) icons for a clean Safari-style interface. To restore them, remove these blocks from your `userChrome.css`:

<details>
  <summary>Restore Extensions Icon</summary>
```css
#unified-extensions-button { width: 3px; padding-inline: 0 !important; }
#unified-extensions-button > .toolbarbutton-icon { width: 0 !important; }
````

</details>
<details>
  <summary>Restore Hamburger Menu</summary>
```css
#PanelUI-menu-button { display: none !important; }
```
</details>
<details>
  <summary>Restore Bookmark (Star) Icon</summary>
```css
#star-button-box { display: none !important; }
```
</details>

## 🙌 Credits

This project is inspired by [Neptune](https://github.com/yiiyahui/Neptune-Firefox) and the [Firefox Adaptive Sur Theme](https://github.com/easonwong-de/Firefox-Adaptive-Sur-Theme), but reimagined with a modern, personal touch.

<p align="center"><em>Crafted with care by <strong>Venqul</strong> ✨</em></p>

