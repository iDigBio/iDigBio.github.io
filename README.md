Lacking any way of defining redirects in GitHub Pages,
we work around that by using [index.html](index.html) to prevent directory listings at web root
and [/404.html](404.html) to handle any other requested URL that is not [/we-moved.html](we-moved.html),
which is how we've been doing this static landing page before porting this to GitHub Pages.

[/portal/index.html](/portal/index.html) emulates the redirect rule we've had for the
[iDigBio Portal](https://portal.idigbio.org/).
