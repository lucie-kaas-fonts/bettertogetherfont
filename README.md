# Better Together Font - Hosted Web Fonts

Custom web fonts optimized for Klaviyo email templates and sign-up forms.

## 📁 Repository Structure

```
bettertogetherfont/
├── fonts/                 # Web font files (WOFF2, WOFF)
├── css/
│   └── fonts.css         # @font-face declarations
├── README.md             # This file
└── index.html            # Demo page (optional)
```

## 🚀 Quick Start

### 1. Convert Your Fonts

If you have TTF files, convert them to web formats:
- Visit [Transfonter.org](https://transfonter.org/) or [Font Squirrel](https://www.fontsquirrel.com/tools/webfont-generator)
- Upload your `.ttf` file
- Download **WOFF2** and **WOFF** versions
- Place converted files in the `fonts/` folder

### 2. Font Files Location

All font files should be placed in:
```
fonts/
├── your-font-name.woff2
└── your-font-name.woff
```

### 3. CSS Configuration

The `css/fonts.css` file contains `@font-face` declarations that reference your fonts.

### 4. Host with GitHub Pages

This repository is automatically hosted via GitHub Pages:

**Your fonts are accessible at:**
```
https://lucie-kaas-fonts.github.io/bettertogetherfont/fonts/your-font-name.woff2
https://lucie-kaas-fonts.github.io/bettertogetherfont/fonts/your-font-name.woff
```

### 5. Use in Klaviyo

Add the following CSS in your Klaviyo email or form:

```css
@font-face {
  font-family: 'YourFontName';
  src: url('https://lucie-kaas-fonts.github.io/bettertogetherfont/fonts/your-font-name.woff2') format('woff2'),
       url('https://lucie-kaas-fonts.github.io/bettertogetherfont/fonts/your-font-name.woff') format('woff');
  font-weight: normal;
  font-style: normal;
  font-display: swap;
}

body { font-family: 'YourFontName', sans-serif; }
```

## 📋 Steps to Set Up

1. **Convert your TTF font** to WOFF2 and WOFF formats
2. **Add font files** to the `fonts/` folder
3. **Update `css/fonts.css`** with your font-face declarations
4. **Enable GitHub Pages** (Settings → Pages → Source: main branch)
5. **Copy the hosted font URL** to use in Klaviyo

## 🔗 Resources

- [Transfonter Font Converter](https://transfonter.org/)
- [Font Squirrel Webfont Generator](https://www.fontsquirrel.com/tools/webfont-generator)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Klaviyo Custom Email Design Guide](https://help.klaviyo.com/)

## 📝 Font License

⚠️ **Important:** Ensure you have the proper license to host and distribute your fonts. Only use fonts you own or have permission to use.

---

**Setup complete!** Add your converted font files and update the CSS to get started.
