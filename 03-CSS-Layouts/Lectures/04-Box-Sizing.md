## Box Sizing

There's a `box-sizing` property in CSS:
```css
.selector {
    box-sizing: border-box;
    box-sizing: content-box;
}
```

Width/Height formula with `content-box`:
```
Final element width = right border + right padding + width + left padding + left border
Final element height = top border + top padding + height + bottom padding + bottom border
```

Width/Height formula with `border-box`:
```
Final element width = width
Final element height = height
```
So, paddings and borders include in width/height.

Starter CSS initialization at this moment will look like:
```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
```