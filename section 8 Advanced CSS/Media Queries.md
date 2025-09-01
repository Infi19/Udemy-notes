# 📐 Media Queries

## 📖 Overview

- **Media Queries** allow CSS to respond to **device characteristics** like screen size, resolution, or orientation.
    
- Core feature of **responsive design**.
    

## 💡 Key Concepts

- Syntax:
    
    ```css
    @media (condition) {
  /* styles here */
    ```
    
- Common conditions:
    
    - `max-width` → Target screens smaller than given width.
        
    - `min-width` → Target screens larger than given width.
        
    - `orientation: portrait/landscape`.
        

## 📌 Example

```css
/* Mobile first design */
body {
  font-size: 16px;
}

@media (min-width: 768px) {
  body {
    font-size: 18px;
  }
}

@media (min-width: 1024px) {
  body {
    font-size: 20px;
  }
}
```

## 🔗 Related Notes

- [[How to Create Responsive Websites]]
    
- [[CSS Display]]
    
- [[Flexbox Layout]]
    
- [[CSS Grid Layout]]