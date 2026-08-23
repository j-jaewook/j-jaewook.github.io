# Your job market website

Four pages, no build step, no dependencies. Edit the HTML directly.

## Files

| File | What it is |
|---|---|
| `index.html` | Home — photo, positioning, education, job market paper |
| `research.html` | Papers, abstracts, links |
| `teaching.html` | Courses, teaching statement, evaluations |
| `cv.html` | CV download and references |
| `style.css` | All the styling. Colors and fonts are at the top. |

## Before you publish

1. **Find and replace** `FIELD` and `UNIVERSITY` across all four HTML files.
   Your name is already filled in. Any decent text editor does find-and-replace
   across a whole folder at once.
2. Fill in the placeholder text. Anything in CAPS or reading like an
   instruction is meant to be replaced.
3. Update the masthead block (name, role, contact) in **all four** files — it's
   duplicated on purpose so the site needs no JavaScript.
4. Drop in your files, named exactly:
   - `photo.jpg` — headshot, roughly square, 500 px or larger
   - `cv.pdf`
   - `jmp.pdf` — job market paper
   - `teaching-statement.pdf`
   - Any other PDFs you linked
5. Delete sections you don't need. Empty sections look worse than absent ones.

To preview locally, just double-click `index.html`.

## Putting it on GitHub Pages

1. Sign in to GitHub as **j-jaewook**.
2. Create a new repository named exactly `j-jaewook.github.io` — all lowercase,
   matching the username. Set it to **Public**.
3. On the repo page, click **Add file → Upload files**, drag in everything from
   this folder, and click **Commit changes**.
4. Wait about a minute, then visit `https://j-jaewook.github.io`.

That's it. There's no build to configure and no plan to choose. To update
anything later, upload the changed file again — it overwrites the old one.

## Adding a custom domain later

Optional, roughly $12/year. Buy the domain, then in the repo go to
**Settings → Pages → Custom domain**, enter it, and add these DNS records at
your registrar:

```
A     @    185.199.108.153
A     @    185.199.109.153
A     @    185.199.110.153
A     @    185.199.111.153
CNAME www  j-jaewook.github.io
```

Tick **Enforce HTTPS** once it becomes available. Your `.github.io` address
keeps working and redirects.

## Two things worth doing the same week

- Set up a **Google Scholar profile** and link it in the masthead. For most
  people it outranks their own site in search results.
- Keep `cv.pdf` at that exact filename forever. People bookmark and email
  direct links to it; changing the name breaks them silently.
