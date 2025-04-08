# Firefox CSS Setup 

*Structure:*
```css
/chrome
|_ userChrome.css
|_ userContent.css

user.js
```

## user.js
The `user.js` file is based on [Betterfox](https://github.com/yokoffing/Betterfox) with some suggested overrides; namely, canvas acceleration, reduced motion, and some *SmoothFox* settings I personally prefer.

## Sideberry
This setup is built around [Sideberry](https://addons.mozilla.org/en-US/firefox/addon/sidebery/). Make sure you have the extension enabled.

### Additional Sideberry CSS
```css
#root.root {--toolbar-bg: #2B2B2B;}
#root.root {--frame-bg: #2B2B2B;}
#root.root {--ctx-menu-bg: #2B2B2B;}
```

## Appearance
> [!IMPORTANT]  
> You must enable `toolkit.legacyUserProfileCustomizations.stylesheets` in `about:config` if you aren't using the `user.js` file for the chrome settings to be applied.

![Sideberry open.](https://i.postimg.cc/2jZDRp5B/image.png)  

![Sideberry closed.](https://i.postimg.cc/pTPFNQfm/image.png)
