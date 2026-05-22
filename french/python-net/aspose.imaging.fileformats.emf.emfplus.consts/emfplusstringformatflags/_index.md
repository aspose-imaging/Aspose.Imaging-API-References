---
title: "Énumération EmfPlusStringFormatFlags"
type: docs
weight: 410
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/
---

Les indicateurs StringFormat spécifient des options pour la mise en page du texte graphique, y compris la direction, le découpage et la gestion des polices. Ces indicateurs peuvent être combinés pour spécifier plusieurs options.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusStringFormatFlags

## **Members**
| **Nom du membre** | **Description** |
| :- | :- |
| STRING_FORMAT_BYPASS_GDI | Ce drapeau PEUT être utilisé pour spécifier un processus spécifique à l'implémentation pour le rendu du texte. |
| STRING_FORMAT_DIRECTION_RIGHT_TO_LEFT | Si défini, l'ordre de lecture de la chaîne DOIT être de droite à gauche. Pour le texte horizontal, cela signifie que les caractères sont lus de droite à gauche. Pour le texte vertical, cela signifie que les colonnes sont lues de droite à gauche.<br/>            Si désactivé, le texte horizontal ou vertical DOIT être lu de gauche à droite. |
| STRING_FORMAT_DIRECTION_VERTICAL | Si défini, les lignes individuelles de texte DOIVENT être dessinées verticalement sur le dispositif d'affichage.<br/>            Si désactivé, les lignes individuelles de texte DOIVENT être dessinées horizontalement, chaque nouvelle ligne étant placée sous la ligne précédente. |
| STRING_FORMAT_DISPLAY_FORMAT_CONTROL | Si défini, les caractères de contrôle DOIVENT apparaître dans la sortie sous forme de glyphes Unicode représentatifs. |
| STRING_FORMAT_LINE_LIMIT | Si défini, les lignes complètes de texte DOIVENT être émises et NE DOIVENT PAS être tronquées par le rectangle de mise en page de la chaîne.<br/>            Si désactivé, la mise en page du texte DOIT continuer jusqu'à ce que toutes les lignes soient émises, ou jusqu'à ce que des lignes supplémentaires ne soient pas visibles à cause du rognage.<br/>            Ce drapeau peut être utilisé soit pour refuser, soit pour autoriser qu'une ligne de texte soit partiellement obscurcie par un rectangle de mise en page qui n'est pas un multiple de la hauteur de ligne. Pour que tout le texte soit visible, le rectangle de mise en page doit être au moins aussi haut que la hauteur d'une ligne. |
| STRING_FORMAT_MEASURE_TRAILING_SPACES | Si l'option est activée, l'espace à la fin de chaque ligne DOIT être inclus dans les mesures de la longueur de la chaîne.<br/>            Si l'option est désactivée, l'espace à la fin de chaque ligne DOIT être exclu des mesures de la longueur de la chaîne. |
| STRING_FORMAT_NO_CLIP | Si l'option est activée, le texte qui dépasse du rectangle de mise en page de la chaîne DOIT être autorisé à s'afficher.<br/>            Si l'option est désactivée, tout texte qui dépasse du rectangle de mise en page DOIT être découpé. |
| STRING_FORMAT_NO_FIT_BLACK_BOX | Si l'option est activée, les parties de caractères DOIVENT être autorisées à dépasser le rectangle de mise en page du texte.<br/>            Si l'option est désactivée, les caractères qui dépassent les limites du rectangle de mise en page du texte DOIVENT être repositionnés pour éviter le dépassement.<br/>            Un \"f\" italique est un exemple de caractère qui peut avoir des parties qui dépassent. |
| STRING_FORMAT_NO_FONT_FALLBACK | Si l'option est activée, une police alternative DOIT être utilisée pour les caractères qui ne sont pas pris en charge par la police demandée.<br/>            Si l'option est désactivée, un caractère absent de la police demandée DOIT apparaître comme un caractère \"police manquante\", qui PEUT être un carré ouvert. |
| STRING_FORMAT_NO_WRAP | Si l'option est activée, une chaîne qui dépasse la fin du rectangle de mise en page du texte NE DOIT PAS être renvoyée à la ligne suivante.<br/>            Si l'option est désactivée, une chaîne qui dépasse la fin du rectangle de mise en page du texte DOIT être coupée à la dernière frontière de mot à l'intérieur du rectangle englobant, et le reste de la chaîne DOIT être renvoyé à la ligne suivante. |
