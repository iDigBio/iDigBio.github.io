Lacking any way of defining redirects in GitHub Pages,
we work around that by using [index.html](index.html) to prevent directory listings at web root
and [/404.html](404.html) to handle any other requested URL that is not [/we-moved.html](we-moved.html),
which is how we've been doing this static landing page before porting this to GitHub Pages.

[/portal/index.html](/portal/index.html) emulates the redirect rule we've had for the
[iDigBio Portal](https://portal.idigbio.org/).


**Effective 20 Nov 2026, iDigBio's [GBIF Hosted Portal](https://idigbio.gbif.us/) is the new official website/portal.**
**Web traffic will be redirected to <https://idigbio.gbif.us/> instead of [/we-moved.html](we-moved.html).**
**Portal traffic will be redirected to the [integrated search portal](https://idigbio.gbif.us/occurrence/search) instead of <https://portal.idigbio.org/>.**
