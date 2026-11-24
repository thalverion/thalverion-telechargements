# Thalverion pour Linux

**L'autonomie du foyer, même sans internet.**
Thalverion aide votre foyer à tenir 72 heures sans aide extérieure : kit, réserves, groupe familial, alertes, carte et bibliothèque hors ligne, assistant.

## Télécharger

👉 **[Dernière version](https://github.com/thalverion/thalverion-telechargements/releases/latest)**

| Fichier | Pour quel ordinateur ? |
|---|---|
| `Thalverion_X.Y.Z_arm64.deb` | Processeur ARM 64 bits (Raspberry Pi 4/5, ordinateurs ARM) |

> Une version pour les PC classiques (Intel / AMD, « amd64 ») arrive bientôt.

Pour connaître votre processeur, tapez `uname -m` dans un terminal : `aarch64` = ARM, `x86_64` = Intel/AMD.

## Installer (Debian, Ubuntu, Raspberry Pi OS…)

```bash
cd ~/Téléchargements
sudo apt install ./Thalverion_*_arm64.deb
```

Thalverion apparaît ensuite dans le menu des applications.

## Désinstaller

```bash
sudo apt remove thalverion
```

## Plus d'informations

Site : https://beta.thalverion.com · Contact : thalverion@thalverion.com
