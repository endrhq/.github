# [05/001] PROFILE MAINTENANCE

The public organization profile lives in `profile/README.md`. The root `README.md` mirrors it so the profile repository presents the same company identity. GitHub requires these discovery paths.

## [05/002] VISUAL IDENTITY

The banner uses endr’s branching mark and outlined lowercase wordmark, warm ivory, graphite, and muted olive. The contour geometry and network are original conceptual illustrations; they contain no geographic, mission, or performance data.

The branching mark follows the founder-supplied website identity. The outlined wordmark uses Cormorant Garamond, distributed under the SIL Open Font License. The existing company avatar uses the same branching mark. No external image service, tracking badge, JavaScript, or animation is required.

Banner URLs pin the asset commit so updates display consistently without waiting for raw-file caches. Refresh both image references when publishing revised artwork.

Desktop and mobile SVGs are in `profile/[endr][assets][github]/`. The profile uses absolute, encoded raw GitHub URLs so images resolve from both the organization page and repository page.

## [05/003] SECTION DESIGNATORS

Use `[SS/III] TITLE` for visible document headings: two digits identify the section family, and three identify the entry within that family. Keep titles uppercase and the company name `endr` lowercase. Use brackets without numeric codes for navigation and short status labels.

| Family | Subject |
| :--- | :--- |
| `[00]` | Company brief |
| `[01]` | Platform architecture and command principles |
| `[02]` | Validation objective |
| `[03]` | Development status and evidence |
| `[04]` | Contact |
| `[05]` | Profile maintenance |

Keep `[01/002] COMMAND PRINCIPLES` subordinate to `[01/001] PLATFORM ARCHITECTURE`. The profile and detailed status document share `[03/001] DEVELOPMENT STATUS` as their reference point. Repository paths continue to follow the existing endr naming convention; these designators label displayed sections.

## [05/004] PUBLICATION PROCEDURE

Keep the two READMEs synchronized. Update the dated public development-status record only when supporting evidence changes. Keep planned mission capabilities separate from implemented internal software. Preserve historical records.

Before publication, render Markdown through GitHub, inspect both desktop and mobile layouts, verify image loading and links, and check the final diff. The public profile is descriptive company information, not a product release or operational capability announcement.

[Development status](<[endr][repository][profile-status].md>) · [Organization](https://github.com/endrhq)
