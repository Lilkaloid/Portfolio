# Content parked from yanranhuangfu.com (Squarespace)

Collected 2026-10-27 from the live site. Text is copied as-is (typos kept, flagged). Nothing here is published; GitHub Pages is not switched on.

## Layout
- `pages/` — one file per page: text, links, videos, flags, and the list of images in page order.
- `images-manifest.csv` — every image reference: page, order, local filename, original filename, source URL. 160 references, 135 unique files.
- `assets/` — image files. **Status: PENDING DOWNLOAD** (see below).

## Labels
| Label | Meaning |
|---|---|
| [MISSING-TEXT] | Expected info absent (role, team, engine, year, description, process) |
| [MISSING-IMAGE] / [THIN-VISUALS] | No or very few visuals |
| [MISSING-LINK] | Play/download link absent or empty |
| [MISSING-VIDEO] | No trailer/gameplay video |
| [VIDEO-NOT-DOWNLOADABLE] | Video hosted by Squarespace as a stream; need your original file |
| [CN-MISSING] | No Chinese version |
| [INCONSISTENT] | EN and CN (or two pages) disagree |
| [BROKEN-LINK] | Link returns 404 |
| [NO-PROJECT-PAGE] | Project only exists as a card linking off-site |
| [ORPHAN] | Page exists but nothing links to it |
| [TEMPLATE] / [EMPTY] / [DUPLICATE] | Squarespace leftovers, not your content |
| [TYPO?] | Possible typo, kept verbatim, needs your call |
| [CHECK] | Something I could not verify; needs your answer |
| [RISK] | Rights or exposure issue |

## Page index
| Page | Text | Visuals | Video | CN |
|---|---|---|---|---|
| Home `/` | complete | 14 | — | `/cn-1` |
| Games index | titles only | 11 | — | mixed in |
| Overtime | thin | **0** | 1 (Squarespace) | **none** |
| Weird Fishes | complete | 1 | 4 (Squarespace) | yes |
| Unwaking | complete | 6 | — | yes (shorter) |
| BALLOON | **thin** | 3 | — | yes |
| ORUU | complete | 1 | 1 (Squarespace) | yes |
| palipop!! | thin | 5 | — | **none** |
| Bunnysnail | thin | 7 | YouTube | **none** |
| Bitsy Elden Ring | thin | 7 | — | **none** |
| Flappy Balloon | complete | 9 | Vimeo | **none** |
| FARSTARX | **none** | 3 | — | **none** |
| GRAVITALIS | card only | — | — | card only |
| ZoOoOoO | card only | — | — | card only |
| Art & Animations | tiles | 1 | — | none |
| Game Art | headings only | 11 | — | none |
| Storyboard | titles only | 3 | — | none |
| Fine Art | 2 titles | 18 | 2 YouTube | none |
| Masterworks of Horror | **none** | 12 | — | none |
| 90 Day Project (orphan) | 1 line | 24 | — | none |

## Site-wide gaps
- [MISSING] No About page beyond the home intro; no CV/resume; no dedicated contact page (footer only).
- [MISSING] No alt text on any image.
- [MISSING] No favicon (Squarespace default).
- [MISSING] Projects not on the site: thesis (Aperture), AGP project (STHH), Tencent level design internship (Delta Force). Confirm what to add and what is under NDA.
- [CHECK] Artistic statement lives in Figma Make — keep as external link or rebuild on the site?
- Design reference from current site: fonts Young Serif + Bitter; dark hero, serif headings; nav = Games / Art & Animations / 中文主页.

## Images: how they get here
The Squarespace image CDN is blocked from Claude's workspace. Two options:
1. You allow `images.squarespace-cdn.com` in claude.ai Settings → Capabilities (network allowlist); I then download all 135 directly.
2. I package them in your browser pane into one zip (~170 MB, WebP) that downloads to your computer; you attach it or connect the folder.
Better still for quality: your original source files, if you have them.
