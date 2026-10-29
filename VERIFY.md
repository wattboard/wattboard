# Verifying your download / Verificar la descarga

Test builds are not signed by Apple or Google yet. To be sure the file you got is exactly the one published here, compare its SHA-256 fingerprint.
Las versiones de pruebas aún no están firmadas por Apple ni Google. Para asegurarte de que el archivo es exactamente el publicado aquí, compara su huella SHA-256.

| File / Archivo | Version | SHA-256 |
|---|---|---|
| `WattBoard-Mac-pruebas.zip` (macOS 14+) | 1.0 test · 15 Oct 2026 | `c9cf8a223a038722dc372ce7d1d5d848c1c441e3e30cfe255853c418cd99c0cb` |
| `Wattboard-35-1.5.2-firmado.apk` (Android) | 1.5.2 · 29 Oct 2026 | `a44f7ab762c7c1f2a7227a4fbfb1dd005b2321bb64f658282c5527c887a3fc1c` |

## macOS
Open Terminal and run / Abre Terminal y escribe:

```bash
shasum -a 256 ~/Downloads/WattBoard-Mac-pruebas.zip
```

## Linux / Windows
```bash
sha256sum WattBoard-Mac-pruebas.zip
```
Windows PowerShell: `Get-FileHash .\WattBoard-Mac-pruebas.zip -Algorithm SHA256`

## Android
Same idea, with the `.apk` file / Misma idea, con el archivo `.apk`:
```bash
shasum -a 256 ~/Downloads/Wattboard-35-1.5.2-firmado.apk
```
Windows PowerShell: `Get-FileHash .\Wattboard-35-1.5.2-firmado.apk -Algorithm SHA256`

The result must match the table exactly. If it does not, **do not open the file** and write to wattboardapp@gmail.com.
El resultado debe coincidir exactamente con la tabla. Si no coincide, **no abras el archivo** y escribe a wattboardapp@gmail.com.

The fingerprint proves the file was not altered after publishing; it does not replace Apple/Google signing, which will come with the store releases.
La huella demuestra que el archivo no se alteró tras publicarse; no sustituye a la firma de Apple/Google, que llegará con las versiones de las tiendas.
