# Maneesh Pyla: Personal Research Website

Static site (plain HTML + CSS, no build step).

## Pages
index, research, publications, talks, resources, cv, contact

## Before you publish
1. **CV privacy:** `files/Maneesh_Pyla_CV.pdf` is your full CV and includes your referees' phone numbers and emails. Replace it with a version without the Referees section before going public.
2. **Profile links:** in `index.html`, `contact.html` and `resources.html`, replace the generic links (scholar.google.com, orcid.org, github.com, linkedin.com) with your own profile URLs.
3. **Photo:** add `images/photo.jpg`, then swap the placeholder div in `index.html` (see the comment there).
4. **Publication links:** add DOI/PDF links in `publications.html` (see the comment under the first entry).
5. Fill in the "add" sections on `resources.html`.

## Deploy on GitHub Pages (free)
1. Create a repository named `<your-username>.github.io`.
2. Upload all files in this folder to the repository root.
3. In Settings > Pages, set the source to the `main` branch, root folder.
4. Your site will be live at `https://<your-username>.github.io`.

## Editing
Colors and layout are in `style.css` (the variables at the top). Dark mode follows the visitor's system setting.
