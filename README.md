CSS Project

## Overview

This project demonstrates a simple sidebar navigation menu with a responsive design. The sidebar contains links to various sections such as Gallery, Shortcuts, Exhibits, Events, Store, Contact, and Feedback, along with social media icons. The sidebar is hidden off-screen by default and can be toggled using a checkbox mechanism to show or hide the menu.

## Features

- **Responsive Sidebar Menu:** The sidebar slides in and out from the left side of the screen.
- **Icon Integration:** Utilizes Font Awesome icons for a modern look.
- **Custom Styling:** Applied custom CSS for styling the sidebar and its elements.
- **Font Integration:** Uses Google Fonts to apply the "Poppins" font family.

## Files

- `index.html`: The main HTML file for the project.
- `style.css`: The CSS file for styling the sidebar and other elements.

HTML Structure

    Main Container (.main_box): Wraps the entire content and sets the background image.
    Sidebar Menu (.sidebar_menu): The fixed sidebar menu that slides in and out.
        Logo (.logo): Displays the project name.
        Button to Close (.btn_two): Button to close the sidebar.
        Menu (.menu): Contains navigation links with icons.
        Social Media Links (.social_media): Displays social media icons.

CSS Details

    Basic Reset: Resets margin and padding for all elements and applies the Poppins font.
    Sidebar Styling: Positions the sidebar off-screen and transitions into view when toggled.
    Responsive Behavior: Adjusts the appearance and visibility of elements based on user interactions.
    Transitions: Smooth transitions for showing/hiding elements and hover effects.
