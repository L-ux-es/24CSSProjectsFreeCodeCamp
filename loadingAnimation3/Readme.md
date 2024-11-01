# Loading Animation 3

![Loading Animation 3](./LoadingAnimation3.gif)

## Requirements

- A portion of a colored circle spins around clockwise within a grey circle.
- Match styles, but feel free to chose your own colors.
- No JavaScript!

## Hints

- Use animation property and key frames.
- Remember that the border property is a shorthand to style all four side of a border at once - you can individually
  style each side of an element's border using properties like border-top, border-right,etc.

## Provided code

### HTML

```html
<div class="container">
    <div class="loader"></div>
</div>
```

### CSS

```css
html,
body {
    margin: 0;
}

:root {
    --spinner: #f3f3f3;
    --spinner-active: purple;
}
```