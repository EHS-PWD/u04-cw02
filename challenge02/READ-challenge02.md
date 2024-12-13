### **Challenge 2: Comparing Style Methods**

**Scenario:**  
Your webpage contains multiple styles for a `<h2>` element:

- Inline style:
   ```html
   <h2 style="color: green;">Heading</h2>
   ```
- Internal style:
   ```html
   <style>
     h2 {
       color: red;
     }
   </style>
   ```
- External style:
   ```css
   h2 {
     color: blue;
   }
   ```
   **Task:**
1. Predict the color of the `<h2>` text.
2. Test it by implementing the styles in your HTML file.
3. Inside of the styles.css, create a comment and explain the result based on style precedence.

**Goal:**  
Understand how precedence determines which style is applied.
