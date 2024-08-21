# Icon Collection

This repository contains a collection of SVG icons organized into different categories (e.g., `social`, `coding`, etc.). You can easily use these icons in your own projects by following the steps below.

## How to Use the Icons

### 1. Find the Icon
- Browse through the folders (`social`, `coding`, etc.) to find the icon that fits your needs.

### 2. Copy the Image Address
- Once you've found the desired icon, right-click on the SVG file.
- Select **"Copy image address"** from the context menu.

### 3. Embed the Icon in Your Project
- You can embed the icon in your HTML or any other code by using the `<img>` tag or as a background image in CSS.

#### Example Using `<img>` Tag:
```html
<img src="YOUR_COPIED_IMAGE_ADDRESS" alt="icon description">
```

Example Using as a CSS Background:
```html
.icon {
  background-image: url('YOUR_COPIED_IMAGE_ADDRESS');
  width: 50px; /* Adjust as needed */
  height: 50px; /* Adjust as needed */
}
```

### 4. Customize the Icon (Optional)
- Since these are SVG files, you can customize their appearance by directly editing the SVG code or applying CSS styles.
  
#### Example of Direct SVG Usage:
```html
<svg width="50" height="50" fill="currentColor">
  <use xlink:href="YOUR_COPIED_IMAGE_ADDRESS"></use>
</svg>
```
