---
layout: page
parent: "Components"
title: "U.S. Government Banner"
intro: "The Treasury Header should include the U.S. Government Banner component as an indication of an official government website."
jump_menu: true
---

<!-- US Government Official Site Banner  -->
<section class="treas-topbanner">
  <div class="treas-topbanner__wrap">
    <div class="treas-topbanner__title">
      <img class="treas-topbanner__usa-flag-icon" src="/img/usflag.png" alt="U.S. flag"> An official website of the United States Government
    </div>
    <div class="treas-topbanner__links">
      <ul>
        <li><a href="#">Accessibility</a></li>
        <li><a href="#">Languages</a></li>
        <li><a href="#">Contact</a></li>
        <li><a href="#">Log In</a></li>
      </ul>
    </div>
  </div>
</section>

## Variations

The U.S. Government Banner of the Treasury Header shall use `class="treas-topbanner"`.

```html
<!-- US Government Official Site Banner  -->
<section class="treas-topbanner">
  <div class="treas-topbanner__wrap">
    <div class="treas-topbanner__title">
      <img class="treas-topbanner__usa-flag-icon" src="/img/usflag.png" alt="U.S. flag"> An official website of the United States Government
    </div>
    <div class="treas-topbanner__links">
      <ul>
        <li><a href="#">Accessibility</a></li>
        <li><a href="#">Languages</a></li>
        <li><a href="#">Contact</a></li>
        <li><a href="#">Log In</a></li>
      </ul>
    </div>
  </div>
</section>
```

## Usage

### Use When

* An Treasury Application is viewable to a public audience.
* An Treasury Application needs to have a clear indication of an offical government website.

### Don't Use

* The U.S. Government Banner component on any area of the page except for the first item (top).

## General Guidance

* The U.S. Government Banner should be positioned above the [Application Header Component](/components/header-app/) when paired together in an Treasury Application.
* The U.S. Government Banner should not contain more than 5 links. 
