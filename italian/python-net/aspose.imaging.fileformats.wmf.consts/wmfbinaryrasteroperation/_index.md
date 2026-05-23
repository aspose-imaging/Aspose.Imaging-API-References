---
title: "Enumerazione WmfBinaryRasterOperation"
type: docs
weight: 20
url: /it/python-net/aspose.imaging.fileformats.wmf.consts/wmfbinaryrasteroperation/
---

La sezione dell'Enumerazione BinaryRasterOperation elenca i codici di operazione raster binari. I codici di operazione raster<br/>                definiscono come l'elaborazione del metafile combina i bit della penna selezionata con i<br/>                bit nel bitmap di destinazione.

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfBinaryRasterOperation

## **Members**
| **Member name** | **Descrizione** |
| :- | :- |
| BLACK | 0, il pixel è sempre 0. |
| COPYPEN | P, il pixel è il colore della penna. |
| MASKNOTPEN | DPna, il pixel è una combinazione del colore dello schermo e dell'inverso del colore della penna. |
| MASKPEN | DPa, Pixel è una combinazione dei colori comuni sia alla penna sia allo schermo. |
| MASKPENNOT | PDna, Pixel è una combinazione dei colori comuni sia alla penna sia all'<br/>                inverso dello schermo. |
| MERGENOTPEN | DPno, Pixel è una combinazione dei colori comuni sia allo schermo sia all'<br/>                inverso della penna. |
| MERGEPEN | DPo, Pixel è una combinazione del colore della penna e del colore dello schermo. |
| MERGEPENNOT | PDno, Pixel è una combinazione del colore della penna e dell'<br/>                inverso del colore dello schermo. |
| NOP | D, Pixel rimane invariato. |
| NOT | Dn, Pixel è l'inverso del colore dello schermo. |
| NOTCOPYPEN | Pn, Pixel è l'inverso del colore della penna. |
| NOTMASKPEN | DPan, Pixel è l'inverso del colore di MASKPEN. |
| NOTMERGEPEN | DPon, Pixel è l'inverso del colore di MERGEPEN |
| NOTXORPEN | DPxn, Pixel è l'inverso del colore di XORPEN. |
| WHITE | 1, Pixel è sempre 1 |
| XORPEN | DPx, Pixel è una combinazione dei colori nella penna o nello schermo, ma non in entrambi. |
