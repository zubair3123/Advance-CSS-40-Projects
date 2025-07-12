# Advance-CSS-40-Projects
Advance-CSS-40-Projects

# 💡 Advanced CSS Interview Questions (With Examples)

This README contains **100 advanced CSS interview questions** with simple explanations and code examples. It is perfect for frontend developers who want to prepare for interviews or improve their CSS skills.

---
## ✅ 1–30: Flexbox, Grid, Positioning, and Basics

### 1. What is Flexbox?
```css
display: flex;
```

### 2. How to center items in Flexbox?
```css
display: flex;
justify-content: center;
align-items: center;
```

### 3. What is `flex-direction`?
```css
flex-direction: row; /* or column */
```

### 4. What is CSS Grid?
```css
display: grid;
grid-template-columns: 1fr 1fr;
```

### 5. 3-column Grid Layout:
```css
grid-template-columns: repeat(3, 1fr);
```

### 6. What is `gap` in Grid?
```css
gap: 20px;
```

### 7. What is `z-index`?
```css
z-index: 10;
```

### 8. Absolute Positioning:
```css
position: absolute;
top: 0;
left: 0;
```

### 9. Sticky Position:
```css
position: sticky;
top: 0;
```

### 10. Difference between `absolute` and `relative`:
- `absolute`: out of normal flow
- `relative`: in flow, moves using `top`, `left`

### 11. Button Animation:
```css
button:hover {
  transform: scale(1.1);
  transition: transform 0.3s;
}
```

### 12. What is `@keyframes`?
```css
@keyframes slide {
  from { left: 0; }
  to { left: 100px; }
}
```

### 13. Transform Example:
```css
transform: scale(1.2);
```

### 14. What is `transition`?
```css
transition: all 0.3s ease;
```

### 15. Hover Pseudo-class:
```css
a:hover {
  color: red;
}
```

### 16. `nth-child()` selector:
```css
li:nth-child(2) {
  color: blue;
}
```

### 17. Make Circle with CSS:
```css
.circle {
  width: 100px;
  height: 100px;
  border-radius: 50%;
}
```

### 18. Box Shadow:
```css
box-shadow: 0 0 10px gray;
```

### 19. Overflow:
```css
overflow: hidden;
```

### 20. Media Query:
```css
@media (max-width: 768px) {
  body {
    background: yellow;
  }
}
```

### 21. `vw` and `vh` units:
- `vw`: 1% of screen width
- `vh`: 1% of screen height

### 22. Clamp for Responsive Font:
```css
font-size: clamp(1rem, 2vw, 2rem);
```

### 23. Object Fit:
```css
object-fit: cover;
```

### 24. Backdrop Filter:
```css
backdrop-filter: blur(10px);
```

### 25. Pseudo-elements:
```css
element::before {
  content: "★";
}
```

### 26. Pointer Events:
```css
pointer-events: none;
```

### 27. Responsive Font Size:
```css
font-size: clamp(14px, 2vw, 18px);
```

### 28. Calc Function:
```css
width: calc(100% - 50px);
```

### 29. Aspect Ratio:
```css
aspect-ratio: 16 / 9;
```

### 30. Hide Scrollbar:
```css
overflow: scroll;
scrollbar-width: none; /* Firefox */
::-webkit-scrollbar { display: none; } /* Chrome */
```

---

## ✅ 31–100: More Advanced CSS Concepts

### 31. `display: contents;` usage?
```css
display: contents; /* removes the element box but keeps its children */
```

### 32. How to create a gradient background?
```css
background: linear-gradient(to right, red, yellow);
```

### 33. How to blur an element using only CSS?
```css
filter: blur(5px);
```

### 34. What is `isolation: isolate` used for?
> Creates a new stacking context.

### 35. How to change scrollbar style?
```css
::-webkit-scrollbar {
  width: 10px;
  background: #ccc;
}
```

### 36. How to limit text to 1 line with ellipsis?
```css
white-space: nowrap;
overflow: hidden;
text-overflow: ellipsis;
```

### 37. What is `will-change`?
> Optimizes performance for animations.
```css
will-change: transform;
```

### 38. Difference between `em` and `rem`?
- `em`: relative to parent
- `rem`: relative to root (html)

### 39. CSS variable example:
```css
:root {
  --main-color: #3498db;
}
body {
  color: var(--main-color);
}
```

### 40. How to hide a checkbox but still use it?
```css
input[type="checkbox"] {
  display: none;
}
```

### 41. `:has()` selector usage?
```css
div:has(img) {
  border: 1px solid green;
}
```

### 42. How to style a disabled input?
```css
input:disabled {
  background-color: #eee;
}
```

### 43. What is `backface-visibility`?
> Hides the back of an element during 3D transforms.

### 44. What is `perspective` in 3D CSS?
```css
transform: perspective(1000px);
```

### 45. CSS-only dropdown menu?
> Use `:hover` with `display: block;`

### 46. What does `inherit` do?
> Inherits value from parent element.

### 47. What does `initial` do?
> Resets to browser default value.

### 48. CSS specificity order?
> Inline > ID > Class > Tag

