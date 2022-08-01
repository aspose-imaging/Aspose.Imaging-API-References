---
title: Warp
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Aplica una transformación warp definida por un rectángulo y un paralelogramo a esteGraphicsPathaspose.imaging/graphicspath .
type: docs
weight: 180
url: /es/net/aspose.imaging/graphicspath/warp/
---
## Warp(PointF[], RectangleF) {#warp}

Aplica una transformación warp, definida por un rectángulo y un paralelogramo, a este[`GraphicsPath`](../../graphicspath) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| destPoints | PointF[] | una matriz de[`PointF`](../../pointf) estructuras que definen un paralelogramo al que se le une el rectángulo definido por*srcRect* se transforma La matriz puede contener tres o cuatro elementos. Si la matriz contiene tres elementos, los primeros tres puntos implican la esquina inferior derecha del paralelogramo. |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef) que representa el rectángulo que se transforma al paralelogramo definido por*destPoints*. |

### Ver también

* struct [PointF](../../pointf)
* struct [RectangleF](../../rectanglef)
* class [GraphicsPath](../../graphicspath)
* espacio de nombres [Aspose.Imaging](../../graphicspath)
* asamblea [Aspose.Imaging](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

Aplica una transformación warp, definida por un rectángulo y un paralelogramo, a este[`GraphicsPath`](../../graphicspath) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| destPoints | PointF[] | una matriz de[`PointF`](../../pointf) estructuras que definen un paralelogramo al que se le une el rectángulo definido por*srcRect* se transforma La matriz puede contener tres o cuatro elementos. Si la matriz contiene tres elementos, los primeros tres puntos implican la esquina inferior derecha del paralelogramo. |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef) que representa el rectángulo que se transforma al paralelogramo definido por*destPoints*. |
| matrix | Matrix | A[`Matrix`](../../matrix) que especifica una transformación geométrica para aplicar a la ruta. |

### Ver también

* struct [PointF](../../pointf)
* struct [RectangleF](../../rectanglef)
* class [Matrix](../../matrix)
* class [GraphicsPath](../../graphicspath)
* espacio de nombres [Aspose.Imaging](../../graphicspath)
* asamblea [Aspose.Imaging](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

Aplica una transformación warp, definida por un rectángulo y un paralelogramo, a este[`GraphicsPath`](../../graphicspath) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| destPoints | PointF[] | una matriz de[`PointF`](../../pointf) estructuras que define un paralelogramo al que se une el rectángulo definido por*srcRect* se transforma La matriz puede contener tres o cuatro elementos. Si la matriz contiene tres elementos, los primeros tres puntos implican la esquina inferior derecha del paralelogramo. |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef) que representa el rectángulo que se transforma al paralelogramo definido por*destPoints*. |
| matrix | Matrix | A[`Matrix`](../../matrix) que especifica una transformación geométrica para aplicar a la ruta. |
| warpMode | WarpMode | A[`WarpMode`](../../warpmode) enumeración que especifica si esta operación de deformación usa perspectiva o modo bilineal. |

### Ver también

* struct [PointF](../../pointf)
* struct [RectangleF](../../rectanglef)
* class [Matrix](../../matrix)
* enum [WarpMode](../../warpmode)
* class [GraphicsPath](../../graphicspath)
* espacio de nombres [Aspose.Imaging](../../graphicspath)
* asamblea [Aspose.Imaging](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

Aplica una transformación warp, definida por un rectángulo y un paralelogramo, a este[`GraphicsPath`](../../graphicspath) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| destPoints | PointF[] | una matriz de[`PointF`](../../pointf) estructuras que definen un paralelogramo al que se le une el rectángulo definido por*srcRect* se transforma La matriz puede contener tres o cuatro elementos. Si la matriz contiene tres elementos, los primeros tres puntos implican la esquina inferior derecha del paralelogramo. |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef) que representa el rectángulo que se transforma al paralelogramo definido por*destPoints*. |
| matrix | Matrix | A[`Matrix`](../../matrix) que especifica una transformación geométrica para aplicar a la ruta. |
| warpMode | WarpMode | A[`WarpMode`](../../warpmode) enumeración que especifica si esta operación de deformación usa perspectiva o modo bilineal. |
| flatness | Single | Un valor de 0 a 1 que especifica qué tan plana es la ruta resultante. Para obtener más información, consulte el[`Flatten`](../flatten) métodos. |

### Ver también

* struct [PointF](../../pointf)
* struct [RectangleF](../../rectanglef)
* class [Matrix](../../matrix)
* enum [WarpMode](../../warpmode)
* class [GraphicsPath](../../graphicspath)
* espacio de nombres [Aspose.Imaging](../../graphicspath)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
