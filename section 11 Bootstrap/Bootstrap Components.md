# 🎨 Bootstrap Components

## 📖 Overview

- Bootstrap provides **ready-to-use UI components** to build modern websites faster 🚀.
    
- Most components are **customizable** via classes and JavaScript options.
    

## 💡 Common Components

### 🔘 Buttons

- Variants: `.btn-primary`, `.btn-success`, `.btn-danger`, `.btn-outline-*`.
    

```html
<button class="btn btn-primary">Click Me</button>
```

### 📌 Navbar

- Responsive navigation header.
    

```html
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">Brand</a>
</nav>
```
### 📑 Cards

- Flexible content container.
    

```html
<div class="card" style="width: 18rem;">
  <img src="img.jpg" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">Card Title</h5>
    <p class="card-text">Some text inside.</p>
    <a href="#" class="btn btn-primary">Go</a>
  </div>
</div>
```

### 📦 Forms

- Simplifies form styling.
    

```html
<form>
  <input type="email" class="form-control" placeholder="Enter email">
</form>
```

### 🪟 Modals

- Popup dialogs requiring JS.
    

```html
<div class="modal" id="myModal">
  <div class="modal-dialog">
    <div class="modal-content">
      <p>Modal Content</p>
    </div>
  </div>
</div>
```

### 🎠 Carousel

- Image/content slideshow with controls.
    

```html
<div id="carouselExample" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="img1.jpg" class="d-block w-100" alt="...">
    </div>
  </div>
</div>
```

## 📌 Other Components

- **Alerts** → `.alert-success`, `.alert-danger`.
    
- **Dropdowns** → `.dropdown-toggle`.
    
- **Badges & Pills** → `.badge`, `.rounded-pill`.
    
- **Accordion/Collapse** → Expandable sections.
    

## 🔗 Related Notes

- [[Bootstrap Layout]]
    
- [[What is Bootstrap]]
    
- [[CSS Positioning]]