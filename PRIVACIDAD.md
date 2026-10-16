# Política de privacidad de WattBoard

*Última actualización: 15 de octubre de 2026.*

## Quién soy
WattBoard (iPhone, iPad, Apple Watch, Mac y Android) es una app creada y mantenida por **zerocoolspain** (proyecto independiente, no afiliado a Tesla, Inc.).
Contacto para cualquier asunto de privacidad: **wattboardapp@gmail.com**.

## Resumen
- Wattboard **no tiene cuentas, ni publicidad, ni analíticas, ni rastreo**.
- La app se conecta **solo a tu propio servidor** (su API REST, Grafana o Postgres). Tus datos de conducción **no pasan por ningún servidor mío**.
- La única información que puede llegar al desarrollador es el **comentario que tú decidas enviar** desde «Enviar comentarios».

## Datos que la app trata en tu dispositivo
- **Datos de tu coche y tus viajes**, leídos de tu servidor. Se muestran en pantalla y se guardan una copia temporal en tu dispositivo para poder verlos sin conexión (borrable al desinstalar la app).
- **Direcciones y credenciales de tu servidor.** Las contraseñas y tokens se guardan en el llavero de iOS/macOS, o cifrados con el Keystore de Android. En los dispositivos Apple, la dirección y el token de la API se comparten con los widgets de la app mediante un contenedor privado (App Group).
- **Ajustes** (idioma, apariencia, avisos) y un **registro de errores recientes** sin direcciones, usuarios ni contraseñas.
- **Notificaciones locales** (fin de carga, batería baja): se calculan en tu dispositivo, sin servidor. El bloqueo con Face ID, Touch ID o huella lo gestiona el sistema operativo: la app nunca recibe tus datos biométricos.

## Servicios de terceros que usa la app
- **Apple Mapas / MapKit** (iPhone, iPad y Mac): para mostrar mapas. Apple recibe las coordenadas necesarias para dibujar el mapa, según su política de privacidad.
- **Escáner de códigos de Google (servicios de Google Play)** en Android, solo si escaneas un QR de configuración. El escaneo se procesa en el dispositivo y la app no recibe las imágenes de la cámara.
- Tu propio servidor y las herramientas que tú alojas (redes privadas, proxies inversos, etc.) se rigen por sus propias condiciones.

## Comentarios enviados por el usuario (opcional)
Solo si pulsas **Enviar** en «Enviar comentarios» (disponible en la app de iPhone/iPad/Mac; la app de Android no tiene formulario de comentarios por ahora):
- Se envía: el texto que escribes, las capturas que adjuntes, tu correo (si lo indicas) y, si lo dejas activado, **información técnica** (versión de la app y del sistema, ajustes, tipo de conexión y últimos errores). **No** incluye direcciones de tu servidor, usuarios, contraseñas ni tus datos de conducción.
- Cómo viaja: la app lo envía a un **relé alojado en Cloudflare (Workers)** operado por el desarrollador, que lo reenvía a un **chat privado de Telegram** del desarrollador mediante un bot. El relé no guarda el contenido; Cloudflare puede tratar tu dirección IP para entregar la petición y para limitar el número de envíos (se conserva como máximo una hora).
- Para qué: solo para leer, reproducir y corregir el problema o estudiar tu sugerencia, y responderte si dejaste un correo.
- Cuánto tiempo: el mensaje permanece en el chat de Telegram del desarrollador hasta que lo borre; se eliminará cuando deje de ser necesario y en todo caso podrás pedir su borrado.
- Proveedores: **Cloudflare, Inc.** y **Telegram Messenger Inc.** actúan como proveedores del servicio, con sus propias políticas de privacidad.
- Alternativas: puedes usar «Enviar por correo» o «Compartir informe» para enviarlo por otro medio.

## Tus derechos
Puedes pedir acceso, rectificación o supresión de lo que hayas enviado en un comentario, y retirar tu consentimiento en cualquier momento, escribiendo a la dirección de contacto. Si estás en la UE/EEE, puedes reclamar ante tu autoridad de protección de datos (en España, la AEPD).

## Menores
Wattboard no está dirigida a menores de 14 años y no recopila datos de ellos de forma deliberada.

## Cambios
Si cambia esta política, se actualizará aquí y en la app con una nueva fecha.
