# urriiy.github.io

Personal homepage of Law Yi Ru — Department of Automation, Tsinghua University.

`index.html` is self-contained: the portrait is embedded in the file as a data URI, so the
page needs no other assets to render.

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

## Publishing

Pushed to `main`; served by GitHub Pages from the repository root at
<https://urriiy.github.io>.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The page. Portrait embedded; upload alone. |
| `photo.jpg` | Source crop of the portrait, 512x512. |
| `index-external-photo.html` | Same page loading `photo.jpg` externally (not published). |
