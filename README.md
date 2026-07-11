# Pixel Sky Clock

This project is a single-file, web-based retro clock that features a dynamic, animated pixel-art sky[cite: 1]. The environment automatically updates to reflect your local time of day, transitioning through different atmospheric color palettes and celestial animations[cite: 1].

---

## Features

*   **Dynamic Day/Night Cycle:** The background smoothly transitions between dawn, day, dusk, and night based on the user's current local time[cite: 1].
*   **Toggleable Clock UI:** Users can switch between a retro digital clock and an analogue clock face[cite: 1].
*   **Animated Sky Elements:** Features continuous animations including drifting clouds, twinkling stars, and moving celestial bodies (a pixel-art sun and moon)[cite: 1].
*   **Ambient Fly-bys:** Flocks of birds and airplanes with contrails occasionally fly across the screen at randomized intervals[cite: 1].
*   **Interactive Skyline:** A layered city skyline sits at the bottom of the screen, featuring windows that randomly light up and flicker during dusk and night modes[cite: 1].
*   **Date Display:** The clock panel includes a live date line showing the current day of the week, month, and date[cite: 1].
*   **Retro Aesthetics:** Built using pixelated box-shadow sprites, hard-edged CSS shapes, and the "Press Start 2P" font to simulate an 8-bit aesthetic[cite: 1].

---

## Time of Day Modes

The application automatically checks the time every second and assigns a specific mode based on the current hour[cite: 1]. 

| Mode | Active Hours | Visual Details |
| :--- | :--- | :--- |
| **Dawn** | 5:00 AM – 8:59 AM[cite: 1] | Features a soft orange and blue gradient with the sun positioned moderately high[cite: 1]. |
| **Day** | 9:00 AM – 4:59 PM[cite: 1] | Features a bright blue sky with a high-positioned sun[cite: 1]. |
| **Dusk** | 5:00 PM – 7:59 PM[cite: 1] | Features a purple and deep orange gradient with lit city windows[cite: 1]. |
| **Night** | 8:00 PM – 4:59 AM[cite: 1] | Features a dark sky, a glowing moon with craters, twinkling stars, and fully lit city windows[cite: 1]. |

---

## Setup and Usage

Because this project is contained entirely within a single HTML file, no build tools or package managers are required[cite: 1].

1. Save the source code as an `.html` file (e.g., `pixel_sky_clock.html`)[cite: 1].
2. Double-click the file to open it in any modern web browser[cite: 1]. 
3. Use the **DIGITAL** and **ANALOGUE** buttons on the screen to toggle your preferred time display[cite: 1].

---

## Technologies Used

*   **HTML5:** Provides the semantic structure and inline SVG elements for the buildings, birds, and airplanes[cite: 1].
*   **CSS3:** Handles the pixelated rendering (`image-rendering: pixelated`), color palettes via CSS variables, and all continuous keyframe animations (drifting, twinkling, flying)[cite: 1].
*   **Vanilla JavaScript:** Drives the real-time clock logic, manages the time-of-day state, and controls the randomized generation intervals for the birds, planes, and flickering windows[cite: 1].
![image alt](https://github.com/tee-uwu/Pixel-Sky-Clock/blob/b3e7d6b10576a8eb2a75c33cf8109ada7d085006/pixel%20clock.png)
