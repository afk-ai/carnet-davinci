# Carnet QR · DaVinci Corporación Educativa

Mini sistema sin servidor: lee `estudiantes.xlsx`, genera el QR de cada cédula y verifica el carnet al escanearlo.

## Publicar en GitHub (3 pasos)
1. Crea un repositorio y sube `index.html`, `estudiantes.xlsx` y este `README.md`.
2. Ve a **Settings → Pages → Source: Deploy from a branch → `main` / root** → Save.
3. Abre `https://TU-USUARIO.github.io/NOMBRE-REPO/`

## Uso
- **Generar:** escribe la cédula (con o sin puntos) → *Generar QR* → *Descargar PNG* (o ZIP con todos).
- **Colocar en el carnet:** inserta el PNG en tu diseño (Canva) en el espacio libre del frente o reverso.
- **Verificar:** al escanear el QR se abre la página con nombre, cédula, curso y si está *Activo* o *Inactivo*.

## Base de datos
Edita `estudiantes.xlsx` (columnas: `cedula, nombre, telefono, curso, estado`) y súbelo de nuevo al repo.
Para dar de baja un carnet, pon `Inactivo` en `estado`. Guarda la cédula como texto.

## Privacidad
En GitHub Pages el Excel es público. Si no quieres exponer teléfonos, elimina esa columna
o usa un repositorio/hosting privado.

## Local
Abre `index.html` con doble clic y selecciona el Excel manualmente cuando lo pida.
