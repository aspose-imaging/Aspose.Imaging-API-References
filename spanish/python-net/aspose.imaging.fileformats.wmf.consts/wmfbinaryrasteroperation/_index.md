---
title: "Enumeración WmfBinaryRasterOperation"
type: docs
weight: 20
url: /es/python-net/aspose.imaging.fileformats.wmf.consts/wmfbinaryrasteroperation/
---

La sección de la enumeración BinaryRasterOperation enumera los códigos de operación raster binaria. Los códigos de operación raster<br/>                definen cómo el procesamiento de metarchivos combina los bits del lápiz seleccionado con los<br/>                bits del bitmap de destino.

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfBinaryRasterOperation

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| BLACK | 0, el píxel siempre es 0. |
| COPYPEN | P, el píxel es el color del lápiz. |
| MASKNOTPEN | DPna, el píxel es una combinación del color de pantalla y el inverso del color del lápiz. |
| MASKPEN | DPa, Pixel es una combinación de los colores comunes tanto al lápiz como a la pantalla. |
| MASKPENNOT | PDna, Pixel es una combinación de los colores comunes tanto al lápiz como al<br/>                inverso de la pantalla. |
| MERGENOTPEN | DPno, Pixel es una combinación de los colores comunes tanto a la pantalla como al<br/>                inverso del lápiz. |
| MERGEPEN | DPo, Pixel es una combinación del color del lápiz y el color de la pantalla. |
| MERGEPENNOT | PDno, Pixel es una combinación del color del lápiz y el inverso del<br/>                color de la pantalla. |
| NOP | D, Pixel permanece sin cambios. |
| NOT | Dn, Pixel es el inverso del color de la pantalla. |
| NOTCOPYPEN | Pn, Pixel es el inverso del color del lápiz. |
| NOTMASKPEN | DPan, Pixel es el inverso del color de MASKPEN. |
| NOTMERGEPEN | DPon, Pixel es el inverso del color de MERGEPEN |
| NOTXORPEN | DPxn, Pixel es el inverso del color de XORPEN. |
| WHITE | 1, Pixel es siempre 1 |
| XORPEN | DPx, Pixel es una combinación de los colores en la pluma o en la pantalla, pero no en ambos. |
