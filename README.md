# Rittwik Hajra: academic website

The whole site is one file, `index.html`. Its styles and script are inside it. The seven pages (Home, Publications, Experience, Education, Talks, Miscellaneous, Contact) switch from the top menu. Each page has its own address, such as `.../#publications`, so you can share a link to it.

## Publish on GitHub Pages

1. Create a public repository named `<your-github-username>.github.io`.
2. Upload `index.html` to the root of the repository.
3. Open **Settings > Pages**. Under "Build and deployment", choose **Deploy from a branch**, then pick `main` and `/ (root)`. Save.
4. After a minute or two, the site is live at `https://<your-github-username>.github.io`.

## Things to fill in

Search `index.html` for `EDIT:` to find each one.

| What | Where it goes |
| --- | --- |
| Google Scholar, DBLP, GitHub and LinkedIn links | The links under your name |
| `cover.jpg` | Included (the Delta Centre). Keep it next to `index.html`. To change it, use another photo in 3:2 shape. |
| `photo.jpg` | Included. Keep it next to `index.html`. To change it, use another square photo. |
| `images/theatre/stage.jpg` | Included (you as Arjun). Keep it in `images/theatre/`. |
| `cv.pdf` | Next to `index.html`. Remove your phone number and references first. |
| `papers/kummer-asiaccs2026.pdf`, `papers/matse-africacrypt2026.pdf` | A `papers` folder, or swap the links for DOIs. Each link appears twice: on Home and on Publications. |
| `papers/mtech-thesis.pdf` | A `papers` folder |
| Paintings (and later poems, photography) | The Miscellaneous page |

Final layout of the repository:

```
index.html
cover.jpg          (included)
photo.jpg          (included)
cv.pdf
papers/
  kummer-asiaccs2026.pdf
  matse-africacrypt2026.pdf
  mtech-thesis.pdf
images/
  theatre/
    stage.jpg
  paintings/
    birth-of-the-primordial.jpg
    erlking-pencil.jpg
    erlking-inverted.jpg
    we-work-through-pain.jpg
    untitled-2021.jpg
    odin-pencil.jpg
    odin-inverted.jpg
    schicchi-capocchio.jpg
    spectral-pencil.jpg
    spectral-inverted.jpg
    hurnaz.jpg
    raven.jpg
    offering-to-cernunnos.jpg
  photography/
```

## The Miscellaneous page

Each topic is a fold-out panel: visitors click its title bar to open it.

- **Theatre** is complete.
- **Paintings** has *The Birth of the Primordial*, *The Erlking*, *We Work Through Pain*, *Untitled* (2021), *Odin Hanging from Yggdrasil*, *Gianni Schicchi's Love Bite to Capocchio*, *Spectral Visions of Mental Warfare*, *Hurnaz*, *The Raven of Allan Poe* and *Offering to Cernunnos*. To add another painting, copy one `<article class="artwork">` block and change the picture, title, details and text. Images go in `images/paintings/`. For a full-width picture with the text below (good for wide paintings), use `<article class="artwork wide">`, as in *The Erlking*, *Untitled* and *Odin Hanging from Yggdrasil*. To stack two wide pictures one above the other, use `<div class="pair stack">`, as in *Spectral Visions of Mental Warfare*. To quote a poem with its line breaks, copy the `<blockquote class="verse">` block from *The Raven of Allan Poe*.
- **Poems** and **Photography** panels are ready but hidden inside HTML comments. To show one, delete the `<!--` and `-->` around it.

## Updating later

- **New paper:** copy one `<li class="pub">` block on the Publications page. Also update "Recent papers" on Home.
- **New position, degree or talk:** copy one `<li class="entry">` block on the right page.
- **Footer date:** change "Last updated" near the bottom of the file.
