# Interactive Digital Portfolio

A simple single-page front-end portfolio built with HTML, CSS and JavaScript.

## Features
- Responsive single-page layout (Home, About, Services, Projects, Contact)
- Typed text animation using Typed.js
- Contact form (client-side handling)
- Light theming via CSS variables

## Quick start

1. Open the project folder:
   c:\Users\ADITYA\Desktop\Interactive Digital Portfolio

2. Serve locally (recommended) and open in your browser:
   - Using Python (Windows):
     python -m http.server 8000
     Then visit http://localhost:8000

   - Or use VS Code Live Server extension (recommended for development).

## Development notes
- Main files:
  - index.html
  - style.css
  - script.js

- Typed.js is included from CDN in `index.html`. Edit the rotating strings in `script.js` to change the typed text.

- Contact form currently uses client-side handling in `script.js` (no backend). Hook a server or service to send messages.

- Image path: change the avatar `src="/Aditya.png"` in `index.html` to a relative path `src="Aditya.png"` for correct local loading.

## Project structure
- index.html — main markup
- style.css — styles and theme variables
- script.js — typed effect and form handling
- Aditya.png — profile image
- .hintrc — HTML linting rules

## Customization tips
- Colors and theme: edit CSS variables in `style.css` (e.g. `--main-bg`, `--accent`).
- Sections: modify the HTML sections (#home, #about, #service, #project, #contact).
- Add real project links in the Projects section and update social links in the footer.

## License
Add a LICENSE file if you want to publish under a specific license.

## Contact
For questions or updates, edit files directly in the project folder or open an issue in your version control.

## Live Link
 `https://kartike2002.github.io/IBM_SKILLS_BUILD/`


