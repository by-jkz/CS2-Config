<div align="center">

# 🎮 CS2 PRO LOW LATENCY CONFIG
### by.jkz — v4.1

![CS2](https://img.shields.io/badge/Game-Counter--Strike%202-orange?style=flat-square)
![Version](https://img.shields.io/badge/Version-4.1-blue?style=flat-square)
![Updated](https://img.shields.io/badge/Updated-Septembre%202026-green?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square)

**Config CS2 compétitif / FACEIT / Low Latency**  
Auditée depuis les fichiers Steam réels — 100% reproductible

</div>

---

## 📁 Structure du repo

```
CS2-Config/
├── README.md                          ← Ce fichier
├── autoexec.cfg                       ← Config principale CS2
├── cs2_video.txt                      ← Paramètres vidéo optimisés
├── cfg/
│   ├── cs2_user_convars_0_slot0.vcfg  ← Crosshair + sensibilité (Steam)
│   ├── cs2_user_keys_0_slot0.vcfg     ← Binds (Steam)
│   └── Keyboard-cfg-byclaude.json    ← Profil clavier M36HE (Attack Shark)
└── docs/
    ├── installation.md                ← Guide d'installation détaillé
    ├── hardware.md                    ← Setup hardware + NVIDIA
    └── crosshair.md                   ← Détails crosshair
```

---

## ⚡ Installation rapide

### 1️⃣ autoexec.cfg
```
C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg\
```

### 2️⃣ cs2_video.txt + fichiers cfg/
```
C:\Program Files (x86)\Steam\userdata\[TON_STEAM_ID]\730\local\cfg\
```
> ⚠️ Remplace `[TON_STEAM_ID]` par ton propre Steam ID  
> ⚠️ Mets `cs2_video.txt` en **lecture seule** après installation

### 3️⃣ Profil clavier M36HE
Importer `cfg/M36HE-CS2.json` dans le logiciel **Attack Shark**

### 4️⃣ Options de lancement Steam
```
-novid +fps_max 240 +exec autoexec.cfg -allow_third_party_software -nojoy
```
> Adapte `fps_max` selon ton Hz : 120Hz→240 / 144Hz→288 / 240Hz→480 / 360Hz→720

📄 [Guide d'installation complet](docs/installation.md)

---

## 🖥️ Paramètres vidéo

| Paramètre | Valeur |
|---|---|
| Résolution | **1280x960** (4:3 stretch) |
| Mode | **Plein écran exclusif** |
| VSync | **OFF** |
| Low Latency | **ON** |
| MSAA | **OFF** |
| Ombres | **OFF** |
| HDR | **OFF** |

---

## 🎯 Crosshair

| Paramètre | Valeur |
|---|---|
| Style | 2 — Statique |
| Taille | 1.5 |
| Gap | -2 (fixe) |
| Couleur | Cyan (R:50 G:255 B:255) |
| Contour | Oui |
| Recoil | Non |

📄 [Détails crosshair](docs/crosshair.md)

---

## 🖱️ Souris

| Paramètre | Valeur |
|---|---|
| DPI | **800** |
| Sensitivity in-game | **1.25** |
| eDPI | **1000** |
| Polling rate | **2000Hz** |
| Angle Snap | **OFF** |

---

## 🌐 Réseau

| Paramètre | Valeur |
|---|---|
| rate | 786432 |
| cl_net_buffer_ticks | **1** (filaire) / **2** (Wi-Fi) |
| mm_dedicated_search_maxping | 25ms |

---

## ⌨️ Binds principaux

| Touche | Action |
|---|---|
| SHIFT | Drop arme secondaire |
| G | Drop bombe |
| CTRL | Équiper bombe |
| E | Couteau |
| F | Use / Ramasser |
| Q | Jeter arme |
| 1-5 | Nades (HE/Flash/Smoke/Molotov/Decoy) |
| MOUSE4 | Accroupi |
| MOUSE5 | Sprint |
| MWHEELUP/DOWN | Arme principale / secondaire |
| X | Push to talk |
| P | Recharger autoexec |

---

## ⌨️ Clavier M36HE — Profil Hall Effect

| Touche | Trigger | Fast Trigger |
|---|---|---|
| W / A / S / D | 0.2mm | ✅ ON (sensitivity 0.2mm) |
| E / F / L-Shift / Space | 0.3mm | ❌ |
| L-Ctrl | 0.5mm | ❌ |
| 1 / 2 / 3 / 4 / 5 | 0.4mm | ❌ |
| Q / G / Esc / F1-F6 | 0.8mm | ❌ |
| Reste | 1.2mm | ❌ |

> SOCD activé sur A+D (Snap Tap)

---

## 🎮 Setup Hardware

| Composant | Modèle |
|---|---|
| Souris | Attack Shark R5 Ultra 8K PAW3950MAX |
| Clavier | Attack Shark M36HE (Hall Effect) |

📄 [Détails hardware + NVIDIA](docs/hardware.md)

---

## ✅ Checklist nouveau PC

- [ ] `autoexec.cfg` → dossier `cfg\` CS2
- [ ] `cs2_video.txt` → dossier `userdata\[STEAMID]\730\local\cfg\`
- [ ] `cs2_video.txt` en **lecture seule**
- [ ] Fichiers `cfg/*.vcfg` → même dossier que cs2_video.txt
- [ ] Options de lancement Steam ajoutées
- [ ] Message de confirmation en console CS2 ✅
- [ ] Panneau NVIDIA configuré
- [ ] Mode alimentation Windows → Performances élevées
- [ ] Souris : 800 DPI / 2000Hz / Angle Snap OFF
- [ ] Clavier M36HE : importer `cfg/M36HE-CS2.json`

---

<div align="center">

*Config v4.1 — Auditée depuis les fichiers Steam réels — septembre 2026*

</div>
