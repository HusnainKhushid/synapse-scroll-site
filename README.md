# Synapse — Systems that answer first

Scroll-driven landing page: six pinned stages (hero that tips away, CSS-3D card reel, WebGL particle field, horizontal work rail, parallax mosaic, chrome-star CTA). Next.js 15 static export. Built for the Scroll Sites marketplace, iframe-ready.

- `npm run dev` / `npm run build` → `out/` (`BASE_PATH=/repo-name` for GitHub Pages; leave unset on Vercel)

## Live URLs
- **Primary (Vercel):** https://synapse-scroll-site.vercel.app — this is the URL the marketplace embeds in its iframe.
- Mirror (GitHub Pages): https://husnainkhushid.github.io/synapse-scroll-site/

Both deploy automatically on push to `main`.

## For the coding agent
Section resources live in the marketplace workspace under `02-sections/synapse/`. Section ids: `00-nav 01-hero 02-reel 03-neural 04-work 05-mosaic 06-cta 07-footer`. DOM anchors: `#top #reel #neural #work #mosaic #cta #footer`. iframe bridge: posts `{ source:'scroll-site', type:'sections'|'section' }`, accepts `{ type:'scrollTo', id }`.
