# Personal Portfolio Website

## Overview

This is a fully responsive, multi-page portfolio website built using semantic HTML5 and modern CSS3. The website showcases my background, technical skills, projects, and contact information through a clean and accessible user interface. The site follows responsive design principles, accessibility best practices, and semantic HTML standards.

---

## Issues Found in Starter Code

I identified and resolved multiple issues across the provided starter files.

### HTML Issues

* Missing `<!DOCTYPE html>` declaration
* Missing viewport meta tag for responsive design
* Missing semantic `<main>` elements
* Inconsistent navigation structure
* Missing form labels
* Insufficient form input variety
* Missing HTML5 validation attributes
* Missing accessibility enhancements
* Missing alt text on images
* Missing semantic structure on several pages
* Missing table structure and semantic headers
* Footer email links incorrectly formatted

### CSS Issues

* Navigation styling missing
* Form styling incomplete
* Table styling missing
* Inconsistent spacing and layout
* Insufficient selector variety
* Weak visual hierarchy
* Missing responsive layout improvements
* Footer alignment issues

---

## Fixes Implemented

### Semantic HTML Improvements

* Added semantic HTML5 elements including:

  * `<header>`
  * `<nav>`
  * `<main>`
  * `<section>`
  * `<article>`
  * `<figure>`
  * `<figcaption>`
  * `<footer>`

* Added meta description tags to all pages

* Added skip-to-content links for accessibility

* Added active navigation indicators

* Added table captions and scope attributes

* Improved heading hierarchy throughout the website

### Navigation Improvements

* Consistent navigation menu across all pages
* Active page highlighting
* Hover and focus states for navigation links
* Accessibility-friendly navigation structure

### Images & Media

* Added descriptive alt text to all images
* Wrapped key images inside `<figure>` elements
* Added meaningful `<figcaption>` descriptions
* Improved semantic image presentation

### Table Improvements

* Added semantic table structure using:

  * `<caption>`
  * `<thead>`
  * `<tbody>`
  * `scope="col"`
  * `scope="row"`

* Improved table readability with alternating row colours and hover effects

### Form Improvements

* Added six form input types:

  * Text
  * Email
  * Telephone
  * Select menu
  * Radio buttons
  * Textarea

* Added HTML5 validation attributes:

  * `required`
  * `minlength`
  * `pattern`

* Added autocomplete attributes

* Grouped radio buttons using `<fieldset>` and `<legend>`

* Added helper text and improved accessibility

### CSS Improvements

Implemented multiple selector types:

1. Element selectors
2. Class selectors
3. ID selectors
4. Descendant selectors
5. Pseudo-class selectors
6. Attribute selectors

Additional improvements include:

* Responsive Flexbox layouts
* CSS Grid project gallery
* Hover and focus effects
* Form validation styling
* Improved spacing and visual consistency
* Responsive mobile layouts

---

## HTML Structure & Semantic Choices

### Header

Contains the site title and primary navigation.

### Navigation

Provides consistent navigation between all pages.

### Main

Contains the unique content for each page and improves screen reader navigation.

### Sections

Used to group related content such as:

* Hero section
* Background information
* Skills section
* Projects section
* Contact form

### Articles

Used to represent individual project content and grouped information.

### Figure & Figcaption

Used for images that require contextual descriptions.

### Table

Used to present technical skills and experience levels in a structured format.

### Form

Used to collect contact information with proper validation and accessibility support.

---

## CSS Styling Approach

### Layout Techniques

* Flexbox for navigation and content alignment
* CSS Grid for project cards
* Responsive media queries
* Consistent spacing and alignment

### Interactive Features

* Hover effects
* Focus states
* Active navigation indicators
* Form validation feedback

### Design Principles

* Clear visual hierarchy
* Consistent spacing
* Professional colour palette
* Accessible typography
* Mobile-first responsiveness

---

## Accessibility Improvements

The website was designed with accessibility in mind.

### Accessibility Features

* Skip-to-content links
* Semantic HTML structure
* Descriptive image alt text
* Figure captions
* Form labels for all inputs
* Fieldset and legend grouping
* Keyboard-accessible navigation
* Visible focus states
* Proper heading hierarchy
* Table captions and scope attributes
* WCAG-compliant colour contrast

---

## Responsive Design

The website adapts to different screen sizes using media queries.

### Desktop

* Three-column project grid
* Horizontal navigation menu

### Tablet

* Two-column project grid
* Optimized spacing and layout

### Mobile

* Single-column project grid
* Stacked navigation menu
* Mobile-friendly spacing

---

## How to View Locally

1. Download or clone the repository.
2. Open the project folder in Visual Studio Code.
3. Launch a local server:

### Option A – Live Server

Right-click `index.html` and select **Open with Live Server**.

### Option B – Browser

Double-click `index.html` to open the project in your browser.

4. Navigate through all four pages.
5. Test responsiveness using browser developer tools.
6. Test form validation by submitting empty or invalid inputs.

---

## Screenshots

All screenshots are stored in the `/screenshots` folder.

| Page/Section    | Filename       | Description                             |
| --------------- | -------------- | --------------------------------------- |
| Homepage        | homepage.png   | Homepage hero section                   |
| About Page      | about.png      | Background information and skills table |
| Projects Page   | projects.png   | Responsive projects grid                |
| Contact Page    | contact.png    | Contact form                            |
| Navigation      | navigation.png | Navigation menu and active state        |
| Responsive View | responsive.png | Mobile layout demonstration             |

---

## Reflection

One of the biggest challenges was identifying and correcting issues across multiple HTML and CSS files while ensuring that the final website remained consistent, accessible, and responsive.

Through this project I strengthened my understanding of:

* Semantic HTML5
* Accessibility best practices
* Responsive web design
* CSS Grid and Flexbox
* Form validation
* Code organization and maintainability

The most valuable lesson was learning how semantic HTML improves both accessibility and maintainability while reducing the need for unnecessary containers and styling workarounds.

---

## Technologies Used

* HTML5
* CSS3
* Flexbox
* CSS Grid
* W3C HTML Validator
* W3C CSS Validator
* Figma (Wireframing)

---

## Credits

* Placeholder images from Unsplash
* Assignment provided by Umuzi Creative Agency
