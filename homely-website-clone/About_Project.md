**Live Demo:**
[View Live Project](https://assignment-1-liart-mu.vercel.app/)


<img src="./assest/live_preview.png" alt="Pokémon Gen I — Pikachu UI" width="100%">

---

## 🏡 Homely — Real Estate & Accommodation UI Recreation

## 📌 Project Overview

Project Type: Frontend UI / Real Estate Accommodation Landing Page

This project is a frontend UI recreation project built from scratch using HTML5 and CSS3, with a focus on creating a modern real-estate and accommodation interface.

The interface presents a fictional property platform named Homely, combining a navigation bar, hero section, accommodation cards, property information, pricing details, amenities, and booking-oriented UI elements into a single scrolling layout.

The primary objective of this project was to strengthen fundamental frontend development skills by practicing Flexbox, spacing, sizing, positioning, background images, typography, reusable layout patterns, hover effects, and visual composition using core CSS.

The project also integrates Remix Icon through its CDN for interface icons and uses image assets from local files and Unsplash for accommodation imagery.

---


## 🎯 Project Objective

The project was created as a practical exercise to understand how different UI sections can be structured and visually composed into a polished accommodation website.

## Main Focus

* HTML5 page structure
* CSS3 styling and layout
* Flexbox
* Responsive-width concepts using flex
* calc() for section sizing
* Background images
* Image positioning with background-size and background-position
* Spacing with padding, margin, gap
* Border radius and visual hierarchy
* Absolute positioning
* Hover interactions
* CSS transitions
* Box shadows
* Typography and sizing
* Icon integration using Remix Icon
* Accommodation card composition
* Property pricing and information layouts

---

## 🛠️ Technologies Used

### Technology

* **HTML5** — Page structure and semantic organization
* **CSS3** — Styling, layout, spacing, and visual presentation
* **Flexbox** — Navigation, hero layout, cards, and content alignment
* **CSS calc()** — Dynamic section height calculation
* **CSS Background Images** — Property and accommodation visuals
* **Remix Icon** — Navigation, rating, arrow, furniture, and amenities icons
* **PNG / Image Assets** — Branding and property imagery
* **Unsplash Images** — Accommodation photographs

---

## 📊 Project Metrics

1 HTML document

1 CSS stylesheet

5 major HTML content sections

3 primary navigation groups

6 navigation links

2 primary hero action buttons

4 trusted-company logo images

2 accommodation preview cards

1 featured accommodation panel

4 accommodation category filters

2 property-detail content blocks

4 basic property information rows per detail block

2 amenity / service content items per booking panel

2 pricing variants shown in the property detail UI

1 primary booking button per booking panel

1 Remix Icon CDN integration

Multiple hover and transition interactions

* 12px main page side padding
* 55px main page horizontal padding
* 45px navigation height
* 60px hero heading size
* 70px accommodation heading size
* 25px card gap used in multiple layouts
* 20px primary content gap in the hero section

🧩 Key CSS Concepts Implemented

1. Flexbox Layout

Flexbox is the primary layout system used throughout the project.

For example:

nav {
    height: 45px;
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
}

This allows the navigation logo, menu links, and action buttons to remain separated into their respective areas.

* Hero layout
* Navigation links
* Button groups
* Property cards
* Accommodation categories
* Amenities
* Text and image combinations

2. Flexible Column Sizing

The hero section divides the available space between the text and image areas using different flex values:

#s1 .left {
    flex: 1;
}

#s1 .right {
    flex: 1.5;
}

This creates a larger visual area for the accommodation image while keeping the text section compact.

3. Dynamic Height with calc()

The hero section uses calc() to derive its available height from the navigation height:

#s1 {
    height: calc(100% - 45px);
}

This helps the hero section occupy the remaining vertical space after the navigation area.

4. Background Image Composition

The main hero image is implemented with a CSS background image:

#s1 .right {
    background-image: url(./assest/room1.png);
    background-size: 100% 100%;
    background-position: center;
    background-repeat: no-repeat;
}

This demonstrates how a visual section can be created without placing an <img> element directly inside the layout.

5. Image-Based Accommodation Cards

The accommodation cards use regular image elements:

.flat img {
    width: 100%;
    flex: 1;
    border-radius: 12px;
}

This allows the property image to expand within its card while maintaining the rounded visual style used across the interface.

6. Absolute Positioning

The rating badge on accommodation cards is positioned independently from the normal document flow:

.fstar {
    position: absolute;
    width: 25px;
    height: 25px;
    background-color: #FDFEFE;
    border-radius: 50%;
    top: 10px;
    left: 250px;
}

The parent card uses:

