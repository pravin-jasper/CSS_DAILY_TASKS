#  LearnHub – Online Learning Platform

LearnHub is a beginner-friendly **Online Learning Platform UI** built using **HTML and CSS**.

The project contains **3 pages** and demonstrates modern CSS concepts such as **CSS Grid, Flexbox, animations, transitions, progress bars, cards, and responsive design**.

---

##  Project Overview

LearnHub is designed like an online education website where students can:

* Explore available courses
* View popular courses
* Check course progress
* View their learning dashboard
* Read student reviews
* See recent learning activity
* Subscribe to a newsletter

This project focuses mainly on practicing **HTML structure and CSS styling**.

---

##  Project Structure

```text
LearnHub/
│
├── index.html
├── courses.html
├── dashboard.html
├── style.css
└── README.md
```

---

##  Pages

### 1. Home Page – `index.html`

The home page contains 6 main sections:

1. Hero / Introduction
2. Popular Courses
3. Why Learn With Us
4. Student Progress
5. Student Reviews
6. Newsletter & Footer

---

### 2.  Courses Page – `courses.html`

The courses page displays different learning courses.

Features include:

* Course cards
* Course images
* Course categories
* Instructor information
* Course ratings
* Course prices
* Category filter UI

Example courses:

* HTML & CSS Mastery
* JavaScript Basics
* UI/UX Design
* Python Programming
* React Development
* Digital Marketing

---

### 3.  Dashboard – `dashboard.html`

The dashboard represents a student's learning area.

It includes:

* Learning streak
* Total courses
* Completed courses
* Learning hours
* Continue learning section
* Course progress bars
* Recent activity

---

##  CSS Concepts Used

This project demonstrates several important CSS concepts.

### CSS Grid

Grid is used for layouts such as course cards and dashboard cards.

```css
.course-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 25px;
}
```

---

### Flexbox

Flexbox is used for navigation, features, and other horizontal layouts.

```css
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
}
```

---

### Progress Bars

Course progress is represented using CSS progress bars.

```css
.progress-fill {
    width: 75%;
}
```

Different widths can represent different learning progress.

---

### CSS Animations

Floating elements use CSS animation.

```css
@keyframes floating {
    0% {
        transform: translateY(0);
    }

    50% {
        transform: translateY(-15px);
    }

    100% {
        transform: translateY(0);
    }
}
```

---

### CSS Transitions

Cards and buttons use transitions for smoother hover effects.

```css
.course-card {
    transition: 0.3s;
}

.course-card:hover {
    transform: translateY(-8px);
}
```

---

### Responsive Design

Media queries are used to make the website work better on different screen sizes.

```css
@media (max-width: 1000px) {
    .course-grid {
        grid-template-columns: repeat(2, 1fr);
    }
}
```

For smaller screens:

```css
@media (max-width: 700px) {
    .course-grid {
        grid-template-columns: 1fr;
    }
}
```

---

##  Main Features

*  Online learning platform design
*  Course cards
*  Student dashboard
*  Course progress bars
*  Student reviews
*  Modern UI design
*  CSS Grid layouts
*  Flexbox layouts
*  CSS animations
*  CSS transitions
*  Responsive design
*  Multi-page website

---

##  Technologies Used

| Technology     | Purpose                         |
| -------------- | ------------------------------- |
| HTML5          | Website structure               |
| CSS3           | Styling and layouts             |
| CSS Grid       | Course and dashboard layouts    |
| Flexbox        | Navigation and flexible layouts |
| CSS Animation  | Floating and entrance effects   |
| CSS Transition | Hover effects                   |
| Media Queries  | Responsive design               |

---

##  Responsive Breakpoints

The project uses two main breakpoints:

### Tablet

```css
@media (max-width: 1000px)
```

Used to reduce the number of columns and adjust spacing.

### Mobile

```css
@media (max-width: 700px)
```

Used to create single-column layouts and improve mobile navigation.

---

##  Learning Objectives

By completing this project, you can practice:

* Creating multi-page websites
* Writing semantic HTML
* Creating reusable CSS classes
* Building layouts with Grid
* Building layouts with Flexbox
* Creating progress bars
* Using CSS transitions
* Creating CSS animations
* Creating responsive layouts
* Organizing a larger CSS project

---

##  How to Run

### Step 1

Download or clone the project.

### Step 2

Open the project folder.

### Step 3

Open:

```text
index.html
```

in your browser.

You can navigate between:

```text
Home → Courses → Dashboard
```

---

##  Future Improvements

The project can be improved by adding:

* JavaScript course filtering
* Login and registration
* Search functionality
* Real course data
* Video course player
* User profile
* Dark mode
* Course enrollment system
* Backend/database
* Real authentication
* Payment integration

---

##  Project Purpose

This project is created for **HTML and CSS practice** and is suitable for beginners who want to build a larger multi-page website.

It demonstrates how multiple CSS concepts can be combined to create a complete website UI.

---

##  Skills Practiced

```text
HTML
CSS
CSS Grid
Flexbox
Responsive Design
Media Queries
CSS Animation
CSS Transition
Cards
Progress Bars
Multi-page Website
UI Design
```

---

