<p align="center">
  <img src="./logo.png" alt="Mac AutoLock" width="96">
</p>

<h1 align="center">Mac AutoLock</h1>

<p align="center">Il tuo Mac si blocca da solo nel momento in cui te ne vai.<br>Rilevamento di prossimità Bluetooth — ti allontani, si blocca; torni, si sblocca. Senza toccare un tasto.</p>

<p align="center">
  <a href="https://www.macautolock.com"><img src="https://img.shields.io/badge/website-macautolock.com-0A84FF" alt="website"></a>
  <a href="https://github.com/mavksoft/macautolock-releases/releases/latest"><img src="https://img.shields.io/github/v/release/mavksoft/macautolock-releases?label=latest" alt="latest release"></a>
  <img src="https://img.shields.io/badge/platform-macOS-black" alt="macOS">
  <img src="https://img.shields.io/badge/license-commercial-orange" alt="commercial license">
</p>

<p align="center"><a href="https://mavksoft.github.io/macautolock-releases/"><img src="https://img.shields.io/badge/docs-mavksoft.github.io%2Fmacautolock-releases-blue" alt="docs"></a></p>

<p align="center">🌍 <a href="README.es.md">🇪🇸 Español</a> · <a href="README.md">🇬🇧 English</a> · <a href="README.de.md">🇩🇪 Deutsch</a> · <a href="README.fr.md">🇫🇷 Français</a> · <strong>🇮🇹 Italiano</strong> · <a href="README.pt.md">🇵🇹 Português</a></p>

> **Questo repository pubblica solo release binarie ufficiali** — il codice sorgente è privato. Download firmati, checksum e feed di aggiornamento automatico.

## Download

| | |
|---|---|
| 📥 **Pro (DMG)** | [Scarica l'ultimo DMG](https://github.com/mavksoft/macautolock-releases/releases/latest) — controllo totale, senza limiti dell'App Store |
| 🍎 **Lite** | [Mac AutoLock Lite sul Mac App Store](https://apps.apple.com/app/id6812660335) |
| 🌍 **Sito ufficiale** | [www.macautolock.com](https://www.macautolock.com) |

## Che cos'è

Mac AutoLock sorveglia il segnale Bluetooth del tuo telefono. Quando ti allontani dalla scrivania il segnale cala e la sessione si blocca; quando torni, si sblocca per te. Il telefono è la chiave — nient'altro da portare, niente da ricordare.

<p align="center"><img src="./screenshots/website.png" width="640" alt="screenshot"></p>

## Funzionalità

- **Blocco e sblocco reali** — sblocco automatico della sessione con Portachiavi (Pro).
- **Avvisi di intrusione** — foto silenziosa di chi tocca il Mac in tua assenza (Pro).
- **Reti fidate** — non si blocca mai a casa o in ufficio (whitelist Wi-Fi).
- **App iOS companion** — blocca e sblocca il Mac a distanza dall'iPhone.
- **Motore di prossimità BLE** — soglie di distanza e temporizzazione regolabili.
- **Mac e telefoni illimitati** — un solo piano copre tutti i dispositivi (Pro).
- **Edizione Lite su App Store** — lo stesso motore di prossimità nel sandbox di Apple.

## Come si usa

1. Scarica il DMG, trascina Mac AutoLock in Applicazioni e aprilo.
2. Associa il tuo iPhone/Android via Bluetooth con la procedura guidata (2 minuti).
3. Regola la distanza di blocco con lo slider — l'app mostra il segnale in tempo reale.
4. Allontanati: quando il segnale cala abbastanza, la sessione si blocca da sola.
5. Opzionale: marca il tuo Wi-Fi come rete fidata per non bloccare mai a casa.

## Edizioni e prezzi

|  | Lite (App Store) | Pro (DMG) |
|---|---|---|
| **Motore di prossimità** | ✓ | ✓ |
| **Blocco sessione** | Standard macOS | ✓ + sblocco automatico |
| **Foto intrusione** | — | ✓ |
| **Reti fidate** | — | ✓ |
| **Sandbox** | ✓ | — |
| **Aggiornamenti** | App Store | Sparkle automatico |

## Requisiti

macOS recente con Bluetooth LE · iPhone o Android con BLE per la prossimità · Firmato e notarizzato da Apple (DMG).

## Cosa contiene questo repository

- `MacAutoLock.dmg` — installer Pro firmato + notarizzato
- `MacAutoLock-<versione>.zip` — archivio di aggiornamento Sparkle (EdDSA) per l'auto-updater
- `*.delta` — aggiornamenti delta Sparkle tra versioni

[Ultima release](https://github.com/mavksoft/macautolock-releases/releases/latest)

## Domande frequenti

**Perché due edizioni?**  
Il sandbox dell'App Store non permette accesso alla fotocamera né lo sblocco automatico reale — il DMG Pro (fuori sandbox) offre tutte le funzioni, Lite il blocco standard.

**Scarica la batteria del telefono?**  
No — usa Bluetooth Low Energy. Il consumo extra è praticamente nullo.

**E se il Bluetooth si spegne?**  
L'app rileva la perdita di segnale e applica la politica configurata (blocco con tolleranza, notifica…).

## Assistenza

- Sito: [www.macautolock.com](https://www.macautolock.com)
- Email: [support@it-systems.es](mailto:support@it-systems.es)

---
<p align="center"><sub>Mac AutoLock · © MavkSoft / IT-Systems</sub></p>
