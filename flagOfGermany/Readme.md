# Flag of Germany

![Flag  of Germany](./FlagOfGermany.png)

## Requirements

- Aspect ratio: 3:5.

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

    <div class="flag-germany">
        <div class="black stripe"></div>
        <div class="red stripe"></div>
        <div class="yellow stripe"></div>
      </div>

### CSS

    html,body{
     margin: 0;
     padding: 0;
    }
    
    :root{
     --black:#000000;
     --red:#DE0002;
     --yellow:#FFCE00;
     --flag-height:150px;
    }