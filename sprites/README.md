# Usage

## `icons.svg`

These can be used as icons embedded in the text.

At the moment two symbols are defined:

- `as-round` ‒ rectangular icon.
- `as-rect` ‒ round icon.

You can include them in a document like this (`d-none` class from Bootstrap)

```html
<span title="Round Awesome Spark Icon">
    <svg class="icon">
        <use xlink:href="icons.svg#as-round"></use>
    </svg>
</span>
```

where `icon` class can be define as shown below (see [How to work with SVG icons](https://fvsch.com/svg-icons)):

```css
.icon {
  fill: currentColor;
  width: 1em;
  height: 1em;
  vertical-align: middle;
  overflow: hidden;
}
```
