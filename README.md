# UiCraft Core

79 UI components. Pure CSS utility classes, design tokens, dark mode, vanilla JS bundle.

**→ [getuicraft.com](https://getuicraft.com)**

## Installation

### CDN

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/tarasenko-by/uicraft-core@latest/uicraft.min.css">
<script src="https://cdn.jsdelivr.net/gh/tarasenko-by/uicraft-core@latest/uicraft.min.js"></script>
```

### Download

[Download from getuicraft.com](https://getuicraft.com/docs/download)

### npm (coming soon)

```bash
npm install @uicraft/core
```

## Usage

```html
<!DOCTYPE html>
<html data-theme="default">
<head>
  <link rel="stylesheet" href="uicraft.min.css">
</head>
<body>
  <button class="uc-btn uc-btn-primary">Button</button>
  <script src="uicraft.min.js"></script>
</body>
</html>
```

### Dark Mode

Add the `.dark` class to `<html>`:

```js
document.documentElement.classList.toggle('dark');
```

### Themes

Set `data-theme` on `<html>`:

```html
<html data-theme="default">     <!-- Default -->
<html data-theme="rounded-sans"> <!-- Rounded Sans -->
<html data-theme="editorial">    <!-- Editorial -->
```

## Files

| File | Description |
|------|-------------|
| `uicraft.css` | Expanded CSS bundle |
| `uicraft.min.css` | Minified CSS bundle |
| `uicraft.js` | Expanded JS bundle |
| `uicraft.min.js` | Minified JS bundle |
| `theme-manifest.json` | Available themes |
| `themes/` | Theme JSON source files |

## License

MIT
