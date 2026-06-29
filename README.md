# Zero Style

Reset most of all styles to Zero.

## Features

- 0px `border`, `margin`, `padding`
- Unaffected font
- Nonunderlined link.
- No appearances of form part
- Width of `<img>` limited to 100%
- And other trivial functions

## Installation

### npm or other PM for Node
```shell
npm i zero-ztyle
# OR
[pnpm|yarn|deno|bun] add zero-style
```

## Usage

### Webpack with css-loader, Vite
```javascript
import 'zero-style'
```

### CDN
```html
<!-- Before other styles -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/zero-style"> 
<!-- OR -->
<link rel="stylesheet" href="https://unpkg.com/zero-style"> 
```
