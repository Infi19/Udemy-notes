# 🔗 Combining CSS Selectors

## 📖 Overview

- CSS allows combining selectors to **target specific elements** more precisely.
    
- Helps in writing **cleaner** and **more powerful** styles.
    

## 💡 Common Combinations

- **Descendant Selector** → `div p` (selects `<p>` inside `<div>`).
    
- **Child Selector** → `div > p` (direct child only).
    
- **Adjacent Sibling** → `h1 + p` (selects `<p>` immediately after `<h1>`).
    
- **General Sibling** → `h1 ~ p` (all `<p>` after `<h1>`).
    
- **Multiple Selector** → `h1, h2, p` (applies style to all).
    

## 📌 Example

```css
/* Descendant */
div p { color: blue; }

/* Child */
div > p { font-weight: bold; }

/* Adjacent sibling */
h1 + p { font-style: italic; }

/* General sibling */
h1 ~ p { text-decoration: underline; }
```

## 🔗 Related Notes

- [[CSS Selectors]]
    
- [[The Cascade - Specificity and Inheritance]]
    
- [[CSS Positioning]]