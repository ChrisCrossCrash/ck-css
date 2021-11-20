# CK CSS

This stylesheet contains a few opinionated styles that I like to use in every one of my projects.

It should be used together with `modern-normalize.css`.

## Installation

`npm i modern-normalize @chris-cross-crash/ck-css`

Then import it where you import your other css files:

```javascript
import 'modern-normalize'
import '@chris-cross-crash/ck-css'
```

### `colors` CSS Custom Properties

You can also import a nice set of colors from this package:

```javascript
// Import the custom properties before your global styles.
import '@chris-cross-crash/ck-css/colors.css'
import '../styles/globals.css'
```

```css
/* globals.css */
/* You can now use the colors here */

.btn {
  background-color: var(--teal-800);
  color: var(--white);
}
```

The colors are from [Tailwind CSS v3.0.0-alpha.1 (MIT License)](https://github.com/tailwindlabs/tailwindcss/blob/v3.0.0-alpha.1/src/public/colors.js):

Here is the [Tailwind CSS color reference](https://tailwindcss.com/docs/customizing-colors#color-palette-reference) (it might differ slightly from this version).
