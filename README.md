# CK CSS

This stylesheet contains a few opinionated styles that I like to use in every one of my projects.

It should be used together with `modern-normalize.css`.

## Installation

`npm i modern-normalize https://github.com/ChrisCrossCrash/ck-css.git#v1.0.0`

Then import it where you import your other css files:

```javascript
import 'modern-normalize.css'
import 'ck-css'
```

### `colors` CSS Custom Properties

You can also import a nice set of colors from this package:

```javascript
// Import the custom properties before your global styles.
import 'ck-css/colors.css'
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

## CC Zero License

<p xmlns:dct="http://purl.org/dc/terms/">
  <a rel="license"
     href="https://creativecommons.org/publicdomain/zero/1.0/">
    <img src="https://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <a rel="dct:publisher"
     href="https://github.com/ChrisCrossCrash/">
    <span property="dct:title">Christopher Kumm</span></a>
  has waived all copyright and related or neighboring rights to
  <span property="dct:title">CK-CSS</span>.
</p>
