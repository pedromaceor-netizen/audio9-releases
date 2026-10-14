# Audio9 — descargas / downloads

Instaladores oficiales de **A9 Sender**, la app de escritorio de [Audio9](https://audio9.app) que envía los canales de tu mesa o DAW a los móviles con **A9 Monitor** por red local con cable.

Official installers for **A9 Sender**, the [Audio9](https://audio9.app) desktop app that sends your desk or DAW channels to phones running **A9 Monitor** over a wired local network.

➡️ **[Última versión / Latest release](https://github.com/pedromaceor-netizen/audio9-releases/releases/latest)**

| Sistema / System | Fichero / File |
|---|---|
| macOS 14+ (Apple Silicon: M1 o posterior) | `A9-Sender-<versión>-macOS.pkg` (instalador firmado y notarizado por Apple) o `.zip` |
| Linux Mint 21/22 · Ubuntu 22.04+ (x86_64) | `a9-sender_<versión>_amd64.deb` |

Guía / guide: https://audio9.app/tutorial-sender.html

## Instalación en Linux

```sh
sudo apt install --no-install-recommends ./a9-sender_0.8.2_amd64.deb
```

## Verificar la descarga / verify the download

```sh
shasum -a 256 -c SHA256SUMS      # macOS
sha256sum -c SHA256SUMS          # Linux
```

## Licencia / license

A9 Sender es software propietario y gratuito, sujeto al [contrato de licencia de usuario final de A9](https://audio9.app/licencia.html). Este repositorio solo contiene los instaladores; el código fuente no se publica, salvo los componentes LGPL que acompañan a cada paquete.

A9 Sender is proprietary freeware under the [A9 End User License Agreement](https://audio9.app/licencia.html). This repository only hosts the installers; the source code is not published, except for the LGPL components shipped with each package.

Contacto / contact: dev@watchineo.com
