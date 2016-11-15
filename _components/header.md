---
title: Header
layout: component
---

This is the header of pollistics

```html
<header>
  <a href="/"><img src="/src/img/logo.svg" alt="home"></a>
  <div class="user">
    <a href="/me"><img src="/src/img/user.svg" alt="me"></a>
    <a href="/login" class="cta">login</a>
    <a href="/register" class="cta">register</a>
  </div>
</header>
```

This should always be visible, but the `.user` div shouldn't contain all three of the call to actions. Either the first one when logged in, the second and third one when logged out.

## Rendered

<div class="example">
  <header>
    <a href="/"><img src="{{site.baseurl}}/src/img/logo.svg" alt="home"></a>
    <div class="user">
      <a href="/me"><img src="{{site.baseurl}}/src/img/user.svg" alt="me"></a>
    </div>
  </header>
</div>

<div class="example">
  <header>
    <a href="/"><img src="{{site.baseurl}}/src/img/logo.svg" alt="home"></a>
    <div class="user">
      <a href="/login" class="cta">login</a>
      <a href="/register" class="cta">register</a>
    </div>
  </header>
</div>
