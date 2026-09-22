BARAMEEL RUN — SCREEN 01 MASTER
================================

Purpose
-------
Production-ready first-screen prototype for the BARAMEEL RUN project.
The visual master is portrait 9:16 and is displayed without a phone mockup.

Baseline design canvas
----------------------
941 x 1672 px (portrait 9:16 reference artwork).
The web shell preserves the artwork aspect ratio and never stretches it.
On narrow phones the artwork is contained inside the viewport; on landscape
orientation the app blocks interaction and asks the user to rotate the phone.

Approved visual decisions
-------------------------
- Only BARAMEEL RUN appears as the game title.
- The separate BARAMEEL master logo is NOT placed above the title.
- Brona is represented in the approved retro visual language with lighter skin.
- Official brand colors: #0E2A3D, #F0C830, #C2571A, #F5E9DC.
- Tagline: خد وقتك.. خد نفسك
- No phone frame / no advertising mockup around the game screen.

Interaction layer
-----------------
- START YOUR RUN: press/ripple/flash + custom barameel:start-run event.
- HOW IT WORKS?: opens an in-screen information sheet.
- Top-right menu: opens the same sheet.
- Escape / close / backdrop closes the sheet.

Files
-----
index.html                  App shell + interaction logic
manifest.webmanifest        Portrait fullscreen web-app metadata
assets/screen01-approved.png Approved Screen 01 visual master
assets/barameel-logo-master.png Original BARAMEEL logo source (reference only; not displayed)
assets/brona-master.png       Original Brona source (reference only)
assets/brona-face-reference.png Face reference (reference only)

Deployment
----------
Upload this folder directly to Netlify Drop. index.html must be at the root
of the uploaded folder.
