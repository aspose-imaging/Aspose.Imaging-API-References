---
title: Jpeg2000Image
second_title: Aspose.Imaging for .NET API Referansı
description: Yeni bir örneğini başlatırJpeg2000Imageaspose.imaging.fileformats.jpeg2000/jpeg2000image sınıf.
type: docs
weight: 10
url: /tr/net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/jpeg2000image/
---
## Jpeg2000Image(string) {#constructor_7}

Yeni bir örneğini başlatır[`Jpeg2000Image`](../../jpeg2000image) sınıf.

```csharp
public Jpeg2000Image(string path)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| path | String | Görüntüyü yükleme ve piksel ve palet verilerini başlatma yolu. |

### Örnekler

Bu örnek, bir dosyadan bir JPEG2000 görüntüsünün nasıl yükleneceğini ve PNG'ye nasıl kaydedileceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// Bir JPEG2000 görüntüsü yükleyin.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(dir + "sample.jp2"))
{
    // PNG'ye kaydet
    jpeg2000Image.Save(dir + "sample.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Ayrıca bakınız

* class [Jpeg2000Image](../../jpeg2000image)
* ad alanı [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* toplantı [Aspose.Imaging](../../../)

---

## Jpeg2000Image(string, int) {#constructor_8}

Yeni bir örneğini başlatır[`Jpeg2000Image`](../../jpeg2000image) sınıf.

```csharp
public Jpeg2000Image(string path, int bitsPerPixel)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| path | String | Görüntüyü yükleme ve piksel ve palet verilerini başlatma yolu |
| bitsPerPixel | Int32 | Piksel başına bit. |

### Ayrıca bakınız

