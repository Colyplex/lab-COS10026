# Validation report

Checked on 15 October 2026 (Asia/Bangkok). These results apply to the final
HTML/CSS files included in this package.

## Official W3C validation

| File | Validator | Result |
| --- | --- | --- |
| `lab05.html` | Nu HTML Checker, version 26.10.12 | 0 errors, 0 warnings, 0 informational messages |
| `styles/lab04.css` | W3C CSS Validator, CSS3 profile | Valid; 0 errors, 0 warnings |
| `styles/layout.css` | W3C CSS Validator, CSS3 profile | Valid; 0 errors, 0 warnings |
| `styles/dl.css` | W3C CSS Validator, CSS3 profile | Valid; 0 errors, 0 warnings |

The final files were submitted directly to the official
[Nu HTML Checker](https://validator.w3.org/nu/) and
[W3C CSS Validator](https://jigsaw.w3.org/css-validator/).
Every final response returned HTTP 200. CSS validation used the documented SOAP
format after an initial response-format attempt returned server errors. Earlier
HTML formatting notices were resolved before the final successful check.

## Local checks

- The page returned HTTP 200 from a temporary local static server.
- Every local HTML link/image reference and CSS background image resolves to an
  included file, with filename case checked for case-sensitive hosting.
- All seven fragment links resolve to the six unique section IDs.
- Stylesheets load in the required order: lab04, layout, then dl.
- HTML opening/closing tags balance, with no duplicate IDs.
- Both supplied stylesheets and all three JPEG files match their source files
  byte for byte using SHA-256 checksums. The JPEGs also decode successfully.
- Image dimensions are 1600 x 1200 (full cat), 160 x 120 (thumbnail), and
  14 x 110 (fade).
- Independent source review confirms the explicit layout/selector requirements
  in the supplied Markdown are implemented.
- The ZIP was reopened and all archived file contents were compared with the
  final repository files. Mac metadata and temporary working files are excluded.

## Verification limits

The app's browser security policy prevented browser inspection of the local
preview. Visual appearance, hover behavior, and viewport resizing were therefore
not observed in a browser. Source review and W3C validation do not constitute a
visual comparison.

The Canvas reference screenshots could not be accessed; their exact appearance
and screenshot-only code values were not verified. `README.md` documents the
aside choices and the assignment's required minimum-width behavior.

The original Blackboard link opens an official
[decommissioning notice](https://ilearn.swin.edu.au/); its demonstration link was
updated to the Canvas domain already present in the supplied assignment. Canvas
course access and the example email recipient were not authenticated or tested
as user accounts. No GitHub push was performed because a destination repository
was not supplied.
