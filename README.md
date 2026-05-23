# Week 11 – Introduction to Bootstrap Framework

## Activity Title: The Instant Landing Page

This project is a responsive landing page developed using the Bootstrap 5 Framework. The activity demonstrates the use of Bootstrap CDN, responsive navigation bars, hero sections, Bootstrap buttons, and grid layouts.

The landing page is designed for a fictional technology startup called **NTC TechHub**.

---

# Activity Overview

Students moved away from manual Float and Flexbox layouts and used Bootstrap 5 to create responsive websites quickly and efficiently using Bootstrap 5 Framework.

---

# Tools Used

- Visual Studio Code
- Google Chrome / Microsoft Edge
- Bootstrap 5 Framework
- HTML5

---

# Time Allotment

**90 Minutes**

---

# Expected Output

A single-page responsive website featuring:

- Navigation Bar
- Hero Section
- Bootstrap Button
- Responsive Feature Grid
- Footer Section

---

# Project Objectives

The objectives of this activity are:

- Understand Bootstrap 5 Framework
- Use Bootstrap CDN
- Create Responsive Layouts
- Implement Bootstrap Grid System
- Build a Modern Landing Page
- Practice Responsive Web Design

---

# Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Website Structure |
| Bootstrap 5 | Responsive Framework |
| VS Code | Code Editor |
| Browser | Website Testing |

---

# Folder Structure

```plaintext
Week11_Bootstrap_Activity/
│
├── index.html
└── README.md
```

---

# Bootstrap CDN

The project uses Bootstrap 5 CDN.

## Bootstrap CSS CDN

```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/css/bootstrap.min.css" rel="stylesheet">
```

## Bootstrap JavaScript CDN

```html
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/js/bootstrap.bundle.min.js"></script>
```

---

# Features

- Responsive Navbar
- Mobile-Friendly Layout
- Hero Section
- Bootstrap Cards
- Responsive Grid System
- Bootstrap Buttons
- Modern UI Design

---

# Responsive Grid Layout

The project uses the following Bootstrap grid classes:

```html
col-12 col-md-6 col-lg-4
```

## Layout Behavior

| Device | Layout |
|---|---|
| Mobile | 1 Column |
| Tablet | 2 Columns |
| Desktop | 3 Columns |

---

# Complete index.html Code

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <title>NTC TechHub</title>

    <!-- Bootstrap 5 CDN -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>

    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">

        <div class="container">

            <a class="navbar-brand fw-bold" href="#">
                NTC TechHub
            </a>

            <button class="navbar-toggler"
                    type="button"
                    data-bs-toggle="collapse"
                    data-bs-target="#navbarContent">

                <span class="navbar-toggler-icon"></span>

            </button>

            <div class="collapse navbar-collapse" id="navbarContent">

                <ul class="navbar-nav ms-auto">

                    <li class="nav-item">
                        <a class="nav-link active" href="#">
                            Home
                        </a>
                    </li>

                    <li class="nav-item">
                        <a class="nav-link" href="#">
                            Features
                        </a>
                    </li>

                    <li class="nav-item">
                        <a class="nav-link" href="#">
                            Contact
                        </a>
                    </li>

                </ul>

            </div>

        </div>

    </nav>

    <!-- Hero Section -->
    <div class="container-fluid bg-light py-5 text-center">

        <div class="container">

            <h1 class="display-4 fw-bold">
                Welcome to NTC TechHub
            </h1>

            <p class="lead mt-3">
                A modern technology startup creating responsive and innovative digital solutions.
            </p>

            <button class="btn btn-primary btn-lg mt-3">
                Get Started
            </button>

        </div>

    </div>

    <!-- Features Section -->
    <div class="container my-5">

        <div class="row g-4">

            <!-- Feature 1 -->
            <div class="col-12 col-md-6 col-lg-4">

                <div class="card h-100 shadow-sm">

                    <div class="card-body text-center">

                        <h3 class="card-title">
                            Responsive Design
                        </h3>

                        <p class="card-text">
                            Build websites that automatically adjust to mobile, tablet, and desktop devices.
                        </p>

                    </div>

                </div>

            </div>

            <!-- Feature 2 -->
            <div class="col-12 col-md-6 col-lg-4">

                <div class="card h-100 shadow-sm">

                    <div class="card-body text-center">

                        <h3 class="card-title">
                            Fast Development
                        </h3>

                        <p class="card-text">
                            Use Bootstrap components and utilities to create professional layouts quickly.
                        </p>

                    </div>

                </div>

            </div>

            <!-- Feature 3 -->
            <div class="col-12 col-md-6 col-lg-4">

                <div class="card h-100 shadow-sm">

                    <div class="card-body text-center">

                        <h3 class="card-title">
                            Modern UI
                        </h3>

                        <p class="card-text">
                            Create clean and modern user interfaces with Bootstrap 5 framework tools.
                        </p>

                    </div>

                </div>

            </div>

        </div>

    </div>

    <!-- Footer -->
    <footer class="bg-dark text-light text-center py-3">

        <p class="mb-0">
            © 2026 NTC TechHub. All Rights Reserved.
        </p>

    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
