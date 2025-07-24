<h1>
  <p align="center">
  <strong style="font-size: 2em;">VenSur</strong>
  <img src="https://github.com/user-attachments/assets/40595330-c5e2-4ff5-a777-38c1aafaacbb" width="40" height="40" style="margin-left: 8px;">
</p>
</h1>


This is a refined and thoughtfully enhanced version of WhiteSur — built for seamless compatibility with [ATBC](https://github.com/easonwong-de/Adaptive-Tab-Bar-Colour). It includes amazing improvements, including a Safari-inspired homepage and intuitive buttons that feel just like Safari.  

For the best experience, pair it with one of my curated Firefox [color themes](#themes).  

This project builds on concepts from both [Neptune](https://github.com/yiiyahui/Neptune-Firefox) and the [Firefox Adaptive Sur Theme](https://github.com/easonwong-de/Firefox-Adaptive-Sur-Theme), offering a clean and modern take on the Firefox interface.

####  Click [here](#installation-steps) or scroll to bottom for installation steps

<p align="center"><img width="45%" src="https://github.com/user-attachments/assets/ba54b08b-e259-4de1-8561-83978ee4cf68"><img width="45%" src="https://github.com/user-attachments/assets/ac27d055-4959-4285-bf8a-599fcdabf2f5"></p>

### Themes
<p align="center"><img width="50%" src="https://github.com/user-attachments/assets/1e53d35a-57d6-4897-9527-cbfab1e539b8"></p>
<p align="center">
<a href="https://addons.mozilla.org/en-US/firefox/addon/safari-15-dark-theme/">DARK THEME 1</a>
</p>

<p align="center"><img width="50%" src="https://github.com/user-attachments/assets/ff72f684-3839-4e27-bef1-988ba713bc6b"></p>
<p align="center">
<a href="https://addons.mozilla.org/en-US/firefox/addon/dark-theme-for-whitesur/">DARK THEME 2</a>
</p>

<p align="center"><img width="50%" src="https://github.com/user-attachments/assets/f3ae6eea-64df-4e2e-a030-76957ae1ce52"></p>
<p align="center">
<a href="https://addons.mozilla.org/en-US/firefox/addon/safari-15-light-theme/">LIGHT THEME</a>
</p>

## Installation Steps
1. Set Browser Configurations

Go to `about:config`

-   Set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`
-   Set `svg.context-properties.content.enabled` to `true`
-   Set `layout.css.color-mix.enabled` to `true`
-   Set `layout.css.backdrop-filter.force-enabled` to `true` (optional)
-   Set `layout.css.color-mix.color-spaces.enabled` to `true` (optional)



2.	Edit your Firefox toolbar, to look like this
 <img width="940" height="79" alt="image" src="https://github.com/user-attachments/assets/45b7cc9e-a2bb-4b19-b5a2-f161341038a7" />


3.	Get this extension: https://addons.mozilla.org/en-US/firefox/addon/reload-in-address-bar/
4.	Download the SF pro fonts
5.	Then, copy the chrome and configuration folders into your User profile folder (you can get this folder by typing "about:support" into your addressbar)
6.	Enjoy!!


#### Disclaimer!!
The theme removes the Extension, Hamburger menu and Bookmark( Star ) icons to give it a Safari experience, To add them back  find and remove the following code in the User Chrome.css file
-	for the Extensions icon:
```
/* code to remove extensions icon */
#unified-extensions-button{
  width: 3px;
  padding-inline: 0 !important
}
#unified-extensions-button > .toolbarbutton-icon {
  width: 0 !important;
}
/* code to remove extensions icon */
```

-	for the Hamburger menu
```
/* code to remove hamburger menu */
#PanelUI-menu-button {

  display: none !important;

}
/* code to remove hamburger menu */

```
-	For the Bookmark icon
```
/* code to remove bookmark "star" icon form adressbar */
#star-button-box { display:none !important; }
/* code to remove bookmark "star" icon form adressbar */
```
