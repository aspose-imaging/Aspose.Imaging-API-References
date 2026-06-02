---
title: "Énumération EmfStretchMode"
type: docs
weight: 340
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.consts/emfstretchmode/
---

L'énumération StretchMode est utilisée pour spécifier comment les données de couleur sont ajoutées ou supprimées des images bitmap qui sont étirées ou compressées.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfStretchMode

## **Members**
| **Nom du membre** | **Description** |
| :- | :- |
| STRETCH_ANDSCANS | Effectue une opération booléenne AND en utilisant les valeurs de couleur des pixels éliminés et existants.<br/>            Si le bitmap est un bitmap monochrome, ce mode préserve les pixels noirs au détriment des pixels blancs |
| STRETCH_DELETESCANS | Supprime les pixels. Ce mode supprime toutes les lignes de pixels éliminées sans essayer de préserver leurs informations. |
| STRETCH_HALFTONE | Mappe les pixels du rectangle source en blocs de pixels dans le rectangle de destination. <br/>            La couleur moyenne du bloc de pixels de destination approxime la couleur des pixels source. |
| STRETCH_ORSCANS | Effectue une opération booléenne OR en utilisant les valeurs de couleur des pixels éliminés et existants. <br/>            Si le bitmap est un bitmap monochrome, ce mode préserve les pixels blancs au détriment des pixels noirs. |
