# Portfolio personal

Proyecto sencillo de portfolio personal desarrollado como práctica de diseño web con HTML, CSS y Sass. La web está estructurada en varias páginas y ofrece una experiencia básica de presentación personal con secciones de inicio, información sobre el autor y formulario de contacto.

## Descripción

Este repositorio contiene un sitio web estático para presentar un perfil personal en el contexto de un proyecto de Desarrollo de Aplicaciones Web (DAW). El objetivo principal es mostrar la identidad del desarrollador, sus habilidades y una forma de contacto sencilla, integrando estilos reutilizables y una organización modular con Sass.

## Características

- Diseño de una página personal con navegación por secciones.
- Páginas principales:
  - `index.html` para la portada/inicio.
  - `sobre.html` para la información personal y habilidades.
  - `contacto.html` para un formulario de contacto.
- Estilos centralizados en `css/principal.css`.
- Organización modular de estilos con Sass en `scss/`.
- Uso de variables, mixins y parciales para mantener el código más ordenado.
- Compatibilidad con navegadores modernos y estructura semántica en HTML5.

## Estructura del proyecto

```text
proyecto-refactorizado/
├── README.md
├── index.html
├── sobre.html
├── contacto.html
├── css/
│   ├── principal.css
│   └── principal.css.map
├── scss/
│   ├── _comunes.scss
│   ├── _inicio.scss
│   ├── _mezclas.scss
│   ├── _sobre.scss
│   ├── _variables.scss
│   └── principal.scss
```

## Tecnologías utilizadas

- HTML5
- CSS3
- Sass
- Fuentes externas de Google Fonts

## Cómo ejecutar el proyecto

### Opción 1: abrir directamente

Simplemente abre cualquiera de los archivos HTML en tu navegador, por ejemplo:

```bash
index.html
```

### Opción 2: servidor local

Si prefieres visualizarlo como un sitio web local con servidor, puedes ejecutar:

```bash
python -m http.server 8000
```

Luego accede a:

```text
http://localhost:8000
```

## Compilación de Sass

Si quieres modificar los estilos y recompilar el archivo CSS generado, puedes usar Sass desde la raíz del proyecto:

```bash
sass --watch scss/principal.scss css/principal.css
```

Esto permite mantener sincronizados los cambios escritos en los archivos `.scss` con la hoja final CSS.

## Validación CSS

La hoja `css/principal.css` ha sido validada con el [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) para CSS3, obteniendo **0 errores**. El validador mostró 10 avisos, principalmente relacionados con la validación de archivos importados cuando se cargan directamente desde disco.

## Estado del proyecto

Es un proyecto de carácter educativo y de práctica, en constante evolución. Actualmente presenta una base funcional para una web personal, y está preparado para continuar ampliándose con más secciones, proyectos, experiencia profesional o diseño más avanzado.

## Autor

Proyecto personal desarrollado como ejercicio de aprendizaje en diseño y desarrollo web.
