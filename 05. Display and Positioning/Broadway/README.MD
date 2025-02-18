### Broadway Design Project: Tasks Breakdown

In this project, you'll improve the layout of a fictional design firm, **Broadway Design**, by adjusting elements like the navigation bar, supporting sections, and header using **CSS** positioning and display properties. Below is the breakdown of the tasks:

---

#### 1. **Fix the Header at the Top**:
   - The `<header>` scrolls with the page; change its position to `fixed` so it stays at the top when scrolling.
   ```css
   header {
       position: fixed;
       top: 0;
       width: 100%;
   }
   ```

#### 2. **Stretch the Header Width**:
   - The `<header>` should stretch across the entire width of the page. Ensure it takes up the full width.
   ```css
   header {
       width: 100%;
   }
   ```

#### 3. **Display Navigation List Horizontally**:
   - Change the display of `<li>` elements inside `<nav>` to be horizontally aligned by setting `display: inline-block` or `flex`.
   ```css
   nav ul {
       display: flex;
   }
   nav li {
       display: inline-block;
   }
   ```

#### 4. **Set List Items Width**:
   - Set the width of each `<li>` element to `80px` to control the size of the navigation items.
   ```css
   nav li {
       width: 80px;
   }
   ```

#### 5. **Adjust Position of `<main>`**:
   - After fixing the header, the content shifts up. Set the `<main>` element to have `position: relative` to position it properly after the header.
   ```css
   main {
       position: relative;
   }
   ```

#### 6. **Bring the Header Above Content Using z-Index**:
   - The header might be hidden behind other content after setting it to fixed. Use `z-index` to bring it to the front.
   ```css
   header {
       z-index: 10;
   }
   ```

#### 7. **Offset `<main>` from the Top**:
   - Offset `<main>` by `80px` from the top to prevent it from being covered by the fixed header.
   ```css
   main {
       margin-top: 80px;
   }
   ```

#### 8. **Style the Supporting Section**:
   - Style the `.supporting .col` elements to appear next to each other by using `flexbox` and setting their height and width.
   ```css
   .supporting {
       display: flex;
   }
   .supporting .col {
       width: 200px;
       height: 200px;
   }
   ```

#### 9. **Set Width and Height for `.supporting .col`**:
   - Set the specific width and height of the `.supporting .col` elements so that they are properly displayed.
   ```css
   .supporting .col {
       width: 200px;
       height: 200px;
   }
   ```

#### 10. **Challenge: Fixed Footer**:
   - If you want to go beyond the basic requirements, challenge yourself by making the `<footer>` fixed at the bottom of the page, regardless of scrolling.
   ```css
   footer {
       position: fixed;
       bottom: 0;
       width: 100%;
   }
   ```

---

### Next Steps:
- **Complete each task step by step** and check how the layout improves as you apply each CSS rule.
- **Challenge yourself** by working on the fixed footer if you have time.

Let me know if you need any further help or clarification with any of these steps!