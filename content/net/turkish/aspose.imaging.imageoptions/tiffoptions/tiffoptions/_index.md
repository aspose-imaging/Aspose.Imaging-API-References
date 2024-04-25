---
title: TiffOptions
second_title: Aspose.Imaging for .NET API Referansı
description: Yeni bir örneğini başlatırTiffOptionsaspose.imaging.imageoptions/tiffoptions sınıf.
type: docs
weight: 10
url: /tr/aspose.imaging.imageoptions/tiffoptions/tiffoptions/
---
## TiffOptions(TiffExpectedFormat, TiffByteOrder) {#constructor_1}

Yeni bir örneğini başlatır[`TiffOptions`](../../tiffoptions) sınıf.

```csharp
public TiffOptions(TiffExpectedFormat expectedFormat, TiffByteOrder byteOrder)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| expectedFormat | TiffExpectedFormat | Beklenen tiff dosya biçimi. |
| byteOrder | TiffByteOrder | Kullanılacak tiff dosya biçimi bayt sırası. |

### Ayrıca bakınız

* enum [TiffExpectedFormat](../../../aspose.imaging.fileformats.tiff.enums/tiffexpectedformat)
* enum [TiffByteOrder](../../../aspose.imaging.fileformats.tiff.enums/tiffbyteorder)
* class [TiffOptions](../../tiffoptions)
* ad alanı [Aspose.Imaging.ImageOptions](../../tiffoptions)
* toplantı [Aspose.Imaging](../../../)

---

## TiffOptions(TiffExpectedFormat) {#constructor}

Yeni bir örneğini başlatır[`TiffOptions`](../../tiffoptions)sınıf. Varsayılan olarak küçük endian kuralı kullanılır.

```csharp
public TiffOptions(TiffExpectedFormat expectedFormat)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| expectedFormat | TiffExpectedFormat | Beklenen tiff dosya biçimi. |

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

Bu örnek, çeşitli seçenekler kullanılarak bir tarama görüntüsünün TIFF biçimine nasıl kaydedileceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions saveOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Her renk bileşeni için 8 bit ayarlayın.
saveOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

// Big Endian bayt sırasını ayarla (Motorola)
saveOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// LZW sıkıştırmasını ayarlayın.
saveOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// Sürekli tonlu görüntülerin boyutunu küçültmeye izin verin.
// Şu anda bu alan yalnızca LZW kodlaması ile kullanılmaktadır çünkü LZW muhtemelen tek TIFF kodlama şemasıdır
// bir tahmin adımından önemli ölçüde yararlanan.
saveOptions.Predictor = Imaging.FileFormats.Tiff.Enums.TiffPredictor.Horizontal;

// RGB renk modelini ayarlayın.
saveOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// YCbCr için aşağıdaki seçeneklerden birini kullanabilirsiniz:
// YCbCrSubSampling alanı JPEG örnekleme faktörleri
// -------------------------------------------------
// 1,1 1x1, 1x1, 1x1
// 2,1 2x1, 1x1, 1x1
// 2,2(varsayılan değer) 2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = yeni ushort[] { 2, 2 };

// Tüm renk bileşenleri tek bir düzlemde saklanacaktır.
saveOptions.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// 100x100 piksellik bir TIFF Çerçevesi oluşturun.
using (Aspose.Imaging.Image image = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Resmin tamamını mavi-sarı gradyanla doldurun.
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(image.Width, image.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Yellow);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);
    graphics.FillRectangle(gradientBrush, image.Bounds);

    image.Save(dir + "output.tif", saveOptions);
}
```

### Ayrıca bakınız

* enum [TiffExpectedFormat](../../../aspose.imaging.fileformats.tiff.enums/tiffexpectedformat)
* class [TiffOptions](../../tiffoptions)
* ad alanı [Aspose.Imaging.ImageOptions](../../tiffoptions)
* toplantı [Aspose.Imaging](../../../)

---

## TiffOptions(TiffOptions) {#constructor_3}

Yeni bir örneğini başlatır[`TiffOptions`](../../tiffoptions) sınıf.

```csharp
public TiffOptions(TiffOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| options | TiffOptions | Kopyalama seçenekleri. |

### Ayrıca bakınız

* class [TiffOptions](../../tiffoptions)
* ad alanı [Aspose.Imaging.ImageOptions](../../tiffoptions)
* toplantı [Aspose.Imaging](../../../)

---

## TiffOptions(TiffDataType[]) {#constructor_2}

Yeni bir örneğini başlatır[`TiffOptions`](../../tiffoptions) sınıf.

```csharp
public TiffOptions(TiffDataType[] tags)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| tags | TiffDataType[] | Seçeneklerin başlatılacağı etiketler. |

### Ayrıca bakınız

* class [TiffDataType](../../../aspose.imaging.fileformats.tiff/tiffdatatype)
* class [TiffOptions](../../tiffoptions)
* ad alanı [Aspose.Imaging.ImageOptions](../../tiffoptions)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
