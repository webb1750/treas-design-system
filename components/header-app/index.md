---
layout: page
parent: "Components"
title: "Application Header"
intro: "The Treasury Application Header should include the branding of your application name."
jump_menu: true
---

<!-- Site Header  -->
<header class="treas-header">
  <div class="treas-header__wrap">
      <a class="treas-header__title" href="#">
        <img class="treas-header__logo" src="/img/seal.svg" alt="U.S. Department of the Treasury seal"> 
        <span class="treas-header__name">U.S. Department of the Treasury</span>
      </a>
      <button class="treas-burger-menu" aria-expanded="false">
        <span class="sr-only">MENU</span>
        <span class="treas-burger-menu__line"></span>
        <span class="treas-burger-menu__line"></span>
        <span class="treas-burger-menu__line"></span>
      </button>
  </div>
</header>

## Variations

The Application Header shall use the following `class="treas-header"` and is modifiable with one variation `treas-header--light`.

```html
<!-- Site Header  -->
<header class="treas-header">
  <div class="treas-header__wrap">
    <a class="treas-header__title" href="/">
       <img class="treas-header__logo" src="/img/seal.svg" alt="U.S. Department of the Treasury seal"> 
       <span class="treas-header__name">U.S. Department of the Treasury</span>
    </a>
    <button class="treas-burger-menu" aria-expanded="false">
        <span class="sr-only">MENU</span>
        <span class="treas-burger-menu__line"></span>
        <span class="treas-burger-menu__line"></span>
        <span class="treas-burger-menu__line"></span>
    </button>
  </div>
</header>
```

### Light
```html
<!-- Site Header  -->
<header class="treas-header treas-header--light">
  <div class="treas-header__wrap">
    <a class="treas-header__title" href="/">
       <img class="treas-header__logo" src="/img/logo.svg" alt="U.S. Department of the Treasury seal"> 
       <span class="treas-header__name">U.S. Department of the Treasury</span>
    </a>
    <button class="treas-burger-menu" aria-expanded="false">
        <span class="sr-only">MENU</span>
        <span class="treas-burger-menu__line"></span>
        <span class="treas-burger-menu__line"></span>
        <span class="treas-burger-menu__line"></span>
    </button>
  </div>
</header>
```
<header class="treas-header treas-header--light">
  <div class="treas-header__wrap">
    <a class="treas-header__title" href="/">
       <img class="treas-header__logo" src="/img/logo.svg" alt="U.S. Department of the Treasury seal"> 
       <span class="treas-header__name">U.S. Department of the Treasury</span>
    </a>
    <button class="treas-burger-menu" aria-expanded="false">
        <span class="sr-only">MENU</span>
        <span class="treas-burger-menu__line"></span>
        <span class="treas-burger-menu__line"></span>
        <span class="treas-burger-menu__line"></span>
    </button>
  </div>
</header>

## Usage

### Use When

* An Treasury Application is viewable to a internal or public audience.
* An Treasury Application needs to display the title and logo of the application.

### Don't Use

* The Application Header component on any area of the page except the top or just below the [U.S. Government Banner Component](/components/gov-banner).

## General Guidance

* The U.S. Government Banner should be positioned above the [Application Header Component](/components/header-app/) when paired together in an Treasury Application.
* The U.S. Government Banner should not contain more than 5 links. 
