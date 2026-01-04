# Podfeed Logo Identity

This folder contains the complete Podfeed logo identity package.

## Brand Colors

| Color | Hex | Usage |
|-------|-----|-------|
| Primary Blue | `#1E51EE` | Gradient start, primary brand color |
| Light Blue | `#4A90D9` | Gradient end, secondary accent |
| Dark | `#1A1A1A` | Monochromatic dark version |
| White | `#FFFFFF` | Monochromatic light version |

## Logo Variants

### With Background

| File | Description | Best Used On |
|------|-------------|--------------|
| `podfeed-logo-primary.svg` | Primary logo with gradient background | Light backgrounds, general use |
| `podfeed-logo-on-dark.svg` | Primary logo with subtle border | Dark backgrounds |
| `podfeed-logo-mono-dark.svg` | Monochromatic with dark background | Light backgrounds, print |
| `podfeed-logo-mono-light.svg` | Monochromatic with light background | Dark backgrounds |

### Without Background (Transparent)

| File | Description | Best Used On |
|------|-------------|--------------|
| `podfeed-logo-no-bg-color.svg` | Gradient colored waves only | Any background with sufficient contrast |
| `podfeed-logo-no-bg-dark.svg` | Dark waves only | Light backgrounds |
| `podfeed-logo-no-bg-light.svg` | White waves only | Dark backgrounds |

### Favicon

| File | Description | Usage |
|------|-------------|-------|
| `podfeed-favicon.svg` | Optimized SVG for favicon | Browser tabs, bookmarks |

## Usage Guidelines

1. **Minimum Size**: The logo should not be displayed smaller than 24x24 pixels
2. **Clear Space**: Maintain clear space around the logo equal to 20% of its size
3. **Don't**: Stretch, rotate, change colors, or add effects to the logo
4. **Background Contrast**: Ensure sufficient contrast between the logo and its background

## Implementation

### Favicon (in HTML head)
```html
<link rel="icon" type="image/svg+xml" href="/logo/podfeed-favicon.svg">
<link rel="icon" type="image/x-icon" href="/favicon.ico">
```

### Vue/Vuetify Component
```vue
<v-img src="/logo/podfeed-logo-primary.svg" width="40" height="40" />
```
