---
title: "Aufzählung WmfBinaryRasterOperation"
type: docs
weight: 20
url: /de/python-net/aspose.imaging.fileformats.wmf.consts/wmfbinaryrasteroperation/
---

Der Abschnitt der BinaryRasterOperation‑Enumeration listet die binären Raster‑Operations‑Codes auf. Raster‑Operations‑Codes<br/>                definieren, wie die Metadateiverarbeitung die Bits des ausgewählten Stifts mit den<br/>                Bits in der Ziel‑Bitmap kombiniert.

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfBinaryRasterOperation

## **Members**
| **Member name** | **Beschreibung** |
| :- | :- |
| BLACK | 0, Pixel ist immer 0. |
| COPYPEN | P, Pixel ist die Stiftfarbe. |
| MASKNOTPEN | DPna, Pixel ist eine Kombination aus der Bildschirmfarbe und dem Inversen der Stiftfarbe. |
| MASKPEN | DPa, Pixel ist eine Kombination der Farben, die sowohl für den Stift als auch für den Bildschirm gemeinsam sind. |
| MASKPENNOT | PDna, Pixel ist eine Kombination der Farben, die sowohl für den Stift als auch für das<br/>                Inverse des Bildschirms gemeinsam sind. |
| MERGENOTPEN | DPno, Pixel ist eine Kombination der Farben, die sowohl für den Bildschirm als auch für das<br/>                Inverse des Stifts gemeinsam sind. |
| MERGEPEN | DPo, Pixel ist eine Kombination der Stiftfarbe und der Bildschirmfarbe. |
| MERGEPENNOT | PDno, Pixel ist eine Kombination der Stiftfarbe und des Inversen der<br/>                Bildschirmfarbe. |
| NOP | D, Pixel bleibt unverändert. |
| NOT | Dn, Pixel ist das Inverse der Bildschirmfarbe. |
| NOTCOPYPEN | Pn, Pixel ist das Inverse der Stiftfarbe. |
| NOTMASKPEN | DPan, Pixel ist das Inverse der MASKPEN-Farbe. |
| NOTMERGEPEN | DPon, Pixel ist das Inverse der MERGEPEN-Farbe |
| NOTXORPEN | DPxn, Pixel ist das Inverse der XORPEN-Farbe. |
| WHITE | 1, Pixel ist immer 1 |
| XORPEN | DPx, Pixel ist eine Kombination der Farben im Stift oder auf dem Bildschirm, jedoch nicht in beiden. |
