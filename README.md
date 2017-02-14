glanche
=======

[GAM](https://github.com/jay0lee/GAM) is pretty sweet if you want to manage
Google G Suite from the command line.

I miss
[`blanche`](https://kb.mit.edu/confluence/pages/viewpage.action?pageId=3907064#HowdoIadministeranAthena%28Moira%29listorgroup%3F-blanche)
from MIT's [Athena](https://en.wikipedia.org/wiki/Project_Athena), though, so I
wrote a wrapper for `gam`'s Google Groups functionality that feels very familiar.

It is not feature-complete; I implemented the pieces I needed and left it at
that. PRs very welcome! In particular, you may notice that all mailing lists
are unmoderated, allow external members (invited by list managers), etc. (This
fits, mostly, with the Moira lists `blanche` was used to manage.)

## Installation
There's just one file, `glanche`. `gam` installs itself to `~/bin/gam/gam`, so I
recommend installing `gam` (see above link) and just dropping `glanche` in next
to it. `glanche` will prompt you to create a config file on first run.
