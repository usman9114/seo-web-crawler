# Brief: README hero and social preview

Date: 2026-11-26. Output: `docs/assets/hero-art.png` (AI illustration, no text), composed with real type into `docs/assets/hero.jpg` (README banner) and `docs/assets/social-preview.jpg` (1280x640, upload in GitHub Settings, Social preview). The exact prompt, model and time are in `docs/assets/hero-art.png.json`. References are inspiration only; none was used as an image input or copied.

## What a newcomer must see
Give it a URL and a keyword; it inspects the page and flags what to fix.

## References
| Reference | What works | Taken / avoided |
|---|---|---|
| [seoscan](https://github.com/Recognity/seoscan) (opened) | One-line tagline, one install command, a table of 11 checks, no banner | Tagline plus checks; the art adds the "inspect a page" idea |
| [On-Page SEO Analyzer](https://github.com/AgriciDaniel/on-page-seo) (opened) | A dashboard screenshot right under the description, but its alt text is generic | Early visual, with descriptive alt text |
| [Lighthouse](https://github.com/GoogleChrome/lighthouse) (opened) | Names the score categories in text; screenshot lower down | Keep category names in README text |

Research note: all three lead with text; a stylised wireframe plus lens makes the repo recognisable at a glance without implying real scores.

## Design (revised 2026-11-26)

- **Style:** Bold flat sticker vector with halftone.
- **Why this picture:** A crawler that checks pages. A monocled spider inspecting web-page tiles is the idea made friendly, and it is the most playful of the set on purpose.
- **Subject:** a cartoon spider with a monocle on a web whose nodes are browser-window tiles, holding a magnifier to a tile with a green check, another tile with an orange warning badge. Palette: grape purple, electric lime, hot pink, white outlines.
- **Layout:** the left third stays quiet for the title; colours and font of the title are set per image in `compose_banner.py`.
- **Must not contain:** text, letters, numbers, logos, watermarks, borders, real people, robots.
- **QA:** schema check by a vision model against this brief, plus a manual look.

## Revision note

The first version of this banner used the same dark navy, teal and grid look as the owner's other repos. It was consistent but samey, so it was replaced with a distinct art direction per repo, each built on a metaphor for what the repo does.
