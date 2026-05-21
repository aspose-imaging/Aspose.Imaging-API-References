---
title: "PathGradientBrushBase"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Temel yol gradyanı işlevselliğine sahip bir fırçayı temsil eder."
type: docs
weight: 15
url: /tr/java/com.aspose.imaging.brushes/pathgradientbrushbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush)
```
public abstract class PathGradientBrushBase extends TransformBrush
```

Temel yol degrade işlevselliğine sahip bir `Brush` nesnesini temsil eder.

`PathGradientBrushBase` sınıfını oluştururken en az 2 nokta ile başlatılması gerektiğini unutmayın. Oluşturulan iç yol her zaman kapalı bir şekil olur, son nokta ilk noktaya bağlanır. Bu şekil bu `PathGradientBrushBase` ile doldurulur. GDI+ uygulaması, boş diziler veya aynı koordinatlara sahip nokta kümesi geçirildiğinde bir `OutOfMemoryError` fırlatır. `PathGradientBrushBase`, nokta dizisi 2'den az nokta içerdiğinde bir istisna fırlatır; kabul edilemez nokta dizisi durumunda `OutOfMemoryError` yerine `ArgumentException` fırlatılır. Merkez nokta, varsayılan olarak verilen noktaların kütle merkezi olarak hesaplanır. Kullanıcı bu noktayı daha sonra değiştirebilir. Odak ölçeği varsayılan olarak boş bir nokta (0.0, 0.0) dir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPathPoints()](#getPathPoints--) | Bu fırçanın üzerine inşa edildiği yol noktalarını alır. |
| [getGraphicsPath()](#getGraphicsPath--) | Bu fırçanın üzerine inşa edildiği grafik yolunu alır. |
| [getCenterPoint()](#getCenterPoint--) | Yol gradyanının merkez noktasını alır veya ayarlar. |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.imaging.PointF-) | Yol gradyanının merkez noktasını alır veya ayarlar. |
| [getFocusScales()](#getFocusScales--) | Gradyan düşüşü için odak noktasını alır. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.imaging.PointF-) | Gradyan düşüşü için odak noktasını alır veya ayarlar. |
### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


Bu fırçanın üzerine inşa edildiği yol noktalarını alır.

**Returns:**
com.aspose.imaging.PointF[] - Yol noktaları.
### getGraphicsPath() {#getGraphicsPath--}
```
public GraphicsPath getGraphicsPath()
```


Bu fırçanın üzerine inşa edildiği grafik yolunu alır.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The graphics path.
### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


Yol gradyanının merkez noktasını alır veya ayarlar.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - A `Aspose.Imaging.PointF` that represents the center point of the path gradient.
### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.imaging.PointF-}
```
public void setCenterPoint(PointF value)
```


Yol gradyanının merkez noktasını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) | Yol gradyanının merkez noktasını temsil eden bir `Aspose.Imaging.PointF`. |

### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


Gradyan düşüşü için odak noktasını alır.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - A `Aspose.Imaging.PointF` that represents the focus point for the gradient falloff.
### setFocusScales(PointF value) {#setFocusScales-com.aspose.imaging.PointF-}
```
public void setFocusScales(PointF value)
```


Gradyan düşüşü için odak noktasını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) | Bir `Aspose.Imaging.PointF` nesnesi, degrade düşüşü için odak noktasını temsil eder. |