```

---

# Bootstrap Classes Used

| Class | Purpose |
|---|---|
| navbar | Navigation Bar |
| navbar-expand-lg | Responsive Navbar |
| navbar-dark | Light Navbar Text |
| bg-dark | Dark Background |
| container | Responsive Container |
| container-fluid | Full Width Container |
| py-5 | Vertical Padding |
| text-center | Center Text |
| btn | Bootstrap Button |
| btn-primary | Blue Button |
| btn-lg | Large Button |
| row | Bootstrap Row |
| col-12 | Full Width on Mobile |
| col-md-6 | 2 Columns on Tablet |
| col-lg-4 | 3 Columns on Desktop |
| card | Bootstrap Card |
| shadow-sm | Small Shadow |

---

# How to Run the Project

1. Open Visual Studio Code

2. Create a folder named:

```plaintext
Week11_Bootstrap_Activity
```

3. Create a file named:

```plaintext
index.html
```

4. Copy the provided HTML code

5. Save the file

6. Open the file in your browser

---

# GitHub Repository Setup

## Steps to Upload the Project to GitHub

1. Open GitHub

2. Click **New Repository**

3. Repository Name:

```plaintext
Week11_Bootstrap_Activity
```

4. Click **Create Repository**

5. Upload the following files:

- `index.html`
- `README.md`

6. Commit the files

7. Open the repository to view the uploaded project

---

# Website Sections Explanation

## 1. Navigation Bar

The Navigation Bar allows users to navigate through the landing page sections.

### Bootstrap Classes Used

| Class | Function |
|---|---|
| navbar | Creates navigation bar |
| navbar-expand-lg | Expands navbar on large screens |
| navbar-dark | Uses light text color |
| bg-dark | Applies dark background |
| navbar-toggler | Creates mobile menu button |

---

## 2. Hero Section

The Hero Section introduces the website and contains a call-to-action button.

### Bootstrap Classes Used

| Class | Function |
|---|---|
| container-fluid | Full-width section |
| bg-light | Light background |
| py-5 | Vertical spacing |
| text-center | Centers content |
| display-4 | Large heading |
| lead | Large paragraph text |
| btn | Bootstrap button |
| btn-primary | Blue button style |

---

## 3. Feature Cards Section

The Features Section displays the main services or advantages of the website.

### Bootstrap Classes Used

| Class | Function |
|---|---|
| row | Creates Bootstrap row |
| g-4 | Adds spacing between columns |
| col-12 | Full width on mobile |
| col-md-6 | 2 columns on tablet |
| col-lg-4 | 3 columns on desktop |
| card | Creates card layout |
| card-body | Card content container |
| shadow-sm | Small card shadow |

---

## 4. Footer Section

The Footer contains copyright information.

### Bootstrap Classes Used

| Class | Function |
|---|---|
| bg-dark | Dark background |
| text-light | Light text color |
| text-center | Center alignment |
| py-3 | Vertical padding |

---

# Mobile Responsiveness

Bootstrap 5 automatically adjusts layouts depending on screen size.

## Responsive Breakpoints

| Breakpoint | Screen Size |
|---|---|
| col-12 | Mobile Devices |
| col-md-6 | Tablets |
| col-lg-4 | Desktop Screens |

---

# Advantages of Bootstrap 5

- Faster Website Development
- Mobile-First Design
- Easy Responsive Layouts
- Built-in Components
- Modern UI Design
- Cross-Browser Compatibility
- Easy Grid System

---

# Common Bootstrap Components

## Buttons

```html
<button class="btn btn-primary">
    Primary Button
