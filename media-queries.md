# Media Quaries

In CSS media queries, `min-width` and `max-width` are used to apply styles based on the width of the viewport or the container. Here's the difference between them:

### `min-width: 600px`
- This sets a *minimum width threshold*.
- The styles inside the media query will be applied if the viewport width is **600 pixels or wider**.
- It is often used for **responsive design targeting larger screens** (e.g., tablets, desktops).
- Example usage:
  ```css
  @media (min-width: 600px) {
    body {
      background-color: lightblue;
    }
  }
  ```
  - The `body` will have a `lightblue` background color if the viewport is at least 600px wide.

### `max-width: 600px`
- This sets a *maximum width threshold*.
- The styles inside the media query will be applied if the viewport width is **600 pixels or narrower**.
- It is often used for **responsive design targeting smaller screens** (e.g., mobile devices).
- Example usage:
  ```css
  @media (max-width: 600px) {
    body {
      background-color: lightcoral;
    }
  }
  ```
  - The `body` will have a `lightcoral` background color if the viewport is 600px wide or less.

### Summary
- **`min-width: 600px`**: Styles apply to viewports **larger than or equal to** 600px.
- **`max-width: 600px`**: Styles apply to viewports **smaller than or equal to** 600px.

In practice, `min-width` is often used for **progressive enhancement** (i.e., adding styles as the screen gets larger), while `max-width` is used for **adaptive design** (i.e., modifying styles for smaller screens).