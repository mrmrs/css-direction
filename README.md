# css-direction

Functional CSS for direction

## Filesize

| File | Size |
|------|------|
| `dist/direction.css` | 385 bytes |
| `dist/direction.min.css` | 263 bytes (117 Gzipped) |

## Install

```sh
npm install css-direction
```

## Usage

### Import

```css
@import "css-direction";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-direction/dist/direction.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-direction/dist/direction.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.ltr` | `direction: ltr;` |
| `.rtl` | `direction: rtl;` |
| `.ltr-s` | `direction: ltr;` |
| `.rtl-s` | `direction: rtl;` |
| `.ltr-m` | `direction: ltr;` |
| `.rtl-m` | `direction: rtl;` |
| `.ltr-l` | `direction: ltr;` |
| `.rtl-l` | `direction: rtl;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.ltr-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/direction.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/direction.css` — formatted
- `dist/direction.min.css` — minified

## License

MIT
