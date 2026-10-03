# Imperio PokéYen

Aplicación web sobre PokeMMO, publicada con GitHub Pages. Los datos salen de
[Wiki-PokeMMO](https://github.com/Yimmer-R/Wiki-PokeMMO) (5.163 páginas Markdown,
mecánicas de 5.ª generación).

## Estructura

```
docs/   # lo que GitHub Pages publica. HTML/CSS/JS estático, sin paso de compilación.
```

## Publicar

Una sola vez, en **Settings → Pages** del repositorio: *Source* = `Deploy from a branch`,
rama `main`, carpeta `/docs`. A partir de ahí cada push a `main` se publica solo, sin
workflow ni Actions.

URL: https://yimmer-r.github.io/Imperio-PokeYen/
