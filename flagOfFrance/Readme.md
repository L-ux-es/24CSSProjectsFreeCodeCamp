# Flag of France

![Flag of France](./FlagOfFrance.png)

## Requirements

- Aspect ratio: 2:3.
- Stripes are equal width.

### Calculate Aspect ratio

Aspect ratio = *height* * *ratioHeight* / *ratioWidth*

#### Example

Flag ratio: **5:4**

Flag height: **200px**

    .country-flag{
     width:calc(200px*4/5);
    }

## Provided code

### HTML

```html
<div class="flag-france">
    <div class="blue stripe"></div>
    <div class="white stripe"></div>
    <div class="red stripe"></div>
</div>
```

### CSS

```css 
    :root {
    --red: #ED2938;
    --white: #FFF;
    --blue: #002495;
    --flag-height: 150px;
}
```