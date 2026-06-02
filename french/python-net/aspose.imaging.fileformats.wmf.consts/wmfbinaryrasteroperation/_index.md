---
title: "Énumération WmfBinaryRasterOperation"
type: docs
weight: 20
url: /fr/python-net/aspose.imaging.fileformats.wmf.consts/wmfbinaryrasteroperation/
---

La section de l'énumération BinaryRasterOperation répertorie les codes d'opération raster binaire. Les codes d'opération raster<br/>                définissent comment le traitement du métafichier combine les bits du stylo sélectionné avec les<br/>                bits du bitmap de destination.

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfBinaryRasterOperation

## **Members**
| **Nom du membre** | **Description** |
| :- | :- |
| BLACK | 0, le pixel est toujours 0. |
| COPYPEN | P, le pixel est la couleur du stylo. |
| MASKNOTPEN | DPna, le pixel est une combinaison de la couleur de l'écran et de l'inverse de la couleur du stylo. |
| MASKPEN | DPa, Pixel est une combinaison des couleurs communes au stylo et à l'écran. |
| MASKPENNOT | PDna, Pixel est une combinaison des couleurs communes au stylo et au<br/>                inverse de l'écran. |
| MERGENOTPEN | DPno, Pixel est une combinaison des couleurs communes à l'écran et au<br/>                inverse du stylo. |
| MERGEPEN | DPo, Pixel est une combinaison de la couleur du stylo et de la couleur de l'écran. |
| MERGEPENNOT | PDno, Pixel est une combinaison de la couleur du stylo et de l'inverse de la<br/>                couleur de l'écran. |
| NOP | D, Pixel reste inchangé. |
| NOT | Dn, Pixel est l'inverse de la couleur de l'écran. |
| NOTCOPYPEN | Pn, Pixel est l'inverse de la couleur du stylo. |
| NOTMASKPEN | DPan, Pixel est l'inverse de la couleur MASKPEN. |
| NOTMERGEPEN | DPon, Pixel est l'inverse de la couleur MERGEPEN |
| NOTXORPEN | DPxn, Pixel est l'inverse de la couleur XORPEN. |
| WHITE | 1, Pixel est toujours 1 |
| XORPEN | DPx, le pixel est une combinaison des couleurs dans le stylo ou à l'écran, mais pas les deux. |
