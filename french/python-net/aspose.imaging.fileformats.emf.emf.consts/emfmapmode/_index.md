---
title: "Énumération EmfMapMode"
type: docs
weight: 210
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.consts/emfmapmode/
---

L'énumération MapMode est utilisée pour définir l'unité de mesure pour transformer les unités d'espace de page <br/>            en unités d'espace dispositif et pour définir l'orientation des axes de dessin.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfMapMode

## **Members**
| **Nom du membre** | **Description** |
| :- | :- |
| MM_ANISOTROPIC | Les unités logiques sont mappées à des unités arbitraires avec des axes à l'échelle arbitraire. <br/>            Les enregistrements EMR_SETWINDOWEXTEX et EMR_SETVIEWPORTEXTEX SHOULD be used to specify the units, <br/>            orientation et mise à l'échelle. |
| MM_HIENGLISH | Chaque unité logique est mappée à 0,001 pouce. Le x positif est vers la droite ; le y positif est vers le haut. |
| MM_HIMETRIC | Chaque unité logique est mappée à 0,01 millimètre. Le x positif est vers la droite ; le y positif est vers le haut. |
| MM_ISOTROPIC | Les unités logiques sont mappées à des unités arbitraires avec des axes également mis à l'échelle ; c'est-à-dire qu'une unité <br/>            le long de l'axe x est égale à une unité le long de l'axe y. Les enregistrements EMR_SETWINDOWEXTEX et <br/>            EMR_SETVIEWPORTEXTEX SHOULD be used to specify the units and the orientation <br/>            of the axes.<br/>            Adjustments MUST be made as necessary to ensure that the x and y units remain the same size. <br/>            For example, when the window extent is set, the viewport MUST be adjusted to keep the units isotropic. |
| MM_LOENGLISH | Chaque unité logique est mappée à 0,01 pouce. Le x positif est vers la droite ; le y positif est vers le haut |
| MM_LOMETRIC | Chaque unité logique est mappée à 0,1 millimètre. Le x positif est vers la droite ; le y positif est vers le haut. |
| MM_TEXT | Chaque unité logique est mappée à un pixel de dispositif. Le x positif est vers la droite ; le y positif est vers le bas. |
| MM_TWIPS | Chaque unité logique est mappée à un vingtième du point d'imprimante <br/>            (1/1440 pouce, également appelé "twip"). Le x positif est vers la droite ; le y positif est vers le haut. |
