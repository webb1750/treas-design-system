---
layout: page
parent: "Components"
title: "Search"
intro: "Search is used for search box input fields."
jump_menu: true
---

<div class="ds-preview">
  <div class="usdt-row align-center">
    <div class="usdt-col-md-8">
      <div class="treas-input-group">
        <input class="treas-input--search" placeholder="Search" type="text" title="Search input">
        <button class="treas-btn--search" type="submit" aria-label="search"><span class="sr-only">Search</span><span class="icon-search ds-icon"></span></button>
      </div>
    </div>
  </div>
</div>

Search box inputs/buttons require a wrapping element with the style `class="treas-input-group"`. They are built using an input field styled with `class="treas-input--search"` and a button styled with `class="treas-btn--search"`.

```html
  <div class="treas-input-group">
    <input class="treas-input--search" placeholder="Search" type="text" title="Search input">
    <button class="treas-btn--search" type="submit" aria-label="search">
      <span class="sr-only">Search</span><span class="icon-search ds-icon"></span>
    </button>
  </div>
```


## Usage

### Use When

* Search box is needed.

