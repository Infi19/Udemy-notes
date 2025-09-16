
# 📐 Bootstrap Layout

## 📖 Overview

- Bootstrap uses a **12-column grid system** 📊 for responsive layouts.
    
- Layout adapts to different screen sizes (`xs`, `sm`, `md`, `lg`, `xl`, `xxl`).
    

## 💡 Core Concepts

- **Container** → Wraps site content.
    
    - `.container` → fixed-width.
        
    - `.container-fluid` → full-width.
        
- **Rows & Columns** → Define grid.
    
    - `.row` contains `.col-*` columns.
        
    - Columns auto-stack on small screens.
        
- **Responsive Breakpoints**:
    
    - `col-sm-*` → small (≥576px).
        
    - `col-md-*` → medium (≥768px).
        
    - `col-lg-*` → large (≥992px).
        
    - `col-xl-*` → extra large (≥1200px).
        

## 📌 Example

```html
<div class="container">
  <div class="row">
    <div class="col-md-4">Column 1</div>
    <div class="col-md-4">Column 2</div>
    <div class="col-md-4">Column 3</div>
  </div>
</div>
```

## 🔗 Related Notes

- [[Bootstrap Components]]
    
- [[CSS Grid Layout]]
    
- [[Flex Layout]]