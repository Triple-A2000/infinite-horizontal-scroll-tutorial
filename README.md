# Scrolling Items Animation Project

This project demonstrates a smooth left-scrolling animation effect using HTML and CSS. The animation creates an infinite scrolling effect where items move from right to left seamlessly.

## Table of Contents
- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Code Explanation](#code-explanation)
- [Contributing](#contributing)
- [License](#license)

## Overview
The project consists of a simple HTML structure and a CSS file that manages the animation. It includes:
- A `wrapper` container to hold scrolling items
- `item` elements that move from right to left
- Keyframe animations that ensure infinite looping

## Technologies Used
- HTML5
- CSS3

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/infinite-horizontal-scroll-tutorial.git
   ```
2. Navigate to the project directory:
   ```bash
   cd infinite-horizontal-scroll-tutorial
   ```
3. Open `index.html` in your browser:
   ```bash
   open index.html   # macOS
   start index.html  # Windows
   ```

## Usage
Simply open the `index.html` file in a web browser. You will see an infinite scrolling animation with items moving from right to left.

## Customization
You can modify the animation speed, item colors, or add more elements:

- **Change animation duration:**
  Modify the `scrollLeft` animation inside `@keyframes` in `style.css`:
  ```css
  @keyframes scrollLeft {
      to {
          left: -150px; /* Adjust the distance */
      }
  }
  ```
- **Change background color:**
  Update the `body` background in `style.css`:
  ```css
  body {
      background-color: #1a1a2e;
  }
  ```
- **Add more items:**
  Copy and paste additional `.item` divs inside the `wrapper` container in `index.html`:
  ```html
  <div class="item item-9">Item 9</div>
  ```

## Code Explanation
### HTML Structure
```html
<div class="wrapper">
    <div class="item item-1">Item 1</div>
    <div class="item item-2">Item 2</div>
    <div class="item item-3">Item 3</div>
    <div class="item item-4">Item 4</div>
    <div class="item item-5">Item 5</div>
    <div class="item item-6">Item 6</div>
    <div class="item item-7">Item 7</div>
    <div class="item item-8">Item 8</div>
</div>
```

### CSS Animation
```css
@keyframes scrollLeft {
    to {
        left: -150px;
    }
}
```

## Contributing
Feel free to fork this project and submit pull requests with improvements.

## License
This project is open-source and available under the [BO License](LICENSE).