.flat {
    position: relative;
}

This creates the positioning relationship required for the rating indicator.

7. Hover Effects and Transitions

Interactive elements use hover states to provide visual feedback.

Navigation links change color and add a glow-like text shadow:

nav .n2 a {
    color: black;
    transition: color 0.25s ease, text-shadow 0.25s ease;
}

nav .n2 a:hover {
    color: #D89B2B;
    text-shadow:
        0 0 4px rgba(216, 155, 43, 0.9),
        0 0 10px rgba(216, 155, 43, 0.7),
        0 0 20px rgba(216, 155, 43, 0.5),
        0 0 35px rgba(216, 155, 43, 0.3);
}

The accommodation filter items also use transition and transform effects:

#s4 p {
    border-radius: 5px;
    transition:
        background-color 0.25s ease,
        box-shadow 0.25s ease,
        transform 0.25s ease;
}

#s4 p:hover {
    background-color: white;
    cursor: pointer;
    transform: translateY(-2px);
}

8. Box Shadow for Depth

Property information cards use shadows to visually separate them from the surrounding interface:

.s5div {
    background-color: white;
    box-shadow: rgba(149, 157, 165, 0.2) 0px 8px 24px;
}

This adds depth while keeping the overall UI minimal.

9. Rounded UI Elements

The interface consistently uses rounded corners and pill-shaped controls:

border-radius: 30px;

This styling is used for navigation buttons, rating elements, hero controls, and other interactive components.

---

## 🎨 UI Components

The interface contains several visually distinct components:

* Homely Brand / Logo Area
* Top Navigation Menu
* Login and Contact Buttons
* Hero Rating Badge
* Hero Heading
* Hero Description
* Primary CTA Buttons
* Trusted Company Logos
* Accommodation Preview Cards
* Featured Accommodation Panel
* Accommodation Category Filters
* Property Rating Badge
* Property Description / Host Area
* Property Pricing
* Basic Property Information
* Cleanliness Information
* Amenities Information
* Book Now Button

---


## 🧠 Key Learnings

* This project helped reinforce several important frontend concepts:

* Structuring a multi-section webpage with HTML5

* Building layouts using Flexbox

* Understanding how flex: 1 and different flex values affect available space

* Using calc() for section sizing

* Combining position: relative and position: absolute

* Working with CSS background images

* Controlling image size and positioning

* Using gap, padding, and margin for consistent spacing

* Creating pill-shaped buttons and badges

* Using border-radius for modern UI styling

* Applying box shadows to create depth

* Creating hover interactions with transitions

* Using transform: translateY() for micro-interactions

* Integrating external icon libraries through a CDN

* Combining content, imagery, pricing, and property information into a single UI

* Translating a visual reference into reusable HTML/CSS structures

---


## 🔍 Development Approach

The project was developed through an iterative frontend design process:

Reference / Design Idea
        ↓
Analyze Layout
        ↓
Create HTML Structure
        ↓
Build Navigation
        ↓
Create Hero Section
        ↓
Add Accommodation Cards
        ↓
Build Property Information Layout
        ↓
Style Typography & Spacing
        ↓
Add Icons & Images
        ↓
Implement Hover Effects
        ↓
Refine Visual Composition

The focus was not only on making the page visually appealing, but also on understanding how each layout and styling property contributes to the final UI.

---


## 📁 Project Structure

Homely/
│
├── index.html
├── style.css
│
└── assest/
    ├── room1.png
    ├── logos/
    │   ├── samsonite-logo.png
    │   ├── airbnb-logo.png
    │   ├── emirates-logo.png
    │   └── united-travel-logo.png
    └── ...

The project also references accommodation images hosted through Unsplash URLs directly inside the HTML/CSS.

---


## 🚀 Future Improvements

* Potential improvements for future iterations:

* Add full responsive layouts for mobile, tablet, and desktop screens

* Add a functional hamburger menu for smaller screens

* Add JavaScript interactions for navigation and booking

* Make accommodation cards reusable and data-driven

* Add functional login and contact forms

* Add real property search and filtering

* Add image sliders or property galleries

* Add smooth scrolling between sections

* Improve accessibility and semantic HTML usage

* Replace placeholder content with real accommodation data

* Optimize locally hosted and external images

* Add backend support for bookings and property management

* Convert repeated property layouts into reusable components

---


## 📌 Project Type

Frontend UI Recreation / Real Estate & Accommodation Landing Page

Core Skills Demonstrated

HTML5 · CSS3 · Flexbox · CSS Positioning · Background Images · UI Recreation · Typography · Layout Design · Hover Effects · Visual Composition · Remix Icon