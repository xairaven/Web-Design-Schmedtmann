## Types of Boxes

### Block
- Elements are formatted visually as blocks
- Elements occupy 100% of parent element’s width, no matter the content
- Elements are stacked vertically by default, one after another
- The box-model applies as showed earlier

```
Default elements: body, main, header, footer, section, nav, 
aside, div, h1-h6, p, ul, ol, li, etc.

With CSS: display: block
```

### Inline
- Occupies only the space necessary for its content
- Causes no line-breaks after or before the element
- Box model applies in a different way: heights and widths do not apply
- Paddings and margins are applied only horizontally (left and right)

```
Default elements: a, img, strong, em, button, etc.

With CSS: display: inline
```

### Inline-block
- Looks like inline from the outside, behaves like blocklevel on the inside
- Occupies only content’s space
- Causes no line-breaks
- Box-model applies as showed

```css
.some-selector {
    display: inline-block;
}
```