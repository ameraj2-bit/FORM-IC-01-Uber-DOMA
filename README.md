# FORM-IC-01 — Arquitectura DOMA de Uber

Investigación individual sobre la arquitectura de microservicios orientada a dominios (DOMA, *Domain-Oriented Microservice Architecture*) de Uber.

- **Asignatura:** Aplicaciones Distribuidas — UTEQ
- **Autora:** Mera Jumbo Allison Michelle
- **Estilo arquitectónico:** Microservicios

## Estructura del repositorio

| Archivo / carpeta | Contenido |
|---|---|
| `main.tex` | Documento principal del análisis |
| `referencias.bib` | Referencias en formato IEEE (biblatex) |
| `capturas/` | Capturas de la fuente principal con anotaciones |
| `main.pdf` | Documento compilado |

## Requisitos

- Distribución LaTeX: **MiKTeX** o **TeX Live**
- **biber** (incluido en MiKTeX y TeX Live)
- Paquetes: `biblatex` (estilo `ieee`), `babel` (spanish), `csquotes`, `graphicx`, `geometry`, `hyperref`

## Compilación

- **Compilador:** `pdflatex`
- **Archivo principal:** `main.tex`

Ejecutar en este orden desde la raíz del repositorio:

```bash
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

El resultado es `main.pdf`.