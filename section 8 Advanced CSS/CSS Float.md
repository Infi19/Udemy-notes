# 🌊 CSS Float

## 📖 Overview

- The **float** property positions elements to the **left** or **right**.
    
- Commonly used for text wrapping around images 🖼️.
    

## 💡 Key Concepts

- Values: `left`, `right`, `none`.
    
- Floated elements are taken out of normal document flow.
    
- Use `clear` to stop wrapping (`clear: both;`).
    
- Often replaced by [[Flexbox Layout]] and [[CSS Grid Layout]].
    

## 📌 Example

```css
img {
  float: right;
  margin: 10px;
}

p {
  clear: both;
}
```

## 🔗 Related Notes

- [[CSS Display]]
    
- [[CSS Positioning]]
    
- [[Flexbox Layout]]