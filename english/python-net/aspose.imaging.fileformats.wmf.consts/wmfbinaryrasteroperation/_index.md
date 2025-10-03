---
title: WmfBinaryRasterOperation Enumeration
type: docs
weight: 20
url: /python-net/aspose.imaging.fileformats.wmf.consts/wmfbinaryrasteroperation/
---

The BinaryRasterOperation Enumeration section lists the binary raster-operation codes. Raster operation codes<br/>                define how metafile processing combines the bits from the selected pen with the<br/>                bits in the destination bitmap.

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfBinaryRasterOperation

## **Members**
| **Member name** | **Description** |
| :- | :- |
| BLACK | 0, Pixel is always 0. |
| COPYPEN | P, Pixel is the pen color. |
| MASKNOTPEN | DPna, Pixel is a combination of the screen color and the inverse of the pen color. |
| MASKPEN | DPa, Pixel is a combination of the colors common to both the pen and the screen. |
| MASKPENNOT | PDna, Pixel is a combination of the colors common to both the pen and the<br/>                inverse of the screen. |
| MERGENOTPEN | DPno, Pixel is a combination of the colors common to both the screen and<br/>                the inverse of the pen. |
| MERGEPEN | DPo, Pixel is a combination of the pen color and the screen color. |
| MERGEPENNOT | PDno, Pixel is a combination of the pen color and the inverse of the<br/>                screen color. |
| NOP | D, Pixel remains unchanged. |
| NOT | Dn, Pixel is the inverse of the screen color. |
| NOTCOPYPEN | Pn, Pixel is the inverse of the pen color. |
| NOTMASKPEN | DPan, Pixel is the inverse of the MASKPEN color. |
| NOTMERGEPEN | DPon, Pixel is the inverse of the MERGEPEN color |
| NOTXORPEN | DPxn, Pixel is the inverse of the XORPEN color. |
| WHITE | 1, Pixel is always 1 |
| XORPEN | DPx, Pixel is a combination of the colors in the pen or in the screen, but not in both. |
