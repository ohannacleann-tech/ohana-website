# OHANA Clean Solutions — guía para Claude

## El negocio
- OHANA Clean Solutions LLC: limpieza residencial en Silicon Valley y el Área de la Bahía. Base en San José, CA. El dueño es Jesús, que está en cada trabajo.
- Posicionamiento: medio-premium. Ni barato ni de lujo.
- Servicios: Regular, Deep, Move In/Out, Airbnb Turnover. Commercial y Post-Construction se cotizan a la medida ("Custom").
- Contacto: (669) 317-6911 (teléfono, SMS y WhatsApp) · ohannacleann@gmail.com
- Redes: https://www.instagram.com/ohanaclean_solutionsllc · https://www.facebook.com/profile.php?id=61560363654454
- Zona de servicio (22 ciudades): San Francisco, Daly City, Burlingame, San Mateo, Redwood City, Menlo Park, Palo Alto, Mountain View, Sunnyvale, Cupertino, Santa Clara, San Jose, Campbell, Los Gatos, Milpitas, Morgan Hill, Gilroy, Fremont, Hayward, Oakland, Berkeley, Antioch. North Bay no se atiende.

## Precios (fuente de verdad: no cambiarlos sin que Jesús lo pida)
| Tamaño | Regular | Deep | Move In/Out | Airbnb |
|---|---|---|---|---|
| Studio / 1 rec. | $149 | $199 | $239 | $119 |
| 2 rec. / 2 baños | $219 | $289 | $339 | $159 |
| 3 rec. / 2 baños | $289 | $369 | $419 | $209 |
| 4+ rec. / 3+ baños | $369 | $459 | $519 | $269 |

- Condición: Well-Kept ×1.0 · Average ×1.25 · Needs Attention ×1.55
- Frecuencia: Weekly −20% · Bi-Weekly −15% · Monthly −10%
- Extras: Oven $50 · Fridge $50 · Interior Windows (up to 10) $60 · Patio/Balcony $40 · Garage $75 · Laundry (per load) $30
- Depósito de $50 al reservar; el resto se paga el día del servicio. Cancelación con 48 h para reembolso completo; el mismo día no se reembolsa. Si algo no quedó bien, se regresa en 24 h sin costo.

## El sitio
- ohanacleansolutions.com. HTML/CSS/JS propio en `index.html`, más `privacy.html` y `terms.html`. Mapa con Leaflet.js.
- Se publica solo en Vercel al hacer push a `main` en GitHub (ohannacleann-tech/ohana-website). Dominio en Namecheap.
- Diseño: oscuro y premium con acentos dorados (#c9a84c). Letras: Cormorant Garamond + DM Sans. Estándar visual tipo Tesla, Apple o Rivian. Nada que parezca "un rectángulo" o "un proyecto de primaria".

## Cómo trabajar con Jesús
- Siempre en español.
- Antes de tocar código, explica el plan y espera su confirmación.
- Un cambio a la vez: muestra el antes y el después y espera su "ok".
- Nunca hagas push sin que lo pida. Puedes hacer commit cuando lo pida.
- Explica los pasos de Git y la terminal de forma simple.
- Prueba en vista de celular (390 px) antes de dar algo por terminado.

## Reglas de contenido
- No decir que el negocio está asegurado ("insured", "bonded") hasta que Jesús confirme que tiene la póliza.
- No mostrar ninguna dirección física (ni en la página ni en el schema).
- "350+ clients" y "4.9★" se quedan: Jesús tiene el respaldo.
- No usar afirmaciones que no se puedan comprobar (por ejemplo, "hospital-grade").

## Detalles técnicos que ya dieron problemas
- Las fotos tienen doble extensión (ej. `oven-before.jpg.jpeg`) porque vienen de WhatsApp Web. El código debe usar el nombre exacto.
- Vercel guarda en caché: después de publicar, revisar con recarga forzada o en incógnito.
- El aviso "LF will be replaced by CRLF" de Git en Windows es normal.

## Pendientes
- Stripe para cobrar el depósito de $50 desde el botón de reserva.
- Correo profesional jesus@ohanacleansolutions.com (cuando exista, cambiar el gmail en la página, el schema y la política de privacidad).
- Botón para dejar reseña en Google.
- Que cada reserva llegue sola (n8n o Stripe), sin depender de que el cliente toque "enviar".
- Mapa de cobertura: resaltar solo las 22 ciudades y que el cotizador responda por ZIP.
- Páginas por ciudad con preguntas frecuentes (SEO y búsquedas con IA).
- Cotizador por dirección con RentCast (la clave va en una función de Vercel, nunca en la página).
