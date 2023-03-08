# Scrimba Bootcamp Solo Project

## Screenshot

![BestBank](./assets/bestbank.png)

## Project Requirements

Build the project from scratch
Follow Scrimba's Figma design and use:

- Semantic HTML
- Hover
- Container
- Group Selectors
- Compound Selectors

## What I learned

Added `text-shadow` instead of `bold` in order to avoid any jitter when hovering on the nav titles:

```css
li:hover,
li:focus {
  text-decoration: underline;
  text-shadow: 0 0 0.01px var(--black);
}
```
