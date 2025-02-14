Here are the steps:

**Step 1: Install font-locale**

To use fonts hosted locally, you'll need a package called `font-locale`. You can install it by running the following command in your terminal or
command prompt:
```bash
npm install font-locale --save-dev
```
This step is necessary because `node` doesn't have access to local files by default.

**Step 2: Create a new CSS file**

Create a new file for your CSS, e.g., `styles.css`. This will be where you'll define your styles using the fonts you just installed.

**Step 3: Import font in your HTML file**

In your `index.html` or wherever your main script is located, add a comment like this:
```html
<!-- Comment to indicate that there's a font being used -->
<link href="path/to/your/font.css" rel="stylesheet">
```
Replace `"path/to/your/font.css"` with the actual path to your local CSS file.

For example:
```html
<!-- Importing font from local machine -->
<link href="/fonts/localFont.css" rel="stylesheet">
```
**Step 4: Define font styles**

Finally, you can define your fonts in your `styles.css` file using the following syntax:

```css
/* Importing font */

body {
  font-family: 'Your Font Name', sans-serif;
}
```

Replace `'Your Font Name'` with the actual name of your font. You can also specify additional properties like size, color, etc.

For example:
```css
/* Custom font styles */
body {
  font-family: 'Open Sans', sans-serif;
  font-size: 18px;
  color: #333;
}
```
That's it! Now you should see your custom fonts appear in the page.