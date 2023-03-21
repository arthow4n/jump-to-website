# jump-to-website

A redirection page so I can add website to home screen on Android ignoring the website's manifest.

## Motivation

Some websites uses [`manifest.json`](https://developer.mozilla.org/en-US/docs/Web/Manifest/display), so when the user adds the website to their home screen, the website can force itself to be opened in a standalone full screen activity instead of inside a browser tab, this makes using my own `https://arthow4n.github.io/web-swedish-reader/` bookmarklets a lot harder, because I need to escape the full screen somehow first and then open the page in a normal broser tab.

If I can add the website to my home screen indirectly by instead adding my own redirection page that's not opened in full screen, I can force the website to be opened in a normal browser tab while I can still have it on my home screen.