

Projet Open Classrooms cursus intégrateur Web 2023: Améliorez l'interface d'un site mobile avec des animations CSS
This project is meant to learn building some simple animations in a website during the OpenClassroom program on web integration.
It is based on their design with a list of animations that should appear on the site when interacting.

#LOADER:
   - With the loader and "background-clip: text",  letters got cut off due to the bounding box and probably to connective script fonts properties. A way to bypass it is to add padding and négative margin. (source: https://stackoverflow.com/questions/19259975/background-clip-property-background-image-is-being-cut-off)
   - If **images are added to Homepage**, change $number-of-images in _variables.scss line 35 to adapt loader
   - All loader animation delays and durations (if none forgotten) can be adapted from _variables.scss under comment section /*HOME*/ > /*LOADER*/ line 40 and above
   - If linear gradient is kept for loader title, color can be adjusted under line 57 in _variables.scss they are depending on the button-color.
   - image animation shows up only on screens from 1024px and up.
   - Loader Fonts are in vh + vw + vmin sizes see line 19 _variables.scss
   - the background-clip:text; for the title during loading cannot be in the container for the letters (loader__logo) as it creates some issues under Chrome and Edge unfortunatly.


Git/GitHub versions:
° There are 3 options for the layout of the dish-cards in checkbox:
    -> two of which are in the branch menuCheckboxs in the ".\restaurants\la_palette_du_gout.html" file
    in the two first dishes only
    -> third and chosen option is in the branch menuCheckboxsBis
° pink-heart: first option was a link before finding out about the checkbox option
    -> can be seen under the branch saveOldLinkVersion or 525d9bc
