# WallGuard
<div align="center">

# 🛡️ WallGuard

**Protection contre l'addiction sur  Android — 100% locale, sans cloud**

![Android](https://img.shields.io/badge/Android-10%2B-green?logo=android)
![Kotlin](https://img.shields.io/badge/Kotlin-1.9-purple?logo=kotlin)
![License](https://img.shields.io/badge/License-No--Derivatives-red)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

[⬇️ Télécharger l'APK](https://github.com/codenosenpai/WallGuard/releases/latest)

</div>

---

## 📖 Description

WallGuard est une application Android de contrôle  qui bloque automatiquement
les contenus adultes via un VPN local et un service d'accessibilité.
Elle fonctionne entièrement en local — aucune donnée n'est envoyée sur internet.

---

## ✨ Fonctionnalités

| Fonction | Description |
|----------|-------------|
| 🔒 VPN local | Filtre le trafic DNS et bloque les domaines adultes |
| 🧠 IA Gamma | Classification NSFW locale via TensorFlow Lite |
| 🛑 Overlay | Écran de blocage plein écran avec timer 15s |
| 🔍 Accessibilité | Surveille les navigateurs et tentatives de contournement |
| 🔄 Auto-restart | Redémarre automatiquement après reboot |
| 🔐 PIN admin | Code PIN nécessaire pour désactiver la protection |
| 📵 Anti-désinstall | Service persistant + administrateur d'appareil |

---

## 📲 Installation

> ⚠️ L'app n'est pas sur le Play Store — installation manuelle requise.

### Étape 1 — Autoriser les sources inconnues
**Paramètres** → **Sécurité** → **Installer des apps inconnues** → autorise ton navigateur

### Étape 2 — Télécharger l'APK
👉 [Cliquer ici pour télécharger](https://github.com/TON_USERNAME/WallGuard/releases/latest)

### Étape 3 — Installer
Ouvre le fichier `.apk` téléchargé et suis les instructions.

### Étape 4 — Configurer dans l'app
1. **PIN Génerer par l'app** administrateur (mémorise-le !)
2. **Activer le VPN** → accepte la demande Android
3. **Activer l'accessibilité** → Paramètres → Accessibilité → Protection WallGuard → ON
4. **Autoriser l'overlay** → accepte la demande Android
5. *(Optionnel)* **Admin d'appareil** → Paramètres → Sécurité → Administrateurs → WallGuard

---

## 🏗️ Architecture
WallGuard
├── VPN Service           → Filtre DNS + paquets réseau
├── AI Module "Gamma"     → Classification NSFW locale (TFLite)
├── Accessibility Service → Anti-contournement + surveillance navigateurs
├── Overlay Manager       → Écran de blocage
├── Boot Receiver         → Redémarrage automatique
└── Device Admin          → Protection désinstallation

---

## 📋 Permissions utilisées

| Permission | Usage |
|------------|-------|
| `BIND_VPN_SERVICE` | Filtrage réseau local |
| `BIND_ACCESSIBILITY_SERVICE` | Surveillance des apps |
| `SYSTEM_ALERT_WINDOW` | Overlay de blocage |
| `RECEIVE_BOOT_COMPLETED` | Démarrage automatique |
| `FOREGROUND_SERVICE` | Service persistant |
| `POST_NOTIFICATIONS` | Notification de service actif |

---

## ⚖️ Licence

Ce logiciel est protégé par une licence personnalisée.
**Le téléchargement et l'utilisation personnelle sont autorisés.**
**La modification, redistribution modifiée et usage commercial sont strictement interdits.**

Voir le fichier [LICENSE](LICENSE) pour les détails complets.

---

## 🐛 Support

Pour signaler un bug :
👉 [Ouvrir une issue](https://github.com/TON_USERNAME/WallGuard/issues)

---

<div align="center">
Fait avec ❤️ pour la protection des familles
</div>
