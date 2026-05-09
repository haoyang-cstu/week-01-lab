# Week 01 Lab — Personal Profile Page

A simple personal profile page built with semantic HTML5 and plain CSS as part of the Week 1 fullstack course lab.

## Files
- `index.html` — page structure (header, main with About/Interests/Contact, footer)
- `styles.css` — styling with CSS custom properties, flexbox layout, hover effects

## Reflection

**1. What was the most surprising thing you learned today?**

How much visual structure flexbox gives you for free. Switching the interests list from `flex-direction: column` to `row` with `flex-wrap: wrap` and a `gap` turned a vertical list into responsive inline pills without writing any media queries or float/clearfix code. Coming from a backend mindset, I expected layout to need a lot more imperative work; the declarative model where the browser handles spacing and wrapping was a pleasant surprise.

**2. What is one question you still have going into Week 2?**

When does it make sense to reach for CSS Grid instead of flexbox? Both seem to overlap for a lot of two-dimensional layouts, and I'd like a clearer mental model for picking the right one — especially for page-level layouts versus component-level layouts.
