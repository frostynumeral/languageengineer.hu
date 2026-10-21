# languageengineer.hu

The source of [languageengineer.hu](https://languageengineer.hu): plain HTML and one stylesheet, no build step, served by GitHub Pages from `main`.

```
index.html, hu/index.html                                   home page (English, Hungarian)
schrodingerscat/index.html, hu/schrodingerscat/index.html   SchrödingersCAT
404.html                                                    not-found page (both languages)
assets/                                                     style.css, favicon.svg
CNAME, .nojekyll                                            custom domain; serve files as they are
```

Every page exists in both languages; when you change one, change its pair, and keep the `hreflang` links and the language switch pointing at each other.

To preview locally:

```bash
python3 -m http.server -d . 8000    # then open http://localhost:8000
```
