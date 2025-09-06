# 🧱 Display: Grid

## 📖 Overview

- **CSS Grid** is a two-dimensional layout system (rows + columns).
    
- Enabled by setting `display: grid;` on a container.
    

## 💡 Key Concepts

- Grid container → Parent element.
    
- Grid items → Direct children.
    
- Provides precise control over both **rows** and **columns**.
    

## 📌 Example

```css
.container {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr; /* 3 equal columns */
  grid-template-rows: auto auto;      /* 2 rows */
}
```

## 🔗 Related Notes

- [[Grid Sizing]]
    
- [[Grid Placement]]
    
- [[Flex Layout]]
    
- [[CSS Display]]