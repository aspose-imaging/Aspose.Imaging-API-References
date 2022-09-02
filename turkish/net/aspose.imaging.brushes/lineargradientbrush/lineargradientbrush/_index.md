---
title: LinearGradientBrush
second_title: Aspose.Imaging for .NET API Referansı
description: Yeni bir örneğini başlatırLinearGradientBrushaspose.imaging.brushes/lineargradientbrush varsayılan parametrelere sahip sınıf. Başlangıç rengi siyah bitiş rengi beyaz açı 45 derece ve dikdörtgen 11 boyutunda 00 içinde bulunur.
type: docs
weight: 10
url: /tr/net/aspose.imaging.brushes/lineargradientbrush/lineargradientbrush/
---
## LinearGradientBrush() {#constructor}

Yeni bir örneğini başlatır[`LinearGradientBrush`](../../lineargradientbrush) varsayılan parametrelere sahip sınıf. Başlangıç rengi siyah, bitiş rengi beyaz, açı 45 derece ve dikdörtgen (1,1) boyutunda (0,0) içinde bulunur.

```csharp
public LinearGradientBrush()
```

### Ayrıca bakınız

* class [LinearGradientBrush](../../lineargradientbrush)
* ad alanı [Aspose.Imaging.Brushes](../../lineargradientbrush)
* toplantı [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Point, Point, Color, Color) {#constructor_1}

Yeni bir örneğini başlatır[`LinearGradientBrush`](../../lineargradientbrush) belirtilen noktalara ve renklere sahip sınıf.

```csharp
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| point1 | Point | A[`Point`](../../../aspose.imaging/point) doğrusal gradyanın başlangıç noktasını temsil eden yapı. |
| point2 | Point | A[`Point`](../../../aspose.imaging/point) doğrusal gradyanın bitiş noktasını temsil eden yapı. |
| color1 | Color | A[`Color`](../../../aspose.imaging/color) doğrusal gradyanın başlangıç rengini temsil eden yapı. |
| color2 | Color | A[`Color`](../../../aspose.imaging/color) doğrusal degradenin bitiş rengini temsil eden yapı. |

### Örnekler

Aşağıdaki örnek, var olan bir çerçevenin gri tonlamalı bir kopyasının nasıl oluşturulacağını ve bunun bir TIFF görüntüsüne nasıl ekleneceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Geçici değil, kalıcı bir dosya kaynağı oluşturun.
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // Resmin sol üst köşesinden sağ alt köşesine doğru doğrusal gradyan.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(tiffImage.Width, tiffImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Aktif çerçeveyi doğrusal bir degrade fırçasıyla doldurun.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(tiffImage.ActiveFrame);
    gr.FillRectangle(brush, tiffImage.Bounds);

    // Gri tonlama seçenekleri
    Aspose.Imaging.ImageOptions.TiffOptions createTiffFrameOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());
    createTiffFrameOptions.Photometric = Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;
    createTiffFrameOptions.BitsPerSample = new ushort[] { 8 };

    // Etkin çerçevenin gri tonlamalı bir kopyasını oluşturun.
    // Piksel verileri korunur ancak istenen formata dönüştürülür.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame grayscaleFrame = Aspose.Imaging.FileFormats.Tiff.TiffFrame.CreateFrameFrom(tiffImage.ActiveFrame, createTiffFrameOptions);

    // Yeni oluşturulan çerçeveyi TIFF görüntüsüne ekleyin.
    tiffImage.AddFrame(grayscaleFrame);

    tiffImage.Save();
}
```

### Ayrıca bakınız

* struct [Point](../../../aspose.imaging/point)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* ad alanı [Aspose.Imaging.Brushes](../../lineargradientbrush)
* toplantı [Aspose.Imaging](../../../)

---

## LinearGradientBrush(PointF, PointF, Color, Color) {#constructor_2}

Yeni bir örneğini başlatır[`LinearGradientBrush`](../../lineargradientbrush) belirtilen noktalara ve renklere sahip sınıf.

```csharp
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| point1 | PointF | A[`PointF`](../../../aspose.imaging/pointf) doğrusal gradyanın başlangıç noktasını temsil eden yapı. |
| point2 | PointF | A[`PointF`](../../../aspose.imaging/pointf) doğrusal gradyanın bitiş noktasını temsil eden yapı. |
| color1 | Color | A[`Color`](../../../aspose.imaging/color) doğrusal gradyanın başlangıç rengini temsil eden yapı. |
| color2 | Color | A[`Color`](../../../aspose.imaging/color) doğrusal degradenin bitiş rengini temsil eden yapı. |

### Ayrıca bakınız

* struct [PointF](../../../aspose.imaging/pointf)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* ad alanı [Aspose.Imaging.Brushes](../../lineargradientbrush)
* toplantı [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Rectangle, Color, Color, float) {#constructor_3}

Yeni bir örneğini başlatır[`LinearGradientBrush`](../../lineargradientbrush) bir dikdörtgene, başlangıç ve bitiş renklerine ve oryantasyon açısına dayalı sınıf.

```csharp
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rect | Rectangle | A[`RectangleF`](../../../aspose.imaging/rectanglef) doğrusal gradyanın sınırlarını belirten yapı. |
| color1 | Color | A[`Color`](../../../aspose.imaging/color) degrade için başlangıç rengini temsil eden yapı. |
| color2 | Color | A[`Color`](../../../aspose.imaging/color) degradenin bitiş rengini temsil eden yapı. |
| angle | Single | Gradyanın oryantasyon çizgisinin x ekseninden saat yönünde derece cinsinden ölçülen açısı. |

### Ayrıca bakınız

* struct [Rectangle](../../../aspose.imaging/rectangle)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* ad alanı [Aspose.Imaging.Brushes](../../lineargradientbrush)
* toplantı [Aspose.Imaging](../../../)

---

## LinearGradientBrush(RectangleF, Color, Color, float) {#constructor_5}

Yeni bir örneğini başlatır[`LinearGradientBrush`](../../lineargradientbrush) bir dikdörtgene, başlangıç ve bitiş renklerine ve oryantasyon açısına dayalı sınıf.

```csharp
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rect | RectangleF | A[`RectangleF`](../../../aspose.imaging/rectanglef) doğrusal gradyanın sınırlarını belirten yapı. |
| color1 | Color | A[`Color`](../../../aspose.imaging/color) degrade için başlangıç rengini temsil eden yapı. |
| color2 | Color | A[`Color`](../../../aspose.imaging/color) degradenin bitiş rengini temsil eden yapı. |
| angle | Single | Gradyanın oryantasyon çizgisinin x ekseninden saat yönünde derece cinsinden ölçülen açısı. |

### Ayrıca bakınız

* struct [RectangleF](../../../aspose.imaging/rectanglef)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* ad alanı [Aspose.Imaging.Brushes](../../lineargradientbrush)
* toplantı [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Rectangle, Color, Color, float, bool) {#constructor_4}

Yeni bir örneğini başlatır[`LinearGradientBrush`](../../lineargradientbrush) bir dikdörtgene, başlangıç ve bitiş renklerine ve oryantasyon açısına dayalı sınıf.

```csharp
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, 
    bool isAngleScalable)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rect | Rectangle | A[`RectangleF`](../../../aspose.imaging/rectanglef) doğrusal gradyanın sınırlarını belirten yapı. |
