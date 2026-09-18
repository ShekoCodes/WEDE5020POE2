# WEDE5020POE2
# The Afro Crown Beauty  Official Website Project

## Student Information
* **Student Name:** Nkahosheko Kopa
* **Student ID:** ST10507079
* **Module:** Web Development (WEDE5020)

## Project Overview
This website is designed and developed for **The Afro Crown Beauty**, an afro specialist hair salon and product retail brand established in 2024. The platform captures a rich African aesthetic while delivering modern functionality for client inquiries and product browsing.

## Website Goals and Objectives
* Create a high converting digital storefront for afro hair products and salon services.
* Promote natural hair health with the brand ethos: *"Royalty rooted in crowning the coils"*.
* Facilitate client engagement via structured inquiry forms.

## Key Features
* 7 Semantic HTML7 web pages (`index`, `about`, `shop`, `enquiry`, `contact`, `service`, `booking`).
* Clean visual layout with African-inspired colour palette.
* Multi location contact details.
* Responsive navigation bar.

## Sitemap
* Home (`index.html`)
* About Us (`about.html`)
* Products & Services (`products.html`)
* Inquiries (`enquiry.html`)
* Contact Us (`contact.html`)
* Shop (`shop.html`)
* Booking (`booking.html`)

## Changelog
### [Part 1] - Initial Release
* Created core folder and file structure (`css/`, `js/`, `images/`).
* Implemented basic semantic HTML markup for all 7 core pages.
* Added navigation bar links across all pages.
* Drafted initial project README documentation.

## References
* Unsplash. 2026. *Free High-Resolution African Hair & Beauty Photos*. Available at: <https://unsplash.com> [Accessed 12 August 2026].
* W3Schools. 2026. *HTML5 Semantic Elements Reference*. Available at: <https://www.w3schools.com/html/> [Accessed 12 August 2026].

# Afro Crown Beauty - Website Development Part 2

Welcome to **Part 2** of the Afro Crown Beauty web application project. This phase focuses on advanced layout styling, custom branding updates, and comprehensive **Responsive Web Design (RWD)** across desktop, tablet, and mobile viewports.

Key Updates & Technical Features in Part 2

### 1. Responsive Layout & Media Queries (`@media`)
* **Mobile Breakpoint Optimization:** Implemented global media queries targeting viewports `768px` and below to ensure content stacks fluidly on mobile devices.
* **Fluid Container Sizing:** Applied relative sizing (`vw`, `%`, `rem`) to prevent unwanted horizontal scrolling across dynamic screen sizes.

### 2. Centered Grid & Desktop Styling Fixes
* **Standardized Alignment:** Applied strict horizontal centering (`margin: 0 auto`, `align-items: center`) across all product cards, hero sections, and image wrappers.
* **Large Display Stability:** Configured desktop overrides (`min-width: 769px`) to maintain grid proportions and center feature images on high-resolution screens.

### 3. Media & Content Optimization
* **Responsive Image Handling:** Enforced `max-width: 100%` and dynamic height properties to prevent stretched or overflowing asset graphics.
* **Map & Media Embeds:** Made embedded Google Maps `iframe` elements fully fluid (`width: 100%`) with capped heights on narrow screens.
* **Text Wrapping & Typography:** Fixed long text string overflows (such as email addresses) using `overflow-wrap: break-word` and responsive text scaling via CSS `clamp()`.

### 4. Navigation & Header Styling
* **Logo Alignment:** Secured global centering for the brand logo across all device widths.
* **Custom Navigation Dividers:** Added and styled subtle menu dividers using CSS border and pseudo-element rules.

## Built With

* **HTML5** – Semantic structure (`header`, `nav`, `main`, `section`, `footer`)
* **CSS3** – Flexbox layouts, CSS Grid, Media Queries, and custom variables
* **VS Code Live Server** – Local testing and network mobile debugging

## How to Test Responsiveness

1. **Chrome Developer Tools:** Open the site, press `F12` (or `Cmd + Option + I`), and toggle the Device Toolbar (`Ctrl + Shift + M`).
2. **Local Network / Live Server:** Run Live Server in VS Code and connect your mobile device using your computer's local IP address (`http://<YOUR-IP>:5500`).  
