## Media Queries (with `max-width`)

Syntax:
```css
/* Maximum width at which media query still applies*/
@media (max-width: 600px) {
    .some-selector {
        background-color: blue;
    }
    
    .another-selector {
        background-color: yellow;
    }
}
```

### Breakpoints
**Strategies for selecting breakpoints:**
- **Bad**: Based on popular devices
- **Good**: Based on screen width ranges
- **Perfect**: When design breaks down