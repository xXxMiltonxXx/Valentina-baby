# Invitación de Valentina — Revelación, Baby Shower y Cumpleaños

Todo está en un solo archivo: `index.html` (las imágenes van dentro). No necesita instalar nada.

## 1. Completar los datos

Abre `index.html` y busca el bloque **CONFIGURACIÓN — EDITA SOLO ESTA PARTE** (al final del archivo, dentro de `<script>`). Cambia:

| Campo | Qué poner |
|---|---|
| `fecha` | Fecha y hora real, ej. `"2026-12-05T16:00:00-05:00"` |
| `horaTexto` | Cómo se muestra la hora, ej. `"4:00 p. m."` |
| `confirmarAntesDe` | Fecha límite para confirmar |
| `lugar` / `direccion` | Nombre del lugar y dirección |
| `mapa` | Enlace de Google Maps (Compartir → Copiar enlace) |
| `whatsapp` | Número que recibe confirmaciones: `593` + número sin el 0 (ej. `593987654321`) |
| `itinerario` | Horas y momentos de la tarde |

## 2. Subirla gratis (elige una)

- **Netlify Drop** (lo más fácil): entra a https://app.netlify.com/drop y arrastra la carpeta `invitacion-valentina`. Te da un enlace al instante.
- **Vercel**: `npx vercel` dentro de la carpeta.
- **GitHub Pages**: sube `index.html` a un repositorio y activa Pages.

## 3. Enlace personalizado por invitado

Agrega `?para=` al final del enlace con el nombre del invitado:

```
https://TU-ENLACE/?para=Sra.%20Marycarmen%20Loor%20y%20esposo
```

(Los espacios se escriben `%20`; WhatsApp normalmente los convierte solo.)
El nombre aparece en el sobre y en el mensaje de confirmación por WhatsApp.

## Opcional

- **Imagen al compartir en WhatsApp**: sube una imagen `portada.jpg` (1200×630) junto al `index.html` y descomenta la línea `og:image` del inicio del archivo con la URL completa.
