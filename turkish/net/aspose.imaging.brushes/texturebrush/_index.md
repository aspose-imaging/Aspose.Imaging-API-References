---
title: TextureBrush
second_title: Aspose.Imaging for .NET API Referansı
description: TextureBrush./texturebrush sınıf birBrush../aspose.imaging/brush bir şeklin içini doldurmak için bir görüntü kullanan nesne. Bu sınıf devralınamaz.
type: docs
weight: 220
url: /tr/net/aspose.imaging.brushes/texturebrush/
---
## TextureBrush class

[`TextureBrush`](../texturebrush) sınıf bir[`Brush`](../../aspose.imaging/brush) bir şeklin içini doldurmak için bir görüntü kullanan nesne. Bu sınıf devralınamaz.

```csharp
public sealed class TextureBrush : TransformBrush
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [TextureBrush](texturebrush#constructor)(Image) | Yeni bir örneğini başlatır[`TextureBrush`](../texturebrush) belirtilen görüntüyü kullanan sınıf. |
| [TextureBrush](texturebrush#constructor_1)(Image, Rectangle) | Yeni bir örneğini başlatır[`TextureBrush`](../texturebrush) belirtilen görüntüyü ve sınırlayıcı dikdörtgeni kullanan sınıf. |
| [TextureBrush](texturebrush#constructor_3)(Image, RectangleF) | Yeni bir örneğini başlatır[`TextureBrush`](../texturebrush) belirtilen görüntüyü ve sınırlayıcı dikdörtgeni kullanan sınıf. |
| [TextureBrush](texturebrush#constructor_5)(Image, WrapMode) | Yeni bir örneğini başlatır[`TextureBrush`](../texturebrush) belirtilen görüntüyü ve sarma modunu kullanan sınıf. |
| [TextureBrush](texturebrush#constructor_2)(Image, Rectangle, ImageAttributes) | Yeni bir örneğini başlatır[`TextureBrush`](../texturebrush) belirtilen görüntüyü, sınırlayıcı dikdörtgeni ve görüntü özniteliklerini kullanan sınıf. |
| [TextureBrush](texturebrush#constructor_4)(Image, RectangleF, ImageAttributes) | Yeni bir örneğini başlatır[`TextureBrush`](../texturebrush) belirtilen görüntüyü, sınırlayıcı dikdörtgeni ve görüntü özniteliklerini kullanan sınıf. |
| [TextureBrush](texturebrush#constructor_6)(Image, WrapMode, Rectangle) | Yeni bir örneğini başlatır[`TextureBrush`](../texturebrush) belirtilen görüntüyü, sarma modunu ve sınırlayıcı dikdörtgeni kullanan sınıf. |
| [TextureBrush](texturebrush#constructor_7)(Image, WrapMode, RectangleF) | Yeni bir örneğini başlatır[`TextureBrush`](../texturebrush) belirtilen görüntüyü, sarma modunu ve sınırlayıcı dikdörtgeni kullanan sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [Image](../../aspose.imaging.brushes/texturebrush/image) { get; } | [`Image`](../../aspose.imaging/image) bununla ilişkili nesne[`TextureBrush`](../texturebrush) nesne. |
| [ImageAttributes](../../aspose.imaging.brushes/texturebrush/imageattributes) { get; } | [`ImageAttributes`](./imageattributes) bununla ilişkili[`TextureBrush`](../texturebrush) . |
| [ImageRectangle](../../aspose.imaging.brushes/texturebrush/imagerectangle) { get; } | [`Rectangle`](../../aspose.imaging/rectangle) bununla ilişkili[`TextureBrush`](../texturebrush) . |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | Dönüşümlerin bir şekilde değiştirilip değiştirilmediğini gösteren bir değer alır. Örneğin, dönüştürme matrisini ayarlamak veya dönüştürme matrisini değiştiren yöntemlerden herhangi birini çağırmak. Özellik, GDI+. ile geriye dönük uyumluluk için sunulmuştur |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | Fırça opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri fırçanın tamamen görünür olduğu, 1 değeri fırçanın tamamen opak olduğu anlamına gelir. |
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

* class [TransformBrush](../transformbrush)
* ad alanı [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
