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
<img width="1366" height="768" alt="VenSur Preview" src="https://github.com/user-attachments/assets/7c703803-173e-4816-a883-5fd32f5b8633" />




## 🎨 Themes
Choose a theme that complements your setup:

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/4ffd5506-02dd-4124-88ae-dd4ba36ea741" width="280" alt="Light Theme"/><br/>
      <a href="https://addons.mozilla.org/en-US/firefox/addon/safari-15-light-theme/">Light Theme</a>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/25012711-8168-46c5-8375-a34e80606c6b" width="280" alt="Dark Theme 1"/><br/>
      <a href="https://addons.mozilla.org/en-US/firefox/addon/safari-15-dark-theme/">Safari 15 Dark</a>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/9b4c862e-cf61-4133-ad16-7f4fdce651fa" width="280" alt="Dark Theme 2"/><br/>
      <a href="https://addons.mozilla.org/en-US/firefox/addon/dark-theme-for-vensur/">Safari Dark</a>
    </td>
  </tr>
</table>

---

## ⚙️ Required Setup (Before Installing)

These steps must be done **regardless of whether you use the manual method or SINE**. 

### 1. 🛠️ Set Up Your Toolbar
Arrange your Firefox toolbar to match this layout:  
<img width="1100" height="86" alt="image" src="https://github.com/user-attachments/assets/65ad8e2c-eb28-4dca-b4e1-4f59661164c2" />


### 2. 📥 Add the Essential Extension
- Install [Reload in Address Bar](https://addons.mozilla.org/en-US/firefox/addon/reload-in-address-bar/) to replicate Safari’s reload button.

### 3. ✒️ Install Safari Fonts
- Download and install **[SF Pro and SF Pro Text](https://drive.google.com/drive/folders/1q41TS2GVQtIJu9RoXP1K0q5v2Wh8HWD_?usp=sharing)** for authentic Safari typography.

### 4. 🖼️ Apply Safari Wallpapers
- Choose and download from the **[Safari Wallpapers](https://drive.google.com/drive/folders/1khKVrJVDQuxpzRS0kimsEPbmxv_RsFnE?usp=sharing)** collection to complete the look.
---

## 🚀 Install with *SINE* 

1. Complete the **Required Setup** above.  
2. Install the latest version of [Sine](https://github.com/CosmoCreeper/Sine/releases), following all prompted instructions.  
3. Restart Firefox.  
4. Open **Settings** and navigate to the **SINE** tab.  
5. Locate the **Local Installation** section (titled “Add your own locally from a GitHub repo”).  
6. Type in: **Venqul/VenSur**.  
7. Restart Firefox again.
8. Customize the settings to match your preferences.
9. 🎉 Enjoy your new setup!

---

## 🛠️ Manual Installation 

1. Follow the **Required Setup** above.
2. 🛠️ Configure Firefox (`about:config`)
Visit `about:config` and apply the following settings:

- `widget.gtk.rounded-bottom-corners.enabled` → `true` **(for linux only)**
- `toolkit.legacyUserProfileCustomizations.stylesheets` → `true`  
- `svg.context-properties.content.enabled` → `true`  
- `layout.css.color-mix.enabled` → `true`
- `sidebar.revamp`→ `true`
- `layout.css.backdrop-filter.force-enabled` → `true`   
- `layout.css.color-mix.color-spaces.enabled` → `true`
- `hide.single.tab` → `true` *(optional)*
- `extensions.menu.in.grid` → `true` *(optional)* 
3. Download the latest release of VenSur (updated less often) or click the green Code → Download ZIP button to get the most up-to-date source code.
4. Locate your profile folder by typing  `about:support`  into your urlbar and opening the “Profile Folder” <img width="1460" height="62" alt="image" src="https://github.com/user-attachments/assets/c592a144-29fc-4011-9ad9-efa260859b56" />
5. Copy the `configuration` and `chrome` folders into your Firefox profile directory. 
   *(You can locate it by visiting `about:support` and clicking the **Open Folder** button next to **Profile folder**)*
6. Restart Firefox and enjoy your new Safari-like experience!

---
## 💡 Optional: Restore Hidden Icons
VenSur removes the Extensions, Hamburger Menu, and Bookmark (Star) icons for a clean Safari-style interface. To restore them, remove these blocks from your `userChrome.css`:

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

