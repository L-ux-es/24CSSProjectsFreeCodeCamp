# Expanding Search Button

Expand a search button
## Example

![Search Button](/expandingSearchBar/SearchBar.png)

After expand:
![Search Button Expanded](/expandingSearchBar/SearchBarExpanded.png)

## Requirements

- Search input
  - Takes up 1/3 of the width of ts container.
- When the user clicks into the search bar:
  - Input grows to entire width of its parent container with smooth transition.
  - Shrinks back to original size when user clicks away.
  - Blue border.
  - **Bonus:** placeholder text is not visible when user clicks inside the search bar.
- Accessibility
  - For accessibility, form inputs should always have a label.Create a label with a valid **for** attribute.
  - Look up some CSS rules ( no need to write it yourself) that hide the search input's label visually but keeps it accesible to screen readers.

## Hints and Help

- use a transition to make sure the search bar expands smoothly.

## What to Research

- The **:focus** pseudo selector.
- A pseudo selector that lets you change placeholder styles.
