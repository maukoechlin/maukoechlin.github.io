# maukoechlin.github.io

Sitio académico, hecho en Quarto.

## Editar

Los archivos de contenido son los `.qmd`:

- `index.qmd` — About
- `research.qmd` — papers
- `teaching.qmd` — cursos
- `notes.qmd` — ideas en proceso

Son markdown. No hace falta tocar HTML.

## Previsualizar

```
/Applications/RStudio.app/Contents/Resources/app/quarto/bin/quarto preview
```

## Publicar

```
/Applications/RStudio.app/Contents/Resources/app/quarto/bin/quarto render
```

Luego commit y push. GitHub Pages sirve la carpeta `docs/`.

## Configuración de GitHub Pages (una sola vez)

Settings → Pages → Source: *Deploy from a branch* → rama `main`, carpeta `/docs`.

## OJO

El repositorio es **público**. Nunca pongas aquí datos de participantes ni nada
de Box.
