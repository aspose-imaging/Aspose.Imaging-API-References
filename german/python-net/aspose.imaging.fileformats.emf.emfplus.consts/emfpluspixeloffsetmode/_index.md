---
title: "EmfPlusPixelOffsetMode Aufzählung"
type: docs
weight: 350
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/
---

Die PixelOffsetMode-Aufzählung definiert, wie Pixel versetzt werden, was den Kompromiss zwischen Rendergeschwindigkeit und Qualität festlegt.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusPixelOffsetMode

## **Members**
| **Member name** | **Beschreibung** |
| :- | :- |
| PIXEL_OFFSET_MODE_DEFAULT | Pixel sind auf ganzzahligen Koordinaten zentriert, wobei Geschwindigkeit über Qualität bevorzugt wird. |
| PIXEL_OFFSET_MODE_HALF | Pixel sind auf halb-ganzzahligen Koordinaten zentriert, was bedeutet, dass das Pixel den Bereich von 0 bis 1 auf beiden Achsen x und y abdeckt und sein Zentrum bei (0.5,0.5) liegt. Durch das Versetzen von Pixeln beim Rendern kann die Renderqualität auf Kosten der Rendergeschwindigkeit verbessert werden. |
| PIXEL_OFFSET_MODE_HIGH_QUALITY | Pixel sind auf halb-ganzzahligen Koordinaten zentriert, wie bei PixelOffsetModeHalf. Höhere Qualität auf Kosten der Geschwindigkeit wird angegeben. |
| PIXEL_OFFSET_MODE_HIGH_SPEED | Pixel sind auf ganzzahligen Koordinaten zentriert, wie bei PixelOffsetModeNone. Höhere Geschwindigkeit auf Kosten der Qualität wird angegeben. |
| PIXEL_OFFSET_MODE_NONE | Pixel sind auf dem Ursprung zentriert, was bedeutet, dass das Pixel den Bereich von -0.5 bis 0.5 auf beiden Achsen x und y abdeckt und sein Zentrum bei (0,0) liegt. |
