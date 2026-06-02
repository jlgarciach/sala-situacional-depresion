# ProyectoFinalDepresion modular

Estructura generada para separar cada pestaña del dashboard en archivos individuales.

## Archivos principales

- `ProyectoFinalDepresion.qmd`: archivo maestro. Solo contiene YAML, librerías e includes.
- `tabs/`: contiene una pestaña por archivo.
- `img/`: coloca aquí las imágenes usadas por el dashboard.

## Cómo usar

1.  Abre `ProyectoFinalDepresion.qmd` en RStudio.
2.  Mantén la carpeta `tabs/` en el mismo nivel que el archivo principal.
3.  Mantén la carpeta `img/` en el mismo nivel que el archivo principal.
4.  Renderiza normalmente con Quarto.

## Nota

Cada archivo dentro de `tabs/` inicia con un encabezado `#`, porque Quarto Dashboard lo interpreta como una pestaña principal.
