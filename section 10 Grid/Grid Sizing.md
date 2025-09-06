# 📏 Grid Sizing

## 📖 Overview

- Defines **how rows and columns are sized** in a grid layout.
    

## 💡 Key Properties

- **grid-template-columns / grid-template-rows**
    
    - Define structure of grid.
        
    - Units: `px`, `%`, `fr` (fraction), `auto`, `minmax()`.
        
- **gap** / `row-gap` / `column-gap` → Space between grid items.
    

## 📌 Example

```css
.container {
  display: grid;
  grid-template-columns: 200px 1fr 2fr;
  grid-template-rows: 100px auto;
  gap: 20px;
}
```

## 🔗 Related Notes

- [[Display Grid]]
    
- [[Grid Placement]]
    
- [[Flex Sizing]]