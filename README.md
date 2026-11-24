# Cartoon 3D Short — version française (JC Digital)

Un skill Claude pour créer des **shorts verticaux animés de 55 à 70 s, en français** : des personnages 2D dans un monde 3D coloré, avec contours encrés, ville peinte, flou de profondeur, caméras fluides, voix off, bruitages et musique de marche. Tout est rendu avec three.js dans Remotion, sur ton propre PC, sans générateur vidéo IA.

Adapté par **JC Digital** pour le public francophone d'Afrique (Cameroun, Sénégal, Côte d'Ivoire…).

## Ce qui change par rapport à l'original
- Script, voix off, titre et description **en français**, dans un français simple et parlé.
- Rythme du script recalé pour le français (environ 150 à 200 mots pour 55-70 s).
- Voix off enregistrée par toi par défaut, sinon une voix française générée.
- Sous-titres français en option (style JC Motion), proposés à chaque short.
- Sujets et comparaisons qui parlent aussi à un public africain quand c'est possible.

Le style visuel, les modèles de code et la méthode de travail restent ceux de l'original.

## Contenu
| Dossier | Contenu |
|---|---|
| `SKILL.md` | Le skill : la méthode complète, les règles et les réglages du look |
| `templates/bridge/` | Le code source complet du short d'exemple (monde, personnages, encre, flou, étalonnage, caméras) |
| `templates/audio/` | Le son synthétisé : bruitages, musique, mixage |
| `templates/scripts/` | Images fixes, planches de comparaison, fusion et contrôle qualité image par image |
| `references/STYLE_BIBLE.md` et `references/reports/` | La formule du script et les mesures du style |

Les images de référence (`references/frames/` et `references/sheets/`) ne sont pas incluses ici. Elles sont dans le dépôt original.

## Installation
1. Copie ce dossier dans `~/.claude/skills/cartoon-3d-short/` (clone-le ou télécharge le ZIP).
2. Installe [Remotion](https://www.remotion.dev/) avec `@remotion/three`, ainsi que Node, Python 3 et ffmpeg.
3. Dans Claude Code, dis : *« Utilise le skill cartoon short et fais un short sur … »*.

Astuce : règle le dossier temporaire sur un grand disque. Chaque rendu Remotion copie `public/` (~1,3 Go) dans le dossier temporaire sans l'effacer.

## Crédits
Basé sur [claude-animated-shorts](https://github.com/mromidev/claude-animated-shorts) de Mr omi, sous licence MIT. La licence d'origine est conservée dans `LICENSE`.

Chaîne YouTube : [JC Digital (@JCTECH2)](https://www.youtube.com/@JCTECH2)
