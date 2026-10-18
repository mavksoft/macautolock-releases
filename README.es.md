<p align="center">
  <img src="./logo.png" alt="Mac AutoLock" width="96">
</p>

<h1 align="center">Mac AutoLock</h1>

<p align="center">Tu Mac se bloquea solo en el momento en que te vas.<br>Detección de proximidad por Bluetooth: te alejas, se bloquea; vuelves, se desbloquea. Sin tocar una tecla.</p>

<p align="center">
  <a href="https://www.macautolock.com"><img src="https://img.shields.io/badge/website-macautolock.com-0A84FF" alt="website"></a>
  <a href="https://github.com/mavksoft/macautolock-releases/releases/latest"><img src="https://img.shields.io/github/v/release/mavksoft/macautolock-releases?label=latest" alt="latest release"></a>
  <img src="https://img.shields.io/badge/platform-macOS-black" alt="macOS">
  <img src="https://img.shields.io/badge/license-commercial-orange" alt="commercial license">
</p>

<p align="center">🌍 <strong>🇪🇸 Español</strong> · <a href="README.md">🇬🇧 English</a> · <a href="README.de.md">🇩🇪 Deutsch</a> · <a href="README.fr.md">🇫🇷 Français</a> · <a href="README.it.md">🇮🇹 Italiano</a> · <a href="README.pt.md">🇵🇹 Português</a></p>

> **Este repositorio publica únicamente releases oficiales** — el código fuente es privado. Descargas firmadas, checksums y feeds de auto-actualización.

## Descarga

| | |
|---|---|
| 📥 **Pro (DMG)** | [Descargar el último DMG](https://github.com/mavksoft/macautolock-releases/releases/latest) — control total, sin límites del App Store |
| 🍎 **Lite** | [Mac AutoLock Lite en la Mac App Store](https://apps.apple.com/app/id6812660335) |
| 🌍 **Web oficial** | [www.macautolock.com](https://www.macautolock.com) |

## Qué es

Mac AutoLock vigila la señal Bluetooth de tu teléfono. Cuando te alejas del escritorio la señal decae y tu sesión se bloquea sola; cuando vuelves, se desbloquea por ti. Tu móvil es la llave — nada más que llevar, nada que recordar.

## Funciones

- **Bloqueo y desbloqueo reales** — desbloqueo automático de la sesión con Llaveros (edición Pro).
- **Alertas de intrusión** — foto silenciosa de quien toca tu Mac mientras estás fuera (Pro).
- **Redes de confianza** — nunca se bloquea en casa ni en la oficina (lista blanca de Wi-Fi).
- **App iOS de compañía** — bloquea y desbloquea tu Mac a distancia desde el iPhone.
- **Motor de proximidad BLE** — umbrales ajustables de distancia y temporización.
- **Macs y teléfonos ilimitados** — un solo plan cubre todos tus equipos (Pro).
- **Edición Lite en App Store** — el mismo motor de proximidad dentro del sandbox de Apple.

## Cómo se usa

1. Descarga el DMG, arrastra Mac AutoLock a Aplicaciones y ábrelo.
2. Empareja tu iPhone/Android por Bluetooth siguiendo el asistente (2 minutos).
3. Ajusta la distancia de bloqueo con el slider — la app te muestra la señal en vivo.
4. Aléjate del Mac: al perder señal suficiente, la sesión se bloquea sola.
5. Opcional: marca tu Wi-Fi como red de confianza para no bloquear en casa.

## Ediciones y precios

|  | Lite (App Store) | Pro (DMG) |
|---|---|---|
| **Motor de proximidad** | ✓ | ✓ |
| **Bloqueo de sesión** | Estándar macOS | ✓ + auto-desbloqueo |
| **Foto de intrusión** | — | ✓ |
| **Redes de confianza** | — | ✓ |
| **Sandbox** | ✓ | — |
| **Actualizaciones** | App Store | Sparkle automático |

## Requisitos

macOS reciente con Bluetooth LE · iPhone o Android con BLE para proximidad · Firmado y notarizado por Apple (DMG).

## Qué contiene este repositorio

- `MacAutoLock.dmg` — instalador Pro firmado + notarizado
- `MacAutoLock-<versión>.zip` — archivo de actualización Sparkle (EdDSA) usado por el auto-actualizador
- `*.delta` — actualizaciones delta de Sparkle entre versiones

[Última release](https://github.com/mavksoft/macautolock-releases/releases/latest)

## Preguntas frecuentes

**¿Por qué hay dos ediciones?**  
El sandbox del App Store no permite acceso a cámara ni el desbloqueo automático real — por eso el DMG Pro (fuera del sandbox) ofrece todas las funciones y Lite ofrece el bloqueo estándar.

**¿Drena la batería del móvil?**  
No: usa Bluetooth Low Energy. El consumo extra en el teléfono es prácticamente nulo.

**¿Qué pasa si se apaga el Bluetooth?**  
La app detecta la pérdida de señal y aplica la política configurada (bloquear con gracia, avisar, etc.).

## Soporte

- Web: [www.macautolock.com](https://www.macautolock.com)
- Email: [support@it-systems.es](mailto:support@it-systems.es)

---
<p align="center"><sub>Mac AutoLock · © MavkSoft / IT-Systems</sub></p>
