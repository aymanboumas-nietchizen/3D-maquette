# Façade perforée — Gare Hay Mohammadi (maquette 3D)

Mini-site 3D de la double peau perforée (concept V1 : fil attracteur, cascade du motif ×3 → ×34, gravure en bande).

**Lien : https://aymanboumas-nietchizen.github.io/3D-maquette/**

- S'ouvre dans n'importe quel navigateur récent (Chrome Android, Safari iPhone, ordinateur) : rotation, zoom, vues prédéfinies.
- Bouton « Voir en RA » : réalité augmentée sur Android (Scene Viewer / WebXR) et iPhone (AR Quick Look, `coque.usdz`).
- QR code : `qr.png` (même lien).

## Contenu
| Fichier | Rôle |
|---|---|
| `index.html` | page (model-viewer de Google, hébergé localement, aucune dépendance externe) |
| `Façade perforée.glb` | maquette 3D glTF (m, Y vers le haut), 130 tôles + pièce d'angle + gravures |
| `Façade perforée.usdz` | même maquette pour iPhone / iPad (AR Quick Look) |
| `model-viewer.min.js` | @google/model-viewer 4.4.0 |
| `poster.jpg`, `qr.png`, `qr.svg` | image d'attente et QR code |

## Mettre à jour la maquette
Remplacer `Façade perforée.glb` et `Façade perforée.usdz` par les nouveaux exports, puis pousser sur `main` : le site se met à jour en 1 à 2 minutes.
