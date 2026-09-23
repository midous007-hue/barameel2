BARAMEEL RUN — SCREEN 03 VIDEO-READY
=======================================

This package is the upload-ready Screen 03 runner-selection build.

FOLDER STRUCTURE
barameel-run/
  screen03-runner-selection.html
  README.txt
  assets/
    screen03-background.png
    runner-rookie.png
    runner-skater.png
    runner-brona.png
    runner-racer.png
    runner-chiller.png
    runner-dreamer.png
    videos/
      brona-select.mp4

WHAT THIS BUILD DOES
1. Keeps the Screen 03 layout as the established BARAMEEL RUN runner-selection screen.
2. Clicking any runner keeps the user on the same screen.
3. The strong gold selection frame moves to the selected runner.
4. Runner traits/details update in place.
5. The large hero artwork changes in the same panel.
6. Brona has a real cinematic video entrance:
   - assets/videos/brona-select.mp4
   - plays once after Brona is selected
   - then automatically returns to the Brona static artwork
   - no page navigation occurs
7. Other runners currently use their static artwork plus the established CSS entrance motion.
   Their future videos can be added later without rebuilding the screen.
8. Existing BARAMEEL-style selection sounds remain for runners without a video.
9. The Brona video keeps its own audio at reduced volume and is triggered by the user tap.
10. The page is mobile-first and fills the phone viewport while preserving the 996:1722 screen ratio.

GITHUB UPLOAD
Upload the CONTENTS of this package into:
barameel2/barameel-run/

Important:
- screen03-runner-selection.html must be directly inside barameel-run/
- assets must be directly inside barameel-run/
- videos must be inside barameel-run/assets/videos/

The final URL will be:
https://midous007-hue.github.io/barameel2/barameel-run/screen03-runner-selection.html

CURRENT VIDEO
The supplied Brona video is installed as:
assets/videos/brona-select.mp4

FUTURE RUNNER VIDEOS
When a video is generated for another runner, place it in:
assets/videos/
and update the videos object in screen03-runner-selection.html:
"rookie":"./assets/videos/rookie-select.mp4"
"skater":"./assets/videos/skater-select.mp4"
"racer":"./assets/videos/racer-select.mp4"
"chiller":"./assets/videos/chiller-select.mp4"
"dreamer":"./assets/videos/dreamer-select.mp4"

No other page needs to be created for this behavior.
