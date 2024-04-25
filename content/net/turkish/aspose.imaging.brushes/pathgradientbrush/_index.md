---
title: PathGradientBrush
second_title: Aspose.Imaging for .NET API Referansı
description: BirBrush../aspose.imaging/brush gradyanlı nesne. Bu sınıf devralınamaz.
type: docs
weight: 180
url: /tr/aspose.imaging.brushes/pathgradientbrush/
---
## PathGradientBrush class

Bir[`Brush`](../../aspose.imaging/brush) gradyanlı nesne. Bu sınıf devralınamaz.

```csharp
public sealed class PathGradientBrush : PathGradientBrushBase
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PathGradientBrush](pathgradientbrush#constructor)(GraphicsPath) | Yeni bir örneğini başlatır[`PathGradientBrush`](../pathgradientbrush) belirtilen yola sahip sınıf. |
| [PathGradientBrush](pathgradientbrush#constructor_1)(PointF[]) | Yeni bir örneğini başlatır[`PathGradientBrush`](../pathgradientbrush) belirtilen noktalara sahip sınıf. |
| [PathGradientBrush](pathgradientbrush#constructor_3)(Point[]) | Yeni bir örneğini başlatır[`PathGradientBrush`](../pathgradientbrush) belirtilen noktalara sahip sınıf. |
| [PathGradientBrush](pathgradientbrush#constructor_2)(PointF[], WrapMode) | Yeni bir örneğini başlatır[`PathGradientBrush`](../pathgradientbrush) belirtilen noktalara ve kaydırma moduna sahip sınıf. |
| [PathGradientBrush](pathgradientbrush#constructor_4)(Point[], WrapMode) | Yeni bir örneğini başlatır[`PathGradientBrush`](../pathgradientbrush) belirtilen noktalara ve kaydırma moduna sahip sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Blend](../../aspose.imaging.brushes/pathgradientbrush/blend) { get; set; } | Alır veya ayarlar[`Blend`](../../aspose.imaging/blend) degrade için özel bir düşüşü tanımlayan konumları ve faktörleri belirtir. |
| [CenterColor](../../aspose.imaging.brushes/pathgradientbrush/centercolor) { get; set; } | Yolun gradyanının merkezindeki rengi alır veya ayarlar. |
| [CenterPoint](../../aspose.imaging.brushes/pathgradientbrushbase/centerpoint) { get; set; } | Yol gradyanının merkez noktasını alır veya ayarlar. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [FocusScales](../../aspose.imaging.brushes/pathgradientbrushbase/focusscales) { get; set; } | Degrade düşüşü için odak noktasını alır veya ayarlar. |
| [GraphicsPath](../../aspose.imaging.brushes/pathgradientbrushbase/graphicspath) { get; } | Bu fırçanın üzerine inşa edildiği grafik yolunu alır. |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | Dönüşümlerin bir şekilde değiştirilip değiştirilmediğini gösteren bir değer alır. Örneğin, dönüştürme matrisini ayarlamak veya dönüştürme matrisini değiştiren yöntemlerden herhangi birini çağırmak. Özellik, GDI+. ile geriye dönük uyumluluk için sunulmuştur |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | Fırça opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri fırçanın tamamen görünür olduğu, 1 değeri fırçanın tamamen opak olduğu anlamına gelir. |
| [PathPoints](../../aspose.imaging.brushes/pathgradientbrushbase/pathpoints) { get; } | Bu fırçanın üzerine inşa edildiği yol noktalarını alır. |
| [SurroundColors](../../aspose.imaging.brushes/pathgradientbrush/surroundcolors) { get; set; } | Bu yoldaki noktalara karşılık gelen bir renk dizisini alır veya ayarlar.[`PathGradientBrush`](../pathgradientbrush) doldurur. |
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
| [SetBlendTriangularShape](../../aspose.imaging.brushes/pathgradientbrush/setblendtriangularshape#setblendtriangularshape)(float) | Merkez rengi olan bir degrade ve çevreleyen bir renge doğrusal bir düşüş oluşturur. |
| [SetBlendTriangularShape](../../aspose.imaging.brushes/pathgradientbrush/setblendtriangularshape#setblendtriangularshape_1)(float, float) | Merkez rengi ve çevreleyen her renge doğrusal bir düşüşle bir degrade oluşturur. |
| [SetSigmaBellShape](../../aspose.imaging.brushes/pathgradientbrush/setsigmabellshape#setsigmabellshape)(float) | Yolun ortasından başlayarak yolun sınırına doğru rengi değiştiren bir degrade fırçası oluşturur. Bir renkten diğerine geçiş, çan şeklindeki bir eğriye dayanır. |
| [SetSigmaBellShape](../../aspose.imaging.brushes/pathgradientbrush/setsigmabellshape#setsigmabellshape_1)(float, float) | Yolun ortasından başlayarak yolun sınırına doğru rengi değiştiren bir degrade fırçası oluşturur. Bir renkten diğerine geçiş, çan şeklindeki bir eğriye dayanır. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float) | Belirtilen boyutlara göre yerel geometrik dönüşümü öteler. Bu yöntem, dönüşümün başına çeviriyi ekler. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | Yerel geometrik dönüşümü belirtilen sırada belirtilen boyutlara göre çevirir. |

### Notlar

Merkez rengi varsayılan olarak beyazdır. Kullanıcı bu değeri daha sonra istediği zaman değiştirebilir.

Surround renkler dizisi, varsayılan olarak beyaz renk içeren tek bir öğe tarafından başlatılır. Çevre renkleri daha sonra değiştirilebilir, ancak çevre renklerini ayarlarken en azından tek bir eleman gereklidir.

Bkz.[`Blend`](./blend) başlatma hakkında daha fazla ayrıntı için.

### Ayrıca bakınız

* class [PathGradientBrushBase](../pathgradientbrushbase)
* ad alanı [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
