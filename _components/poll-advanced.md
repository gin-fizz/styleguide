---
title: Poll advanced
layout: component
---

This is the spot you can put more options when creating a poll

```html
<details class="poll--advanced">
  <summary>advanced options</summary>
  <select name="someOption" id="someOption">
    <option value="memes">memes</option>
    <option value="no-memes">no memes 😭</option>
  </select>
</details>
```

> Note: not supported on Firefox, needs a polyfill

This should be inside the `.poll` form

## Rendered

<details class="poll--advanced">
  <summary>advanced options</summary>
  <select name="someOption" id="someOption">
    <option value="memes">memes</option>
    <option value="no-memes">no memes 😭</option>
  </select>
</details>
