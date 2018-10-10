---
layout: page
parent: "Components"
title: "Avatar"
intro: "An avatar is used as a placeholder image for a user's profile, and it may be replaced by a custom profile picture."
jump_menu: true
---
### Default (no profile picture)
<div class="ds-preview">
  <div class="treas-avatar treas-avatar--large">
    <span class="sr-only">Default user avatar</span>
  </div>

  <div class="treas-avatar treas-avatar--default">
    <span class="sr-only">Default user avatar</span>
  </div>

  <div class="treas-avatar  treas-avatar--small">
    <span class="sr-only">Default user avatar</span>
  </div>


  <div class="treas-avatar treas-avatar--xsmall">
      <span class="sr-only">Default user avatar</span>
    </div>
</div>

Buttons are styled with `class="treas-avatar"`, and optionally modifiable with one or no size variations (e.g. `treas-avatar--[large | default | small | xsmall]`).

```html
<div class="ds-preview">
  <div class="treas-avatar  treas-avatar--[variation]">
    <span class="sr-only">Default user avatar</span>
  </div>
</div>
```
### With Profile picture
<div class="ds-preview">
  <div class="treas-avatar treas-avatar--large">
    <img class="treas-avatar__picture" src="/img/secretary.png" alt="Secretary Mnuchin's Profile Picture">
  </div>
  <div class="treas-avatar treas-avatar--default">
      <img class="treas-avatar__picture" src="/img/secretary.png" alt="Secretary Mnuchin's Profile Picture">
  </div>
  <div class="treas-avatar treas-avatar--small">
    <img class="treas-avatar__picture" src="/img/secretary.png" alt="Secretary Mnuchin's Profile Picture">
  </div>
  <div class="treas-avatar treas-avatar--xsmall">
      <img class="treas-avatar__picture" src="/img/secretary.png" alt="Secretary Mnuchin's Profile Picture">
    </div>
</div>

```html
<div class="ds-preview">
  <div class="treas-avatar treas-avatar--[variation]">
    <img class="treas-avatar__picture" src="/img/secretary.png" alt="Secretary Mnuchin's Profile Picture">
  </div>
</div>
```

## Usage

### Use When

* Profile pictures are needed.

## Accessibility

* Always use `<span class="sr-only">...</span>` text for empty/default avatars.
* Always use meaningful `alt` tag attributes for profile pictures (e.g. `alt="Secretary Mnuchin's Profile Picture"`).