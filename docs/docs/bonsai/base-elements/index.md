---
title: "Base Elements"
description: "A complete CSS solution allowing you to build beautifully crafted web interfaces with ease."
layout: default

eleventyNavigation:
  key: BaseElements
  title: Base Elements
  parent: BonsaiCSS
  has_children: true
  order: 40
---

## Buttons

#### Base styling for button elements including button groups and variations

### Buttons

{% codepen "https://unpkg.com/bonsai.css@latest/dist/bonsai.min.css", "", "Heyyy", "Waz uuuuuuuup", "Test it" %}

```html
<button>Button</button>
<button aria-label="add">
  <svg
    aria-hidden="true"
    role="img"
    xmlns="https://www.w3.org/2000/svg"
    viewBox="0 0 448 512"
  >
    <path
      fill="currentColor"
      d="M416 208H272V64c0-17.67-14.33-32-32-32h-32c-17.67 0-32 14.33-32 32v144H32c-17.67 0-32 14.33-32 32v32c0 17.67 14.33 32 32 32h144v144c0 17.67 14.33 32 32 32h32c17.67 0 32-14.33 32-32V304h144c17.67 0 32-14.33 32-32v-32c0-17.67-14.33-32-32-32z"
    ></path>
  </svg>
  Button
</button>
<button disabled="">Button Disabled</button>
```

{% endcodepen %}

### Button Color Variations

{% codepen "https://unpkg.com/bonsai.css@latest/dist/bonsai.min.css", "", "Heyyy", "Waz uuuuuuuup", "Test it" %}

```html
<button class="green">Green</button>
<button class="orange">Orange</button>
<button class="red">Red</button>
<button class="white">White</button>
<button class="grey">Grey</button>
<button class="black">Black</button>
```

{% endcodepen %}

### Button Groups (Horizontal)

{% codepen "https://unpkg.com/bonsai.css@latest/dist/bonsai.min.css", "", "Heyyy", "Waz uuuuuuuup", "Test it" %}

```html
<div class="group">
  <button>Button</button>
  <button>Button</button>
  <button>Button</button>
</div>
```

{% endcodepen %}

{% codepen "https://unpkg.com/bonsai.css@latest/dist/bonsai.min.css", "", "Heyyy", "Waz uuuuuuuup", "Test it" %}

```html
<div class="group">
  <input type="text" placeholder="John" aria-label="Name" />
  <button>Button</button>
  <button>Button</button>
</div>
```

{% endcodepen %}

{% codepen "https://unpkg.com/bonsai.css@latest/dist/bonsai.min.css", "", "Heyyy", "Waz uuuuuuuup", "Test it" %}

```html
<div class="group">
  <button aria-label="upload">
    <svg viewBox="0 0 24 24" xmlns="https://www.w3.org/2000/svg">
      <path d="M13 7H7V5H13V7Z" fill="currentColor" />
      <path d="M13 11H7V9H13V11Z" fill="currentColor" />
      <path d="M7 15H13V13H7V15Z" fill="currentColor" />
      <path
        fill-rule="evenodd"
        clip-rule="evenodd"
        d="M3 19V1H17V5H21V23H7V19H3ZM15 17V3H5V17H15ZM17 7V19H9V21H19V7H17Z"
        fill="currentColor"
      />
    </svg>
  </button>
  <input type="text" placeholder="filename.txt" aria-label="Filename" />
</div>
```

{% endcodepen %}

### Button Groups (Vertical)

{% codepen "https://unpkg.com/bonsai.css@latest/dist/bonsai.min.css", "", "Heyyy", "Waz uuuuuuuup", "Test it" %}

```html
<div class="group vertical">
  <button>Button</button>
  <button>Button</button>
  <button>Button</button>
  <button>Button</button>
</div>
```

{% endcodepen %}

{% codepen "https://unpkg.com/bonsai.css@latest/dist/bonsai.min.css", "", "Heyyy", "Waz uuuuuuuup", "Test it" %}

```html
<div class="group vertical">
  <button class="white">Button</button>
  <button class="grey">Button</button>
  <button class="green">Button</button>
</div>
```

{% endcodepen %}

{% codepen "https://unpkg.com/bonsai.css@latest/dist/bonsai.min.css", "", "Heyyy", "Waz uuuuuuuup", "Test it" %}

```html
<div class="group vertical">
  <input type="text" placeholder="Name" aria-label="Name" />
  <button>Button</button>
</div>
```

{% endcodepen %}
