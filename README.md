# Progress Bar

A simple, interactive progress steps component built with HTML, CSS, and JavaScript.  
It visually represents a multi-step process with clickable **Next** and **Prev** buttons, updating both the step indicators and a progress bar dynamically.

## Demo

[Live Demo](https://princesharma-afk.github.io/Progress-Bar/)

## Features

- Visual progress bar that fills as you move through steps.
- Four step circles that highlight the current progress.
- **Next** and **Prev** buttons to navigate between steps.
- Buttons are disabled appropriately at the first and last steps.
- Smooth transitions and responsive design.

## Responsiveness

- The layout and controls are fully responsive and optimized for screen widths **down to 360px**.
- Circles and buttons resize appropriately for smaller screens to maintain usability.
- Tested on mobile devices and small viewports for a seamless experience.

## How It Works

- Clicking **Next** advances the progress one step, highlighting the corresponding circle and filling the progress bar.
- Clicking **Prev** goes back one step, updating the UI accordingly.
- The progress bar width is calculated based on the number of active steps.
- The component prevents navigating beyond the first or last step by disabling buttons.

## Getting Started

1. Clone the repository:
   git clone https://github.com/princesharma-afk/Progress-Steps.git
2. Open index.html in your browser.
3. Use the Next and Prev buttons to interact with the progress steps.
