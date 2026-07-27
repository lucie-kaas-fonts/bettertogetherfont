# Using BetterTogether Fonts in Klaviyo

Your custom fonts are now hosted and ready to use! Here's how to integrate them into Klaviyo.

## 📍 Your Font URLs

Your fonts are hosted at these URLs:

```
https://lucie-kaas-fonts.github.io/bettertogetherfont/BetterTogether-Condenesed.woff2
https://lucie-kaas-fonts.github.io/bettertogetherfont/BetterTogether-Condenesed.woff
https://lucie-kaas-fonts.github.io/bettertogetherfont/BetterTogether-Caps.woff2
https://lucie-kaas-fonts.github.io/bettertogetherfont/BetterTogether-Caps.woff
```

## 🎨 Adding Fonts to Klaviyo Sign-up Forms

### **Step 1: Navigate to Fonts**
1. Go to Klaviyo
2. Click **Content** → **Images & brand** → **Fonts**
3. Click **"Import font"**

### **Step 2: Import Each Font**

**For BetterTogether-Condensed:**
- Source Address: `https://lucie-kaas-fonts.github.io/bettertogetherfont/BetterTogether-Condenesed.woff`
- Click **Import**

**For BetterTogether-Caps:**
- Source Address: `https://lucie-kaas-fonts.github.io/bettertogetherfont/BetterTogether-Caps.woff`
- Click **Import**

### **Step 3: Use in Your Forms**
Once imported, select the fonts from the font dropdown in your sign-up form designer.

## 📧 Using in Email Templates

Add this CSS to your Klaviyo email's custom CSS section:

```css
@font-face {
  font-family: 'BetterTogether-Condensed';
  src: url('https://lucie-kaas-fonts.github.io/bettertogetherfont/BetterTogether-Condenesed.woff2') format('woff2'),
       url('https://lucie-kaas-fonts.github.io/bettertogetherfont/BetterTogether-Condenesed.woff') format('woff');
  font-display: swap;
}

@font-face {
  font-family: 'BetterTogether-Caps';
  src: url('https://lucie-kaas-fonts.github.io/bettertogetherfont/BetterTogether-Caps.woff2') format('woff2'),
       url('https://lucie-kaas-fonts.github.io/bettertogetherfont/BetterTogether-Caps.woff') format('woff');
  font-display: swap;
}
```

Then use in your email HTML:
```html
<h1 style="font-family: 'BetterTogether-Condensed', sans-serif;">Your Heading</h1>
<p style="font-family: 'BetterTogether-Caps', sans-serif;">YOUR IMPACTFUL MESSAGE</p>
```

## ✅ Testing

1. Visit https://lucie-kaas-fonts.github.io/bettertogetherfont/ to see the fonts in action
2. The fonts are optimized for web use with fallback support
3. WOFF format is recommended for maximum email client compatibility

**Your fonts are live and ready to use!** 🎉
