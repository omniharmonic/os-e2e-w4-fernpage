# Import report: os-e2e-w4-fernpage

Imported from fernhollow.html on 2026-10-28 with `openspace import html`.
Sources: the page's HTML and CSS. 2 requests.

## Summary

- **1** pages, **0** collection items in 0 collection(s)
- **2** media files (0.1 MB) downloaded into `media/`
- **0** redirects so old addresses keep working
- **0** item(s) need your attention (below)

## Pages

| Old address | OpenSpace | Title | Sections | Blocks |
| --- | --- | --- | ---: | ---: |
| `/` | `/` | Grow something slow and lovely | 1 | 1 |

## Design

The look was recreated with OpenSpace's own design system (Site Styles tokens, section color themes, layouts and section presets), not by copying the original site's CSS or code.

- Brand color #c86b3c (the site's accent color).
- Fonts on the original site: Work Sans → pairing "Young Serif & Work Sans" (Young Serif / Work Sans), same family for Work Sans. Licensed fonts can be uploaded in Site Styles → Fonts.
- The contrast solver adjusted 6 color pairing(s) so every section theme meets WCAG AA (e.g. light accent-hover, light accent-pressed).
- Page background #f6f0e4 on the original site → #fef9f5 (text contrast 15.5:1).

Design check: 0 error(s), 15 warning(s).

- warning (site): Your custom background color is hard to read in the light theme: accent-hover on background (2.61:1, needs 3:1); accent-pressed on background (2.08:1, needs 3:1). It's adjusted automatically when published.
- warning (/): “Grow something slow and lovely” has no clear call to action — nothing tells visitors what to do next.
- warning (/): Four sections in a row use the light color theme, so the page reads as one long block.
- warning (site): The Grow something slow and lovely section uses 2 fixed colours, so Site Styles can't restyle them.
- warning (site): The Grow something slow and lovely section switches layout at 760px, not at OpenSpace's phone/tablet/desktop sizes.
- warning (site): The What you’ll find here section uses 3 fixed colours, so Site Styles can't restyle them.
- warning (site): The What you’ll find here section switches layout at 760px, not at OpenSpace's phone/tablet/desktop sizes.
- warning (site): The Started on a back porch section uses 1 fixed colour, so Site Styles can't restyle it.
- warning (site): The Started on a back porch section switches layout at 760px, not at OpenSpace's phone/tablet/desktop sizes.
- warning (site): The Section section uses 1 fixed colour, so Site Styles can't restyle it.
- warning (site): The Section section switches layout at 760px, not at OpenSpace's phone/tablet/desktop sizes.
- warning (site): The Come and wander section uses 2 fixed colours, so Site Styles can't restyle them.
- … and 3 more: run Design check in Studio or `design_check` with Claude.

## Needs attention

Nothing: every page, block and link was mapped.

## Not moved by the importer

- Scripts, animations and anything rendered only by JavaScript (try `--render` for script-built pages).
- Server-side features: shops, logins, search, comments.
- Form submissions, newsletter subscribers, member accounts and comments.
- Analytics and SEO history (search engines follow the redirects).

## Next steps

1. `npm install`, then `npx openspace check` (it should report no errors) and `npx openspace dev` to look around.
2. Bring it to visual parity with Claude: in this folder run `claude`, then `/openspace:migrate https://site.openspace.invalid` (or ask Claude to compare each page with the original). It screenshots both sites at desktop and mobile and adjusts presets, Site Styles and sections — never raw HTML.
3. Fix the items under **Needs attention**, then publish (push to GitHub, or `publish` with Claude).
4. Move the domain only after the new site is live and checked:
   - add the custom domain in OpenSpace (`deploy.customDomain` in `openspace.json`, or the Hub);
   - at your DNS provider (your registrar or elsewhere), point the records at the new host as the domain guide says (GitHub Pages: `A`/`CNAME` records; Cloudflare: the Pages project's records);
   - keep the old hosting until the new site serves your domain over HTTPS and the redirects work; then cancel it (and transfer the domain if you like).


## Designed sections

6 sections keep their own design as a designer component. Every word, picture and link in them is a field you edit in Studio; the design itself changes only through Component code (designers) or Claude.

| Section | Page | Fields | CSS |
|---|---|---|---|
| Grow something slow and lovely (`hero`) | / | 7 | 1.5 KB |
| What you’ll find here (`plants`) | / | 3 | 1.3 KB |
| Started on a back porch (`story`) | / | 5 | 1.3 KB |
| Section (`quote`) | / | 2 | 0.9 KB |
| Come and wander (`visit`) | / | 4 | 1.1 KB |
| Footer (`site-footer`) | footer | 1 | 0.9 KB |
