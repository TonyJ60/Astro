---
'astro': patch
---

Fixes `<ClientRouter />` writing the scroll position to the browser history on every frame of a scroll that a script animates with `window.scrollTo()`. In Safari these writes could hit its history rate limit and stop internal links from working for several seconds.
