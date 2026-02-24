# Font Awesome Pro CDN

Use the latest Font Awesome Pro Icons pack for free (for educational purposes and personal testing only)

## Author's Note

This small project was created for educational purposes only.

Use this repository for personal testing or previewing how icons appear in your projects. If you find Font Awesome useful and can afford it, please support the creators by purchasing a Font Awesome Pro license.
<https://fontawesome.com/plans>

## 🌐 Hosting & Usage

Latest release: **v7.2.0**

### 1️⃣ Local Usage

Clone or download the repository and include it in your project.

Icons can then be loaded using the local CSS path:

```html
<link rel="stylesheet" href="./font-awesome-pro/css/fontawesome.css" />
<link rel="stylesheet" href="./font-awesome-pro/css/allmain.css" />
```

### 2️⃣ Hosting on Vercel

You can deploy this repository on Vercel to use it as a CDN.

After deploying, include the CSS files in your HTML:

```html
<link
  rel="stylesheet"
  href="https://your-project-name.vercel.app/css/fontawesome.css"
/>
<link
  rel="stylesheet"
  href="https://your-project-name.vercel.app/css/allmain.css"
/>
```

Note:

- You can use `/css/all.css` in place of `/css/fontawesome.css`; if any issues occur, simply switch between the two.
- All style-specific and individual icon CSS files have been merged into a single file: `allmain.css`.
- Individual icon CSS files can still be used by accessing their direct file paths.

### 3️⃣ Official CDN Font Awesome v7.2.0 Pro

Simply add the following CSS links to the <head> section of your HTML file:

```html
<link
  rel="stylesheet"
  href="https://site-assets.fontawesome.com/releases/v7.2.0/css/all.css"
/>
<link
  rel="stylesheet"
  href="https://site-assets.fontawesome.com/releases/v7.2.0/css/sharp-solid.css"
/>
<link
  rel="stylesheet"
  href="https://site-assets.fontawesome.com/releases/v7.2.0/css/sharp-regular.css"
/>
<link
  rel="stylesheet"
  href="https://site-assets.fontawesome.com/releases/v7.2.0/css/sharp-light.css"
/>
<link
  rel="stylesheet"
  href="https://site-assets.fontawesome.com/releases/v7.2.0/css/duotone.css"
/>

<!-- Additional Font Awesome Pro+ Icons for v7.2.0 -->

<!-- Sharp Duotone -->
<link
  rel="stylesheet"
  href="https://site-assets.fontawesome.com/releases/v7.2.0/css/sharp-duotone-solid.css"
/>
<!-- Chisel -->
<link
  rel="stylesheet"
  href="https://site-assets.fontawesome.com/releases/v7.2.0/css/chisel-regular.css"
/>
<!-- Etch -->
<link
  rel="stylesheet"
  href="https://site-assets.fontawesome.com/releases/v7.2.0/css/etch-solid.css"
/>
<!-- Graphite -->
<link
  rel="stylesheet"
  href="https://site-assets.fontawesome.com/releases/v7.2.0/css/graphite-thin.css"
/>
<!-- Jelly -->
<link
  rel="stylesheet"
  href="https://site-assets.fontawesome.com/releases/v7.2.0/css/jelly-regular.css"
/>
<!-- Notdog -->
<link
  rel="stylesheet"
  href="https://site-assets.fontawesome.com/releases/v7.2.0/css/notdog-solid.css"
/>
<!-- Slab -->
<link
  rel="stylesheet"
  href="https://site-assets.fontawesome.com/releases/v7.2.0/css/slab-regular.css"
/>
<!-- Thumb Print -->
<link
  rel="stylesheet"
  href="https://site-assets.fontawesome.com/releases/v7.2.0/css/thumbprint-light.css"
/>
<!-- Utility -->
<link
  rel="stylesheet"
  href="https://site-assets.fontawesome.com/releases/v7.2.0/css/utility-semibold.css"
/>
<!-- Whiteboard -->
<link
  rel="stylesheet"
  href="https://site-assets.fontawesome.com/releases/v7.2.0/css/whiteboard-semibold.css"
/>
```

To obtain an individual icon's svg directly:

```
https://site-assets.fontawesome.com/releases/v7.2.0/svgs-full/{icon-family}-{style}/{icon-name}.svg
```

```
https://site-assets.fontawesome.com/releases/v7.2.0/svgs/{icon-family}-{style}/{icon-name}.svg
```

Note:

- List of available icon families and their styles: <https://docs.fontawesome.com/web/dig-deeper/styles>
- Replace `{icon-family}` with the `kebab-case` form of an icon family, in lowercase
  - Exception: Classic: `classic-` is omitted
    - e.g Classic, Solid, globe-stand: `https://site-assets.fontawesome.com/releases/v7.2.0/svgs-full/solid/globe-stand.svg`
- Replace `{style}` with a family's style, in lowercase
  - Exception: Duotone Solid: `-solid` is omitted
    - e.g Duotone, Solid, globe-stand: `https://site-assets.fontawesome.com/releases/v7.2.0/svgs-full/duotone/globe-stand.svg`
- Replace `{icon-name}` with the icon name found in FA's website
- Example: Sharp Duotone, Light, globe-stand: `https://site-assets.fontawesome.com/releases/v7.2.0/svgs/sharp-duotone-light/globe-stand.svg`
