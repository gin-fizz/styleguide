---
title: (Footer)
layout: component
---

This is the footer of pollistics

```html
<footer>
	<a href="/"><img src="/src/img/logo.svg" alt="home"></a>
	<div class="footer">
		<p>Pollistics - Copyright &copy; Gin-Fizz 2016</p>
	</div>
	<nav>
		<ul class="socialmedia">
			<li><a href="http://www.facebook.com" class="facebook">Fb</a></li>
			<li><a href="https://twitter.com/?lang=nl" class="twitter">Twitter</a></li>
		</ul>
	</nav>
</footer>
```

The footer should always be visible and should look like this.

## Rendered
<footer>
	<a href="/"><img src="/src/img/logo.svg" alt="home"></a>
	<div class="footer">
		<p>Pollistics - Copyright &copy; Gin-Fizz 2016</p>
	</div>
	<nav>
		<ul class="socialmedia">
			<li><a href="http://www.facebook.com" class="facebook">Fb</a></li>
			<li><a href="https://twitter.com/?lang=nl" class="twitter">Twitter</a></li>
		</ul>
	</nav>
</footer>

<style>
	{{ '@import "variables","components/footer";' | scssify }}
</style>
