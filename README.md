# contactjrapps.github.io

Web de **contactjrapps**: lista de apps, soporte y políticas de privacidad (necesarias para Google Play y para la verificación de Google de la sincronización con Google Drive).

## Archivos

| Archivo | Qué es |
|---|---|
| `index.html` | Página de inicio: apps, enlaces a su política y a Google Play, correo de soporte |
| `privacidad/<app>.html` | Política de privacidad de cada app (español) |
| `404.html` | Página de «no encontrada» |

Direcciones finales (cuando esté publicada):

- Inicio: https://contactjrapps.github.io/
- Políticas: https://contactjrapps.github.io/privacidad/escanix.html, …/volleypoint.html, …/basketpoint.html, …/pingpoint.html, …/electriccalc.html, …/letramania.html, …/elec360.html, …/esquemaspro.html, …/timerpro.html

## Subirla con la web de GitHub

1. Crea el repositorio con el nombre exacto **`contactjrapps.github.io`** (cuenta `contactjrapps`, público).
2. En el repositorio: **Add file → Upload files**.
3. Arrastra **el contenido** de esta carpeta (no la carpeta en sí): `index.html`, `404.html`, `README.md` y la carpeta `privacidad` entera (con sus archivos dentro).
4. Abajo, **Commit changes**.
5. **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` / `(root)` → Save.**
6. Espera 1–2 minutos y abre https://contactjrapps.github.io/

Para cambiar algo: abre el archivo en GitHub, pulsa el lápiz (Edit), cambia y **Commit changes**. Se publica solo en un minuto.

## Antes de usarla en Play Console / Google Cloud

- Rellena los huecos marcados con `PENDIENTE (Javi)` (busca ese texto en los archivos).
- En Play Console, cambia la URL de la política de cada app por la nueva de `privacidad/<app>.html`.
- En Google Cloud (pantalla de consentimiento de OAuth para Drive): página principal `https://contactjrapps.github.io/` y política `https://contactjrapps.github.io/privacidad/<app>.html`.
