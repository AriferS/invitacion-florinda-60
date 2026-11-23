# Invitación · 60 años de Florinda Apagueño Mori

Invitación digital (sitio estático) para el cumpleaños número 60 de **Florinda Apagueño Mori** — lunes 7 de diciembre de 2026 a las 7:00 p.m. en **Broostheria Eithan** (Chazuta, frente a la Plaza de Armas).

Incluye:
- `index.html`: Invitación general con **Pase de honor**, retrato en marco dorado de laurel, **cuenta regresiva**, **Google Maps** (`-6.5736,-76.1378`), código de vestimenta (**Semi formal**), confirmación por **WhatsApp** a Maira (`+51 901 366 227`) y **música** (`cancion.mp3`).
- `festejada.html`: Versión especial para la festejada.
- Imágenes HD optimizadas: `florinda-hd.png`, `marco-laurel-hd.png`, `rosas-hd.png`, `flor-esquina-hd.png`, `mano-lapiz.png`.

## Cómo editar los datos

Abre `index.html` y busca el bloque `const CONFIG = { ... }`:

| Campo | Qué es |
|---|---|
| `whatsapp` | Número de Maira (`51901366227`) |
| `fechaISO` / `fechaTexto` / `horaTexto` | Fecha y hora del evento |
| `lugar` / `direccion` / `mapsQuery` | Lugar, dirección y coordenadas de Google Maps |
| `vestimenta` | Código de vestimenta (`Semi formal`, o vacío `""` para ocultar) |
| `firma` | Texto del pie de la tarjeta |
| `pase` | Número de pase (también configurable por URL: `?pase=002`) |
| `mp3Url` | Archivo de audio (`cancion.mp3`) |

## Publicar

Sitio estático, sin build. En Netlify: *Add new site → Import from GitHub → este repositorio → Deploy*.
