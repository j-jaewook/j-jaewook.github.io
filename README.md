# jaewook-jung.github.io — site files

Four pages, plain HTML, no build step. Edit the HTML directly on GitHub.

| File | What it is |
|---|---|
| `index.html` | Home — about me, job market paper, fields |
| `research.html` | Papers and abstracts |
| `teaching.html` | Courses and teaching statement |
| `cv.html` | CV download and references |
| `style.css` | All styling. Colors are at the very top. |

## Still to fill in

In `index.html`: the About me paragraph, `ADVISOR NAME`, and the job market
paper block. Then `research.html` and `teaching.html`.

In the sidebar (all four files): your real Google Scholar and LinkedIn URLs.
If you don't have a Scholar profile yet, delete that `<li>` — a link to
Scholar's homepage looks worse than no link.

## Files to upload alongside these

Named exactly:

- `photo.jpg` — headshot. Portrait orientation, at least 600 px wide.
  It is cropped to 4:5, so leave a little headroom.
- `cv.pdf`
- `jmp.pdf` — job market paper
- `teaching-statement.pdf`

## Editing on GitHub

Open the repo → click the file → pencil icon → edit → **Commit changes** →
confirm. Live in about a minute. Hard-refresh to see it (Cmd+Shift+R on Mac,
Ctrl+Shift+R on Windows).

**The sidebar is duplicated in all four files.** Get it right in `index.html`,
then copy the whole `<aside class="sidebar">` ... `</aside>` block and paste it
over the matching block in the other three.

## Changing the color

Top of `style.css`:

```css
--olive:      #556b2f;   /* buttons, links, headings rule */
--olive-dark: #3e4f21;   /* hover state */
--olive-wash: #f1f3e8;   /* job market paper background */
```

Change those three and the whole site follows.
