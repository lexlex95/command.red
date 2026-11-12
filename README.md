# COMMAND.RED — EVASION.ROUGE // FUITE 1983

Prototype de jeu HTML5/Three.js : fuyez à vélo à travers une forêt enneigée de nuit
et atteignez le point d'extraction sans être intercepté par les patrouilles.

## Jouer

Ouvrez `index.html` dans un navigateur, ou en ligne via GitHub Pages :
https://lexlex95.github.io/command.red/

## Contrôles

| Action | Clavier | Mobile |
|---|---|---|
| Pédaler | `Z` / `↑` | automatique |
| Freiner | `S` / `↓` | bouton FREIN |
| Tourner | `Q` / `D` ou `←` / `→` | moitiés gauche/droite de l'écran |
| Lampe frontale | `F` | bouton LAMPE |

## Mécaniques

- **Bruit** : plus vous roulez vite, plus les patrouilles vous entendent.
- **Traces dans la neige** : vos traces persistent derrière vous.
- **Niveau d'alerte** : les projecteurs des jeeps vous repèrent de plus loin si votre lampe est allumée. À 100 % d'alerte, la jeep passe en poursuite.
- **Batterie** : la lampe la consomme ; ramassez les batteries dorées sur la carte.

## Technique

- Un seul fichier `index.html`, Three.js chargé via CDN (connexion internet requise).
- Audio 100 % procédural (Web Audio API), aucun asset externe.
