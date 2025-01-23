# Box Model Review

I learned about the four primary properties of the box model:

- **Width & Height**:  
  - Define the size of the content area.
  - Can be set in **pixels** or **percentages**.

- **Padding**:  
  - The space between the content area and the border.
  - Can be set individually for each side or as shorthand for all sides.

- **Borders**:  
  - Surround the content and padding areas.
  - Can be customized with the following properties:
    - **Width**: Set in **pixels** or keywords (`thin`, `medium`, `thick`).
    - **Style**: Various styles like `none`, `dotted`, `solid`, etc.
    - **Color**: Set using color names or color codes.

- **Margins**:  
  - Space outside the border of an element.
  - **Horizontal margins**: Add up (sum of right and left margins).
  - **Vertical margins**: Collapse to the larger value.

## Important Points:
- `margin: 0 auto` centers an element horizontally.
- The **overflow** property can be set to `visible`, `hidden`, or `scroll` to control content overflow.
- The **visibility** property can show or hide elements.

### Example CSS Syntax:

```css
/* Set the width and height */
.example {
  width: 100px;
  height: 200px;
}

/* Set padding */
.example-padding {
  padding: 10px 20px 15px 25px;  /* top right bottom left */
}

/* Set border */
.example-border {
  border: 2px solid #000;  /* thickness, style, color */
}

/* Set margin */
.example-margin {
  margin: 0 auto;  /* Horizontally center an element */
}

/* Set overflow */
.example-overflow {
  overflow: hidden;  /* Content that overflows is hidden */
}

/* Set visibility */
.example-visibility {
  visibility: hidden;  /* Hide the element */
}
