# Mi Proyecto Web

Sitio web sencillo hecho solo con HTML para practicar el control de versiones con **Git** y **GitHub**: repositorio local y remoto, trabajo por ramas, commits descriptivos y Pull Requests.

## Tabla de contenido

- [Descripción](#descripción)
- [Instalación](#instalación)
- [Estructura](#estructura)
- [Mejoras implementadas](#mejoras-implementadas)
- [Flujo de trabajo con Git](#flujo-de-trabajo-con-git)
- [Autor](#autor)

## Descripción

El proyecto parte de un `index.html` básico y se amplía con mejoras desarrolladas cada una en su propia rama `feature/*`. Cada rama se sube a GitHub y se integra en `main` mediante un Pull Request.

## Instalación

1. Clona el repositorio:

   ```bash
   git clone https://github.com/dzeledonj-create/mi-proyecto-web.git
   ```

2. Entra en la carpeta del proyecto:

   ```bash
   cd mi-proyecto-web
   ```

3. Abre `index.html` en cualquier navegador web. No necesita servidor ni dependencias.

## Estructura

```
mi-proyecto-web/
├── .gitignore   # Excluye .vscode/, archivos del sistema y temporales
├── index.html   # Página principal del sitio
└── README.md    # Documentación del proyecto
```

## Mejoras implementadas

| Mejora | Rama | Pull Request | Descripción |
| --- | --- | --- | --- |
| Menú de navegación | `feature/menu` | [#1](https://github.com/dzeledonj-create/mi-proyecto-web/pull/1) | Menú en `<nav>` con enlaces internos a las secciones de la página. |
| Tabla de horario | `feature/tabla` | [#2](https://github.com/dzeledonj-create/mi-proyecto-web/pull/2) | Tabla con el horario semanal de clases y enlace en el menú. |
| Footer con redes sociales | `feature/footer` | [#3](https://github.com/dzeledonj-create/mi-proyecto-web/pull/3) | Pie de página con enlaces de texto a redes sociales. |

## Flujo de trabajo con Git

1. Crear una rama para cada mejora: `git checkout -b feature/nombre-mejora`.
2. Modificar `index.html` y hacer commits descriptivos.
3. Subir la rama: `git push origin feature/nombre-mejora`.
4. Abrir un Pull Request en GitHub y fusionarlo con `main`.
5. Actualizar `main` en local: `git checkout main` y `git pull origin main`.

## Autor

[dzeledonj-create](https://github.com/dzeledonj-create)
