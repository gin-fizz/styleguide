---
title: Poll vote
layout: component
---

Once a poll is created, you can vote on it like this:

```html
<div class="vote--options">
  <label for="optionXX">
    <input type="radio" name="option" id="optionXX" value="optionXX">
    <div class="vote--options--radio"></div>
    Groen
  </label>
  <label for="optionXX">
    <input type="radio" name="option" id="optionXX" value="optionXX">
    Oranje
  </label>
  <label for="optionXX">
    <input type="radio" name="option" id="optionXX" value="optionXX">
    Blauw
  </label>
  <label for="optionXX">
    <input type="radio" name="option" id="optionXX" value="optionXX">
    Rood
  </label>
</div>
```

## Rendered


<div class="vote--options">
  
  <label for="optionXX">
    <div class="vote--options--container">
      <input type="radio" name="option" id="optionXX" value="optionXX">
      <div class="vote--options--radio"></div> 
    </div>
    Groen
  </label>
  

  <label for="optionXX">
    <input type="radio" name="option" id="optionXX" value="optionXX">
    Oranje
  </label>
  <label for="optionXX">
    <input type="radio" name="option" id="optionXX" value="optionXX">
    Blauw
  </label>
  <label for="optionXX">
    <input type="radio" name="option" id="optionXX" value="optionXX">
    Rood
  </label>
</div>

