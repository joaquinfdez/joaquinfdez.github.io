# Joaquín Fernández-León — personal portfolio

Static, accessible research and ML engineering portfolio for https://joaquinfdez.github.io/.

## Edit and preview

- `index.html`: biography, selected projects (expandable case studies), publications, career, education and contact.
- `style.css`: responsive layout, typography, colors and print styles.
- `assets/joaquin.png`: profile photograph.
- `assets/Joaquin-Fernandez-CV.pdf`: public CV, with phone number omitted.

No dependencies or build step. Run `python3 -m http.server 8000` and open http://localhost:8000.

## Publish on GitHub Pages

Push these site files to `main`. In the repository's **Settings → Pages**, choose **Deploy from a branch → main → / (root)**. GitHub publishes at https://joaquinfdez.github.io/.

Keep private working documents in `output/` and `tmp/` out of commits. Only the public CV belongs in `assets/`. Publication statuses and current roles are maintained manually; review them when updating the site.
