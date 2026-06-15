# Scientific Calculator

A modern, interactive scientific calculator built as a single static HTML file. No dependencies, no build step — open in a browser or deploy anywhere.

## Features

**Arithmetic**
- Addition, subtraction, multiplication, division
- Parentheses for grouping expressions
- Percentage operator
- Chained expressions with live expression display

**Scientific functions**
- Trigonometry: `sin`, `cos`, `tan` and their inverses (`sin⁻¹`, `cos⁻¹`, `tan⁻¹`)
- Logarithms: `log` (base 10) and `ln` (natural log)
- Square root (`√`), power (`xʸ`), square (`x²`)
- Absolute value (`|x|`)
- Factorial (`n!`) — supports integers up to 170

**Constants**
- π (pi)

**Memory**
- `MS` — store current value to memory
- `MR` — recall memory into expression
- `M+` / `M−` — add or subtract from memory
- `MC` — clear memory

**Modes**
- DEG / RAD toggle for trig functions
- INV toggle for inverse trig functions

**Keyboard support**

| Key | Action |
|-----|--------|
| `0–9` | Digit input |
| `.` | Decimal point |
| `+ - * /` | Operators |
| `( )` | Parentheses |
| `%` | Percentage |
| `Enter` or `=` | Calculate |
| `Backspace` | Delete last character |
| `Escape` | Clear all |

## Usage

Open `index.html` directly in any modern browser — no server required.

```bash
open index.html
```

## Deployment

### Vercel (recommended)

1. Push this repo to GitHub
2. Go to [vercel.com/new](https://vercel.com/new) and import the repository
3. Click **Deploy** — no build configuration needed

Vercel will auto-deploy on every push to `main`.

### GitHub Pages

1. Go to **Settings → Pages** in the repository
2. Set source to `main` branch, root folder
3. Save — the site will be live at `https://<username>.github.io/<repo-name>`

### Any static host

Upload `index.html` to any static hosting provider (Netlify, Cloudflare Pages, AWS S3, etc.).

## Tech stack

- Plain HTML, CSS, JavaScript — zero dependencies
- No build tools, no frameworks
- Single file (`index.html`)

## Browser support

Works in all modern browsers (Chrome, Firefox, Safari, Edge).
