# to-floodreport

Redirects `floodreport.hyderabad.urbanobservatory.in`, Amruth's flood report form, to the observatory's own flood
report, `https://hyderabad.urbanobservatory.in/contribute/flood/` (15 Nov 2026; the old reports and photos were
copied over). The old app was one page, so every address lands on the new form. `404.html` is the same page, so deep
links are caught too. GitHub Pages cannot send server redirects, so this works in browsers only.
Takes effect once the `floodreport.hyderabad` DNS record at Cloudflare points at `hulf-observatory.github.io`
(CNAME, DNS only) instead of Amruth's Contabo server.
