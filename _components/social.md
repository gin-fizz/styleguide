---
layout: component
title: Social
---

A component for sharing the current page (requires js).

```html
<div class="social">
  <div class="social--item">
    <a href="https://www.facebook.com/sharer/sharer.php?u=https%3A%2F%2Fpollistics.com%2F😏😏😏&amp;quote=test+en+zo+poll" target="_blank" rel="noopener" class="cta">share on facebook</a>
    <a href="https://twitter.com/intent/tweet?text=test+en+zo+poll%0A%0Avia+Pollistics+%E2%80%94+https%3A%2F%2Fpollistics.com%2F😏😏😏" target="_blank" rel="noopener" class="cta">share on twitter</a>
  </div>
  <div class="social--item" id="social"></div>
</div>
```

> only one is allowed per page.

> You need to add the current description to twitter and facebook URLs

## Rendered

<div class="social">
  <div class="social--item">
    <a href="https://www.facebook.com/sharer/sharer.php?u=https%3A%2F%2Fpollistics.com%2F😏😏😏&amp;quote=test+en+zo+poll" target="_blank" rel="noopener" class="cta">share on facebook</a>
  <a href="https://twitter.com/intent/tweet?text=test+en+zo+poll%0A%0Avia+Pollistics+%E2%80%94+https%3A%2F%2Fpollistics.com%2F😏😏😏" target="_blank" rel="noopener" class="cta">share on twitter</a>
  </div>
  <div class="social--item" id="social">
    <div class="social--url">https://pollistics.com/😏😏😏</div>
    <button class="social--copy">🔗</button>
  </div>
</div>
