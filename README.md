# Proyecto SASS - Trabajo Práctico

Proyecto simple realizado con HTML, SASS y CSS.

## Contenido

- `index.html`: página principal.
- `sass/estilos.scss`: archivo fuente de SASS.
- `css/estilos.css`: CSS compilado desde SASS.

## Conceptos de SASS utilizados

### Variables
Se utilizan variables para guardar colores y otros valores reutilizables.

### Anidamiento
Los selectores relacionados se escriben dentro de otros selectores para organizar mejor el código.

### Mixin
Se utiliza el mixin `centrado` para reutilizar las propiedades de Flexbox.

## Compilar SASS

Si SASS está instalado, ejecutar:

```bash
sass sass/estilos.scss css/estilos.css
```

Para observar los cambios automáticamente:

```bash
sass --watch sass/estilos.scss:css/estilos.css
```
