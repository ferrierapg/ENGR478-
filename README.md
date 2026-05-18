# STM32 Digital Piano Website

This folder is ready to open in VS Code, push to GitHub, and deploy with Vercel.

## What is inside

- `index.html` - main website page
- `site.css` - website styling
- `assets/` - diagrams used on the page
- `docs/` - project PDF, presentation, and flowchart page
- `vercel.json` - small Vercel config for a static website

## How to run locally

Open `index.html` in a browser.

You can also use the VS Code Live Server extension if you have it installed.

## How to deploy with Vercel

1. Open this folder in VS Code.
2. Push this folder to a new GitHub repository.
3. Go to Vercel and import that GitHub repository.
4. Keep the framework preset as `Other`.
5. Leave the build command empty.
6. Leave the output directory empty.
7. Click deploy.

## Project Summary

This website presents an ENGR 478 STM32 digital piano project using:

- GPIO speaker outputs on PA5, PA6, and PA7
- Push buttons on PC0, PC1, PC2, and PC3
- ADC volume control on PA0
- ADC octave control on PA1
- SysTick timing for sound generation
- EXTI interrupts for button press and release
# ENGR478-
