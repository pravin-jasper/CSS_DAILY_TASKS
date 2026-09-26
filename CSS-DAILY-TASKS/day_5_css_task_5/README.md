# 🎬 StrangerJ Landing Page

A simple **Netflix-style movie streaming landing page** created using **HTML and CSS**.

This project is designed for beginners who want to practice CSS layouts, animations, transitions, hover effects, and movie card designs.

> **Note:** This is a practice project inspired by streaming-platform layouts and is not an official Netflix website.

## 📌 Project Description

**MovieFlix** is a movie streaming landing page that includes a navigation bar, hero section, movie cards, trending movies, buttons, animations, and hover effects.

The project focuses mainly on **CSS styling, animations, and transitions**.

## 🛠️ Technologies Used

* HTML5
* CSS3

## ✨ Features

* 🎬 Netflix-style dark theme
* 🧭 Navigation bar
* 🎥 Hero section
* 🍿 Popular Movies section
* 🔥 Trending Now section
* ⭐ Movie ratings
* 🎨 CSS hover effects
* ✨ CSS animations
* 🔄 CSS transitions
* 🔍 Movie card scaling effect
* 📱 Basic webpage layout
* 🚫 No JavaScript
* 🚫 No media queries

## 🎨 CSS Concepts Used

This project demonstrates:

* CSS Flexbox
* `transition`
* `transform`
* `scale()`
* `translateX()`
* `translateY()`
* `@keyframes`
* `animation`
* `:hover`
* `box-shadow`
* `background-image`
* `linear-gradient()`
* `position: sticky`
* Border radius
* CSS colors and typography

## ✨ Animation

The hero content uses a CSS keyframe animation:

```css
@keyframes slideIn {
    from {
        opacity: 0;
        transform: translateX(-80px);
    }

    to {
        opacity: 1;
        transform: translateX(0);
    }
}
```

The movie cards use transitions when the mouse moves over them:

```css
.movie-card:hover {
    transform: translateY(-15px) scale(1.05);
}
```

## 📂 Project Structure

```text
Netflix-Landing-Page/
│
├── index.html
├── style.css
└── README.md
```

## 🚀 How to Run

1. Download or clone this project.
2. Open the project folder.
3. Open `index.html` in your browser.
4. Move your mouse over the navigation links, buttons, and movie cards to see the CSS effects.

## 🎬 Sections

### Navigation Bar

Contains:

* MovieFlix logo
* Home
* Movies
* Series
* My List
* Login button

### Hero Section

Contains:

* Movie title
* Description
* Watch Now button
* More Info button
* Background image
* Slide-in animation

### Popular Movies

Displays movie cards with:

* Movie image
* Movie title
* Rating
* Hover animation

### Trending Now

Displays another collection of movie cards with the same CSS effects.

## 🎯 Learning Objectives

After completing this project, beginners can understand:

* How to create a landing page
* How to create movie cards
* How to use Flexbox
* How CSS transitions work
* How CSS animations work
* How to create hover effects
* How to use `transform`
* How to create a dark-themed website
* How to organize HTML and CSS files

## 🔮 Future Improvements

You can improve this project by adding:

* JavaScript movie search
* Movie categories
* Video player
* Login form
* Dark/light mode
* Responsive design using media queries
* Movie details popup
* Favorite movie functionality

## 👨‍💻 Author

Created as a beginner **HTML & CSS project**.

## ❤️ Thank You

Thanks for checking out **MovieFlix**!

**Watch. Enjoy. Repeat. 🎬🍿**
