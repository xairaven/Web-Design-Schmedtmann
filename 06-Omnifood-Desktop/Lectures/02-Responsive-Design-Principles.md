## Responsive Design Principles

### Responsive Design
- Design technique to make a webpage adjust its layout and visual
style to **any possible screen size** (window or viewport size)
- In practice, this means that responsive design makes websites
usable on all devices, such as **desktop computers, tablets, and
mobile phones**.

### Responsive Design Ingredients
- **Fluid Layouts**
  - To allow webpage to adapt to the **current viewport** width (or
  even height)
  - Use `%` (or `vh` / `vw`) unit instead of `px` for elements that
  **should adapt to viewport (usually layout)**
  - Use `max-width` instead of `width`
  
- **Responsive Units**
  - Use `rem` unit instead of `px` for most lengths
  - To make it easy to **scale the entire layout down** (or up)
  automatically
  - **Helpful trick:** setting `1rem` to `10px` for easy calculations

- **Flexible images**
  - By default, images **don't scale automatically** as we change
  the viewport, so we need to fix that
  - Always use `%` for image dimensions, together with the
  `max-width` property

- **Media Queries**
  - Bring responsive sites to life!
  - To change CSS styles on **certain viewport widths** (called
  breakpoints)

### Development Approaches
- **Desktop-First**
  - Start writing CSS for the desktop: **large screen**
  - Then, media queries **shrink design** to smaller screens.
- **Mobile-First**
  - Start writing CSS for the desktop: **small screen**
  - Then, media queries **expand design** to larger screens.
  - Forces us to reduce websites and apps to **absolute essentials**.