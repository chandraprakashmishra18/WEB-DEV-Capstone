WEB-DEVELOPMENT CAPSTONE PROJECT
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Wanderlust Travel Agency
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## **Project Overview**
Wanderlust Travel Agency is a responsive and modern landing page built for a fictional travel agency. It is designed to showcase popular destinations, tour packages, testimonials, and a streamlined booking process. The design is clean, using a vibrant primary color (`--primary: #1e90ff`) and a warm accent color (`--accent: #ffb347`) to create an inviting user experience.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## **Features**

  * **Responsive Navigation Bar:** A sticky navigation bar that includes a responsive hamburger menu for mobile devices.
  * **Hero Section (`.cpm`):** An engaging, full-width header with a background image, overlay, and clear Call-to-Action (CTA) button with animations.
  * **Popular Destinations:** A grid layout to beautifully display featured travel spots.
  * **Tour Packages:** Cards detailing different tour offerings, including price and duration.
  * **"How It Works" Section:** A simple, three-step process explanation using animated step numbers.
  * **Traveler Testimonials:** A section to build trust, showcasing customer reviews with avatars and star ratings.
  * **Travel Blog Preview:** A section with cards linking to recent blog posts.
  * **Animated Stats Counter:** A section to highlight key business metrics (Cities Served, Happy Travelers, etc.).
  * **Newsletter Signup:** A prominent signup form integrated into a colorful banner.
  * **Contact Section:** Includes a form for inquiries and a mock map location.
  * **Comprehensive Footer:** Contains sitemap links, social media links, and company info.
  * **Custom Animations:** Uses CSS `@keyframes` for subtle, modern effects (`fadeInDown`, `fadeInUp`, `popIn`, `countUp`).
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## **Technologies Used**

  * **HTML5** (`CapstoneA.html`) - For the structure and content.
  * **CSS3** (`csfcp-capstonemain.css`) - For styling, layout (using Flexbox and CSS Grid), and responsive design.
  * **Google Fonts (Montserrat)** - For typography.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## **Setup and Installation**

To view and run this project locally, follow these simple steps:

1.  **Clone the repository (if applicable) or download the files:**
    ```bash
    git clone [your-repo-link]
    # OR download the zip file
    ```
2.  **Ensure you have the following files in the root directory:**
      * `CapstoneA.html`
      * `csfcp-capstonemain.css`
      * **Image files:** (e.g., `download (1).jpg`, `maldives.jpg`, `paris.jpg`, etc. as referenced in the CSS and HTML).
3.  **Open `CapstoneA.html`** in your preferred web browser.

The website should load and be fully interactive.

## **File Structure**

| File | Description |
| :--- | :--- |
| `CapstoneA.html` | The main HTML file containing the page structure and content. |
| `csfcp-capstonemain.css` | The complete stylesheet, including variables, layout, components, and media queries. |
| `[image files]` | All image assets referenced in the HTML and CSS (e.g., backgrounds, destination images, avatars). |
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## **Key CSS Variables**

The `csfcp-capstonemain.css` file uses custom CSS properties (variables) for easy theme customization:

css
:root {
    --primary: #1e90ff; /* Dodger Blue - Main brand color */
    --accent: #ffb347;  /* Light Orange - Highlight color for CTAs */
    --bg: #f7f9fa;      /* Light Gray - Page background */
    --dark: #222;       /* Dark Gray - Primary text color */
    --light: #fff;      /* White - Backgrounds for cards and nav */
    --gray: #888;       /* Medium Gray - Secondary text color */
}

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## **Responsiveness**

The project is fully responsive and optimized for various screen sizes using media queries:

  * **Tablet/Mid-Screen (`max-width: 900px`)**: Adjusts padding, simplifies the newsletter and contact layout, and stacks footer columns.
  * **Mobile (`max-width: 768px`)**: Implements the responsive hamburger menu for the main navigation.
  * **Small Mobile (`max-width: 600px`)**: Stacks most grid and flex components (e.g., steps, stats, packages) into a single column for optimal viewing on smaller screens.

-----
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## **Further Development**

Potential next steps for this project could include:

  * Integrating a real backend for handling form submissions (Contact/Newsletter).
  * Implementing a simple carousel/slider for the Testimonials or Hero section.
  * Adding dedicated internal pages (e.g., individual package details, full blog post views).
  * Adding JavaScript to dynamically count the numbers in the Stats section.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Author: Chandra Prakash Mishra
Roll no: 2501010311
 --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
