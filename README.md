# 🧠 Obsidian Workshop

Vault de [Obsidian](https://obsidian.md) organizado en español, pensado como espacio de trabajo para notas, proyectos e ideas.

## 📂 Estructura

| Carpeta | Uso |
|---|---|
| `00 - Bandeja de entrada` | Captura rápida. Todo entra aquí primero y luego se procesa. |
| `01 - Notas` | Notas permanentes y de conceptos (tu base de conocimiento). |
| `02 - Proyectos` | Notas ligadas a proyectos activos con fecha de fin. |
| `03 - Recursos` | Referencias, artículos, enlaces y material de consulta. |
| `04 - Archivo` | Proyectos terminados y notas que ya no están activas. |
| `Plantillas` | Plantillas para crear notas nuevas (plugin *Templates* o *Templater*). |
| `Adjuntos` | Imágenes, PDFs y demás archivos adjuntos. |

La estructura sigue de forma libre el método **PARA** (Projects, Areas, Resources, Archive).

## 🚀 Cómo usarlo

1. Clona el repo:
   ```bash
   git clone git@github.com:azhtom/obsidian-workshop.git
   ```
2. Abre Obsidian → **Abrir carpeta como vault** → selecciona la carpeta clonada.
3. En **Ajustes → Archivos y enlaces**, configura `Adjuntos` como carpeta por defecto para archivos adjuntos.
4. En **Ajustes → Plugins principales → Plantillas**, apunta a la carpeta `Plantillas`.

## 🔄 Flujo de trabajo sugerido

1. **Captura**: cualquier idea o pendiente va a `00 - Bandeja de entrada`.
2. **Procesa**: una vez al día/semana, mueve cada nota a donde corresponda.
3. **Conecta**: usa enlaces `[[nota]]` para relacionar ideas — ahí está el valor de Obsidian.
4. **Archiva**: lo que ya no está activo se mueve a `04 - Archivo`, no se borra.

## 📝 Convenciones

- Nombres de nota en español, descriptivos: `Cómo funciona X.md` mejor que `nota1.md`.
- Fechas en formato `YYYY-MM-DD` (ordenan solas).
- Etiquetas en minúsculas y sin espacios: `#idea`, `#pendiente`, `#en-progreso`.
