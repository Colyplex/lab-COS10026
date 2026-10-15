# Week 5: CSS Layout

Open `lab05.html` in a web browser. No installation or build step is required.

## Repository contents

```text
lab05.html
images/
  mycat.jpg
  mycat_small.jpg
styles/
  lab04.css
  layout.css
  dl.css
  images/
    fade.jpg
README.md
VALIDATION.md
.gitignore
```

Copy the contents of this folder into the root of the lab05 repository. The
assignment's page is named `lab05.html`; when using GitHub Pages, open that file's
URL explicitly.

## Completed work

- Linked `lab04.css`, `layout.css`, and `dl.css` in that order.
- Restored the aside on hover, displayed the menu paragraphs inline, and applied
  the required header, aside, figure, and footer styling.
- Used floats, 50% section widths, table centering, and clear rules for the
  two-column layout. Kept list content left aligned and the article's required
  `30em` minimum width.
- Added the footer's first-child, nth-child(2), and last-child selectors, using
  valid `text-align: right` syntax in place of the handout's typo.
- Linked the provided definition-list stylesheet, including its `::after` example.
- Fixed the in-page Lists link (`#list` became `#lists`). Updated the starter's
  retired Blackboard destination and wording to Swinburne Canvas. The supplied
  `mailto:someone@swin.edu.au` remains a teaching example.
- Removed redundant trailing slashes on HTML void elements and corrected two
  small typos in the aside text.

## Supplied resources and limits

`lab04.css` came from `Week05.zip`; `dl.css` came from `lab05.zip`. The fade image
and both cat images were also supplied. These five files are unchanged, with
their checksums verified against the originals. No replacement assets were
invented. The layout stylesheet's author name follows the supplied partial
stylesheet header.

The Canvas example screenshots and screenshot-only CSS snippets were not
accessible. All explicit requirements in the supplied Markdown were implemented.
Where the text did not specify the aside's exact border or spacing values,
`layout.css` uses a 4px inset purple border, 1em margin/padding, a 14px radius,
and the supplied fade image repeated horizontally. Exact comparison with those
Canvas screenshots remains unavailable.

The handout explicitly requires `article { min-width: 30em; }`. At viewports
narrower than that width the page can scroll horizontally; the assignment's
float behavior has been retained.

No GitHub destination repository was supplied, so no remote commit or push was
performed. GitHub sign-in is needed only when publishing; no credentials are
included in, or required to open, this package.

See `VALIDATION.md` for the checks and verification limits.
