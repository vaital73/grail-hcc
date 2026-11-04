# GRAIL-HCC website

Static website of GRAIL-HCC, served with GitHub Pages at https://grail-hcc.org.

## Structure
| File | Page |
|---|---|
| `index.html` | Home |
| `map.html` | Interactive evidence map (self-contained, data embedded) |
| `methods.html` | Methods |
| `working-groups.html` | Steering committee, extraction team, working groups |
| `publications.html` | Outputs, how to cite, version history |
| `style.css` | Shared style for all pages except the map |
| `CNAME` | Custom domain for GitHub Pages |
| `CHANGELOG.md` | Version history of the map and dataset |

## Adding a page
Copy an existing page (e.g. `methods.html`), change its `<title>` and content inside `<main>`,
and add the link to the `<nav>` block of every page.

## Releasing a new map version
1. Replace `map.html` with the new build.
2. Update the version and date in the footer, in `publications.html` (citation and version history) and in `CHANGELOG.md`.
3. Commit, then create a GitHub release (e.g. `v11`): Zenodo archives it and assigns a DOI.

## To complete after the first release
- Zenodo DOI (publications page and citation).

Licence: content CC BY 4.0.
