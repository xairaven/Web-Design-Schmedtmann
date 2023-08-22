## Floats
- Element is removed from the normal flow: “out of flow”
- Text and inline elements will wrap around the floated element
- The container will not adjust its height to the element

```css
.selector {
    float: left;
    float: right;
}
```

### Example:
```css
.author {
    margin-left: 80px;
    margin-top: 10px;
    float: left;
}

.author-img {
    float: left;
    margin-bottom: 20px;
}

h1 {
    float: left;
}

nav {
    float: right;
}
```