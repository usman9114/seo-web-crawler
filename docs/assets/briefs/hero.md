# Brief: README hero and social preview

Date: 2026-11-26. Output: `docs/assets/hero-art.png` (AI illustration, no text), composed with real type into `docs/assets/hero.png` (README banner) and `docs/assets/social-preview.png` (1280x640, upload in GitHub Settings, Social preview). The exact prompt, model and time are in `docs/assets/hero-art.png.json`. References are inspiration only; none was used as an image input or copied.

## What a newcomer must see
Give it a URL and a keyword; it inspects the page and flags what to fix.

## References
| Reference | What works | Taken / avoided |
|---|---|---|
| [seoscan](https://github.com/Recognity/seoscan) (opened) | One-line tagline, one install command, a table of 11 checks, no banner | Tagline plus checks; the art adds the "inspect a page" idea |
| [On-Page SEO Analyzer](https://github.com/AgriciDaniel/on-page-seo) (opened) | A dashboard screenshot right under the description, but its alt text is generic | Early visual, with descriptive alt text |
| [Lighthouse](https://github.com/GoogleChrome/lighthouse) (opened) | Names the score categories in text; screenshot lower down | Keep category names in README text |

Research note: all three lead with text; a stylised wireframe plus lens makes the repo recognisable at a glance without implying real scores.

## Design
- **Subject:** an isometric browser-window wireframe (blank title bar, heading block, image placeholder, text lines) under a glowing magnifying lens, green check markers beside most elements and one amber warning.
- **Palette and style (shared across the owner's repos):** deep navy ink (#0B1020), teal/green highlight, amber for the exception, soft glow, faint perspective grid, minimal and not photoreal. Subject in the right two-thirds, calm empty left third for the title.
- **Must not contain:** text, letters, numbers, logos, watermarks, borders, people, robots, brains.
- **QA:** schema check by vision model against this brief, plus a manual look. Result noted in the commit.
