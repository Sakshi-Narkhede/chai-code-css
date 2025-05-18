# CSS Box Model

## What is Box Model?

- It is one of the most foundational concept of CSS.
- The concept of CSS Box Model defines how elements are sized, positioned and rendered on a webpage. 
- This concept governs how much space an element is going to consume on a webpage.
- When a webpage is layed out, each element is represented as a rectangular box according to the standard CSS Box Model.
- This is done by the browser's rendering engine.

## Box Model Components

### Diagram

[Components of Box Model](./box_model.png)

1. **Content** - The area where text or other content is displayed. 
2. **Padding** - It is the space between the content and the element's border.
3. **Border** - A boundary that wraps around the content and the padding.
4. **Margin** - The space between the element's border and neighboring elements. 

## Box Sizing Properties

- Whenever we talk about box model, we talk about box-sizing properties. 
- This is because box-sizing directly affects how the box model dimensions are applied.
- This property controls how the total width and height of an element are calculated.

1. **content-box (default behavior of the browser)** - width/height of an element includes only content.
2. **border-box** - width/height of an element includes content + padding + border.

Here, margin is not included in both cases as its always outside and not part of the box's size.
