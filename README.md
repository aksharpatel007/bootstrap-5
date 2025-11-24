# 📘 Bootstrap Cheatsheet

A clean and developer-friendly **Bootstrap 5 Cheatsheet** with installation steps, layout guides, utilities, and examples. Use this README directly in your GitHub repository.

---

## 🚀 Overview

This cheatsheet provides a quick reference for commonly used **Bootstrap utilities, components, and layout rules**. It's ideal for beginners and professionals needing a fast lookup while building responsive websites.

---

## 📦 Installation

### **Using CDN**

```html
<!-- CSS -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- JS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
```

### **Using NPM**

```bash
npm install bootstrap
```

---

## 🎨 Colors

Common Bootstrap text & background color classes:

```
text-primary    bg-primary
text-secondary  bg-secondary
text-success    bg-success
text-danger     bg-danger
text-warning    bg-warning
text-info       bg-info
text-light      bg-light
text-dark       bg-dark
```

---

## 📐 Spacing Utilities

Use `m` for margin, `p` for padding.

```
m-0  m-1  m-2  m-3  m-4  m-5
p-0  p-1  p-2  p-3  p-4  p-5
mt-3 mb-3 ms-3 me-3
pt-3 pb-3 ps-3 pe-3
mx-auto my-4 px-4 py-2
```

---

## 📏 Display Utilities

```
d-none
d-block
d-inline
d-inline-block
d-flex
d-grid
d-md-block
d-lg-none
```

---

## ✍️ Typography

```
h1-h6     Text headings
lead      Larger subtitle text
fw-bold   Bold text
fw-light  Light text
text-uppercase
text-center
```

---

## 🧱 Grid System

### **Basic Layout**

```html
<div class="container">
  <div class="row">
    <div class="col">Column 1</div>
    <div class="col">Column 2</div>
    <div class="col">Column 3</div>
  </div>
</div>
```

### **Column Sizes**

```
col-4       (mobile full width)
col-sm-6
col-md-4
col-lg-3
col-xl-2
```

### **Grid Alignment**

```
justify-content-center
align-items-center
g-3 (grid gap)
```

---

## 🎛 Buttons

```html
btn btn-primary
btn btn-outline-success
btn-lg
btn-sm
w-100
```

---

## 🧩 Forms

```html
<form>
  <input class="form-control" placeholder="Enter text">
  <select class="form-select mt-2"></select>
  <button class="btn btn-primary mt-3">Submit</button>
</form>
```

---

## 🟦 Cards

```html
<div class="card" style="width: 18rem;">
  <img src="img.jpg" class="card-img-top">
  <div class="card-body">
    <h5 class="card-title">Card Title</h5>
    <p class="card-text">Description text goes here.</p>
    <button class="btn btn-dark">Read More</button>
  </div>
</div>
```

---

## ⚙️ Flex Utilities

```
d-flex
flex-row
flex-column
justify-content-between
align-items-center
gap-3
```

---

## 🧭 Navbar Example

```html
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Brand</a>

    <button class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#menu">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="menu">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
        <li class="nav-item"><a class="nav-link" href="#">About</a></li>
      </ul>
    </div>
  </div>
</nav>
```

---

## 🔗 Additional Resources

* Official Docs: [https://getbootstrap.com](https://getbootstrap.com)
* Bootstrap Icons: [https://icons.getbootstrap.com](https://icons.getbootstrap.com)

---

## ⭐ Contributing

Feel free to fork this repository and submit improvements, examples, or additional UI components.

---

### 💙 Enjoy building with Bootstrap!
