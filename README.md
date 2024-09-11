# Sushiman - Sushi Selling & Home Delivery Website

## Overview
**Sushiman** is a sleek, responsive website for ordering sushi online with a home delivery service. The website is built entirely using **HTML** and **CSS** with the **BEM (Block Element Modifier)** methodology to maintain clean, modular, and scalable code. 

This project focuses on a minimalistic design with smooth navigation to provide an effortless sushi ordering experience for users.

## Features
- **Responsive Layout:** Adapts seamlessly to different screen sizes, from desktops to mobile devices.
- **BEM Methodology:** Ensures that the codebase is structured, easy to maintain, and scalable.
- **Simple Navigation:** Users can easily browse through the menu, add items to their cart, and complete the order.
- **Delivery Feature:** Emphasizes home delivery for sushi orders.
- **CSS-Only Styling:** All visual elements are styled with CSS, without any frameworks or libraries.

## Technologies Used
- **HTML5:** Used for creating the structure and content of the website.
- **CSS3:** For styling and layout, using modern CSS features like Flexbox.
- **BEM Naming Convention:** For writing modular and maintainable CSS code.
  
## BEM Naming Convention
Here is a quick reference to the BEM naming scheme used in this project:
- **Block:** Represents a standalone entity (e.g., `menu`, `header`, `footer`).
- **Element:** A component of a block, separated by double underscores (e.g., `menu__item`, `header__logo`).
- **Modifier:** A flag on a block or element, separated by double hyphens (e.g., `menu__item--active`, `button--primary`).

Example:
```html
<div class="menu">
  <div class="menu__item menu__item--active">
    Sushi Roll
  </div>
</div>
