# Paint Store - CSS Color Customization  

## Project Overview  
This project enhances a vibrant paint store webpage by refining color choices using CSS. You'll replace named colors, apply transparency, and use HSL to improve the color swatches.  

### Tasks & Changes  

1. **Replace Named Colors with Hex Codes**  
   - Change all instances of `orange` to `#ff8000` for brand consistency.  
   - Affects:  
     - `header` background  
     - `#color-guide h2` text color  
     - `.button` in `footer`  

2. **Make h1 Title Text Semi-Transparent**  
   - Set `color: rgba(0, 0, 0, 0.7);` to give the title a subtle effect.  

3. **Apply a Semi-Transparent Overlay to the Header**  
   - Add `background-color: rgba(255, 128, 0, 0.75);` in `#banner:before` to enhance the filter effect.  

4. **Add a Semi-Transparent Footer Overlay**  
   - Use the same transparency effect as the header in `footer:before`.  

5. **Soften Subtitle Colors**  
   - Change `.color .swatches h4` text color to `#9b9b9b` for a subtle effect.  

6. **Convert Base Colors to HSL**  
   - Update `.reds .base-color` from `#ff002b` to `hsl(350, 100%, 50%)`.  
   - Similarly, adjust `green` and `blue` base colors using their respective HSL values.  

7. **Complete Missing HSL Color Swatches**  
   - Follow the existing pattern for lightness, saturation, and hue.  
   - Example: `.reds .lightness .color-1` should be `hsl(350, 100%, 80%)`.  

### Conclusion  
These improvements enhance the website’s aesthetic, making colors more precise and visually appealing. Enjoy styling your Paint Store project! 🎨