| color1 | Color | A[`Color`](../../../aspose.imaging/color) degrade için başlangıç rengini temsil eden yapı. |
| color2 | Color | A[`Color`](../../../aspose.imaging/color) degradenin bitiş rengini temsil eden yapı. |
| angle | Single | Gradyanın oryantasyon çizgisinin x ekseninden saat yönünde derece cinsinden ölçülen açısı. |
| isAngleScalable | Boolean | ayarlanırsa`doğru` bununla dönüşümler sırasında açı değiştirilir[`LinearGradientBrush`](../../lineargradientbrush). |

### Ayrıca bakınız

* struct [Rectangle](../../../aspose.imaging/rectangle)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* ad alanı [Aspose.Imaging.Brushes](../../lineargradientbrush)
* toplantı [Aspose.Imaging](../../../)

---

## LinearGradientBrush(RectangleF, Color, Color, float, bool) {#constructor_6}

Yeni bir örneğini başlatır[`LinearGradientBrush`](../../lineargradientbrush) bir dikdörtgene, başlangıç ve bitiş renklerine ve oryantasyon açısına dayalı sınıf.

```csharp
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, 
    bool isAngleScalable)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rect | RectangleF | A[`RectangleF`](../../../aspose.imaging/rectanglef) doğrusal gradyanın sınırlarını belirten yapı. |
| color1 | Color | A[`Color`](../../../aspose.imaging/color) degrade için başlangıç rengini temsil eden yapı. |
| color2 | Color | A[`Color`](../../../aspose.imaging/color) degradenin bitiş rengini temsil eden yapı. |
| angle | Single | Gradyanın oryantasyon çizgisinin x ekseninden saat yönünde derece cinsinden ölçülen açısı. |
| isAngleScalable | Boolean | ayarlanırsa`doğru` bununla dönüşümler sırasında açı değiştirilir[`LinearGradientBrush`](../../lineargradientbrush). |

### Ayrıca bakınız

* struct [RectangleF](../../../aspose.imaging/rectanglef)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* ad alanı [Aspose.Imaging.Brushes](../../lineargradientbrush)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
