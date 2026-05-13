# Rehavid – Recolector de Información para el Boletín Interno

App web para recolectar la información mensual de cada área administrativa y generar automáticamente el JSON del boletín interno.

## Archivos incluidos

```
rehavid-boletin/
├── index.html      ← App recolectora (este archivo se despliega en GitHub Pages)
└── boletin.html    ← Plantilla del boletín mensual (se actualiza con el JSON)
```

---

## Cómo subir a GitHub Pages (paso a paso)

### Paso 1 — Crear el repositorio

1. Ve a [github.com](https://github.com) e inicia sesión.
2. Haz clic en **New repository** (botón verde, esquina superior derecha).
3. Nombre: `rehavid-boletin` (sin espacios, en minúsculas).
4. Selecciona **Public**.
5. Haz clic en **Create repository**.

### Paso 2 — Subir los archivos

1. En la página del repositorio recién creado, haz clic en **uploading an existing file**.
2. Arrastra los archivos `index.html` y `boletin.html` al área indicada.
3. En la parte inferior escribe el mensaje: `Primer deploy boletín Rehavid`.
4. Haz clic en **Commit changes**.

### Paso 3 — Activar GitHub Pages

1. Ve a la pestaña **Settings** del repositorio.
2. En el menú lateral izquierdo, haz clic en **Pages**.
3. En **Source**, selecciona la rama `main` y la carpeta `/ (root)`.
4. Haz clic en **Save**.

### Paso 4 — Obtener la URL

Después de 1-2 minutos, GitHub Pages genera la URL:

```
https://TU_USUARIO.github.io/rehavid-boletin/
```

Esa URL la compartes con tu equipo por WhatsApp, correo o Teams.

---

## Flujo mensual de uso

```
Cada área llena el formulario  →  Genera JSON  →  Pegar en boletin.html  →  Distribuir
```

1. El responsable abre la URL, completa su sección y copia el JSON.
2. El editor del boletín recibe los JSON de todas las áreas.
3. Abre `boletin.html`, reemplaza el objeto `BD` con el JSON consolidado.
4. Guarda y envía `boletin.html` por correo a todo el equipo.

---

## Para actualizar los archivos en GitHub

1. Ve al repositorio en github.com.
2. Haz clic en el archivo que quieres actualizar.
3. Haz clic en el ícono del lápiz (editar).
4. Pega el contenido nuevo y haz clic en **Commit changes**.

Los cambios se reflejan en la URL en menos de 1 minuto.
