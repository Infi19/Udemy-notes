# 🌊 The Cascade - Specificity and Inheritance

## 📖 Overview

- **Cascade** determines how conflicting CSS rules are applied.
    
- Three key factors: **specificity**, **importance**, and **order**.
    

## 💡 Key Concepts

- **Specificity** → Which selector is more “powerful.”
    
    - Inline styles > ID selectors > Class selectors > Type selectors.
        
- **Inheritance** → Some properties (like `color`, `font`) are passed down to child elements.
    
- **!important** → Overrides all other rules (use sparingly 🚨).
    
- **Order of Rules** → If two rules have same specificity, the **last one wins**.
    

## 📌 Example

```css
/* Type selector */
p { color: blue; }

/* Class selector (higher specificity) */
.intro { color: green; }

/* ID selector (highest specificity before inline) */
#main { color: red; }

/* Inline (overrides all) */
<p id="main" class="intro" style="color: purple;">Hello</p>
```

## 🔗 Related Notes

- [[CSS Selectors]]
    
- [[Combining CSS Selectors]]
    
- [[Font Properties]]