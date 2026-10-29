# Presentacion Personal - ASIR

Este repositorio contiene el codigo fuente de mi pagina web de presentacion personal, construida mediante el generador de sitios estaticos Hugo y basada en el tema Terminal. 

El diseno incluye una paleta de colores personalizada mediante CSS y una estructura orientada a mostrar el perfil profesional y habilidades tecnicas.

## Requisitos previos

Para poder ejecutar este proyecto en local, es necesario contar con:
- Git
- Hugo (se recomienda la version extended)

## Instrucciones de ejecucion local

Para descargar y visualizar el proyecto en tu propio equipo, sigue estos pasos desde la terminal:

1. **Clonar el repositorio**:
   ```bash
   git clone [https://github.com/LiaRobles27/mi-presentacion-github.git](https://github.com/LiaRobles27/mi-presentacion-github.git)
   ```

2. **Acceder al directorio**:
   ```bash
   cd mi-presentacion-github
   ```

3. **Arrancar el servidor de desarrollo**:
   ```bash
   hugo server -D
   ```

4. **Visualizar en el navegador**:
   Una vez iniciado el servidor, abre tu navegador y accede a la ruta asignada:
   http://localhost:1313/mi-presentacion-github/

## Tecnologias utilizadas

- **Hugo**: Framework de renderizado estatico.
- **Markdown**: Para la redaccion del contenido principal (`content/_index.md`).
- **CSS**: Estilos inyectados nativamente para el rediseño de la interfaz (`static/css/custom.css`).
EOF

git add README.md
git commit -m "Añadido archivo README con instrucciones de ejecucion"
git push