* class [Jpeg2000Image](../../jpeg2000image)
* ad alanı [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* toplantı [Aspose.Imaging](../../../)

---

## Jpeg2000Image(Stream) {#constructor_5}

Yeni bir örneğini başlatır[`Jpeg2000Image`](../../jpeg2000image) sınıf.

```csharp
public Jpeg2000Image(Stream stream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Görüntüyü yüklemek ve piksel ve palet verilerini başlatmak için akış. |

### Örnekler

Bu örnek, bir dosya akışından bir JPEG2000 görüntüsünün nasıl yükleneceğini ve PNG'ye nasıl kaydedileceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// Akıştan bir JPEG2000 görüntüsü yükleyin.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.jp2"))
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(stream))
{
    // PNG'ye kaydet
    jpeg2000Image.Save(dir + "sample.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Ayrıca bakınız

* class [Jpeg2000Image](../../jpeg2000image)
* ad alanı [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* toplantı [Aspose.Imaging](../../../)

---

## Jpeg2000Image(Stream, int) {#constructor_6}

Yeni bir örneğini başlatır[`Jpeg2000Image`](../../jpeg2000image) sınıf.

```csharp
public Jpeg2000Image(Stream stream, int bitsPerPixel)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Görüntüyü yüklemek ve piksel ve palet verilerini başlatmak için akış. |
| bitsPerPixel | Int32 | Piksel başına bit. |

### Ayrıca bakınız

* class [Jpeg2000Image](../../jpeg2000image)
* ad alanı [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* toplantı [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int) {#constructor_2}

Yeni bir örneğini başlatır[`Jpeg2000Image`](../../jpeg2000image) sınıf.

```csharp
public Jpeg2000Image(int width, int height)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| width | Int32 | görüntü genişliği |
| height | Int32 | görüntü yüksekliği |

### Örnekler

Bu örnek, bir JPEG2000 görüntüsünün nasıl oluşturulacağını ve bir dosyaya nasıl kaydedileceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// 100x100 piksellik bir JPEG2000 görüntüsü oluşturun.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpeg2000Image);

    // Resmin tamamını kırmızı ile doldurun.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, jpeg2000Image.Bounds);

    // Bir dosyaya kaydet
    jpeg2000Image.Save(dir + "sample.output.jp2", new Aspose.Imaging.ImageOptions.Jpeg2000Options());
}
```

### Ayrıca bakınız

* class [Jpeg2000Image](../../jpeg2000image)
* ad alanı [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* toplantı [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int, Jpeg2000Options) {#constructor_3}

Yeni bir örneğini başlatır[`Jpeg2000Image`](../../jpeg2000image) sınıf.

```csharp
public Jpeg2000Image(int width, int height, Jpeg2000Options options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| width | Int32 | görüntü genişliği |
| height | Int32 | görüntü yüksekliği |
| options | Jpeg2000Options | Seçenekler. |

### Örnekler

Bu örnek, bir PNG görüntüsünün nasıl oluşturulacağını ve istenen seçeneklerle JPEG2000'e nasıl kaydedileceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// 100x100 piksellik bir PNG görüntüsü oluşturun.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Resmin tamamını kırmızı ile doldurun.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    Aspose.Imaging.ImageOptions.Jpeg2000Options saveOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

    // Tersine çevrilemez Ayrık Dalgacık Dönüşümü 9-7 kullanın
    saveOptions.Irreversible = true;

    // JP2, JPEG 2000 kod akışları için "kapsayıcı" biçimidir.
    // J2K, sarıcı olmayan ham sıkıştırılmış veridir.
    saveOptions.Codec = Imaging.FileFormats.Jpeg2000.Jpeg2000Codec.J2K;

    // Bir dosyaya kaydet
    pngImage.Save(dir + "output.j2k", saveOptions);
}
```

Bu örnek, istenen seçeneklerle bir JPEG2000 görüntüsünün nasıl oluşturulacağını ve bir dosyaya nasıl kaydedileceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.Jpeg2000Options createOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

// Tersine çevrilemez Ayrık Dalgacık Dönüşümü 9-7 kullanın
createOptions.Irreversible = true;

// JP2, JPEG 2000 kod akışları için "kapsayıcı" biçimidir.
// J2K, sarıcı olmayan ham sıkıştırılmış veridir.
createOptions.Codec = Imaging.FileFormats.Jpeg2000.Jpeg2000Codec.J2K;

// 100x100 piksellik bir JPEG2000 görüntüsü oluşturun.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(100, 100, createOptions))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpeg2000Image);

    // Resmin tamamını kırmızı ile doldurun.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, jpeg2000Image.Bounds);

    // Bir dosyaya kaydet
    jpeg2000Image.Save(dir + "sample.output.j2k");
}
```

### Ayrıca bakınız

* class [Jpeg2000Options](../../../aspose.imaging.imageoptions/jpeg2000options)
* class [Jpeg2000Image](../../jpeg2000image)
* ad alanı [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* toplantı [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int, int) {#constructor_4}

Yeni bir örneğini başlatır[`Jpeg2000Image`](../../jpeg2000image) sınıf.

```csharp
public Jpeg2000Image(int width, int height, int bitsCount)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| width | Int32 | görüntü genişliği |
| height | Int32 | görüntü yüksekliği |
| bitsCount | Int32 | Bitler sayılır. |

### Ayrıca bakınız

* class [Jpeg2000Image](../../jpeg2000image)
* ad alanı [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* toplantı [Aspose.Imaging](../../../)

---

## Jpeg2000Image(RasterImage) {#constructor}

Yeni bir örneğini başlatır[`Jpeg2000Image`](../../jpeg2000image) sınıf.

```csharp
public Jpeg2000Image(RasterImage image)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| image | RasterImage | Görüntü. |

### Örnekler

Bu örnek, başka bir tarama görüntüsünden bir JPEG2000 görüntüsünün nasıl oluşturulacağını gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// 100x100 piksellik bir PNG görüntüsü oluşturun.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Resmin tamamını kırmızı ile doldurun.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // PNG görüntüsünü temel alan bir JPEG2000 görüntüsü oluşturun.
    using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(pngImage))
    {
        // Bir dosyaya kaydet
        jpeg2000Image.Save(dir + "output.jp2", new Aspose.Imaging.ImageOptions.Jpeg2000Options());
    }
}
```

### Ayrıca bakınız

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [Jpeg2000Image](../../jpeg2000image)
* ad alanı [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* toplantı [Aspose.Imaging](../../../)

---

## Jpeg2000Image(RasterImage, int) {#constructor_1}

Yeni bir örneğini başlatır[`Jpeg2000Image`](../../jpeg2000image) sınıf.

```csharp
public Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rasterImage | RasterImage | Piksel ve palet verilerinin başlatılacağı görüntü. |
| bitsPerPixel | Int32 | Piksel başına bit. |

### Ayrıca bakınız

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [Jpeg2000Image](../../jpeg2000image)
* ad alanı [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
