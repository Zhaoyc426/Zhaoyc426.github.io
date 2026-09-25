# Yicheng Zhao - Academic Homepage

This directory contains the static academic homepage and the English CV for Yicheng Zhao. The selected research project is presented under its current name, **VESTA**: Variational Experts with Soft Routing for Tail-Aware Portfolio Management.

## Files

- `index.html`: homepage content
- `styles.css`: responsive styling
- `assets/Yicheng_Zhao_CV.pdf`: English academic CV

## GitHub Pages deployment

1. Create a public repository named `Zhaoyc426.github.io` on GitHub.
2. Copy the contents of this directory into the repository root.
3. In **Settings -> Pages**, choose **Deploy from a branch**, select `main`, and select `/root`.
4. After GitHub finishes the deployment, use `https://zhaoyc426.github.io/` as the OpenReview Homepage URL.

If you prefer a project repository instead, a repository named `academic-homepage` can also be published through GitHub Pages, but the URL will be `https://zhaoyc426.github.io/academic-homepage/`.

## Local preview

From this directory, run a simple static server:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000/` in a browser. The CV link points to `assets/Yicheng_Zhao_CV.pdf`.

The current homepage uses the public contact details supplied for this profile:

- GitHub: https://github.com/Zhaoyc426
- ORCID: https://orcid.org/0009-0009-2049-7214
- Email: zhaoyc426@sjtu.edu.cn
