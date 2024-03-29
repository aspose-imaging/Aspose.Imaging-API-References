---
title: DrawLines
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Dibuja una serie de segmentos de línea que conectan una matriz dePointaspose.imaging/point estructuras.
type: docs
weight: 260
url: /es/net/aspose.imaging/graphics/drawlines/
---
## DrawLines(Pen, Point[]) {#drawlines_1}

Dibuja una serie de segmentos de línea que conectan una matriz de[`Point`](../../point) estructuras.

```csharp
public void DrawLines(Pen pen, Point[] points)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) que determina el color, el ancho y el estilo de los segmentos de línea. |
| points | Point[] | Gama de[`Point`](../../point) estructuras que representan los puntos a conectar. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. -o- *points* es nulo. |
| ArgumentException | los*points* matriz contiene menos de 2 puntos. |

### Ver también

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* espacio de nombres [Aspose.Imaging](../../graphics)
* asamblea [Aspose.Imaging](../../../)

---

## DrawLines(Pen, PointF[]) {#drawlines}

Dibuja una serie de segmentos de línea que conectan una matriz de[`PointF`](../../pointf) estructuras.

```csharp
public void DrawLines(Pen pen, PointF[] points)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) que determina el color, el ancho y el estilo de los segmentos de línea. |
| points | PointF[] | Gama de[`PointF`](../../pointf) estructuras que representan los puntos a conectar. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. -o- *points* es nulo. |
| ArgumentException | los*points* matriz contiene menos de 2 puntos. |

### Ver también

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* espacio de nombres [Aspose.Imaging](../../graphics)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
