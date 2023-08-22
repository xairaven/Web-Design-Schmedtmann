## Clearing Floats

### Outdated way:
- Add HTML `div` block after floated elements:
```html
<div class="clear"></div>
```
- CSS styles:
```css
.clear {
    clear: both;
}
```

### Preferred way:
- Add a CSS class to container with floating elements:
```html

<header class="main-header clearfix">
    <h1>📘 The Code Magazine</h1>

    <nav>
        <a href="blog.html">Blog</a>
        <a href="#">Challenges</a>
        <a href="#">Flexbox</a>
        <a href="#">CSS Grid</a>
    </nav>
</header>
```
- CSS code:
```css
.clearfix::after {
    clear: both;
    content: "";
    display: block;
}
```
This code replaces redundant `div` block with `::after` pseudo-element,
so now code is clearer. `clear` property "clears" flow, `content` is needed
because this pseudo-element is shown only if there are some content.
Also, it's work only with block elements, so we need property `display: block`.