<p align="center">
  <img src="https://raw.githubusercontent.com/mavksoft/macautolock-releases/main/logo.png" alt="Mac AutoLock" width="96">
</p>

<h1 align="center">Mac AutoLock</h1>

<p align="center">Dein Mac sperrt sich von selbst, sobald du gehst.<br>Bluetooth-Näherungserkennung — du gehst, er sperrt; du kommst zurück, er entsperrt. Ohne eine Taste zu berühren.</p>

<p align="center">
  <a href="https://www.macautolock.com"><img src="https://img.shields.io/badge/website-macautolock.com-0A84FF" alt="website"></a>
  <a href="https://github.com/mavksoft/macautolock-releases/releases/latest"><img src="https://img.shields.io/github/v/release/mavksoft/macautolock-releases?label=latest" alt="latest release"></a>
  <img src="https://img.shields.io/badge/platform-macOS-black" alt="macOS">
  <img src="https://img.shields.io/badge/license-commercial-orange" alt="commercial license">
</p>

<p align="center"><a href="https://mavksoft.github.io/macautolock-releases/"><img src="https://img.shields.io/static/v1?label=docs&message=mavksoft.github.io/macautolock-releases&color=blue" alt="docs"></a></p>

<p align="center">🌍 <a href="README.es.md">🇪🇸 Español</a> · <a href="README.md">🇬🇧 English</a> · <strong>🇩🇪 Deutsch</strong> · <a href="README.fr.md">🇫🇷 Français</a> · <a href="README.it.md">🇮🇹 Italiano</a> · <a href="README.pt.md">🇵🇹 Português</a></p>

> **Dieses Repository veröffentlicht ausschließlich offizielle Binär-Releases** — der Quellcode ist privat. Signierte Downloads, Prüfsummen und Auto-Update-Feeds.

## Download

| | |
|---|---|
| <img src='https://raw.githubusercontent.com/mavksoft/macautolock-releases/main/icons/apple.svg' width='15' style='vertical-align:-2px' alt='apple'> **Pro (DMG)** | [Neuestes DMG laden](https://github.com/mavksoft/macautolock-releases/releases/latest) — volle Kontrolle, keine App-Store-Limits |
| <img src='https://raw.githubusercontent.com/mavksoft/macautolock-releases/main/icons/appstore.svg' width='15' style='vertical-align:-2px' alt='appstore'> **Lite** | [Mac AutoLock Lite im Mac App Store](https://apps.apple.com/app/id6812660335) |
| <img src='https://raw.githubusercontent.com/mavksoft/macautolock-releases/main/logo.png' width='15' style='vertical-align:-2px'> **Website** | [www.macautolock.com](https://www.macautolock.com) |

## Was ist das

Mac AutoLock überwacht das Bluetooth-Signal deines Telefons. Entfernst du dich vom Schreibtisch, fällt das Signal ab und die Sitzung sperrt sich; kehrst du zurück, wird entsperrt. Dein Handy ist der Schlüssel — nichts mitzunehmen, nichts zu merken.

<p align="center"><img src="./screenshots/website.png" width="640" alt="screenshot"></p>

## Funktionen

- **Echte Sitzungssperre & Entsperrung** — automatisches Entsperren mit Schlüsselbund (Pro).
- **Einbruchsalarm** — stilles Foto von jedem, der deinen Mac in deiner Abwesenheit anfasst (Pro).
- **Vertrauenswürdige Netzwerke** — sperrt nie zu Hause oder im Büro (WLAN-Whitelist).
- **iOS-Begleit-App** — sperre und entsperre deinen Mac aus der Ferne vom iPhone.
- **BLE-Näherungs-Engine** — einstellbare Distanz- und Zeit-Schwellenwerte.
- **Unbegrenzte Macs & Telefone** — ein Plan deckt alle Geräte ab (Pro).
- **App-Store-Lite-Edition** — dieselbe Näherungs-Engine in Apples Sandbox.

## So wird es verwendet

1. DMG laden, Mac AutoLock nach Programme ziehen und öffnen.
2. iPhone/Android per Bluetooth koppeln — der Assistent führt dich (2 Minuten).
3. Sperrdistanz mit dem Regler einstellen — die App zeigt die Signalstärke live.
4. Entferne dich: Fällt das Signal genug ab, sperrt sich die Sitzung von selbst.
5. Optional: dein WLAN als vertrauenswürdiges Netz markieren, damit zu Hause nie gesperrt wird.

## Editionen & Preise

|  | Lite (App Store) | Pro (DMG) |
|---|---|---|
| **Näherungs-Engine** | ✓ | ✓ |
| **Sitzungssperre** | macOS-Standard | ✓ + Auto-Entsperrung |
| **Einbruchsfoto** | — | ✓ |
| **Vertrauenswürdige Netze** | — | ✓ |
| **Sandbox** | ✓ | — |
| **Updates** | App Store | Automatisch via Sparkle |

## Voraussetzungen

Aktuelles macOS mit Bluetooth LE · iPhone oder Android mit BLE für die Näherungserkennung · Von Apple signiert und notarisiert (DMG).

## Was dieses Repository enthält

- `MacAutoLock.dmg` — signiertes + notarisiertes Pro-Installationsprogramm
- `MacAutoLock-<Version>.zip` — Sparkle-Update-Archiv (EdDSA) für den In-App-Updater
- `*.delta` — Sparkle-Delta-Updates zwischen Versionen

[Neueste Version](https://github.com/mavksoft/macautolock-releases/releases/latest)

## Häufige Fragen

**Warum zwei Editionen?**  
Die App-Store-Sandbox erlaubt keinen Kamerazugriff und kein echtes Auto-Entsperren — deshalb bietet das Pro-DMG (außerhalb der Sandbox) alle Funktionen, Lite die Standardsperre.

**Zieht das den Handy-Akku leer?**  
Nein — es nutzt Bluetooth Low Energy. Der Mehrverbrauch ist praktisch null.

**Was passiert, wenn Bluetooth ausgeht?**  
Die App erkennt den Signalverlust und wendet die konfigurierte Richtlinie an (Sperren mit Gnadenfrist, Hinweis usw.).

## Support

- Website: [www.macautolock.com](https://www.macautolock.com)
- E-Mail: [support@it-systems.es](mailto:support@it-systems.es)

---
<p align="center"><sub>Mac AutoLock · © MavkSoft / IT-Systems</sub></p>
