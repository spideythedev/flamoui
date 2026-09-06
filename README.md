# FlamoUI

<img src="./flamoui.png" width="100%" height="50%"></img>

> Enterprise CSS Framework - Built for scale. Designed for power.

**120+ components · 200+ utilities · 10,000+ lines · Zero dependencies **

---

## Installation

### CDN

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/spideythedev/flamoui@main/dist/css/flamoui.css">
```

### Self-Hosted

Download `dist/css/flamoui.css` and link it:

```html
<link rel="stylesheet" href="path/to/flamoui.css">
```

---

## Quick Start

```html
<!DOCTYPE html>
<html lang="en" data-fl-theme="light">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My App</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/spideythedev/flamoui@main/dist/css/flamoui.css">
</head>
<body>
    <button class="fl-btn fl-btn-primary">Click Me</button>

    <div class="fl-card">
        <div class="fl-card-body">
            Hello FlamoUI
        </div>
    </div>
</body>
</html>
```

---

## Features

| Feature | Detail |
|----------|----------|
| Components | 120+ production-ready UI components |
| Utilities | 200+ utility classes |
| Themes | Light, Dark, System |
| Dependencies | Zero — Pure CSS |
| Responsive | Mobile-first |
| Accessible | WCAG AA |
| Print Ready | Built-in print styles |
| Variables | 400+ CSS custom properties |

---

## Components

### Layout
- Container
- Grid
- Flex
- Sidebar
- Dashboard Shell

### Navigation
- Navbar
- Sidebar
- Breadcrumb
- Pagination
- Tabs
- Steps

### Data
- Table
- DataTable
- Card
- Stat Card
- KPI Card
- List
- Badge
- Avatar
- Tag
- Chip

### Forms
- Input
- Textarea
- Select
- Checkbox
- Radio
- Toggle
- Range
- File Upload
- Dropzone

### Feedback
- Alert
- Toast
- Modal
- Drawer
- Sheet
- Banner
- Empty State

### Actions
- Button
- FAB
- Speed Dial
- Segmented Control

### Overlays
- Tooltip
- Popover
- Dropdown
- Menu
- Command Palette

### Dashboard
- Stats Grid
- Chart Container
- Activity Feed
- Gauge
- Heat Map

### Advanced
- Timeline
- Calendar
- Kanban
- Date Picker
- Signature Pad
- Rich Editor

---

## Themes

```html
<html data-fl-theme="light">
<html data-fl-theme="dark">
<html data-fl-theme="system">
```

---

## Customization

Override any of the 400+ CSS variables:

```css
:root {
    --fl-primary-500: #your-color;
    --fl-brand-gradient: linear-gradient(
        135deg,
        #your-color,
        #other-color
    );
    --fl-radius-lg: 16px;
}
```

---

## Browser Support

| Chrome | Firefox | Safari | Edge |
|---------|---------|---------|---------|
| 90+ | 88+ | 14+ | 90+ |

---

## License

MIT © FlamicsLLC

---

## Author

**spideythedev** for **FlamicsLLC**

- GitHub: spideythedev
- Website: flamics-llc.vercel.app