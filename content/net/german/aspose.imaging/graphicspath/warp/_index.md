---
title: Warp
second_title: Aspose.Imaging für .NET-API-Referenz
description: Wendet eine durch ein Rechteck und ein Parallelogramm definierte Warp-Transformation darauf anGraphicsPathaspose.imaging/graphicspath .
type: docs
weight: 180
url: /de/aspose.imaging/graphicspath/warp/
---
## Warp(PointF[], RectangleF) {#warp}

Wendet eine durch ein Rechteck und ein Parallelogramm definierte Warp-Transformation darauf an[`GraphicsPath`](../../graphicspath) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destPoints | PointF[] | Eine Reihe von[`PointF`](../../pointf) Strukturen, die ein Parallelogramm definieren, zu dem das Rechteck definiert ist*srcRect* wird transformiert. Das Array kann entweder drei oder vier Elemente enthalten. Wenn das Array drei Elemente enthält, wird die untere rechte Ecke des Parallelogramms durch die ersten drei Punkte impliziert. |
| srcRect | RectangleF | EIN[`RectangleF`](../../rectanglef) das das Rechteck darstellt, das in das durch definierte Parallelogramm transformiert wird*destPoints*. |

### Siehe auch

* struct [PointF](../../pointf)
* struct [RectangleF](../../rectanglef)
* class [GraphicsPath](../../graphicspath)
* namensraum [Aspose.Imaging](../../graphicspath)
* Montage [Aspose.Imaging](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

Wendet eine durch ein Rechteck und ein Parallelogramm definierte Warp-Transformation darauf an[`GraphicsPath`](../../graphicspath) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destPoints | PointF[] | Eine Reihe von[`PointF`](../../pointf) Strukturen, die ein Parallelogramm definieren, zu dem das Rechteck definiert ist*srcRect* wird transformiert. Das Array kann entweder drei oder vier Elemente enthalten. Wenn das Array drei Elemente enthält, wird die untere rechte Ecke des Parallelogramms durch die ersten drei Punkte impliziert. |
| srcRect | RectangleF | EIN[`RectangleF`](../../rectanglef) das das Rechteck darstellt, das in das durch definierte Parallelogramm transformiert wird*destPoints*. |
| matrix | Matrix | EIN[`Matrix`](../../matrix) die eine geometrische Transformation angibt, die auf den Pfad angewendet werden soll. |

### Siehe auch

* struct [PointF](../../pointf)
* struct [RectangleF](../../rectanglef)
* class [Matrix](../../matrix)
* class [GraphicsPath](../../graphicspath)
* namensraum [Aspose.Imaging](../../graphicspath)
* Montage [Aspose.Imaging](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

Wendet eine durch ein Rechteck und ein Parallelogramm definierte Warp-Transformation darauf an[`GraphicsPath`](../../graphicspath) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destPoints | PointF[] | Eine Reihe von[`PointF`](../../pointf) Strukturen, die ein Parallelogramm definieren, zu dem das Rechteck definiert ist*srcRect* wird transformiert. Das Array kann entweder drei oder vier Elemente enthalten. Wenn das Array drei Elemente enthält, wird die untere rechte Ecke des Parallelogramms durch die ersten drei Punkte impliziert. |
| srcRect | RectangleF | EIN[`RectangleF`](../../rectanglef) das das Rechteck darstellt, das in das durch definierte Parallelogramm transformiert wird*destPoints*. |
| matrix | Matrix | EIN[`Matrix`](../../matrix) die eine geometrische Transformation angibt, die auf den Pfad angewendet werden soll. |
| warpMode | WarpMode | EIN[`WarpMode`](../../warpmode) Enumeration, die angibt, ob dieser Warp-Vorgang den perspektivischen oder den bilinearen Modus verwendet. |

### Siehe auch

* struct [PointF](../../pointf)
* struct [RectangleF](../../rectanglef)
* class [Matrix](../../matrix)
* enum [WarpMode](../../warpmode)
* class [GraphicsPath](../../graphicspath)
* namensraum [Aspose.Imaging](../../graphicspath)
* Montage [Aspose.Imaging](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

Wendet eine durch ein Rechteck und ein Parallelogramm definierte Warp-Transformation darauf an[`GraphicsPath`](../../graphicspath) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destPoints | PointF[] | Eine Reihe von[`PointF`](../../pointf) Strukturen, die ein Parallelogramm definieren, zu dem das Rechteck definiert ist*srcRect* wird transformiert. Das Array kann entweder drei oder vier Elemente enthalten. Wenn das Array drei Elemente enthält, wird die untere rechte Ecke des Parallelogramms durch die ersten drei Punkte impliziert. |
| srcRect | RectangleF | EIN[`RectangleF`](../../rectanglef) das das Rechteck darstellt, das in das durch definierte Parallelogramm transformiert wird*destPoints*. |
| matrix | Matrix | EIN[`Matrix`](../../matrix) die eine geometrische Transformation angibt, die auf den Pfad angewendet werden soll. |
| warpMode | WarpMode | EIN[`WarpMode`](../../warpmode) Enumeration, die angibt, ob dieser Warp-Vorgang den perspektivischen oder den bilinearen Modus verwendet. |
| flatness | Single | Ein Wert zwischen 0 und 1, der angibt, wie flach der resultierende Pfad ist. Weitere Informationen finden Sie unter[`Flatten`](../flatten) Methoden. |

### Siehe auch

* struct [PointF](../../pointf)
* struct [RectangleF](../../rectanglef)
* class [Matrix](../../matrix)
* enum [WarpMode](../../warpmode)
* class [GraphicsPath](../../graphicspath)
* namensraum [Aspose.Imaging](../../graphicspath)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
