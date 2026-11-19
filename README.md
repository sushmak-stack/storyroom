# Storyroom

Storyboard dashboards for the Social Beat production team, deployed on Netlify from this repo.

| Path | What it is |
|---|---|
| `/` | Landing page |
| `/grt/` | Storyroom · GRT Jewellers (BAU rows, festival topicals, PRISM import, products, dress & continuity lock, Gemini frames, QC flags) |
| `/studio/` | Storyroom Studio, the general board for any client |

Every push to `main` redeploys the site on Netlify. Roll back from Netlify → Deploys if a change misbehaves.

On Netlify, boards save in each person's browser only. The claude.ai version adds shared team boards, Claude features and Google Slides export.

The GRT edition uses its own browser-storage key (`storyroom-grt-v1`) so it doesn't mix with the Studio board on the same site.
