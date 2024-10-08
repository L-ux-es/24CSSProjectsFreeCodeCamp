# Ace of Spades

![Ace of Spades](./AceOfSpades.png)

## Requirements

- Match layout as closely as you can.
- Card width should be 2/3 its height.
- Card can be fixed size (does not need to grow and shrink with browser).

## Provided code

### HTML

    <div class="container">
      <div class="card">
        <div class="top">
          <div>A</div>
          <div>&spades;</div>
        </div>
        <div class="center">&spades;</div>
        <div class="bottom">
          <div>A</div>
          <div>&spades;</div>
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
