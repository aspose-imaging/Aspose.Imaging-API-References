---
title: "Enumeración TextRenderingHint"
type: docs
weight: 11260
url: /es/python-net/aspose.imaging/textrenderinghint/
---

Especifica la calidad del renderizado de texto.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.TextRenderingHint

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| ANTI_ALIAS | Cada carácter se dibuja usando su mapa de bits de glifo antialiasado sin hinting. Mejor calidad debido al antialiasing. Las diferencias de ancho de tallo pueden ser notables porque el hinting está desactivado. |
| ANTI_ALIAS_GRID_FIT | Cada carácter se dibuja usando su mapa de bits de glifo antialiasado con hinting. Mucha mejor calidad gracias al antialiasing, pero con un mayor costo de rendimiento. |
| CLEAR_TYPE_GRID_FIT | Cada carácter se dibuja usando su mapa de bits de glifo ClearType con hinting. La configuración de mayor calidad. Se utiliza para aprovechar las características de fuente ClearType. |
| SINGLE_BIT_PER_PIXEL | Cada carácter se dibuja usando su mapa de bits de glifo. No se utiliza hinting. |
| SINGLE_BIT_PER_PIXEL_GRID_FIT | Cada carácter se dibuja usando su mapa de bits de glifo. Se utiliza hinting para mejorar la apariencia del carácter en tallos y curvaturas. |
| SYSTEM_DEFAULT | Cada carácter se dibuja usando su mapa de bits de glifo, con la sugerencia de renderizado predeterminada del sistema. El texto se dibujará usando los ajustes de suavizado de fuentes que el usuario haya seleccionado para el sistema. |
