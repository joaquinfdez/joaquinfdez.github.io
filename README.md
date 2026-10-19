# Joaquín Fernández-León — personal portfolio

Static, accessible research and ML engineering portfolio for https://joaquinfdez.github.io/.

## Edit and preview

- `index.html`: biography, selected projects (expandable case studies), publications, career, education and contact.
- `style.css`: responsive layout, typography, colors and print styles.
- `assets/joaquin.png`: profile photograph.

No dependencies or build step. Run `python3 -m http.server 8000` and open http://localhost:8000.

## Publish on GitHub Pages

Push these site files to `main`. In the repository's **Settings → Pages**, choose **Deploy from a branch → main → / (root)**. GitHub publishes at https://joaquinfdez.github.io/.

Keep private working documents in `output/` and `tmp/` out of commits. Keep personal contact details and CV files off the public site; use LinkedIn for contact. Publication statuses and current roles are maintained manually; review them when updating the site.

## Recruiter-focused content

Keep the introduction brief and use each expandable project to explain the problem, individual contribution, technical approach and outcome. Attribute original TAO research to its authors, distinguish experimental world-model research from deployed systems, and separate architecture design from implementation claims.

Revenue, client counts, programme budgets and precise customer dataset sizes are intentionally omitted pending public-disclosure clearance. The 100× simulation speedup is omitted pending a directly supporting publication. The digital-twin pressure error (<1%) and consultation time (<50 ms) are supported by its linked 2024 paper. ICAIF 2026 acceptance is based on the owner's supplied information; add the proceedings link when available.
