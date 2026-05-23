---
title: "EmfPlusPixelOffsetMode Sıralaması"
type: docs
weight: 350
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/
---

PixelOffsetMode sayımı, piksellerin nasıl kaydırıldığını tanımlar; bu da render hızları ile kalite arasındaki dengeyi belirler.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusPixelOffsetMode

## **Members**
| **Üye adı** | **Açıklama** |
| :- | :- |
| PIXEL_OFFSET_MODE_DEFAULT | Pikseller tam sayı koordinatlarında ortalanır, hızın kaliteye tercih edildiğini belirtir. |
| PIXEL_OFFSET_MODE_HALF | Pikseller yarı tam sayı koordinatlarında ortalanır, bu da pikselin x ve y eksenlerinde 0 ile 1 arasındaki alanı kapsadığı ve merkezinin (0.5,0.5) konumunda olduğu anlamına gelir. İşleme sırasında pikselleri kaydırarak, render kalitesi render hızının maliyetine karşı iyileştirilebilir. |
| PIXEL_OFFSET_MODE_HIGH_QUALITY | Pikseller yarı tam sayı koordinatlarında ortalanır, PixelOffsetModeHalf gibi. Hızın maliyetine karşı daha yüksek kalite belirtilir. |
| PIXEL_OFFSET_MODE_HIGH_SPEED | Pikseller tam sayı koordinatlarında ortalanır, PixelOffsetModeNone gibi. Kalitenin maliyetine karşı daha yüksek hız belirtilir. |
| PIXEL_OFFSET_MODE_NONE | Pikseller orijinde ortalanır, bu da pikselin x ve y eksenlerinde -0.5 ile 0.5 arasındaki alanı kapsadığı ve merkezinin (0,0) konumunda olduğu anlamına gelir. |
