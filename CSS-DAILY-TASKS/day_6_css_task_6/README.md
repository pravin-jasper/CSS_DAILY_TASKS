#  3D Product Showcase

A beginner-friendly **3D Product Showcase** website created using **HTML and CSS**.

This project demonstrates **CSS 3D transforms, animations, transitions, Flexbox, CSS Grid, and responsive design using media queries**.

> This is a frontend practice project created for learning CSS.

---

##  Project Description

The **3D Product Showcase** displays a modern technology product with a 3D animated hero section and multiple product cards.

The main product uses CSS `perspective`, `rotateX()`, `rotateY()`, `scale()`, and animations to create a 3D effect.

The website also includes responsive layouts for **desktop, tablet, and mobile screens**.

---

##  Technologies Used

* HTML5
* CSS3

No JavaScript is used in this project.

---

##  Features

*  3D product showcase
*  CSS animations
*  CSS transitions
*  3D transforms
*  CSS perspective
*  Hover effects
*  Product cards
*  CSS Grid
*  Flexbox
*  Responsive design
*  Desktop layout
*  Tablet layout
*  Mobile layout
*  Gradient backgrounds
*  Product sections
*  Feature section
*  Add to Cart buttons

---

## 🎨 CSS Concepts Used

### 1. Flexbox

Flexbox is used for the navigation bar, hero section, and features.

```css
.feature-container {
    display: flex;
    justify-content: center;
    gap: 30px;
}
```

---

### 2. CSS Grid

CSS Grid is used to display the product cards.

```css
.product-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 25px;
}
```

---

### 3. CSS Perspective

The product scene uses perspective to create a 3D environment.

```css
.product-scene {
    perspective: 800px;
}
```

---

### 4. 3D Transform

The main product is rotated in 3D space.

```css
.product {
    transform:
        rotateX(10deg)
        rotateY(-20deg);
}
```

---

### 5. Hover Animation

When the user moves the mouse over the product, it rotates and becomes larger.

```css
.product:hover {
    transform:
        rotateX(0deg)
        rotateY(25deg)
        scale(1.1);
}
```

---

### 6. CSS Animation

The main product continuously floats up and down.

```css
@keyframes floating {

    0% {
        transform:
            rotateX(10deg)
            rotateY(-20deg)
            translateY(0);
    }

    50% {
        transform:
            rotateX(10deg)
            rotateY(-20deg)
            translateY(-20px);
    }

    100% {
        transform:
            rotateX(10deg)
            rotateY(-20deg)
            translateY(0);
    }
}
```

---

##  Responsive Design

The project uses CSS media queries to adjust the layout for different screen sizes.

###  Desktop

For screens larger than `900px`:

```css
.product-grid {
    grid-template-columns: repeat(4, 1fr);
}
```

The products are displayed in **4 columns**.

---

###  Tablet

For screens up to `900px`:

```css
@media (max-width: 900px) {

    .product-grid {
        grid-template-columns: repeat(2, 1fr);
    }

}
```

The products are displayed in **2 columns**.

---

### 📱 Mobile

For screens up to `600px`:

```css
@media (max-width: 600px) {

    .product-grid {
        grid-template-columns: 1fr;
    }

}
```

The products are displayed in **1 column**.

---

##  Project Structure

```text
3D-Product-Showcase/
│
├── index.html
├── style.css
└── README.md
```

---

##  How to Run

1. Download or clone the project.
2. Open the project folder.
3. Open `index.html` in a web browser.
4. Move your mouse over the product and cards to see the CSS effects.
5. Resize the browser window to test the responsive design.

---

##  Project Sections

### Navigation Bar

Contains:

* TechStore logo
* Home
* Products
* About
* Contact
* Cart button

### Hero Section

Contains:

* New Arrival text
* Product heading
* Product description
* Buy Now button
* 3D product
* Floating animation

### Featured Products

Contains:

* Headphones
* Smart Watch
* Smartphone
* Laptop
* Product prices
* Add to Cart buttons

### Features

Contains:

* Free Delivery
* Secure Payment
* Quality Products

### Footer

Contains the copyright information.

---

## 🎯 Learning Objectives

This project helps beginners understand:

* HTML page structure
* CSS styling
* Flexbox
* CSS Grid
* Responsive design
* Media queries
* CSS transitions
* CSS animations
* CSS transforms
* 3D perspective
* Hover effects
* Gradients
* Box shadows
* Responsive layouts

---

## 🔮 Future Improvements

The project can be improved by adding:

* JavaScript shopping cart
* Product details page
* Product search
* Product filtering
* Image-based products
* Login and registration
* Dark/light mode
* More 3D effects
* Product carousel
* Checkout page

---


