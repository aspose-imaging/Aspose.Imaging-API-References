---
title: "EmfPlusPixelOffsetMode Enumerazione"
type: docs
weight: 350
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/
---

L'enumerazione PixelOffsetMode definisce come i pixel sono offset, specificando il compromesso tra velocità di rendering e qualità.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusPixelOffsetMode

## **Members**
| **Member name** | **Descrizione** |
| :- | :- |
| PIXEL_OFFSET_MODE_DEFAULT | I pixel sono centrati su coordinate intere, privilegiando la velocità rispetto alla qualità. |
| PIXEL_OFFSET_MODE_HALF | I pixel sono centrati su coordinate semi-intere, il che significa che il pixel copre l'area da 0 a 1 sia sull'asse x che sull'asse y e il suo centro è a (0.5,0.5). Spostando i pixel durante il rendering, la qualità del rendering può essere migliorata a costo della velocità di rendering. |
| PIXEL_OFFSET_MODE_HIGH_QUALITY | I pixel sono centrati su coordinate semi-intere, come con PixelOffsetModeHalf. È specificata una qualità superiore a scapito della velocità. |
| PIXEL_OFFSET_MODE_HIGH_SPEED | I pixel sono centrati su coordinate intere, come con PixelOffsetModeNone. È specificata una velocità superiore a scapito della qualità. |
| PIXEL_OFFSET_MODE_NONE | I pixel sono centrati sull'origine, il che significa che il pixel copre l'area da -0.5 a 0.5 sia sull'asse x che sull'asse y e il suo centro è a (0,0). |
