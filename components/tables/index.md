---
layout: page
parent: "Components"
title: "Tables"
intro: "Tables show tabular data in columns and rows."
jump_menu: true
---

Tables are great for displaying tabular data. Minimal visual styling helps surface this information more easily.

<div class="ds-preview">
  <table class="treas-table">
    <caption>[Table caption]</caption>
    <thead>
      <tr>
        <th scope="col">Column A</th>
        <th scope="col">Column B</th>
        <th scope="col">Column C</th>
        <th scope="col">Column D</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>1A</td>
        <td>1B</td>
        <td>1C</td>
        <td>1D</td>
      </tr>
      <tr>
        <td>2A</td>
        <td>2B</td>
        <td>2C</td>
        <td>2D</td>
      </tr>
      <tr>
        <td>3A</td>
        <td>3B</td>
        <td>3C</td>
        <td>3D</td>
      </tr>
    </tbody>
  </table>
</div>

## Variations

Styled `<table>` components use `class="treas-table"`.

```html
<table class="treas-table">
  ...
</table>
```

## Usage

### Use When

* When you need to display tabular information, such as statistical data.

### Don't Use

* For layout, use [Grids](/visual-style/grid/).
* If the amount of content is simple or brief enough, and depending on its context, consider structuring as an [unordered list](/visual-style/typography/#unordered-list-bullet), [ordered list](/visual-style/typography/#ordered-list-numbered), or [definition list](/visual-style/typography/#definition-list).

## Accessibility

* Simple tables can have two levels of headers. Each header cell should have `scope="col"` or `scope="row"`.
* Complex tables are tables with more than two levels of headers. Each header should be given a unique `id` and each data cell should have a `headers` attribute with each related header cell’s `id` listed.