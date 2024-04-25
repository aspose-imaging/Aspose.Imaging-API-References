---
title: PathGradientBrushBase
second_title: Aspose.Imaging for .NET API Referansı
description: BirBrush../aspose.imaging/brush temel yol gradyan işlevselliği ile.
type: docs
weight: 190
url: /tr/aspose.imaging.brushes/pathgradientbrushbase/
---
## PathGradientBrushBase class

Bir[`Brush`](../../aspose.imaging/brush) temel yol gradyan işlevselliği ile.

```csharp
public abstract class PathGradientBrushBase : TransformBrush
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [CenterPoint](../../aspose.imaging.brushes/pathgradientbrushbase/centerpoint) { get; set; } | Yol gradyanının merkez noktasını alır veya ayarlar. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [FocusScales](../../aspose.imaging.brushes/pathgradientbrushbase/focusscales) { get; set; } | Degrade düşüşü için odak noktasını alır veya ayarlar. |
| [GraphicsPath](../../aspose.imaging.brushes/pathgradientbrushbase/graphicspath) { get; } | Bu fırçanın üzerine inşa edildiği grafik yolunu alır. |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | Dönüşümlerin bir şekilde değiştirilip değiştirilmediğini gösteren bir değer alır. Örneğin, dönüştürme matrisini ayarlamak veya dönüştürme matrisini değiştiren yöntemlerden herhangi birini çağırmak. Özellik, GDI+. ile geriye dönük uyumluluk için sunulmuştur |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | Fırça opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri fırçanın tamamen görünür olduğu, 1 değeri fırçanın tamamen opak olduğu anlamına gelir. |
| [PathPoints](../../aspose.imaging.brushes/pathgradientbrushbase/pathpoints) { get; } | Bu fırçanın üzerine inşa edildiği yol noktalarını alır. |
| [Transform](../../aspose.imaging.brushes/transformbrush/transform) { get; set; } | Bir kopya alır veya ayarlar[`Matrix`](../../aspose.imaging/matrix) bunun için yerel bir geometrik dönüşüm tanımlayan[`TransformBrush`](../transformbrush) . |
| [WrapMode](../../aspose.imaging.brushes/transformbrush/wrapmode) { get; set; } | Alır veya ayarlar[`WrapMode`](../../aspose.imaging/wrapmode) bunun için sarma modunu gösteren numaralandırma[`TransformBrush`](../transformbrush) . |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [DeepClone](../../aspose.imaging/brush/deepclone)() | Geçerli olanın yeni bir derin klonunu oluşturur[`Brush`](../../aspose.imaging/brush) . |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Geçerli örneği atar. |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform)(Matrix) | [`Matrix`](../../aspose.imaging/matrix) bunun yerel geometrik dönüşümünü temsil eden[`LinearGradientBrush`](../lineargradientbrush) belirtilen tarafından[`Matrix`](../../aspose.imaging/matrix) belirtilenleri başa ekleyerek[`Matrix`](../../aspose.imaging/matrix) . |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform)(Matrix, MatrixOrder) | [`Matrix`](../../aspose.imaging/matrix) bunun yerel geometrik dönüşümünü temsil eden[`LinearGradientBrush`](../lineargradientbrush) belirtilen tarafından[`Matrix`](../../aspose.imaging/matrix) belirtilen sırada. |
| [ResetTransform](../../aspose.imaging.brushes/transformbrush/resettransform)() | [`Transform`](../transformbrush/transform) kimlik özelliği. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform)(float) | Yerel geometrik dönüşümü belirtilen miktarda döndürür. Bu yöntem, dönüşümü dönüşüme hazırlar. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform)(float, MatrixOrder) | Yerel geometrik dönüşümü belirtilen sırada belirtilen miktarda döndürür. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform)(float, float) | Yerel geometrik dönüşümü belirtilen miktarlara göre ölçekler. Bu yöntem, ölçeklendirme matrisini dönüşümün başına ekler. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform)(float, float, MatrixOrder) | Yerel geometrik dönüşümü belirtilen sırada belirtilen miktarlara göre ölçeklendirir. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float) | Belirtilen boyutlara göre yerel geometrik dönüşümü öteler. Bu yöntem, dönüşümün başına çeviriyi ekler. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | Yerel geometrik dönüşümü belirtilen sırada belirtilen boyutlara göre çevirir. |

### Notlar

[`PathGradientBrushBase`](../pathgradientbrushbase) sınıfı en az 2 puan ile başlatılmalıdır. Created dahili yolu her zaman kapalı bir şekil olacaktır, son nokta ilk noktayı birbirine bağlar. Bu şekil bununla dolu[`PathGradientBrushBase`](../pathgradientbrushbase) . GDI+ uygulaması birOutOfMemoryException aynı koordinatlara sahip boş diziler veya noktalar kümesinden geçerken. [`PathGradientBrushBase`](../pathgradientbrushbase) puan dizisi 2'den az nokta içerdiğinde bir istisna atar,ArgumentException yerine atılan is OutOfMemoryExceptionnoktalar dizisi kabul edilemez olduğunda. Merkez noktası, varsayılan olarak geçirilen noktalar için bir kütle merkezi olarak hesaplanır. Kullanıcı bu noktayı daha sonra değiştirebilir. Odak ölçekleri varsayılan olarak boş bir noktadır (0.0, 0.0).

### Ayrıca bakınız

* class [TransformBrush](../transformbrush)
* ad alanı [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
