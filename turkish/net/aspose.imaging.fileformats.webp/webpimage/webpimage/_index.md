---
title: WebPImage
second_title: Aspose.Imaging for .NET API Referansı
description: Yeni bir örneğini başlatırWebPImageaspose.imaging.fileformats.webp/webpimage class akışından.
type: docs
weight: 10
url: /tr/net/aspose.imaging.fileformats.webp/webpimage/webpimage/
---
## WebPImage(Stream) {#constructor_4}

Yeni bir örneğini başlatır[`WebPImage`](../../webpimage) class akışından.

```csharp
public WebPImage(Stream stream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Akış WebP görüntüsü. |

### Örnekler

Bu örnek, bir WebP görüntüsünün bir dosya akışından nasıl yükleneceğini ve PNG'ye nasıl kaydedileceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// Bir dosya akışından bir WebP görüntüsü yükleyin.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "test.webp"))
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(stream))
{
    // PNG'ye kaydet
    // PNG çok sayfalı bir format olmadığı için yalnızca etkin çerçevenin PNG'ye kaydedileceğini unutmayın.
    webPImage.Save(dir + "test.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Ayrıca bakınız

* class [WebPImage](../../webpimage)
* ad alanı [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* toplantı [Aspose.Imaging](../../../)

---

## WebPImage(Stream, LoadOptions) {#constructor_5}

Yeni bir örneğini başlatır[`WebPImage`](../../webpimage) stream. sınıfından

```csharp
public WebPImage(Stream stream, LoadOptions loadOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Akış WebP görüntüsü. |
| loadOptions | LoadOptions | Yük seçenekleri. |

### Ayrıca bakınız

* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* ad alanı [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* toplantı [Aspose.Imaging](../../../)

---

## WebPImage(string) {#constructor_6}

Yeni bir örneğini başlatır[`WebPImage`](../../webpimage) dosyadan sınıf.

```csharp
public WebPImage(string path)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| path | String | WebP Görüntüsü dosya yolu |

### Örnekler

Bu örnek, bir dosyadan bir WebP görüntüsünün nasıl yükleneceğini ve PNG'ye nasıl kaydedileceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// Bir dosyadan bir WebP görüntüsü yükleyin.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(dir + "test.webp"))
{
    // PNG'ye kaydet
    // PNG çok sayfalı bir format olmadığı için yalnızca etkin çerçevenin PNG'ye kaydedileceğini unutmayın.
    webPImage.Save(dir + "test.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Ayrıca bakınız

* class [WebPImage](../../webpimage)
* ad alanı [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* toplantı [Aspose.Imaging](../../../)

---

## WebPImage(string, LoadOptions) {#constructor_7}

Yeni bir örneğini başlatır[`WebPImage`](../../webpimage) dosyadan sınıf.

```csharp
public WebPImage(string path, LoadOptions loadOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| path | String | WebP Görüntüsü dosya yolu |
| loadOptions | LoadOptions | Yük seçenekleri. |

### Ayrıca bakınız

* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* ad alanı [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* toplantı [Aspose.Imaging](../../../)

---

## WebPImage(RasterImage) {#constructor}

Yeni bir örneğini başlatır[`WebPImage`](../../webpimage) rasterImage. 'den sınıf

```csharp
public WebPImage(RasterImage rasterImage)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rasterImage | RasterImage | Raster görüntü. |

### Örnekler

Bu örnek, başka bir tarama görüntüsünden bir WebP görüntüsünün nasıl oluşturulacağını gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// 100x100 piksellik bir PNG resmi yükleyin.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Resmin tamamını kırmızı ile doldurun.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // PNG görüntüsünü temel alan bir WebP görüntüsü oluşturun.
    using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(pngImage))
    {
        // Varsayılan seçeneklerle bir WebP dosyasına kaydet
        webPImage.Save(dir + "output.webp", new Aspose.Imaging.ImageOptions.WebPOptions());
    }
}
```

### Ayrıca bakınız

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [WebPImage](../../webpimage)
* ad alanı [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* toplantı [Aspose.Imaging](../../../)

---

## WebPImage(RasterImage, LoadOptions) {#constructor_1}

Yeni bir örneğini başlatır[`WebPImage`](../../webpimage) rasterImage. 'den sınıf

```csharp
public WebPImage(RasterImage rasterImage, LoadOptions loadOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rasterImage | RasterImage | Raster görüntü. |
| loadOptions | LoadOptions | Yük seçenekleri. |

### Ayrıca bakınız

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* ad alanı [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* toplantı [Aspose.Imaging](../../../)

---

## WebPImage(int, int, WebPOptions) {#constructor_2}

Yeni bir örneğini başlatır[`WebPImage`](../../webpimage) boş resimli sınıf.

```csharp
public WebPImage(int width, int height, WebPOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| width | Int32 | görüntü genişliği |
| height | Int32 | Görüntü yüksekliği. |
| options | WebPOptions | Seçenekler. |

### Örnekler

Bu örnek, sıfırdan belirtilen seçeneklerle bir WebP görüntüsünün nasıl oluşturulacağını gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.WebPOptions createOptions = new Aspose.Imaging.ImageOptions.WebPOptions();
createOptions.Lossless = true;
createOptions.Quality = 100f;
//createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "output.webp");

// 100x100 piksellik bir WebP görüntüsü oluşturun.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(webPImage);

    // Resmin tamamını kırmızı ile doldurun.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, webPImage.Bounds);

    // Bir WebP dosyasına kaydet
    webPImage.Save(dir + "output.webp");
}
```

Bu örnek, belirtilen seçeneklerle çok çerçeveli bir animasyonlu WebP görüntüsünün nasıl oluşturulacağını gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.WebPOptions createOptions = new Aspose.Imaging.ImageOptions.WebPOptions();
createOptions.Lossless = true;
createOptions.Quality = 100f;
createOptions.AnimBackgroundColor = (uint)Aspose.Imaging.Color.Gray.ToArgb();

// Varsayılan çerçeve artı 36 + 36 ek çerçeve.
createOptions.AnimLoopCount = 36 + 36 + 1;

// 100x100 piksellik bir WebP görüntüsü oluşturun.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    // İlk daire kırmızı
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // İkinci daire siyah
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // Kırmızı yay şeklinin açısını kademeli olarak artırın.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush1, block.Bounds, 0, angle);

        webPImage.AddBlock(block);
    }

    // Siyah yayın açısını kademeli olarak artırın ve kırmızı yayı silin.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);

        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush2, block.Bounds, 0, angle);
        graphics.FillPie(brush1, block.Bounds, angle, 360 - angle);

        webPImage.AddBlock(block);
    }

    // Bir WebP dosyasına kaydet
    webPImage.Save(dir + "output.webp");
}
```

### Ayrıca bakınız

* class [WebPOptions](../../../aspose.imaging.imageoptions/webpoptions)
* class [WebPImage](../../webpimage)
* ad alanı [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* toplantı [Aspose.Imaging](../../../)

---

## WebPImage(int, int, WebPOptions, LoadOptions) {#constructor_3}

Yeni bir örneğini başlatır[`WebPImage`](../../webpimage) boş resimli sınıf.

```csharp
public WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| width | Int32 | görüntü genişliği |
| height | Int32 | Görüntü yüksekliği. |
| options | WebPOptions | Seçenekler. |
| loadOptions | LoadOptions | Yük seçenekleri. |

### Ayrıca bakınız

* class [WebPOptions](../../../aspose.imaging.imageoptions/webpoptions)
* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* ad alanı [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
