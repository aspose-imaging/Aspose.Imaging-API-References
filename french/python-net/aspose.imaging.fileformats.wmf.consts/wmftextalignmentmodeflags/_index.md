---
title: "Énumération WmfTextAlignmentModeFlags"
type: docs
weight: 270
url: /fr/python-net/aspose.imaging.fileformats.wmf.consts/wmftextalignmentmodeflags/
---

Les indicateurs TextAlignmentMode spécifient la relation entre un point de référence et un rectangle englobant<br/>                pour l'alignement du texte. Ces indicateurs peuvent être combinés pour spécifier plusieurs options, avec la<br/>                restriction qu'un seul indicateur peut être choisi et qui modifie la position de dessin dans le contexte du dispositif de lecture<br/>                de lecture.<br/>                L'alignement horizontal du texte est effectué lorsque la police possède une ligne de base horizontale par défaut.

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfTextAlignmentModeFlags

## **Members**
| **Nom du membre** | **Description** |
| :- | :- |
| BASELINE | Le point de référence DOIT être sur la ligne de base du texte. |
| BOTTOM | Le point de référence DOIT être sur le bord inférieur du rectangle englobant. |
| CENTER | Le point de référence DOIT être aligné horizontalement avec le centre du rectangle englobant. |
| HORIZONTAL | Représente les ensembles d'alignement de texte horizontal (Gauche | Droite | Centre) |
| LEFT | Le point de référence DOIT être sur le bord gauche du rectangle englobant. |
| NOUPDATECP | La position de dessin dans le contexte du dispositif de lecture NE DOIT PAS être mise à jour après chaque<br/>                appel de sortie de texte. Le point de référence DOIT être transmis à la fonction de sortie de texte. |
| RIGHT | Le point de référence DOIT être sur le bord droit du rectangle englobant. |
| RTLREADING | Le texte DOIT être disposé dans l'ordre de lecture de droite à gauche, au lieu de l'ordre par défaut de gauche à droite. Cela DOIT<br/>                être appliqué uniquement lorsque la police définie dans le contexte du dispositif de lecture est soit hébreu, soit arabe. |
| TOP | Le point de référence DOIT être sur le bord supérieur du rectangle englobant. |
| UPDATECP | La position de dessin dans le contexte du dispositif de lecture DOIT être mise à jour après chaque texte<br/>                appel de sortie de texte. Elle DOIT être utilisée comme point de référence. |
| VERTICAL | Représente les ensembles d'alignement de texte vertical (Haut | Bas | Baseline) |
