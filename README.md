# Pixel Sky Clock

This project is a single-file, web-based retro clock that features a dynamic, animated pixel-art sky. The environment automatically updates to reflect your local time of day, transitioning through different atmospheric color palettes and celestial animations.

---

## Features

*   **Dynamic Day/Night Cycle:** The background smoothly transitions between dawn, day, dusk, and night based on the user's current local time.
*   **Toggleable Clock UI:** Users can switch between a retro digital clock and an analogue clock face.
*   **Animated Sky Elements:** Features continuous animations including drifting clouds, twinkling stars, and moving celestial bodies (a pixel-art sun and moon).
*   **Ambient Fly-bys:** Flocks of birds and airplanes with contrails occasionally fly across the screen at randomized intervals.
*   **Interactive Skyline:** A layered city skyline sits at the bottom of the screen, featuring windows that randomly light up and flicker during dusk and night modes.
*   **Date Display:** The clock panel includes a live date line showing the current day of the week, month, and date.
*   **Retro Aesthetics:** Built using pixelated box-shadow sprites, hard-edged CSS shapes, and the "Press Start 2P" font to simulate an 8-bit aesthetic.

---

## Time of Day Modes

The application automatically checks the time every second and assigns a specific mode based on the current hour. 

| Mode | Active Hours | Visual Details |
| :--- | :--- | :--- |
| **Dawn** | 5:00 AM – 8:59 AM | Features a soft orange and blue gradient with the sun positioned moderately high. |
| **Day** | 9:00 AM – 4:59 PM | Features a bright blue sky with a high-positioned sun. |
| **Dusk** | 5:00 PM – 7:59 PM | Features a purple and deep orange gradient with lit city windows. |
| **Night** | 8:00 PM – 4:59 AM | Features a dark sky, a glowing moon with craters, twinkling stars, and fully lit city windows. |

---

## Setup and Usage

Because this project is contained entirely within a single HTML file, no build tools or package managers are required.

1. Save the source code as an `.html` file (e.g., `pixel_sky_clock.html`).
2. Double-click the file to open it in any modern web browser. 
3. Use the **DIGITAL** and **ANALOGUE** buttons on the screen to toggle your preferred time display.

---

## Technologies Used

*   **HTML5:** Provides the semantic structure and inline SVG elements for the buildings, birds, and airplanes.
*   **CSS3:** Handles the pixelated rendering (`image-rendering: pixelated`), color palettes via CSS variables, and all continuous keyframe animations (drifting, twinkling, flying).
*   **Vanilla JavaScript:** Drives the real-time clock logic, manages the time-of-day state, and controls the randomized generation intervals for the birds, planes, and flickering windows.

  
![image alt](https://github.com/tee-uwu/Pixel-Sky-Clock/blob/b3e7d6b10576a8eb2a75c33cf8109ada7d085006/pixel%20clock.png)
