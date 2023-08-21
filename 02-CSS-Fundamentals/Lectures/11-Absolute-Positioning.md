## Absolute Positioning

### Normal flow
- Default positioning 
- Element is “in flow” 
- Elements are simply laid out according to their order in the HTML code

```css
/* Default positioning */
.selector {
    position: relative;
}
```

### Absolute positioning
- Element is removed from the normal flow: “out of flow”
- No impact on surrounding elements, might overlap them
- We use top, bottom, left, or right to offset the element from its relatively positioned container

```css
.selector {
    position: absolute;
}
```