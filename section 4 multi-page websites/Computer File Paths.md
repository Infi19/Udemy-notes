# 🗂️ Computer File Paths

## 📖 Overview

- A **file path** tells the browser where to find a file 📂.
    
- Important when linking [[Image Elements]], [[Anchor Elements]], or external resources.
    

## 💡 Key Concepts

- **Absolute Path** → Full URL or system location.
    
    - Example: `https://example.com/images/cat.jpg`
        
- **Relative Path** → Location relative to the current file.
    
    - Example: `images/cat.jpg` (inside project folder).
        
- Special notations:
    
    - `./` → Current directory.
        
    - `../` → Move up one directory.
        

## 📌 Example

```html
<!-- Absolute path -->
<img src="https://example.com/images/logo.png" alt="Logo">

<!-- Relative path -->
<img src="images/logo.png" alt="Logo">

<!-- Navigate up one folder -->
<img src="../assets/pic.png" alt="Picture">

```

## 🔗 Related Notes

- [[Image Elements]]
    
- [[Anchor Elements]]
    
- [[What is HTML]]