</button>
```

## Cards

```html
<div class="card">
    <div class="card-body">
        Card Content
    </div>
</div>
```

## Containers

```html
<div class="container">
    Content Here
</div>
```

---

# Bootstrap Utility Classes

| Utility Class | Purpose |
|---|---|
| mt-3 | Margin Top |
| mb-0 | Margin Bottom |
| py-5 | Vertical Padding |
| text-center | Center Text |
| fw-bold | Bold Font |
| shadow-sm | Small Shadow |

---

# Testing the Website

## Desktop Testing

- Open the website in Chrome or Edge
- Resize the browser window
- Observe responsive layout changes

## Mobile Testing

1. Right-click the browser
2. Select **Inspect**
3. Click **Toggle Device Toolbar**
4. Choose a mobile device

---

# Troubleshooting

## Bootstrap Design Not Appearing

### Possible Cause

Bootstrap CDN is missing.

### Solution

Check if the Bootstrap CSS CDN is included inside the `<head>` section.

```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/css/bootstrap.min.css" rel="stylesheet">
```

---

## Navbar Toggle Not Working

### Possible Cause

Bootstrap JavaScript CDN is missing.

### Solution

Add the Bootstrap Bundle JS before the closing `</body>` tag.

```html
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/js/bootstrap.bundle.min.js"></script>
```

---

# Screenshots to Include

Take screenshots of the following:

1. Navbar
2. Hero Section
3. Mobile View
4. Tablet View
5. Desktop View
6. Feature Cards
7. Full Landing Page

---

# Learning Outcomes

This activity helped develop skills in:

- Bootstrap Framework
- Responsive Design
- Bootstrap Grid System
- Modern UI Development
- Navigation Bar Design
- Hero Section Design
- Mobile-Friendly Layouts

---

# Sample Workflow

```plaintext
START
   ↓
Create Project Folder
   ↓
Create index.html
   ↓
Add Bootstrap CDN
   ↓
Create Navbar
   ↓
Create Hero Section
   ↓
Create Responsive Grid
   ↓
Add Footer
   ↓
Run Website
   ↓
END
```

---

# Sample Output Description

The final website output should contain:

- A dark responsive navigation bar
- A hero section with heading and button
- Three responsive Bootstrap cards
- A clean footer section
- Mobile-friendly responsive design

---

# Conclusion

The activity successfully demonstrated how Bootstrap 5 simplifies responsive web development. The landing page showed proper usage of Bootstrap components, responsive grid layouts, and modern web design principles.

The project also improved understanding of mobile-first development and Bootstrap utility classes.

---

# Future Improvements

- Add Animation Effects
- Add Contact Form
- Add Carousel Section
- Add Pricing Section
- Add Dark Mode
- Add Login Page
- Improve UI Design

---

# References

- Bootstrap Official Documentation
- HTML5 Documentation
- Visual Studio Code Documentation

---

# Submitted By

| Information | Details |
|---|---|
| Name | __________________ |
| Course & Section | __________________ |
| Instructor | __________________ |
| Date Submitted | __________________ |

---

# Author

## Student Information

| Information | Details |
|---|---|
| Student Name | Joezainne Melitante |
| Course/Section | 2.1 BSIT |
| Instructor | Mr. Edward James V. Grageda |
| School | National Teachers College |
| Submission Date | May 23, 2026 |

---

# License

This project is for educational purposes only.

---
