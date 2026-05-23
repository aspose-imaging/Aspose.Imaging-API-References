---
title: "Enumeración EmfPlusTextRenderingHint"
type: docs
weight: 430
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/
---

La enumeración TextRenderingHint define tipos de sugerencias de texto y anti-aliasing, que afectan la calidad del renderizado de texto.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusTextRenderingHint

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| TEXT_RENDERING_HINT_ANTIALIAS | Especifica que cada carácter de texto se dibuja usando su mapa de bits de glifo anti-alias sin hinting. La calidad es mejor con antialiasing, pero las diferencias de ancho de tallo PUEDEN ser perceptibles porque el hinting está desactivado. |
| TEXT_RENDERING_HINT_ANTIALIAS_GRID_FIT | Especifica que cada carácter de texto DEBE dibujarse usando su mapa de bits de glifo anti-alias con suavizado. La renderización es de alta calidad gracias al antialiasing, pero con un mayor coste de rendimiento. |
| TEXT_RENDERING_HINT_CLEAR_TYPE_GRID_FIT | Especifica que cada carácter de texto DEBE dibujarse usando su mapa de bits de glifo ClearType con suavizado. Esta es la configuración de hinting de texto de mayor calidad, que se utiliza para aprovechar las características de fuentes ClearType. |
| TEXT_RENDERING_HINT_SINGLE_BIT_PER_PIXEL | Especifica que cada carácter de texto DEBE dibujarse usando su mapa de bits de glifo. No se utiliza suavizado. |
| TEXT_RENDERING_HINT_SINGLE_BIT_PER_PIXEL_GRID_FIT | Especifica que cada carácter de texto SHOULD dibujarse usando su mapa de bits de glifo. El suavizado MAY usarse para mejorar la apariencia de los tallos y la curvatura de los glifos de los caracteres. |
| TEXT_RENDERING_HINT_SYSTEM_DEFAULT | Especifica que cada carácter de texto SHOULD dibujarse usando cualquier configuración de suavizado de fuentes que haya sido configurada en el sistema operativo. |
