### **Challenge 4: Applying Specificity Rules**  
**Scenario:**  
You are designing a `<button>` element that should follow these styles:  
- Default color is red (element selector).  
- Class `.btn-primary` changes the color to blue.  
- ID `#important-btn` changes the color to green.  

**Task:**  
1. Write the CSS rules to implement the scenario above.  
2. Create a button in your HTML that follows all three rules.  
3. Predict which color the button will be and explain why.  

**Example Code:**  
```html
<button id="important-btn" class="btn-primary">Click Me</button>
```  

**Goal:**  
Understand how specificity determines the applied styles.  