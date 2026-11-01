# Octavian Mihai Ghiță — Academic website

Static, responsive academic website inspired by the page structure and general visual style of https://serigc.github.io/academic-website/index.html. **No portrait photography, image files or photograph elements are used**; the hero's decorative monogram is pure CSS. The favicon is an SVG icon.

## Pages
- `index.html` — Overview, quantitative highlights, selected projects and publications
- `research.html` — Research areas and 21 source-backed project/grant entries
- `publications.html` — Searchable, filterable catalogue of 73 source bibliographic records
- `teaching.html` — Course materials, bibliographic educational resources and academic teaching
- `about.html` — Career, education, leadership
- `contact.html` — Academic email, affiliation and ORCID

## Publish with GitHub Pages
1. Create a **public** GitHub repository, e.g. `octavian-ghita-academic-website`.
2. Upload all files and folders from this directory to the repository root (do not upload the ZIP as a single file).
3. Open **Settings → Pages → Build and deployment**; select **Deploy from a branch** → **main** → **/(root)** → **Save**.
4. GitHub Pages will publish the site at `https://USERNAME.github.io/octavian-ghita-academic-website/` (using your GitHub username).

For a user site at `https://USERNAME.github.io/`, name the repository `USERNAME.github.io` and upload the same files to its root.

## Local use
Open `index.html` in your browser. All HTML, JavaScript catalogue search and navigation work without a server. For development, serve the directory with `python3 -m http.server 8000`.

## Update content
- Edit the individual HTML files for page copy.
- Publications and projects are stored in `assets/catalogue.json` for reuse, and `assets/catalogue-data.js` for offline browser search. If you edit publication records, update both to keep them consistent.
- Edit `assets/site.css` for styling; `assets/site.js` controls filters, load-more and mobile navigation.

## Source and accuracy notes
- `CV_Ghita Octavian_2026.doc`, dated 14 September 2026: professional experience and CV statistics.
- `Criterii_CNATDCU_2026_Ghita.xlsx`: bibliography, course materials and project descriptions. Category names follow the spreadsheet, not an independent indexing audit.
- ORCID iD: https://orcid.org/0009-0004-2254-2596. The supplied `my-orcid` link required JavaScript/login and could not be used to extract works automatically; its public identifier is linked.
- The 73 catalogue entries are extracted from spreadsheet sections 2.1.a, 2.1.b and 2.2.b, and should **not** be presented as a count of unique publications; the CV separately states 68 articles, of which 27 were reported as ISI-listed.
- There are no external visual assets, trackers or forms; optional Google Fonts will fall back to system fonts when offline.
- Original CV and workbook are not redistributed in the published website to avoid publishing personal material and administrative working documents.

No build process or account credentials required.
