# Colors

```js script
import { html } from 'lit';
import '@divriots/dockit-core/css-showcases/dockit-css-showcases.define.js';
import './styles.css';
import '~/tokens/variables.css';
```

## Core

### Primary colors

Primary colors of our brand.

```js story
export const primary = () => html`
  <dockit-css-showcases
    css-props-prefix="--dds-core-color-primary"
    component-class="box"
    style-key="background-color"
  ></dockit-css-showcases>
`;
```

### Secondary colors

Primary colors of our brand.

```js story
export const secondary = () => html`
  <dockit-css-showcases
    css-props-prefix="--dds-core-color-secondary"
    component-class="box"
    style-key="background-color"
  ></dockit-css-showcases>
`;
```

### Secondary colors

Neutral colors of our brand.

```js story
export const neutral = () => html`
  <dockit-css-showcases
    css-props-prefix="--dds-core-color-neutral"
    component-class="box"
    style-key="background-color"
  ></dockit-css-showcases>
`;
```
