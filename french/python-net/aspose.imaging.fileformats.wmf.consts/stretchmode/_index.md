---
title: "Énumération StretchMode"
type: docs
weight: 10
url: /fr/python-net/aspose.imaging.fileformats.wmf.consts/stretchmode/
---

L'énumération [StretchMode](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/stretchmode/) spécifie le mode d'étirement du bitmap<br/>                qui définit comment le système combine les lignes ou colonnes<br/>                d'un bitmap avec les pixels existants.

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.StretchMode

## **Members**
| **Nom du membre** | **Description** |
| :- | :- |
| BLACK_ON_WHITE | Effectue une opération booléenne AND en utilisant les valeurs de couleur pour les<br/>                pixels éliminés et existants. Si le bitmap est un bitmap monochrome<br/>                ce mode préserve les pixels noirs au détriment des pixels blancs<br/>                pixels |
| COLOR_ON_COLOR | Supprime les pixels. Ce mode supprime toutes les lignes de pixels éliminées<br/>                sans essayer de préserver leurs informations. |
| HALF_TONE | Mappe les pixels du rectangle source en blocs de pixels dans le<br/>                rectangle de destination. La couleur moyenne sur le bloc de destination<br/>                de pixels approxime la couleur des pixels source. |
| WHITE_ON_BLACK | Effectue une opération OU booléenne en utilisant les valeurs de couleur pour les pixels éliminés et existants.<br/>                Si le bitmap est un bitmap monochrome,<br/>                ce mode préserve les pixels blancs au détriment des pixels noirs. |
