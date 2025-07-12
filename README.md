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

... (content for 1-50 remains unchanged) ...

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



