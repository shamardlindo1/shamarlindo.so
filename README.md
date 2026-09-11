# shamarlindo.so

Personal site — mechanical engineering portfolio. Static HTML/CSS, no build step.

**Live:** https://shamardlindo1.github.io/shamarlindo.so/

## Files

| File | What it is |
|---|---|
| `index.html` | Home — hero, about, projects list, research, skills, contact |
| `projects.html` | Long-form project write-ups (anchors: `#air-engine`, `#toiletries-case`, `#ultrasonic`, `#hemp-hurd`) |
| `404.html` | Not-found page, served automatically by GitHub Pages |
| `style.css` | All styling for every page |
| `assets/` | Images — renders, drawings, photos, micrographs |

## Editing

**Colors** live at the top of `style.css` in `:root`. `--accent` is the green;
change that one value and it updates everywhere. Dark mode uses the second block
and follows the visitor's system setting.

**Adding a photo of yourself:** drop the file in `assets/`, then in `index.html`
replace `<span class="monogram">SL</span>` with
`<img src="assets/portrait.jpg" alt="Shamar Lindo">`.

**Adding project images:** each slot in `projects.html` is a dashed placeholder
with the target filename on it. Replace the `<div class="ph">...</div>` with
`<img src="assets/that-filename.png" alt="...">`.

**Résumé and LinkedIn:** both are commented out in the contact list at the bottom
of `index.html`. Uncomment and fill in the handle; upload `resume.pdf` to the repo
root for the résumé link to work.

## Deploying

Push to `main`. GitHub Pages rebuilds in about a minute
(Settings → Pages → Deploy from a branch → `main` / root).
