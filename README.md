# SAV — Statická analýza a verifikace

Source of the web page for the [SAV course](https://www.fit.vut.cz/study/course/SAV)
at FIT BUT, plus the public course materials.

**Published at <https://verifit.github.io/sav-public/>**

## Editing the page

All of the student-facing content is a single file, [`index.md`](index.md).
Pushing to `master` deploys; the new version is usually live within a minute.

Lecture slides and other materials live under `OLD-2025/Lectures/<year>/` and are
linked from `index.md` with plain relative links.

## How it is built

GitHub Pages' own Jekyll build — there is no CI workflow, and nothing to
configure in the repository settings. The theme is
[just-the-docs](https://github.com/just-the-docs/just-the-docs), pulled in with
`remote_theme` and pinned to a tag, because GitHub's build cannot install theme
gems.

To preview locally (the `Gemfile` pins the same `github-pages` gem GitHub uses,
so a local build matches what gets deployed):

```sh
bundle install
bundle exec jekyll serve
```

→ <http://127.0.0.1:4000/sav-public/>

## Layout

| Path | What it is |
| --- | --- |
| `index.md` | The whole page |
| `404.md` | Served for missing paths |
| `_config.yml` | Theme and site settings, with the reasoning in comments |
| `_includes/` | Local overrides of theme includes (see below) |
| `_sass/custom/custom.scss` | Custom styles; compiled into every colour scheme |
| `assets/` | Favicon, and the shadow files described below |
| `OLD-2025/` | The previous page and the lecture PDFs it linked |

## What is customised, and why

- **The sidebar navigation is this page's table of contents.** just-the-docs
  builds its sidebar from *pages*, and this site is one page, so the kramdown
  table of contents is generated at the top of `index.md` and moved into the
  sidebar by a script in `_includes/head_custom.html`. Only the top level is
  kept.
- **Dark mode** follows the system setting and can be overridden with the icon
  in the top bar; the choice is remembered in `localStorage`. The dark
  stylesheet loads behind a `prefers-color-scheme` media query, so the default
  needs no JavaScript and cannot flash, and printing always uses the light
  scheme. Wired up in `_includes/head_custom.html` and
  `_includes/scheme_toggle.html`.
- **Search is disabled**, along with the theme's aux links in the top bar.
- **The theme's own footer credit is suppressed** by
  `_includes/nav_footer_custom.html`, which the theme falls back on only when
  that include renders blank — so the file has to render *something*.
- **The previous page's HTML is not published** (`exclude` in `_config.yml`);
  only its PDFs are. It referenced absolute paths on the FIT server and would
  render broken.

## Traps worth knowing before you edit

- **`assets/js/vendor/lunr.min.js` and `assets/js/zzzz-search-data.json` are
  empty on purpose.** The theme ships a search index and lunr even with search
  turned off, and `exclude` cannot reach files that come from the theme, so an
  empty file of the same name shadows each one. A shadow only works if it is
  *published*: Jekyll drops unpublished pages before it reads theme assets.
  Delete both if search is ever turned back on.
- **Do not shadow `assets/css/just-the-docs-{dark,light}.scss` the same way** —
  dark mode needs the dark stylesheet to be published.
- **Commenting a block out in Markdown needs care.** `<!--` must start its own
  line with a blank line before it; written tight against text above, kramdown
  treats it as inline, its typographer turns `--` into an en dash, and the
  "commented out" block renders on the page.
- **Colours in `custom.scss` should come from the scheme variables**
  (`$body-text-color`, `$border-color`, `$link-color`), not from grey literals
  or the theme's `.text-grey-*` utilities — those are fixed values and stop
  being legible in one scheme or the other.
