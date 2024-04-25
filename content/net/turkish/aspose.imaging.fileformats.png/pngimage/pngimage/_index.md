---
title: PngImage
second_title: Aspose.Imaging for .NET API Referansı
description: Yeni bir örneğini başlatırPngImageaspose.imaging.fileformats.png/pngimage sınıf.
type: docs
weight: 10
url: /tr/aspose.imaging.fileformats.png/pngimage/pngimage/
---
## PngImage(int, int) {#constructor_3}

Yeni bir örneğini başlatır[`PngImage`](../../pngimage) sınıf.

```csharp
public PngImage(int width, int height)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| width | Int32 | Genişlik. |
| height | Int32 | Yükseklik. |

### Örnekler

Bu örnek, belirtilen boyutta bir PNG görüntüsünün nasıl oluşturulacağını, düz renkle nasıl doldurulacağını ve bir dosyaya nasıl kaydedileceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// 100x100 piksellik bir PNG görüntüsü oluşturun.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    // Biraz görüntü işleme yapın, örneğin tüm görüntüyü kırmızı ile doldurun.
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // Bir dosyaya kaydet.
    pngImage.Save(dir + "output.png");
}
```

### Ayrıca bakınız

* class [PngImage](../../pngimage)
* ad alanı [Aspose.Imaging.FileFormats.Png](../../pngimage)
* toplantı [Aspose.Imaging](../../../)

---

## PngImage(string) {#constructor_6}

Yeni bir örneğini başlatır[`PngImage`](../../pngimage) sınıf.

```csharp
public PngImage(string path)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| path | String | Görüntü yükleme yolu. |

### Örnekler

Bu örnek, bir dosyadan PNG görüntüsünün nasıl yükleneceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// Bir dosyadan bir PNG görüntüsü yükleyin.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(dir + "sample.png"))
{
    // Resmi gri tonlamalı gösterime dönüştürün
    pngImage.Grayscale();

    // Bir dosyaya kaydet.
    pngImage.Save(dir + "sample.grayscale.png");
}
```

### Ayrıca bakınız

* class [PngImage](../../pngimage)
* ad alanı [Aspose.Imaging.FileFormats.Png](../../pngimage)
* toplantı [Aspose.Imaging](../../../)

---

## PngImage(RasterImage) {#constructor_1}

Yeni bir örneğini başlatır[`PngImage`](../../pngimage) sınıf.

```csharp
public PngImage(RasterImage rasterImage)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rasterImage | RasterImage | Raster görüntü. |

### Örnekler

Bu örnek, bir BMP görüntüsünden PNG görüntüsünün nasıl yükleneceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// BMP görüntüsünden TrueColor PNG görüntüsü yükleyin.
// İlk olarak, bir PNG görüntüsü oluşturmak için temel oluşturacak geçici bir BMP görüntüsü oluşturun.
// Ayrıca bir dosyadan BMP görüntüsünü yükleyebilir veya başka herhangi bir raster formatındaki bir görüntüyü kullanabilirsiniz.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // BMP görüntüsünün tamamını kırmızı ile doldurun.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(bmpImage))
    {
        System.Console.WriteLine("The PNG color type: {0}", pngImage.GetOriginalOptions());
        pngImage.Save(dir + "output.png");
    }
}
```

### Ayrıca bakınız

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [PngImage](../../pngimage)
* ad alanı [Aspose.Imaging.FileFormats.Png](../../pngimage)
* toplantı [Aspose.Imaging](../../../)

---

## PngImage(string, PngColorType) {#constructor_7}

Yeni bir örneğini başlatır[`PngImage`](../../pngimage) sınıf.

```csharp
public PngImage(string path, PngColorType colorType)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| path | String | Görüntü yükleme yolu. |
| colorType | PngColorType | Renk türü. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException |  |

### Örnekler

Bu örnek, belirtilen renk türüne sahip bir dosyadan PNG görüntüsünün nasıl yükleneceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// Bir dosyadan bir PNG görüntüsü yükleyin.
// Renkli görüntünün otomatik olarak gri tonlamaya dönüştürüleceğini unutmayın.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(dir + "sample.png", Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
{
    // Bir dosyaya kaydet.
    pngImage.Save(dir + "sample.grayscale.png");
}
```

### Ayrıca bakınız

* enum [PngColorType](../../pngcolortype)
* class [PngImage](../../pngimage)
* ad alanı [Aspose.Imaging.FileFormats.Png](../../pngimage)
* toplantı [Aspose.Imaging](../../../)

---

## PngImage(RasterImage, PngColorType) {#constructor_2}

Yeni bir örneğini başlatır[`PngImage`](../../pngimage) sınıf.

