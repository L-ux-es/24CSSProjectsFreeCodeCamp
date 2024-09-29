# Flag of Japan

![Flag of Japan](./FlagOfJapan.png)

## Requirements

- Aspect ratio: 2:3.
- Circle is 3/5 the size of the flag.

### Calculate Aspect ratio

Aspect ratio = *height* * *ratioHeight* / *ratioWidth*

#### Example

Flag ratio: **5:4**

Flag height: **200px**

    .country-flag{
     width:calc(200px*4/5);
    }

## Provided code

### CSS

    html,
    body {
      margin: 0;
      padding: 0;
      background: black;
    }

    :root {
      --white: #FFFFFF;
      --red: #BC022C;
      --flag-height: 200px;
    }
