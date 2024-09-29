# Flag of Niger

![Flag of Niger](./FlagOfNiger.png)

## Requirements

- Aspect ratio: 6:7.
- Stripes have equal area.
- Circle 85% of the height of the stripe.

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

    <div class="flag flag-niger">
        <div class="stripe orange"></div>
        <div class="stripe white">
          <div class="circle"></div>
        </div>
        <div class="stripe green"></div>
      </div>

### CSS

    html,
    body {
      margin: 0;
      padding: 0;
      background: black;
    }

    :root {
      --orange: #E15307;  
      --white: #FFFFFF;
      --green: #10AF2A;
      --flag-height: 200px;
    }