### 49. How to select the last child?
```css
li:last-child {
  color: red;
}
```

### 50. What is `clip-path`?
```css
clip-path: circle(50%);
```

### 51. How to make a CSS-only toggle switch?

```css
input:checked + .toggle {
  background: green;
}
```

### 52. What is `scroll-behavior: smooth;`?

> Enables smooth scrolling for anchor links.

### 53. What is a logical property in CSS?

> Replaces physical properties for better i18n.

```css
margin-inline-start, padding-block-end
```

### 54. How to make an element unselectable?

```css
user-select: none;
```

### 55. How to create responsive square div?

```css
.square {
  width: 100%;
  aspect-ratio: 1 / 1;
}
```

### 56. What is `contain: layout;`?

> Isolates layout calculations for better performance.

### 57. How to create a masonry grid?

> Use `column-count` for simple masonry:

```css
.masonry {
  column-count: 3;
  column-gap: 1rem;
}
```

### 58. What is `filter` in CSS?

```css
filter: grayscale(100%) brightness(1.2);
```

### 59. What is a media feature?

> A condition like `max-width`, `orientation`, `hover`, etc.

### 60. How to add animation delay?

```css
animation-delay: 1s;
```

### 61. What is the default display of `<div>`?

> `block`

### 62. How to style file input?

> Hide original and style label:

```css
input[type="file"] {
  display: none;
}
```

### 63. How to animate transform on scroll?

> Use JS or intersection observer + CSS class.

### 64. How to create fullscreen modal?

```css
.modal {
  position: fixed;
  top: 0; left: 0;
  width: 100%; height: 100%;
}
```

### 65. How to fade an element in?

```css
opacity: 0;
transition: opacity 0.3s ease-in;
```

### 66. How to vertically align text in a div?

```css
line-height: equal to height;
```

### 67. What is `object-position`?

> Controls alignment of replaced content (like images).

### 68. What is `resize` in CSS?

```css
resize: both;
overflow: auto;
```

### 69. What is `all: unset;`?

> Removes all styles, including browser default.

### 70. How to force hardware acceleration?

```css
transform: translateZ(0);
```

### 71. How to pause a CSS animation?

```css
animation-play-state: paused;
```

### 72. What does `mix-blend-mode` do?

> Mixes element with background (like Photoshop layers).

### 73. What is `aspect-ratio: auto;`?

> Keeps intrinsic aspect ratio of replaced elements.

### 74. What is `image-rendering: pixelated;`?

> Used for crisp pixel art display.

### 75. What is a pseudo-element vs pseudo-class?

> `::before` is element, `:hover` is class.

### 76. What is `:not()` selector?

```css
div:not(.active) {
  opacity: 0.5;
}
```

### 77. How to target input placeholder?

```css
::placeholder {
  color: gray;
}
```

### 78. What is `scroll-snap-type`?

```css
scroll-snap-type: x mandatory;
```

### 79. CSS-only tooltip:

> Use `:hover` on parent and `position: absolute;` on tooltip.

### 80. How to apply dark mode with media query?

```css
@media (prefers-color-scheme: dark) {
  body {
    background: #000;
    color: #fff;
  }
}
```

### 81. How to apply style only if screen is landscape?

```css
@media (orientation: landscape) {
  ...
}
```

### 82. What is `accent-color` in CSS?

> Change checkbox, radio, range colors.

```css
accent-color: red;
```

### 83. How to use variable fallback in CSS?

```css
color: var(--primary, blue);
```

### 84. How to animate with steps?

```css
animation-timing-function: steps(5);
```

### 85. How to make an element full screen?

```css
width: 100vw;
height: 100vh;
```

### 86. What is `box-sizing: border-box;`?

> Includes padding and border in width/height.

### 87. What is `overscroll-behavior`?

> Controls scroll chaining between containers.

### 88. CSS-only accordions?

> Use `input:checked` + `label` toggle trick.

### 89. Difference: `inline`, `inline-block`, `block`?

- `inline`: no width/height
- `inline-block`: allows box sizing
- `block`: full width

### 90. How to create a glass effect?

```css
backdrop-filter: blur(10px);
background: rgba(255,255,255,0.2);
```

### 91. How to center div vertically in parent?

```css
display: flex;
align-items: center;
```

### 92. What is `text-shadow`?

```css
text-shadow: 1px 1px 2px #000;
```

### 93. What is a container query?

```css
@container (min-width: 500px) {
  .card { font-size: 1.2rem; }
}
```

### 94. What is the default position value?

> `static`

### 95. What is `writing-mode`?

```css
writing-mode: vertical-rl;
```

### 96. What is `hyphens: auto;`?

> Enables automatic word breaking for long words.

### 97. How to define fallback fonts?

```css
font-family: "Poppins", Arial, sans-serif;
```

### 98. How to center text in a div?

```css
text-align: center;
```

### 99. What is `line-clamp`?

```css
display: -webkit-box;
-webkit-line-clamp: 2;
-webkit-box-orient: vertical;
overflow: hidden;
```

### 100. How to prevent layout shift on image load?

```css
img {
  width: 300px;
  height: auto;
  aspect-ratio: 16 / 9;
}
```



