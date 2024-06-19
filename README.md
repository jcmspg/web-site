# 42 Lisbon School Website Renovation Project

Welcome to the repository for the 42 Lisbon School Website Renovation Project! This project was developed as part of a 48-hour coding challenge aimed at modernizing and improving the school’s website. Below you will find an overview of the project, installation instructions, and a detailed explanation of the features implemented.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Overview

The goal of this project is to redesign the 42 Lisbon School website to make it more modern, user-friendly, and functional. This includes improving the design, enhancing user experience, adding valuable features, ensuring responsiveness, and adhering to accessibility standards.

## Features

- **Modern Design:** A visually appealing and contemporary design that reflects the spirit and values of 42 Lisbon.
- **User Experience:** Improved navigation and usability for candidates, students, and partners.
- **Functionality:** Enhanced features providing valuable information and services to visitors.
- **Responsiveness:** Fully responsive design that works seamlessly on desktops, tablets, and smartphones.
- **Accessibility:** Website accessible to all users, including those with disabilities.

### Pages

- **Home Page:**
  - Events section with Piscines dates (dynamic display based on event availability)
  - "What is 42" section with images and descriptive text
  - Methodology section with images and text
  - How to Apply section with a redirect button
  - Donate section
- **Donation Page:** Information and options for individual donations or becoming a partner.
- **How to Apply Page:** Detailed instructions on the application process with a link to the POE application platform.

## Installation

To set up this project locally, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/42-lisbon-website.git
    cd 42-lisbon-website
    ```

2. **Install dependencies:**
    ```bash
    npm install
    ```

3. **Start the development server:**
    ```bash
    npm start
    ```

4. **Visit the website:**
    Open your browser and go to `http://localhost:3000`

## Usage

This project is designed to be compatible with WordPress. The prototype can be implemented on the WordPress platform using a specified builder. Please refer to the documentation for detailed instructions on integration.

## Code Structure

### HTML

The `index.html` file serves as the main structure of the website, containing the following sections:

- **Header and Navigation:**
  - Logo and navigation links with dropdowns for different sections like About, Events, Methodology, Apply, and Donate.
  - Language switcher buttons for English and Portuguese.
- **Content Sections:**
  - **Upcoming Events:** Displays a series of event cards with images, titles, dates, descriptions, and registration buttons.
  - **Information Sections:** Various sections providing information about 42 Network, 42 Lisboa campus, 42 Program, 42 Team, and Partners.
- **Footer:**
  - Contains contact information, network links, and social media links.

### CSS

The `style.css` file defines the styling for the website, including:

- **General Styles:**
  - Global styles for scroll behavior, margins, paddings, and font families.
  - Background settings and body styling.
- **Navigation Styles:**
  - Styles for the navigation bar, logo, menu items, dropdowns, and language switcher.
- **Content Styles:**
  - Styles for different content sections, including cards for events and partners.
  - Focus effect for sections when scrolling.
- **Card Styles:**
  - Styles for event cards, including hover effects, buttons, and text alignment.
- **Footer Styles:**
  - Styling for the footer, including layout and link styles.

### JavaScript

The inline scripts included in the `index.html` file provide functionality for:

- **Horizontal Scroll:** Enabling mouse drag to scroll horizontally in the events section.
- **Dynamic Dates:** Automatically filling event dates with the current date.
- **Random Background Images:** Assigning random background images to content sections on page load.
- **Scroll-based Focus:** Adding a focus effect to content sections based on the scroll position.

## Technologies Used

- **Frontend:**
  - HTML, CSS, JavaScript

- **Backend:**
  - Node.js (if applicable)
  - Express (if applicable)

- **Other Tools:**
  - WordPress
  - Django

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
