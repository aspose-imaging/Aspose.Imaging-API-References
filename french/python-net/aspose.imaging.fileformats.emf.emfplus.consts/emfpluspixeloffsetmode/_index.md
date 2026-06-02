---
title: "Énumération EmfPlusPixelOffsetMode"
type: docs
weight: 350
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/
---

L'énumération PixelOffsetMode définit comment les pixels sont décalés, ce qui spécifie le compromis entre la vitesse de rendu et la qualité.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusPixelOffsetMode

## **Members**
| **Nom du membre** | **Description** |
| :- | :- |
| PIXEL_OFFSET_MODE_DEFAULT | Les pixels sont centrés sur des coordonnées entières, privilégiant la vitesse plutôt que la qualité. |
| PIXEL_OFFSET_MODE_HALF | Les pixels sont centrés sur des coordonnées demi‑entiers, ce qui signifie que le pixel couvre la zone de 0 à 1 sur les axes x et y et que son centre se trouve à (0.5,0.5). En décalant les pixels lors du rendu, la qualité du rendu peut être améliorée au prix de la vitesse de rendu. |
| PIXEL_OFFSET_MODE_HIGH_QUALITY | Les pixels sont centrés sur des coordonnées demi‑entiers, comme avec PixelOffsetModeHalf. Une qualité supérieure au détriment de la vitesse est spécifiée. |
| PIXEL_OFFSET_MODE_HIGH_SPEED | Les pixels sont centrés sur des coordonnées entières, comme avec PixelOffsetModeNone. Une vitesse supérieure au détriment de la qualité est spécifiée. |
| PIXEL_OFFSET_MODE_NONE | Les pixels sont centrés sur l'origine, ce qui signifie que le pixel couvre la zone de -0.5 à 0.5 sur les axes x et y et que son centre se trouve à (0,0). |
