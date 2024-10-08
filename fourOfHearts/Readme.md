# Four of Hearts

![Four of Hearts](./FourOfHearts.png)

## Requirements

- Match layout as closely as you can.
- Card width should be 2/3 its height.
- Card can be fixed size (does not need to grow and shrink with browser).

## Provided code

### HTML

    <div class="container">
        <div class="card">
            <div class="left">
                <div>4</div>
                <div>&hearts;</div>
            </div>
            <div class="middle">
                <div>&hearts;</div>
                <div>&hearts;</div>
                <div>&hearts;</div>
                <div>&hearts;</div>
            </div>
            <div class="right">
                <div>4</div>
                <div>&hearts;</div>
            </div>
        </div>
    </div>

### CSS

    html,
    body {
      margin: 0;
      padding: 0;
    }

    :root {
      --card-height: 200px;
    }
