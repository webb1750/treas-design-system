---
layout: page
parent: "Components"
title: "Application Card"
intro: "The Application Card can be used to display multiple apps or services on your site."
jump_menu: true
---

<div class="treas-app-card--wrapper">
        
        <!-- App Card -->
        <div class="treas-app-card">
          <div class="treas-app-card--content">
            <div class="treas-app-card--graphic">
              <img class="treas-app-card--icon" src="/img/graphic.svg" />
            </div>
            <h3 class="treas-app-card--heading">Provisioning for People (P4P)</h3>
            <div class="treas-app-card--desc">
              <p class="treas-app-card--text">This is where some descriptive text will go. More information will go in this area.</p>
            </div>
            <div class="treas-app-card--action">
              <a href="#" class="treas-btn treas-btn--outline treas-btn--block">Launch App</a>
            </div>
          </div>
        </div>
        <!-- /App Card -->

        <!-- App Card -->
        <div class="treas-app-card">
          <div class="treas-app-card--content">
            <div class="treas-app-card--graphic">
              <img class="treas-app-card--icon" src="/img/graphic.svg" />
            </div>
            <h3 class="treas-app-card--heading">Secure Container Tracking</h3>
            <div class="treas-app-card--desc">
              <p class="treas-app-card--text">This is where some descriptive text will go. More information will go in this area.</p>
            </div>
            <div class="treas-app-card--action">
              <a href="#" class="treas-btn treas-btn--outline treas-btn--block">Launch App</a>
            </div>
          </div>
        </div>
        <!-- /App Card -->

        <!-- App Card -->
        <div class="treas-app-card">
          <div class="treas-app-card--content">
            <div class="treas-app-card--graphic">
              <img class="treas-app-card--icon" src="/img/graphic.svg" />
            </div>
            <h3 class="treas-app-card--heading">IT Service Desk</h3>
            <div class="treas-app-card--desc">
              <p class="treas-app-card--text">This is where some descriptive text will go. More information will go in this area.</p>
            </div>
            <div class="treas-app-card--action">
              <a href="#" class="treas-btn treas-btn--outline treas-btn--block">Launch App</a>
            </div>
          </div>
        </div>
        <!-- /App Card -->
        
        <!-- App Card -->
        <div class="treas-app-card">
          <div class="treas-app-card--content">
            <div class="treas-app-card--graphic">
              <img class="treas-app-card--icon" src="/img/graphic.svg" />
            </div>
            <h3 class="treas-app-card--heading">Intake Request Mananagement</h3>
            <div class="treas-app-card--desc">
              <p class="treas-app-card--text">This is where some descriptive text will go. More information will go in this area.</p>
            </div>
            <div class="treas-app-card--action">
              <a href="#" class="treas-btn treas-btn--outline treas-btn--block">Launch App</a>
            </div>
          </div>
        </div>
        <!-- /App Card -->
      </div>

## App Card

The Treasury App Card shall use the following `class="treas-app-card"` and requires a wrapping element with the class `treas-app-card--wrapper`. The description text for each card should be kept short (84 characters max). 

```html
<!-- App Card Wrapper  -->
<div class="treas-app-card--wrapper">
  <!-- App Card -->
  <div class="treas-app-card">
    <div class="treas-app-card--content">
      <div class="treas-app-card--graphic">
        <img class="treas-app-card--icon" src="/img/graphic.svg" />
      </div>
      <h3 class="treas-app-card--heading">[Card Title Goes Here]</h3>
      <div class="treas-app-card--desc">
        <p class="treas-app-card--text">This is where some descriptive text will go. More information will go in this area.</p>
      </div>
      <div class="treas-app-card--action">
        <a href="#" class="treas-btn treas-btn--outline treas-btn--block">Launch App</a>
      </div>
    </div>
  </div>
</div>
```

## Usage

### Use When

* An Treasury Application has at least 3 or more apps on a landing page.
* An Treasury Application needs to display the title and logo of the application, and short description.