```csharp
public PngImage(RasterImage rasterImage, PngColorType colorType)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rasterImage | RasterImage | Raster görüntü. |
| colorType | PngColorType | Renk türü. |

### Örnekler

Bu örnek, belirtilen renk türüne sahip bir BMP görüntüsünden PNG görüntüsünün nasıl yükleneceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// Renkli bir BMP görüntüsünden gri tonlamalı bir PNG görüntüsü yükleyin.
// İlk olarak, bir PNG görüntüsü oluşturmak için temel oluşturacak geçici bir BMP görüntüsü oluşturun.
// Ayrıca bir dosyadan BMP görüntüsünü yükleyebilir veya başka herhangi bir raster formatındaki bir görüntüyü kullanabilirsiniz.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // BMP görüntüsünün tamamını kırmızı ile doldurun.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // Görüntü piksellerinin renkleri, gri tonlamalı karşılıklarına dönüştürülecektir.
    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(bmpImage, Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
    {
        pngImage.Save(dir + "output.grayscale.png");
    }
}
```

### Ayrıca bakınız

* class [RasterImage](../../../aspose.imaging/rasterimage)
* enum [PngColorType](../../pngcolortype)
* class [PngImage](../../pngimage)
* ad alanı [Aspose.Imaging.FileFormats.Png](../../pngimage)
* toplantı [Aspose.Imaging](../../../)

---

## PngImage(Stream) {#constructor_5}

Yeni bir örneğini başlatır[`PngImage`](../../pngimage) sınıf.

```csharp
public PngImage(Stream stream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Bir görüntü yüklemek için akış. |

### Örnekler

Bu örnek, bir dosyadan veya dosya akışından PNG görüntüsünün nasıl yükleneceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// Bir dosya akışından bir PNG görüntüsü yükleyin.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.png"))
{
    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(stream))
    {
        // Resmi gri tonlamalı gösterime dönüştürün
        pngImage.Grayscale();

        // Bir dosyaya kaydet.
        pngImage.Save(dir + "sample.grayscale.png");
    }
}
```

### Ayrıca bakınız

* class [PngImage](../../pngimage)
* ad alanı [Aspose.Imaging.FileFormats.Png](../../pngimage)
* toplantı [Aspose.Imaging](../../../)

---

## PngImage(int, int, PngColorType) {#constructor_4}

Yeni bir örneğini başlatır[`PngImage`](../../pngimage) sınıf.

```csharp
public PngImage(int width, int height, PngColorType colorType)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| width | Int32 | Genişlik. |
| height | Int32 | Yükseklik. |
| colorType | PngColorType | Renk türü. |

### Örnekler

Bu örnek, belirtilen renk türüyle belirtilen boyutta bir PNG görüntüsünün nasıl oluşturulacağını, düz renkle nasıl doldurulacağını ve bir dosyaya nasıl kaydedileceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// 100x100 piksellik gri tonlamalı bir PNG görüntüsü oluşturun.
// Tüm renkler otomatik olarak gri tonlama formatına dönüştürülecektir.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100, Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
{
    // Biraz görüntü işleme yapın, örneğin tüm görüntüyü kırmızı ile doldurun.
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // Bir dosyaya kaydet.
    pngImage.Save(dir + "output.grayscale.png");
}
```

### Ayrıca bakınız

* enum [PngColorType](../../pngcolortype)
* class [PngImage](../../pngimage)
* ad alanı [Aspose.Imaging.FileFormats.Png](../../pngimage)
* toplantı [Aspose.Imaging](../../../)

---

## PngImage(PngOptions, int, int) {#constructor}

Yeni bir örneğini başlatır[`PngImage`](../../pngimage) sınıf.

```csharp
public PngImage(PngOptions pngOptions, int width, int height)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pngOptions | PngOptions | png seçenekleri. |
| width | Int32 | Genişlik. |
| height | Int32 | Yükseklik. |

### Örnekler

Bu örnek, belirtilen seçeneklerle bir PNG görüntüsünün nasıl oluşturulacağını, doğrusal gradyan renklerle nasıl doldurulacağını ve bir dosyaya nasıl kaydedileceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();

// Renk kanalı başına bit sayısı
createOptions.BitDepth = 8;

// Her piksel bir (kırmızı, yeşil, mavi) üçlüsüdür ve ardından alfa bileşeni gelir.
createOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

// Maksimum sıkıştırma seviyesi.
createOptions.CompressionLevel = 9;

// Filtrelerin kullanımı, sürekli tonlu görüntülerin daha etkin bir şekilde sıkıştırılmasını sağlar.
createOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Sub;

// Aşamalı yüklemeyi kullan
createOptions.Progressive = true;

// Özel parametrelerle bir PNG görüntüsü oluşturun.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(createOptions, 100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Resmi yarı saydam bir gradyanla doldurun.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    // Bir dosyaya kaydet.
    pngImage.Save(dir + "output.explicitoptions.png");
}
```

### Ayrıca bakınız

* class [PngOptions](../../../aspose.imaging.imageoptions/pngoptions)
* class [PngImage](../../pngimage)
* ad alanı [Aspose.Imaging.FileFormats.Png](../../pngimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
