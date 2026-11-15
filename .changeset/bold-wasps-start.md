---
'astro': patch
---

Fixes a `CannotFetchFontFile` build error when using `fontProviders.npm({ remote: false })` by reading the installed font files from the file system
