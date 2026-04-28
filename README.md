# zaeinstore-subtitles

Public CDN-backed storage for auto-extracted WebVTT subtitle tracks.

This repo is **public** so jsDelivr can serve its files at:

```
https://cdn.jsdelivr.net/gh/<owner>/zaeinstore-subtitles@latest/subtitles/<slug>/...
```

Pushed to automatically by [`zaeinstore-processor`](../zaeinstore-processor) GitHub Actions. Do not edit `subtitles/` by hand.

## Structure

- Movies: `subtitles/<slug>/movie_<lang>.vtt`
- Series: `subtitles/<slug>/s<NN>/E<NN>_<lang>.vtt`

`<slug>` is a lowercased, dash-separated form of the film title.
`<lang>` is a 2-letter ISO 639-1 code (`id`, `en`, `ja`, …).
