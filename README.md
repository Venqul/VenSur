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

<img width="1949" height="618" alt="Vensur image 1" src="https://github.com/user-attachments/assets/dd6b4e81-c6ed-4113-b257-6eefd5a3f812" />


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

### 1. 🧩 Customize your Toolbar
Modify your toolbar layout to look like this:  
<img width="940" height="79" alt="toolbar layout" src="https://github.com/user-attachments/assets/45b7cc9e-a2bb-4b19-b5a2-f161341038a7" />

### 2. 📦 Install Required Add-on
- [Reload in Address Bar](https://addons.mozilla.org/en-US/firefox/addon/reload-in-address-bar/)

### 3. 🔤 Install SF Pro Fonts
Download and install the **SF Pro** system font to match Safari typography.

---

## 🚀 Install with *SINE*

1. Complete the **Required Setup** above.  
2. Install the latest version of [Sine](https://github.com/CosmoCreeper/Sine/releases), following all prompted instructions.  
3. Restart Firefox.  
4. Open **Settings** and navigate to the **SINE** tab.  
5. Locate the **Local Installation** section (titled “Add your own locally from a GitHub repo”).  
6. Install **Venqul/VenSur**.  
7. Restart Firefox again.
8. Customize the settings to match your preferences.
9. 🎉 Enjoy your new setup!

---

## 🛠️ Manual Installation

1. Follow the **Required Setup** above.
2. 🛠️ Configure Firefox (`about:config`)
Visit `about:config` and apply the following settings:

- `toolkit.legacyUserProfileCustomizations.stylesheets` → `true`  
- `svg.context-properties.content.enabled` → `true`  
- `layout.css.color-mix.enabled` → `true`
- `sidebar.revamp`→ `true`
- `layout.css.backdrop-filter.force-enabled` → `true` *(optional)*  
- `layout.css.color-mix.color-spaces.enabled` → `true` *(optional)* 
3. Download the latest version of VenSur.
4. Copy the `chrome` and `configuration` folders into your Firefox profile directory.  
   *(You can locate it by visiting `about:support` and opening the “Profile Folder”)*  
5. Restart Firefox and enjoy your new Safari-like experience!

---

## ⚠️ Optional: Restore Hidden Icons
VenSur removes the Extensions, Hamburger Menu, and Bookmark (Star) icons for a clean Safari-style interface. To restore them, remove these blocks from your `userChrome.css`:

<details>
  <summary>Restore Extensions Icon</summary>

<pre><code>#unified-extensions-button { width: 3px; padding-inline: 0 !important; }
#unified-extensions-button > .toolbarbutton-icon { width: 0 !important; }</code></pre>

</details>

<details>
  <summary>Restore Hamburger Menu</summary>

<pre><code>#PanelUI-menu-button { display: none !important; }</code></pre>

</details>

<details>
  <summary>Restore Bookmark (Star) Icon</summary>

<pre><code>#star-button-box { display: none !important; }</code></pre>

</details>


## 🙌 Credits

This project is inspired by [WhiteSur](https://github.com/AdamXweb/WhiteSurFirefoxThemeMacOS), [Firefox Adaptive Sur Theme](https://github.com/easonwong-de/Firefox-Adaptive-Sur-Theme) and [Neptune](https://github.com/yiiyahui/Neptune-Firefox) , but reimagined with a modern, personal touch.

<p align="center"><em>Crafted with care by <strong>Venqul</strong> ✨</em></p>

