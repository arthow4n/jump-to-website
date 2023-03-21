# jump-to-website

A redirection page so I can add website to home screen on Android ignoring the website's manifest.

## Motivation

Some websites uses [`manifest.json`](https://developer.mozilla.org/en-US/docs/Web/Manifest/display) so when the user adds the website to their home screen, the website can control so it's opened in a standalone full screen instead of inside a browser tab, this makes using my own `https://arthow4n.github.io/web-swedish-reader/` bookmarklets a lot harder because I need to escape the full screen somehow and open the page in a normal broser tab. If I can add the website to my home screen indirectly on a redirection page which will be added to the home screen as opening a browser tab to the redirection page, then I can redirect to the website I actually wanted to have shortcut on my home screen without being forced into full screen.