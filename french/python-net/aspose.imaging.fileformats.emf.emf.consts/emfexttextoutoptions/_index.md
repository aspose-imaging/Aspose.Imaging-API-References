---
title: "EmfExtTextOutOptions Énumération"
type: docs
weight: 100
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/
---

L'énumération ExtTextOutOptions spécifie les paramètres qui contrôlent divers aspects de la<br/>            sortie de texte par les enregistrements EMR_SMALLTEXTOUT (section 2.3.5.37) et dans les objets EmrText.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfExtTextOutOptions

## **Members**
| **Nom du membre** | **Description** |
| :- | :- |
| ETO_CLIPPED | Ce bit indique que le texte DOIT être découpé au rectangle. |
| ETO_GLYPH_INDEX | Ce bit indique que les codes des caractères dans une chaîne de texte de sortie sont en fait <br/>            des index des glyphes de caractères dans une police TrueType. Les index de glyphes sont spécifiques à la police, <br/>            donc pour afficher les caractères corrects lors de la lecture, la police utilisée DOIT être <br/>            identique à la police utilisée pour générer les index. |
| ETO_IGNORELANGUAGE | Ce bit indique qu'aucun traitement spécial du système d'exploitation pour le placement des glyphes ne doit être <br/>            effectué sur les chaînes de droite à gauche ; c'est-à-dire que tout le positionnement des glyphes DOIT être pris en charge par <br/>            le dessin et les enregistrements d'état dans le métafichier. |
| ETO_NO_RECT | Ce bit indique que l'enregistrement ne spécifie pas de rectangle englobant pour la sortie de texte. |
| ETO_NUMERICSLATIN | Ce bit indique que pour afficher les nombres, les chiffres européens DOIVENT être utilisés. |
| ETO_NUMERICSLOCAL | Ce bit indique que pour afficher les nombres, les chiffres appropriés à la locale DOIVENT être utilisés. |
| ETO_OPAQUE | Ce bit indique que la couleur d'arrière-plan actuelle DOIT être utilisée pour remplir le rectangle |
| ETO_PDY | Ce bit indique que les valeurs de déplacement horizontal et vertical des caractères DOIVENT être fournies |
| ETO_REVERSE_INDEX_MAP | Ce bit est réservé et NE DOIT PAS être utilisé |
| ETO_RTLREADING | Ce bit indique que le texte DOIT être disposé dans l'ordre de lecture de droite à gauche, <br/>            au lieu de l'ordre par défaut de gauche à droite. Cela DOIT être appliqué uniquement lorsque la police<br/>            sélectionnée dans le contexte du dispositif de lecture est soit l'hébreu soit l'arabe |
| ETO_SMALL_CHARS | Ce bit indique que les codes des caractères dans une chaîne de texte de sortie sont sur 8 bits, <br/>            dérivés des octets de poids faible des codes de caractères Unicode UTF16-LE de 16 bits, <br/>            où l'octet de poids fort est supposé être 0. |
