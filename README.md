# O uso educativo da intelixencia artificial - Guía práctica

Repositorio da guía en liña construída con MkDocs e o tema Material para apoiar ao profesorado no uso responsable da intelixencia artificial na aula.

## Contido
- Guía principal con 15 capítulos (introdución, aplicacións na aula, prompting, proxectos, avaliación, marco legal e futuro da IA educativa).
- Anexos con guías rápidas, plantillas de prompts, ferramentas para profesorado e alumnado, checklist legal, glosario e recursos recomendados.
- Páxina «Sobre o autor» con información profesional.

## Requisitos
- Python 3.9+
- [MkDocs Material](https://squidfunk.github.io/mkdocs-material/) (`pip install mkdocs-material`)

## Uso local
1) (Opcional) Crear e activar un entorno virtual de Python.
2) Instalar a dependencia: `pip install mkdocs-material`.
3) Servir en local con recarga en quente: `mkdocs serve` (abre en http://localhost:8000).
4) Xerar a web estática: `mkdocs build` (resultado en `site/`).

## Estrutura do proxecto
- `mkdocs.yml`: configuración de navegación, idioma (gl) e tema.
- `contenido/`: documentos Markdown da guía (`index.md`, `capitulo*.md`, `anexo*.md`), carpeta `about/`, imaxes en `media/` e estilos en `styles/extra.css`.
- `.github/workflows/deploy.yml`: fluxo de GitHub Actions para despregar en GitHub Pages.
- `.gitignore`: ignora artefactos de construción e cachés.

## Despregue
- Cada `push` a `main` executa o fluxo de accións: instala `mkdocs-material`, executa `mkdocs build --strict` e publica o contido en GitHub Pages.
- Actualiza `site_url` en `mkdocs.yml` e activa Pages no repositorio para que a URL pública sexa correcta.

## Licenza e autor
- Contido licenciado baixo [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.gl).
- Autor: Javier Feijóo López · [LinkedIn](https://www.linkedin.com/in/javierfeijoolopez/).
