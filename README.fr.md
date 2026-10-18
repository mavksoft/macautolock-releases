<p align="center">
  <img src="./logo.png" alt="Mac AutoLock" width="96">
</p>

<h1 align="center">Mac AutoLock</h1>

<p align="center">Votre Mac se verrouille tout seul dès que vous partez.<br>Détection de proximité Bluetooth — vous partez, il verrouille ; vous revenez, il déverrouille. Sans toucher une touche.</p>

<p align="center">
  <a href="https://www.macautolock.com"><img src="https://img.shields.io/badge/website-macautolock.com-0A84FF" alt="website"></a>
  <a href="https://github.com/mavksoft/macautolock-releases/releases/latest"><img src="https://img.shields.io/github/v/release/mavksoft/macautolock-releases?label=latest" alt="latest release"></a>
  <img src="https://img.shields.io/badge/platform-macOS-black" alt="macOS">
  <img src="https://img.shields.io/badge/license-commercial-orange" alt="commercial license">
</p>

<p align="center"><a href="https://mavksoft.github.io/macautolock-releases/"><img src="https://img.shields.io/badge/docs-mavksoft.github.io%2Fmacautolock-releases-blue" alt="docs"></a></p>

<p align="center">🌍 <a href="README.es.md">🇪🇸 Español</a> · <a href="README.md">🇬🇧 English</a> · <a href="README.de.md">🇩🇪 Deutsch</a> · <strong>🇫🇷 Français</strong> · <a href="README.it.md">🇮🇹 Italiano</a> · <a href="README.pt.md">🇵🇹 Português</a></p>

> **Ce dépôt publie uniquement les releases officielles** — le code source est privé. Téléchargements signés, sommes de contrôle et flux de mise à jour automatique.

## Téléchargement

| | |
|---|---|
| 📥 **Pro (DMG)** | [Télécharger le dernier DMG](https://github.com/mavksoft/macautolock-releases/releases/latest) — contrôle total, sans les limites de l'App Store |
| 🍎 **Lite** | [Mac AutoLock Lite sur le Mac App Store](https://apps.apple.com/app/id6812660335) |
| 🌍 **Site officiel** | [www.macautolock.com](https://www.macautolock.com) |

## Qu'est-ce que c'est

Mac AutoLock surveille le signal Bluetooth de votre téléphone. Éloignez-vous du bureau et le signal faiblit → la session se verrouille. Revenez → il déverrouille pour vous. Votre téléphone est la clé — rien à transporter, rien à retenir.

<p align="center"><img src="./screenshots/website.png" width="640" alt="screenshot"></p>

## Fonctionnalités

- **Verrouillage et déverrouillage réels** — déverrouillage automatique avec le Trousseau (Pro).
- **Alertes d'intrusion** — photo silencieuse de quiconque touche votre Mac en votre absence (Pro).
- **Réseaux de confiance** — jamais de verrouillage à la maison ou au bureau (liste blanche Wi-Fi).
- **App iOS compagnon** — verrouillez et déverrouillez votre Mac à distance depuis l'iPhone.
- **Moteur de proximité BLE** — seuils de distance et de temporisation réglables.
- **Macs et téléphones illimités** — un seul forfait couvre tous vos appareils (Pro).
- **Édition Lite App Store** — le même moteur de proximité dans le sandbox d'Apple.

## Mode d'emploi

1. Téléchargez le DMG, glissez Mac AutoLock dans Applications et ouvrez-le.
2. Appairez votre iPhone/Android en Bluetooth via l'assistant (2 minutes).
3. Réglez la distance de verrouillage au curseur — l'app affiche le signal en direct.
4. Éloignez-vous : quand le signal chute suffisamment, la session se verrouille.
5. Optionnel : marquez votre Wi-Fi comme réseau de confiance pour ne jamais verrouiller à la maison.

## Éditions et tarifs

|  | Lite (App Store) | Pro (DMG) |
|---|---|---|
| **Moteur de proximité** | ✓ | ✓ |
| **Verrouillage de session** | Standard macOS | ✓ + déverrouillage auto |
| **Photo d'intrusion** | — | ✓ |
| **Réseaux de confiance** | — | ✓ |
| **Sandbox** | ✓ | — |
| **Mises à jour** | App Store | Sparkle automatique |

## Configuration requise

macOS récent avec Bluetooth LE · iPhone ou Android avec BLE pour la proximité · Signé et notarisé par Apple (DMG).

## Contenu de ce dépôt

- `MacAutoLock.dmg` — installateur Pro signé + notarisé
- `MacAutoLock-<version>.zip` — archive de mise à jour Sparkle (EdDSA) pour l'auto-updater
- `*.delta` — mises à jour delta Sparkle entre versions

[Dernière version](https://github.com/mavksoft/macautolock-releases/releases/latest)

## Questions fréquentes

**Pourquoi deux éditions ?**  
Le sandbox de l'App Store interdit l'accès caméra et le vrai déverrouillage auto — le DMG Pro (hors sandbox) offre toutes les fonctions, Lite le verrouillage standard.

**Est-ce que ça vide la batterie du téléphone ?**  
Non — il utilise le Bluetooth Low Energy. La consommation supplémentaire est négligeable.

**Et si le Bluetooth se coupe ?**  
L'app détecte la perte de signal et applique la politique configurée (verrouillage temporisé, notification…).

## Assistance

- Site : [www.macautolock.com](https://www.macautolock.com)
- E-mail : [support@it-systems.es](mailto:support@it-systems.es)

---
<p align="center"><sub>Mac AutoLock · © MavkSoft / IT-Systems</sub></p>
