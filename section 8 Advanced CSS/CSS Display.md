# 🖼️ CSS Display

## 📖 Overview

- The **display** property defines how an element is shown on the page.
    
- Controls layout behavior of [[HTML]] elements.
    

## 💡 Common Values

- **block** → Takes full width, starts on new line (`div`, `p`).
    
- **inline** → Flows with text, only takes necessary space (`span`, `a`).
    
- **inline-block** → Inline but respects width/height.
    
- **none** → Hides the element (not just invisible, it’s removed from flow).
    
- **flex** → Enables [[Flexbox Layout]].
    
- **grid** → Enables [[CSS Grid Layout]].
    

## 📌 Example

```css
div {
  display: block;
}

span {
  display: inline;
}

nav {
  display: flex;
}
```

## 🔗 Related Notes

- [[CSS Float]]
    
- [[CSS Positioning]]
    
- [[Flexbox Layout]]
    
- [[CSS Grid Layout]]