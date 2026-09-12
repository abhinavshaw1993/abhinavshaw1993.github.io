# Abhinav Shaw's personal website

A lightweight, responsive static website hosted at https://abhinavshaw1993.github.io/.

## Local preview

From this repository, run:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Then open http://127.0.0.1:8000. No build step or package installation is required.

## Editing

- `index.html`: profile, biography, projects, navigation, and contact links.
- `style.css`: layout, typography, colors, and responsive styles.
- `img/profile.jpeg`: profile photograph.
- `resume/AbhinavResume.pdf`: linked résumé.

The navigation contains About, Publications, and Projects. Education and the move from
ML-for-health research to autonomous driving are summarized in About. Recent work is
featured first, with three older projects in an expandable section. The résumé remains
available as a sidebar PDF link; its contents are not reproduced on the page.

Publication titles were selected from LinkedIn and checked against available primary
sources. The 2025 Stanford work is labeled as a course project report; the 2019 paper
uses the Adaptive & Multitask Learning Workshop venue recorded on arXiv.

Content sources:
- https://www.linkedin.com/in/abhinav-shaw/
- https://www.nature.com/articles/s41598-024-56674-2
- https://arxiv.org/abs/1906.11356
- https://cs224r.stanford.edu/spring_2025/projects/pdfs/CS224R_Custom_Project_Report.pdf
- https://github.com/Information-Fusion-Lab-Umass/personalized-stress-prediction

## Design reference

The layout is a standalone HTML/CSS adaptation of the profile-sidebar and content-column
design in [John Femiani's website](https://github.com/jfemiani/jfemiani.github.io),
which uses Academic Pages / Minimal Mistakes. It does not require the reference site's
Jekyll build, publication collections, or plugins. Attribution is included in the footer
and the upstream license is recorded in `THIRD_PARTY_NOTICES.md`.
