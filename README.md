# Modern-portfolio
template portfolio 

This code is a modern, single-page portfolio website template designed for a UI/UX designer named Alex Smith. It's built with HTML, styled with the Tailwind CSS framework, and includes interactive elements powered by JavaScript.

Key Features:

    Responsive Design: The layout adapts to different screen sizes, ensuring it looks great on desktops, tablets, and mobile devices.

    Interactive Elements: It includes a mobile navigation menu, a skill radar chart, and on-scroll animations.

    Modern Technologies: It leverages popular and modern web development tools like Tailwind CSS, Chart.js, and Lucide icons.

    Single-Page Layout: All sections are on one page, accessible through smooth scrolling navigation links.

How It's Built

The website is structured into several distinct sections, each serving a specific purpose.

Header and Navigation (<header>)

    A sticky navigation bar remains at the top of the page as you scroll.

    It includes links to the "Work," "About," and "Contact" sections.

    For mobile devices, a hamburger menu icon appears, which toggles a full-screen navigation menu.

Hero Section (<section class="relative overflow-hidden">)

    This is the first thing a visitor sees. It contains a headline, a brief introduction, and call-to-action buttons ("Explore Work" and "Get in Touch").

    It features decorative background blurs for a modern aesthetic.

    The text and image in this section animate into view when the page loads.

Work Section (<section id="work">)

    This section showcases a portfolio of projects.

    Projects are displayed in a grid of cards, each with an image, title, and a brief description that appears on hover.

About Section (<section id="about">)

    Provides more information about the designer, including their experience and design philosophy.

    It features a "Skill Radar" chart, which is a dynamic and visually engaging way to display proficiency in different areas (e.g., UI, UX, Research).

Contact Section (<section id="contact">)

    Includes a contact form for potential clients or employers to get in touch.

    The form has fields for a name, email, and a message.

Footer (<footer>)

    The footer contains copyright information (with the year automatically updated by JavaScript) and links to social media profiles.

Scripts (<script>)

The JavaScript at the bottom of the file handles the website's interactivity:

    Lucide Icons: Initializes the icons used throughout the site.

    Mobile Navigation: Toggles the visibility of the mobile menu.

    Chart.js Skill Radar: Creates and configures the animated radar chart in the "About" section.

    Intersection Observer: Manages the fade-in and slide-up animations as you scroll down the page.

    Dynamic Year: Sets the current year in the footer.

How to Use and Customize It

This template is a great starting point for your own portfolio. Here’s how you can make it your own:

Basic Information

    Title and Name:

        Change the page title in the <title> tag in the <head> section.

        Replace "Alex Smith" in the navigation bar and footer with your name.

    Text Content:

        Update the text in the hero, about, and contact sections to reflect your own skills and experience.

Images

    Portrait Image: Replace the src URL in the <img> tag within the hero section with a link to your own photo.

    Project Images: In the "Work" section, change the src URLs for each project <img> tag to your own project screenshots.

Projects

    To add, remove, or edit projects, simply copy, paste, or delete the <article> elements within the "Work" section's grid.

    Update the project title (<h3>) and description (<p>) for each project.

Skill Radar Chart

You can customize the skills and your proficiency levels in the JavaScript section:

    Labels: Change the skill names in the labels array:
    JavaScript

labels: ['Your Skill 1', 'Your Skill 2', 'Your Skill 3', ...],

Data: Adjust the corresponding scores (out of 100) in the data array:
JavaScript

    data: [80, 95, 75, ...],

Social Media Links

    In the <footer>, change the href="#" for the LinkedIn, Dribbble, and Twitter links to your own profile URLs. You can also add or remove icons as needed.

Styling and Colors

The colors and styling are managed by Tailwind CSS.

    Primary Color: The main color is indigo-600. You can globally find and replace this with another Tailwind color (e.g., blue-600, purple-600) to change the site's accent color.

    Fonts: The font is set to 'Inter' from Google Fonts. You can change this by updating the <link> in the <head> and the font-['Inter'] class on the <body>.

    Animations: The on-scroll animations are triggered by the data-animate attribute. You can remove this attribute from any element to disable its animation.

