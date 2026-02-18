# Portfolio Website

This repository contains a single-page portfolio for **Varun Kumar Reddy Gunnreddy**, generated from resume content.

## Run locally

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000`.

## Publish and get a public link (GitHub Pages)

1. Create a GitHub repository (for example: `varun-portfolio`).
2. Push this code:

```bash
git add .
git commit -m "Add portfolio website"
git branch -M main
git remote add origin https://github.com/<your-username>/varun-portfolio.git
git push -u origin main
```

3. In GitHub: `Settings -> Pages`.
4. Under **Build and deployment**, select:
   - Source: `Deploy from a branch`
   - Branch: `main` and folder `/ (root)`
5. Save. After deployment, your link will be:

`https://<your-username>.github.io/varun-portfolio/`

You can use that URL in job applications.
