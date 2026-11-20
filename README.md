# Bryan Cee

The Hugo source for Bryan Cee’s artist website. The published-site URLs are configured for `https://www.bryancee.net/`. Build and preview commands run locally.

## Preview

Requires Hugo 0.158 or newer. The site was built with Hugo 0.168.0.

```sh
hugo server
```

Open [the local Hugo preview](http://localhost:1313/). Run `hugo` to produce the static site in `public/`.

## Update the site

- Edit the homepage introduction, bio, and contact copy under [content](content/).
- Edit album summaries, track lists, liner notes, SoundCloud players, and external `listenLink` URLs under [content/album](content/album/).
- Edit the booking email and social profiles in [hugo.toml](hugo.toml).
- Add upcoming performances to the front matter in [content/live.md](content/live.md). Remove entries once the shows have passed.

```toml
[[shows]]
date = 'YYYY-MM-DD'
venue = 'Venue name'
location = 'City, State'
url = 'https://example.com/tickets'
```

The [archive index](site-archive-2026-11-20/README.md) contains the original site copy and assets. The redesigned site uses optimized WebP versions of the portrait and album artwork. SoundCloud serves the album players.

## Design references

The supplied [desktop mockup](design/homepage-desktop.png), [mobile mockup](design/homepage-mobile.png), and [visual style guide](design/visual-style-guide.png) are saved with the project. Shared color, type, and layout rules live in [the site stylesheet](assets/css/site.css). Homepage headlines and the introduction live in [the homepage content file](content/_index.md).

The desktop and phone hero images are art-directed composites based on the supplied mockups. WebP production files live under `static/images/brand/` with textures and decorative details taken from the mockups. The archived artist portrait and album covers are retained separately.
