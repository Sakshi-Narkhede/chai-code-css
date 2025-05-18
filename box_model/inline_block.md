# Inline and Block Level Elements

## Block-level Elements

- These elements take up the full width available.
- They create a new line before and after them.
- They always start on new line and stack vertically.
- Some common examples: `<div>`, `<p>`, `<ul>`, `<li>`, etc.

### Key Points

- Always start on a new line.
- By default their width is 100%.
- They can contain block or inline elements.
- Width and height properties applied here.

## Inline Elements

- They do not start on a new line and only take up as much width as needed.
- Some common examples: `<span>`, `<a>`, `<img>`, `<label>`, etc.

### Key Points

- Only take up as much width as their content.
- Width and height properties have no effect here.
- Can only contain other inline elements, not block ones.

## Display Properties

1. **display: inline** - Behaves like an inline element. It ignores the width and height and flows with text (without breaking into a new line).

2. **display: block** - Behaves like a block element. They start on a new line and fits full width.

3. **display: inline-block** - Behaves like an inline element, but allows width, height, padding and margin.

4. **display: none** - Doesn't behave like inline or block element. It hides the element from layout and view.