<p align="center"><img src="assets/icon.png" width="120" alt="WattBoard icon"></p>

# WattBoard

**EN** · Native iPhone, Mac & Android app for your own [TeslaMate](https://github.com/teslamate-org/teslamate). No cloud, no account, no tracking.
**ES** · App nativa para tu propio TeslaMate en iPhone, Mac y Android. Sin nube, sin cuenta, sin rastreo.

> **Status / Estado:** testing / en pruebas. Not yet in the App Store or Google Play.

<p align="center">
<img src="assets/coche.png" width="230" alt="Car">
<img src="assets/estadisticas.png" width="230" alt="Stats">
<img src="assets/trayectos.png" width="230" alt="Drives">
</p>

## What it does
- Car status, battery, range, climate, tyres, doors and locks (via TeslaMateApi).
- Drives and charges with filters, stats by date range, CSV and GPX export.
- Widgets, Apple Watch, charge and plug-in alerts, offline cache.
- Your own Grafana dashboards as native screens.
- Face ID / fingerprint lock, privacy mode, QR setup between devices.
- 7 languages: es, en, de, fr, pt, zh, fi.

## Guía de conexión / Connection guide
[Guía de conexión (PDF, ES)](guides/Wattboard-guia-conexion.pdf) · [Connection guide (PDF, EN)](guides/Wattboard-connection-guide.pdf)

## Downloads / Descargas
Test builds are published in [Releases](../../releases). Check the fingerprint with [VERIFY.md](VERIFY.md) · Comprueba la huella con [VERIFY.md](VERIFY.md).

## Privacy
Your data goes straight from **your server** to **your phone**. There is no WattBoard server, no account and no analytics. See the [privacy policy](PRIVACY.md) · [política de privacidad](PRIVACIDAD.md).

## Testing / Pruebas
Want to try it? Open an [issue](../../issues/new/choose) or write to **wattboardapp@gmail.com**. The Android test build (APK) and the Mac test build are in [Releases](../../releases) · Los APK de Android y el de Mac de pruebas están en [Releases](../../releases). If you already installed an older Android build, uninstall it first (the signing key changed) · Si tenías una versión anterior de Android, desinstálala antes (ha cambiado la clave de firma).

## Plans / Planes
Free: car, drives, charges, basic statistics, widgets and share cards. **Plus** (one-time): Grafana dashboards as native screens. **Pro** (one-time): everything in Plus and the advanced features. 14 days of Pro free when you connect your car · Gratis con lo esencial; **Plus** (pago único) añade los dashboards de Grafana; **Pro** (pago único) añade las funciones avanzadas. 14 días de Pro gratis al conectar tu coche.

## What you need
A running TeslaMate. For the full experience also [TeslaMateApi](https://github.com/tobiasehlert/teslamateapi) and Grafana. Never expose these services to the internet without protection: use a VPN or a reverse proxy with HTTPS.

## Disclaimer
WattBoard is an independent project and is not affiliated with, endorsed by, or sponsored by Tesla, Inc. or the TeslaMate project. Tesla is a trademark of Tesla, Inc.

© zerocoolspain. All rights reserved. This repository contains project information only, not the source code.
