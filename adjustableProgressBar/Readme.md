# Adjustable Progress Bar

Stage 1:
![Progress Bar Stage 1](AdjustableProgressBarStage1.png)

Stage 2:
![Progress Bar Stage 2](AdjustableProgressBarStage2.png)

Stage 3:
![Progress Bar Stage 3](AdjustableProgressBarStage3.png)

Stage 4:
![Progress Bar Stage 4](AdjustableProgressBarStage4.png)

## Requirements

Build a progress bar that you can change by swapping classes. Style a class for each of the progress bar's stages:

- Stage 1: 25% finished.
- Stage 2: 50% finished.
- Stage 3: 75% finished.
- Stage 4: 100% finished.

## Hint

It may help to think the progress bar as two elements, one on top of another: an outer progress bar and an inner progress bar. How can you use the width of the inner progress bar to create the effect of the outer progress bar filling?

## Provided code

### HTML

     <div class="container">
      <div class="progress-bar">
        <div class="prog-status stage-4"></div>
      </div>
    </div>

### CSS

    html,
    body {
        margin: 0;
        padding: 0;
    }

    :root {
        --stage-1: 25%;
        --stage-2: 50%;
        --stage-3: 75%;
        --stage-4: 100%;
        --progbar-bg: lightgray;
        --stage-1-bg: red;
        --stage-2-bg: orangered;
        --stage-3-bg: greenyellow;
        --stage-4-bg: green;
    }

