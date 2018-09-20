---
layout: page
parent: "Components"
title: "Buttons"
intro: "Use buttons to signal actions."
jump_menu: true
---

<div class="ds-preview ds-preview--dark">
  <button class="treas-btn treas-btn--primary" type="button">Label</button>
  <button class="treas-btn treas-btn--secondary" type="button">Label</button>
  <button class="treas-btn treas-btn--ghost" type="button">Label</button>
  <button class="treas-btn treas-btn--inverse" type="button">Label</button>
  <button class="treas-btn treas-btn--rectangle treas-btn--small treas-btn--secondary" type="button">Label</button>
</div>

## Variations

Buttons are styled with `class="treas-btn"`, modifiable with one or multiple `treas-btn--[variation]`.

```html
<button class="treas-btn treas-btn--[variation]" type="button">Label</button>
<a class="treas-btn treas-btn--[variation]" href="link.html">Label</a>
```

### Default

```html
<button class="treas-btn treas-btn--primary" type="button">Label</button>
```
<div class="ds-preview">
  <button class="treas-btn treas-btn--primary" type="button">Label</button>
</div>

### Secondary

```html
<button class="treas-btn treas-btn--secondary" type="button">Label</button>
```
<div class="ds-preview">
  <button class="treas-btn treas-btn--secondary" type="button">Label</button>
</div>

### Ghost

```html
<button class="treas-btn treas-btn--ghost" type="button">Label</button>
```
<div class="ds-preview">
  <button class="treas-btn treas-btn--ghost" type="button">Label</button>
</div>

### Inverse

```html
<button class="treas-btn treas-btn--inverse" type="button">Label</button>
```
<div class="ds-preview ds-preview--dark">
  <button class="treas-btn treas-btn--inverse" type="button">Label</button>
</div>

### Rectangle 
In the following example, we chained two different buttons states to create a small rectangular shaped button.

```html
<button class="treas-btn treas-btn--secondary treas-btn--rectangle treas-btn--small" type="button">Label</button>
```
<div class="ds-preview">
    <button class="treas-btn treas-btn--secondary treas-btn--rectangle treas-btn--small" type="button">Label</button>
</div>

## States

Each button variation can be modified with one or multiple states:

```html
<button class="treas-btn treas-btn--[variation] treas-btn--[state]" type="button">Label</button>
```

### Full-width

```html
<button class="treas-btn treas-btn--[variation] treas-btn--block" type="button">Label</button>
```
<div class="ds-preview">
  <button class="treas-btn treas-btn--primary treas-btn--block" type="button">Label</button>
</div>

### Disabled

Disabled buttons do not have a `class="treas-btn--[state]"`, instead using the `disabled` attribute.

```html
<button class="treas-btn treas-btn--[variation]" type="button" disabled="disabled">Label</button>
```
<div class="ds-preview">
  <button class="treas-btn treas-btn--primary" type="button" disabled="disabled">Label</button>
  <button class="treas-btn treas-btn--secondary" type="button" disabled="disabled">Label</button>
  <button class="treas-btn treas-btn--ghost" type="button" disabled="disabled">Label</button>
  <button class="treas-btn treas-btn--secondary treas-btn--rectangle" type="button" disabled="disabled">Labels</button>
</div>

### Small

```html
<button class="treas-btn treas-btn--[variation] treas-btn--small" type="button">Label</button>
```
<div class="ds-preview">
  <button class="treas-btn treas-btn--primary treas-btn--small" type="button">Label</button>
</div>

### Large

```html
<button class="treas-btn treas-btn--[variation] treas-btn--large" type="button">Label</button>
```
<div class="ds-preview">
  <button class="treas-btn treas-btn--primary treas-btn--large" type="button">Label</button>
</div>

## Decorative
Buttons can include icons for more decorative styling. For a list of available icons, to to the [icons list](/visual-style/icons) page. 

```html
<button class="treas-btn treas-btn--ghost treas-btn--small" type="button">
    <span class="treas-btn__icon icon-launch"></span>Label
</button>
```
<div class="ds-preview">
    <button class="treas-btn treas-btn--ghost treas-btn--small" type="button">
        <span class="treas-btn__icon icon-launch"></span>Label
    </button>
</div>

## Usage

### Use When

Use buttons for the most important actions you want users to take on your site, such as "Download," "Sign up," or "Log out."

### Don't Use

* If you want to lead users between pages of a website. Use [text links]({{ site.baseurl }}components/links/) instead.
* Less popular or less important actions may be visually styled as links.

## Accessibility

* Buttons should display a visible focus state when users tab to them.
* Avoid using `<div>`, `<img>`, or other such tags to create buttons. Screen readers don't automatically know either is a usable button.
* When styling links to look like buttons, remember that screen readers handle links slightly differently than they do buttons. Pressing the Space key triggers a button, but pressing the Enter key triggers a link.

## General Guidance

* Button styles can be applied to nearly any HTML element, e.g. `<foo class="treas-btn treas-btn--[variant]">Label</foo>`. 99% of the time it will be a `<button>` or `<a>`.
* For `<button>` elements, `type` attribute is required, and will most likely be `type="button"`. Use `type="submit"` to submit a `<form>`. Omitting `type` attribute will default to `type="submit"`.
* Generally, use primary buttons for actions that go to the next step and use secondary buttons for actions that happen on the current page.
* Style the button most users should click in a way that distinguishes from other buttons on the page. Try using the “large button” or the most visually distinct fill color.
* Make sure buttons look clickable — use color variations to distinguish static, hover and active states.
* Avoid using too many buttons on a page.
* Use sentence case for button labels, e.g. "Sign up" instead of "Sign Up".
* Button labels should be as short as possible with “trigger words” that your users will recognize to clearly explain what will happen when the button is clicked (for example, “Download,” “View” or “Sign up”).
* Make the first word of the button’s label an action verb. For example, instead of “Complaint Filing” label the button “File a complaint.”
* At times, consider adding an icon to signal specific actions (“Download”, “Open in a new window”, etc).
