# Blah language packs

Translations served by Blah DCs. `webk_bfb` is the Blah feedback widget platform.

Each language lives at `webk_bfb/<lang>/`, with `info.json` and one directory per
key. Plain strings use `value`; plurals use `zero`, `one`, `two`, `few`, `many`
and `other` (required). Text is UTF-8 with one final newline.

Publish versions with tags `webk_bfb-<lang>-v<N>` (for example `webk_bfb-en-v1`).
See [the language-pack guide](https://docs.blahim.com/guides/language-packs/).

`webk_bfb` holds only keys used by the widget. Custom widget keys start with `Bfb`.
