# CSS Selectors Review

## Key Points

### Basic Selectors
- **Type Selector**: Targets all elements of a specified type (e.g., `div`, `p`).
- **Class Selector**: Targets elements with a specific class (e.g., `.example`).
- **ID Selector**: Targets a single element with a specific ID (e.g., `#unique`).

### Universal Selector
- `*`: Targets all elements.

### Pseudo-classes
- Used to style elements in specific states (e.g., `:hover`, `:nth-child(n)`).

### Specificity
- **Order of Specificity**: IDs > Classes > Types.
- IDs override class and type styles, while classes override type styles.

### Combining Selectors
- **Chaining**: Combine multiple selectors for precise targeting (e.g., `div.example`).
- **Descendant Selector**: Select elements nested within others (e.g., `div p`).
- **Group Selector**: Apply styles to multiple unrelated selectors (e.g., `h1, h2, h3`).

### Reusability
- **Classes**: Can be reused for multiple elements.
- **IDs**: Unique to a single element.

### Tips
- Use classes for general styling.
- Reserve IDs for unique elements or JavaScript manipulation.
- Avoid overusing `!important` to maintain CSS hierarchy.

---

Feel free to expand your knowledge by experimenting with selectors to customize websites effectively!

