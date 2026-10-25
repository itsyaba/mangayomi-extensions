# itsyaba's Mangayomi extensions

Extensions not (yet) in [m2k3a/mangayomi-extensions](https://github.com/m2k3a/mangayomi-extensions). Add this next to that repo, not instead of it.

In Mangayomi: More → Settings → Browse → add a manga repository:

```
https://raw.githubusercontent.com/itsyaba/mangayomi-extensions/repo/index.json
```

| Source | Site |
| --- | --- |
| MangaGeko | https://www.mgeko.cc |
| Manga18fx (18+) | https://manga18fx.com |
| Manga Demon | https://demonicscans.org |
| Vortex Scans | https://vortexscans.org |
| Hivetoons | https://hivetoons.org |
| Thunder Scans | https://en-thunderscans.com |
| Flame Comics | https://flamecomics.xyz |
| VoyceMe | https://www.voyce.me |
| Asura Scans | https://asurascans.com |
| MangaDex (English) | https://mangadex.org |

Asura Scans and MangaDex are m2k3a's extensions with one change: their `getHeaders()` no longer reads
source settings, which makes installing them fail silently on Mangayomi 0.9.9
(fixed upstream in kodjodevf/mangayomi#1093). Once that fix ships, use m2k3a's versions instead.

MangaGeko is also proposed upstream in m2k3a/mangayomi-extensions#73.
