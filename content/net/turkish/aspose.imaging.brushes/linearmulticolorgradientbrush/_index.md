---
title: LinearMulticolorGradientBrush
second_title: Aspose.Imaging for .NET API Referansı
description: BirBrush../aspose.imaging/brush birden çok renk ve uygun konumlarla tanımlanan doğrusal gradyan ile. Bu sınıf devralınamaz.
type: docs
weight: 170
url: /tr/aspose.imaging.brushes/linearmulticolorgradientbrush/
---
## LinearMulticolorGradientBrush class

Bir[`Brush`](../../aspose.imaging/brush) birden çok renk ve uygun konumlarla tanımlanan doğrusal gradyan ile. Bu sınıf devralınamaz.

```csharp
public sealed class LinearMulticolorGradientBrush : LinearGradientBrushBase
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor)() | Yeni bir örneğini başlatır[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush) varsayılan parametrelere sahip sınıf. Başlangıç rengi siyah, bitiş rengi beyaz, açı 45 derece ve dikdörtgen (1,1) boyutunda (0,0) içinde bulunur. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_1)(Point, Point) | Yeni bir örneğini başlatır[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush) belirtilen noktalara sahip sınıf. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_2)(PointF, PointF) | Yeni bir örneğini başlatır[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush) belirtilen noktalara sahip sınıf. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_3)(Rectangle, float) | Yeni bir örneğini başlatır[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush) bir dikdörtgene ve bir oryantasyon açısına dayalı sınıf. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_5)(RectangleF, float) | Yeni bir örneğini başlatır[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush) bir dikdörtgene ve bir oryantasyon açısına dayalı sınıf. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_4)(Rectangle, float, bool) | Yeni bir örneğini başlatır[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush) bir dikdörtgene ve bir oryantasyon açısına dayalı sınıf. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_6)(RectangleF, float, bool) | Yeni bir örneğini başlatır[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush) bir dikdörtgene ve bir oryantasyon açısına dayalı sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Angle](../../aspose.imaging.brushes/lineargradientbrushbase/angle) { get; set; } | Gradyan açısını alır veya ayarlar. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [GammaCorrection](../../aspose.imaging.brushes/lineargradientbrushbase/gammacorrection) { get; set; } | Bunun için gama düzeltmesinin etkinleştirilip etkinleştirilmediğini gösteren bir değer alır veya ayarlar[`LinearGradientBrushBase`](../lineargradientbrushbase) . |
| [InterpolationColors](../../aspose.imaging.brushes/linearmulticolorgradientbrush/interpolationcolors) { get; set; } | Alır veya ayarlar[`ColorBlend`](../../aspose.imaging/colorblend) bu, çok renkli bir doğrusal gradyanı tanımlar. |
| [IsAngleScalable](../../aspose.imaging.brushes/lineargradientbrushbase/isanglescalable) { get; set; } | olup olmadığını gösteren bir değer alır veya ayarlar.[`Angle`](../lineargradientbrushbase/angle) bununla dönüşümler sırasında değiştirilir[`LinearGradientBrushBase`](../lineargradientbrushbase) . |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | Dönüşümlerin bir şekilde değiştirilip değiştirilmediğini gösteren bir değer alır. Örneğin, dönüştürme matrisini ayarlamak veya dönüştürme matrisini değiştiren yöntemlerden herhangi birini çağırmak. Özellik, GDI+. ile geriye dönük uyumluluk için sunulmuştur |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | Fırça opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri fırçanın tamamen görünür olduğu, 1 değeri fırçanın tamamen opak olduğu anlamına gelir. |
| [Rectangle](../../aspose.imaging.brushes/lineargradientbrushbase/rectangle) { get; set; } | Degradenin başlangıç ve bitiş noktalarını tanımlayan dikdörtgen bir bölge alır veya ayarlar. |
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

### Ayrıca bakınız

* class [LinearGradientBrushBase](../lineargradientbrushbase)
* ad alanı [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
