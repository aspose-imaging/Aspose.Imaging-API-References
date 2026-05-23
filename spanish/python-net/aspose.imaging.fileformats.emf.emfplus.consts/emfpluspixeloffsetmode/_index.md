---
title: "Enumeración EmfPlusPixelOffsetMode"
type: docs
weight: 350
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/
---

La enumeración PixelOffsetMode define cómo se desplazan los píxeles, lo que especifica el compromiso entre la velocidad de renderizado y la calidad.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusPixelOffsetMode

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| PIXEL_OFFSET_MODE_DEFAULT | Los píxeles se centran en coordenadas enteras, especificando velocidad sobre calidad. |
| PIXEL_OFFSET_MODE_HALF | Los píxeles se centran en coordenadas medio-enteras, lo que significa que el píxel cubre el área de 0 a 1 en ambos ejes x e y y su centro está en (0.5,0.5). Al desplazar los píxeles durante el renderizado, la calidad del renderizado puede mejorarse a costa de la velocidad de renderizado. |
| PIXEL_OFFSET_MODE_HIGH_QUALITY | Los píxeles se centran en coordenadas medio-enteras, como con PixelOffsetModeHalf. Se especifica mayor calidad a expensas de la velocidad. |
| PIXEL_OFFSET_MODE_HIGH_SPEED | Los píxeles se centran en coordenadas enteras, como con PixelOffsetModeNone. Se especifica mayor velocidad a expensas de la calidad. |
| PIXEL_OFFSET_MODE_NONE | Los píxeles se centran en el origen, lo que significa que el píxel cubre el área de -0.5 a 0.5 en ambos ejes x e y y su centro está en (0,0). |
