# 🎨 Flex Layout

## 📖 Overview

- Flexbox controls **alignment and distribution** of flex items along two axes:
    
    - **Main Axis** (defined by [[Flex Direction]])
        
    - **Cross Axis** (perpendicular to main axis).
        

## 💡 Properties

- **justify-content** (main axis)
    
    - `flex-start`, `center`, `flex-end`, `space-between`, `space-around`, `space-evenly`.
        
- **align-items** (cross axis)
    
    - `flex-start`, `center`, `flex-end`, `stretch`, `baseline`.
        
- **align-content** → controls multiple rows.
    

## 📌 Example

```css
.container {
  display: flex;
  justify-content: center;
  align-items: center;
}
```

## 🔗 Related Notes

- [[Display: Flex]]
    
- [[Flex Direction]]
    
- [[Flex Sizing]]