---
title: Photometric
second_title: Aspose.Imaging for .NET API Referansı
description: Fotometriyi alır veya ayarlar.
type: docs
weight: 340
url: /tr/net/aspose.imaging.imageoptions/tiffoptions/photometric/
---
## TiffOptions.Photometric property

Fotometriyi alır veya ayarlar.

```csharp
public TiffPhotometrics Photometric { get; set; }
```

### Mülk değeri

Fotometrik.

### Örnekler

Bu örnek, sıfırdan bir TIFF görüntüsünün nasıl oluşturulacağını ve bir dosyaya nasıl kaydedileceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    
// Her renk bileşeni için 8 bit ayarlayın.
createOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

// Big Endian bayt sırasını ayarla (Motorola)
createOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// LZW sıkıştırmasını ayarlayın.
createOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// RGB renk modelini ayarlayın.
createOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// Tüm renk bileşenleri tek bir düzlemde saklanacaktır.
createOptions.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// 100x100 piksellik bir TIFF Çerçevesi oluşturun.
// TiffImage'a dahil edilmişse, bir çerçeveyi açıkça elden çıkarmanız gerekmediğine dikkat edin.
// Konteyner atıldığında tüm çerçeveler otomatik olarak atılacaktır.
Aspose.Imaging.FileFormats.Tiff.TiffFrame firstFrame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions, 100, 100);
    
// Tüm çerçeveyi mavi-sarı gradyanla doldurun.
Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(firstFrame.Width, firstFrame.Height),
        Aspose.Imaging.Color.Blue,
        Aspose.Imaging.Color.Yellow);

Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(firstFrame);
graphics.FillRectangle(gradientBrush, firstFrame.Bounds);

// Bir TIFF görüntüsü oluşturun.
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(firstFrame))
{
    tiffImage.Save(dir + "output.tif");
}
```

Aşağıdaki örnek, tek tek tarama görüntülerinden çok sayfalı bir TIFF'nin nasıl oluşturulacağını gösterir.

```csharp
[C#]

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource("c:\\temp\\multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // Bu, tek tek çerçevelere metin çizmek için Yazı Tipi ve Fırça'dır.
    Aspose.Imaging.Font font = new Aspose.Imaging.Font("Arial", 64);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.White);

    // 5 kare oluştur
    for (int i = 1; i <= 5; i++)
    {
        Aspose.Imaging.ImageOptions.PngOptions createPngOptions = new Aspose.Imaging.ImageOptions.PngOptions();
        createPngOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

        // Bir PNG resmi oluşturun ve üzerine sayfa numarasını çizin.
        Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)Image.Create(createPngOptions, 100, 100);
        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(pngImage);
        gr.DrawString(i.ToString(), font, brush, 10, 10);

        // PNG görüntüsünü temel alan bir çerçeve oluşturun.
        Aspose.Imaging.FileFormats.Tiff.TiffFrame frame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(pngImage);

        // Çerçeveyi TIFF görüntüsüne ekleyin.
        tiffImage.AddFrame(frame);
    }

    // Görüntü, tek bir varsayılan çerçeve ile oluşturuldu. Kaldıralım.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame activeFrame = tiffImage.ActiveFrame;
    tiffImage.ActiveFrame = tiffImage.Frames[1];
    tiffImage.RemoveFrame(0);

    // Başka bir TiffImage'a eklemeyecekseniz çerçeveyi elden çıkarmayı unutmayın
    activeFrame.Dispose();

    tiffImage.Save();
}
```

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

Bu örnek, 2 çerçeveli bir TIFF görüntüsünün nasıl oluşturulacağını ve bir dosyaya nasıl kaydedileceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// İlk kare için seçenekler
Aspose.Imaging.ImageOptions.TiffOptions createOptions1 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Her renk bileşeni için 8 bit ayarlayın.
createOptions1.BitsPerSample = new ushort[] { 8, 8, 8 };

// Big Endian bayt sırasını ayarla (Motorola)
createOptions1.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// LZW sıkıştırmasını ayarlayın.
createOptions1.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// RGB renk modelini ayarlayın.
createOptions1.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// Tüm renk bileşenleri tek bir düzlemde saklanacaktır.
createOptions1.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// 100x100 piksellik ilk TIFF çerçevesini oluşturun.
// TiffImage'a dahil edilmişlerse çerçeveleri açıkça elden çıkarmanız gerekmediğine dikkat edin.
// Konteyner atıldığında tüm çerçeveler otomatik olarak atılacaktır.
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame1 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions1, 100, 100);

// İlk kareyi mavi-sarı gradyanla doldurun.
Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(frame1.Width, frame1.Height),
        Aspose.Imaging.Color.Blue,
        Aspose.Imaging.Color.Yellow);

Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(frame1);
graphics.FillRectangle(gradientBrush, frame1.Bounds);

// İlk kare için seçenekler
Aspose.Imaging.ImageOptions.TiffOptions createOptions2 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// S/B görüntü için piksel başına 1 bit ayarlayın.
createOptions2.BitsPerSample = new ushort[] { 1 };

// Little Endian bayt sırasını ayarla (Intel)
createOptions2.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.LittleEndian;

// CCITT Group 3 Faks sıkıştırmasını ayarlayın.
createOptions2.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.CcittFax3;

// S/B renk modelini 0 siyah, 1 beyaz olacak şekilde ayarlayın.
createOptions2.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;

// 200x200 piksellik ikinci TIFF çerçevesini oluşturun.
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame2 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions2, 200, 200);

// İkinci kareyi mavi-sarı gradyanla doldurun.
// Çerçevenin ilgili ayarları nedeniyle otomatik olarak S/B formatına dönüştürülecektir.
Aspose.Imaging.Graphics graphics2 = new Aspose.Imaging.Graphics(frame2);
graphics2.FillRectangle(gradientBrush, frame2.Bounds);

// Bir TIFF görüntüsü oluşturun.
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(
    new Aspose.Imaging.FileFormats.Tiff.TiffFrame[] { frame1, frame2 }))
{
    tiffImage.Save(dir + "output.mutliframe.tif");
}
```

### Ayrıca bakınız

* enum [TiffPhotometrics](../../../aspose.imaging.fileformats.tiff.enums/tiffphotometrics)
* class [TiffOptions](../../tiffoptions)
* ad alanı [Aspose.Imaging.ImageOptions](../../tiffoptions)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
