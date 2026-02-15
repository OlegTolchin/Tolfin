# Tolfin

Modern CSS theme for Jellyfin media server with custom fonts, smooth animations and responsive design.

## Installation

### Method 1: Via CDN URL (Recommended)

1. Go to Jellyfin Dashboard → General → Custom CSS
2. Paste this code:
   ```css
   @import url("https://cdn.jsdelivr.net/gh/OlegTolchin/Tolfin@latest/theme/complete.css");
   ```
3. Click Save

### Method 2: Manual

1. Download `theme/complete.css` from this repository
2. Go to Jellyfin Dashboard → General → Custom CSS
3. Paste the contents of the file
4. Click Save

### Method 3: Custom Modules

You can also import individual modules with base.css:

```css
@import url("https://cdn.jsdelivr.net/gh/OlegTolchin/Tolfin@latest/theme/base.css");
@import url("https://cdn.jsdelivr.net/gh/OlegTolchin/Tolfin@latest/theme/modules/static-sidebar.css");
@import url("https://cdn.jsdelivr.net/gh/OlegTolchin/Tolfin@latest/theme/modules/change-logo.css");
/* Add more modules as needed */
```

Available modules:
- `static-sidebar.css` - Static sidebar on desktop
- `central-libraries-small.css` - Centered libraries on homepage
- `change-logo.css` - Custom logo/banner
- `count-indicators.css` - Custom count indicators
- `forgot-password.css` - Hide forgot password button
- `hide-my-media.css` - Hide "My Media" section
- `moving-cards.css` - Card hover animation
- `smaller-cast.css` - Smaller cast cards
- `floating-progress.css` - Floating progress bars

## Features

- 🎨 Modern design with improved aesthetics
- 🔤 Custom fonts for better readability
- ✨ Smooth animations and transitions
- 📱 Fully responsive layout
- 🎯 Optimized for desktop and mobile viewing

## Manifest

This theme includes a `manifest.json` for automatic installation via theme repositories and plugins.

## Repository

https://github.com/OlegTolchin/Tolfin

## Author

OlegTolchin

## License

MIT
