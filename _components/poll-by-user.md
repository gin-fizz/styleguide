---
title: Polls by user
layout: component
---

This is the the list of polls by user

```html
<ul class="poll-list">
  <li>
    <p class="list-title">Dit is een titel</p>
    <div>
      <a href="/katja-wauw-peter" class="cta">view</a>
      <a href="/katja-wauw-peter/results" class="cta">results</a>
      <form method="post" action="/polls/delete/katja-wauw-peter">
        <input type="submit" value="delete">
        <input type="hidden" name="csrf" value="csrf_token"/>
      </form>
    </div>    
  </li>
  <li>
    <p class="list-title">Dit is een andere titel</p>
    <div>
      <a href="/katja-wauw-haroen" class="cta">view</a>
      <a href="/katja-wauw-haroen/results" class="cta">results</a>
      <form method="post" action="/polls/delete/katja-wauw-haroen">
        <input type="submit" value="delete">
        <input type="hidden" name="csrf" value="csrf_token"/>
      </form>
    </div>    
  </li>
</ul>
```

Every poll in a list of polls by user should look like this

## Rendered

<ul class="poll-list">
  <li>
    <p class="list-title">Dit is een titel</p>
    <div>
      <a href="/katja-wauw-peter" class="cta">view</a>
      <a href="/katja-wauw-peter/results" class="cta">results</a>
      <form method="post" action="/polls/delete/katja-wauw-peter">
        <input type="submit" value="delete">
        <input type="hidden" name="csrf" value="csrf_token"/>
      </form>
    </div>    
  </li>
  <li>
    <p class="list-title">Dit is een andere titel</p>
    <div>
      <a href="/katja-wauw-haroen" class="cta">view</a>
      <a href="/katja-wauw-haroen/results" class="cta">results</a>
      <form method="post" action="/polls/delete/katja-wauw-haroen">
        <input type="submit" value="delete">
        <input type="hidden" name="csrf" value="csrf_token"/>
      </form>
    </div>    
  </li>
</ul>
