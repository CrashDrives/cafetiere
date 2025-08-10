# ☕ Cafetière Connectée

Un projet ESPHome pour automatiser et programmer une cafetière via Home Assistant.  
Affichage OLED, encodeur rotatif, boutons physiques, LED RGB, et écran de veille intelligent.

---

## 🔧 Fonctionnalités

- Programmation horaire (heure + minute)
- Affichage OLED avec pages dynamiques
- Encodeur rotatif pour navigation et réglage
- Boutons physiques pour sélection et validation
- LED RGB avec effets visuels selon l’état
- Screensaver anti burn-in après 2 minutes d’inactivité
- Intégration complète dans Home Assistant

---

## 🧠 Matériel utilisé

| Composant         | Rôle                        |
|-------------------|-----------------------------|
| ESP32             | Microcontrôleur principal   |
| SH1106 OLED 128x64| Affichage                   |
| Rotary Encoder    | Navigation et réglage       |
| Boutons GPIO      | Interaction physique        |
| LED RGB           | Feedback visuel             |
| Relais GPIO       | Activation de la cafetière  |

---

## 📦 Installation

1. Cloner ce dépôt :
   ```bash
   git clone https://github.com/CrashDrives/cafetiere.git![1754835535150](https://github.com/user-attachments/assets/ad6a34e2-87fc-4723-96c2-735c3778d6ff)

