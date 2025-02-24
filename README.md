# Lineberry: A One-Line + Sideberry Firefox setup 
This setup **requires** the Sideberry extension. [Click to install](https://addons.mozilla.org/firefox/downloads/file/4246774/sidebery-5.2.0.xpi).

Some CSS is recommended for better colour coordination:
```css
#root.root {--toolbar-bg: #1c1b22;}
#root.root {--frame-bg: #1c1b22;}
#root.root {--ctx-menu-bg: #1c1b22;}
```
Add this to the Sideberry Styles Editor section: `Sideberry Settings` > `Styles Editor`.

Also go to `about:addons` > `Sideberry` > `Run in Private Windows` and select `Allow`.

The `userChome.css` file is based on [One-line Firefox](https://github.com/khuedoan/one-line-firefox) with heavy modifications and improvements and a disappearing bar option (disabled by default + has a very minor issue when in fullscreen).  
The `user.js` file is based on [Betterfox](https://github.com/yokoffing/Betterfox) with SmoothFox Sharpen Scrolling, GPU accelerated canvas, and a reduced motion user preference.  
The `userContent.css` file just removes some stuff from the new tab page.

Enjoy.

---
### *Credits*
[One-line Firefox](https://github.com/khuedoan/one-line-firefox)  
[Sideberry](https://github.com/mbnuqw/sidebery)  
[Betterfox](https://github.com/yokoffing/Betterfox)
