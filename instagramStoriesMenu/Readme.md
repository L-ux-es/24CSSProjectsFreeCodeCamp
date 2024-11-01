# Instagram Stories Menu

![Instagram Stories Menu](./InstagramStoriesMenu.png)

*Note:The images of the profiles are different from the ones in the image shown.*

## Requirements

Instagram "stories" are slideshows of photos, memes, and text. Each element in the example represents a user who has
posted a story. The state of each story is communicated visually via the color of its border. Create 3 classes that can
be added to the .story element to visually indicate the state of each story.

- .new - add gradient border to show story has NOT yet been viewed.
- .viewed - adds gray border to show story has been viewed.
- .live - adds red notification badge, to show user is currently live streaming.

## Hints

- A gradient border effect can be accomplished using a wrapping div( note that the border-image property will not work
  properly whit border radius).
- How you add the "LIVE" badge if that text doesn't already exist in the DOM? Trying using a pseudo element and the
  content property.

## Provided code

### HTML

```html
<ul class="stories-menu">
    <li class="story new">
        <div class="img-wrapper">
            <img
                    src="./Images/deepin_1_stock_underwater.jpg"
                    alt="profile-pic"
                    class="img"
            />
        </div>
        <p>Julian</p>
    </li>
    <li class="story viewed live">
        <div class="img-wrapper">
            <img
                    src="./Images/jamie-haughton-unsplash.jpg"
                    alt="profile-pic"
                    class="img"
            />
        </div>
        <p>Scrimdella</p>
    </li>
    <li class="story new">
        <div class="img-wrapper">
            <img
                    src="./Images/Mammal-Seals-Smile-Funny.jpg"
                    alt="profile-pic"
                    class="img"
            />
        </div>
        <p>Gumdrop</p>
    </li>
</ul>
```

### CSS

```css
html,
body {
    margin: 0;
    padding: 0;
}

:root {
    --font: 'Karla', san-serif;
    --font-color: #fff;
    --grad1: #feda75;
    --grad2: #fa7e1e;
    --grad3: #d62979;
    --grad4: #962fbf;
    --grad5: #4f5bd5;
    --viewed: gray;
    --bg-main: #000;
    --bg-live: red;
}
```