# Invitación · 60 años de Florinda Apagueño Mori

Invitación digital (sitio estático) para el cumpleaños número 60 de **Florinda Apagueño Mori** — lunes 7 de diciembre de 2026 a las 7:00 p.m. en **Chazuta · Frente a la plaza** (**Broostheria Eithan**).

Incluye:
- `index.html`: Invitación general con **Pase de honor**, retrato en marco dorado de laurel, **cuenta regresiva**, **Google Maps** (`-6.5736,-76.1378`), código de vestimenta (**Semi formal**), confirmación por **WhatsApp** a Maira (`+51 901 366 227`) y **música** (`cancion.mp3`).
- `festejada.html`: Versión especial para la festejada.
- `Invitacion-Florinda-60.pdf`: Sobre PDF en alta nitidez con enlace invisible sobre el sello dorado "60".
- Imágenes ligeras optimizadas: `florinda.jpg`, `marco-laurel.avif`, `rosas.avif`, `flor-esquina.avif`, `mano-lapiz.png`.

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

Sitio estático, sin build. En Netlify: *Add new project → Import an existing project → GitHub → Deploy*.
