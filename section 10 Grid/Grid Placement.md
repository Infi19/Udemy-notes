# 📍 Grid Placement

## 📖 Overview

- Defines **where grid items are positioned** inside the grid.
    

## 💡 Key Properties

- **grid-column-start / grid-column-end**
    
- **grid-row-start / grid-row-end**
    
- **grid-column** shorthand → `grid-column: 1 / 3;`
    
- **grid-row** shorthand → `grid-row: 2 / 4;`
    

## 📌 Example

```css
.item1 {
  grid-column: 1 / 3; /* spans 2 columns */
  grid-row: 1 / 2;    /* stays in first row */
}

.item2 {
  grid-column: 3 / 4;
  grid-row: 1 / 3;    /* spans 2 rows */
}
```

## 🔗 Related Notes

- [[Display Grid]]
    
- [[Grid Sizing]]
    
- [[CSS Positioning]]