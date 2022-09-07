---
title: JpegImage
second_title: Aspose.Imaging for .NET API Referansı
description: Yeni bir örneğini başlatırJpegImageaspose.imaging.fileformats.jpeg/jpegimage sınıf.
type: docs
weight: 10
url: /tr/net/aspose.imaging.fileformats.jpeg/jpegimage/jpegimage/
---
## JpegImage(string) {#constructor_4}

Yeni bir örneğini başlatır[`JpegImage`](../../jpegimage) sınıf.

```csharp
public JpegImage(string path)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| path | String | Görüntüyü yükleme ve piksel ve palet verilerini başlatma yolu. |

### Örnekler

Örnek, bir dosyadan bir JpegImage'ın nasıl yükleneceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// Bir dosyadan bir JPEG görüntüsü yükleyin.
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(dir + "sample.jpg"))
{
    // Biraz görüntü işleme yapın.
    // Başka bir JPEG dosyasına kaydedin.
    jpegImage.Save(dir + "sample.output.jpg");
}
```

### Ayrıca bakınız

* class [JpegImage](../../jpegimage)
* ad alanı [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* toplantı [Aspose.Imaging](../../../)

---

## JpegImage(Stream) {#constructor_3}

Yeni bir örneğini başlatır[`JpegImage`](../../jpegimage) sınıf.

```csharp
public JpegImage(Stream stream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Görüntüyü yüklemek ve piksel ve palet verilerini başlatmak için akış. |

### Örnekler

Örnek, bir dosya akışından bir JpegImage'ın nasıl yükleneceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// Bir dosya akışından bir JPEG görüntüsü yükleyin.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.jpg"))
{
    using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(stream))
    {
        // Biraz görüntü işleme yapın.
        // Başka bir JPEG dosyasına kaydedin.
        jpegImage.Save(dir + "sample.output.jpg");
    }
}
```

### Ayrıca bakınız

* class [JpegImage](../../jpegimage)
* ad alanı [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* toplantı [Aspose.Imaging](../../../)

---

## JpegImage(RasterImage) {#constructor_1}

Yeni bir örneğini başlatır[`JpegImage`](../../jpegimage) sınıf.

```csharp
public JpegImage(RasterImage rasterImage)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rasterImage | RasterImage | Piksel ve palet verilerinin başlatılacağı resim. |

### Örnekler

Örnek, bir JpegImage'ın başka bir RasterImage'dan nasıl yükleneceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// Başka bir tarama görüntüsünden bir JPEG görüntüsü yükleyin.
// Önce, bir JPEG görüntüsü oluşturmak için temel oluşturacak geçici bir PNG görüntüsü oluşturun.
// Bir dosyadan PNG görüntüsünü de yükleyebilir veya başka herhangi bir raster biçimindeki bir görüntüyü kullanabilirsiniz.
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), false);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // PNG görüntüsünün tamamını kırmızıyla doldurun.
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, rasterImage.Bounds);

    // PNG görüntüsüne dayalı bir JPEG görüntüsü oluşturun.
    using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(rasterImage))
    {
        // JPEG dosyasına kaydet
        jpegImage.Save(dir + "output.jpg");
    }
}
```

### Ayrıca bakınız

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [JpegImage](../../jpegimage)
* ad alanı [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* toplantı [Aspose.Imaging](../../../)

---

## JpegImage(int, int) {#constructor_2}

Yeni bir örneğini başlatır[`JpegImage`](../../jpegimage) sınıf.

```csharp
public JpegImage(int width, int height)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| width | Int32 | Görüntü genişliği. |
| height | Int32 | Görüntü yüksekliği. |

### Örnekler

Aşağıdaki örnek, belirtilen boyutta JPEG görüntüsünün nasıl oluşturulacağını gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// 100x100 piksellik bir JPEG görüntüsü oluşturun.
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(100, 100))
{
    // Biraz görüntü işleme yapın.
    // Bir dosyaya kaydet.
    jpegImage.Save(dir + "output.jpg");
}
```

Aşağıdaki örnek, bir BMP görüntüsünü yükler ve çeşitli kaydetme seçeneklerini kullanarak onu JPEG'e kaydeder.

```csharp
[C#]

string dir = "c:\\temp\\";

// Bir dosyadan bir BMP görüntüsü yükleyin.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Biraz görüntü işleme yapın.

    // İstenen görüntü parametrelerini belirtmek için ek seçenekleri kullanın.
    Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

    // Kanal başına bit sayısı 8'dir.
    // Bir palet kullanıldığında, renk indeksi, rengin kendisi yerine görüntü verisinde saklanır.
    saveOptions.BitsPerChannel = 8;

    // Aşamalı sıkıştırma türünü ayarlayın.
    saveOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

    // Görüntü kalitesini ayarlayın. 1 ile 100 arasında bir değerdir.
    saveOptions.Quality = 100;

    // Yatay/dikey çözünürlüğü inç başına 96 nokta olarak ayarlayın.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
    saveOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

    // Kaynak görüntü renkli ise gri tonlamaya dönüştürülür.
    saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Grayscale;

    // Çıktı boyutunu küçültmek için bir palet kullanın.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

    image.Save(dir + "sample.palettized.jpg", saveOptions);
}
```

### Ayrıca bakınız

* class [JpegImage](../../jpegimage)
* ad alanı [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* toplantı [Aspose.Imaging](../../../)

---

## JpegImage(JpegOptions, int, int) {#constructor}

Yeni bir örneğini başlatır[`JpegImage`](../../jpegimage) sınıf.

```csharp
public JpegImage(JpegOptions jpegOptions, int width, int height)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| jpegOptions | JpegOptions | jpeg seçenekleri. |
| width | Int32 | Görüntü genişliği. |
| height | Int32 | Resim yüksekliği. |

### Örnekler

Aşağıdaki örnek, bir BMP görüntüsünü yükler ve çeşitli kaydetme seçeneklerini kullanarak onu JPEG'e kaydeder.

```csharp
[C#]

string dir = "c:\\temp\\";

// Bir dosyadan bir BMP görüntüsü yükleyin.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Biraz görüntü işleme yapın.

    // İstenen görüntü parametrelerini belirtmek için ek seçenekleri kullanın.
    Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

    // Kanal başına bit sayısı 8'dir.
    // Bir palet kullanıldığında, renk indeksi, rengin kendisi yerine görüntü verisinde saklanır.
    saveOptions.BitsPerChannel = 8;

    // Aşamalı sıkıştırma türünü ayarlayın.
    saveOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

    // Görüntü kalitesini ayarlayın. 1 ile 100 arasında bir değerdir.
    saveOptions.Quality = 100;

    // Yatay/dikey çözünürlüğü inç başına 96 nokta olarak ayarlayın.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
    saveOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

    // Kaynak görüntü renkli ise gri tonlamaya dönüştürülür.
    saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Grayscale;

    // Çıktı boyutunu küçültmek için bir palet kullanın.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

    image.Save(dir + "sample.palettized.jpg", saveOptions);
}
```

Aşağıdaki örnek, belirtilen parametrelerle belirtilen boyutta JPEG görüntüsünün nasıl oluşturulacağını gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// 100x100 piksellik bir JPEG görüntüsü oluşturun.
// İstenen görüntü parametrelerini belirtmek için ek seçenekleri kullanın.
Aspose.Imaging.ImageOptions.JpegOptions createOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

// Y, Cr, Cb bileşenleri için kanal başına bit sayısı 8, 8, 8'dir.
createOptions.BitsPerChannel = 8;

// Aşamalı sıkıştırma türünü ayarlayın.
createOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

// Görüntü kalitesini ayarlayın. 1 ile 100 arasında bir değerdir.
createOptions.Quality = 100;

// Yatay/dikey çözünürlüğü inç başına 96 nokta olarak ayarlayın.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
createOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

// Bu, JPEG görüntüleri için standart bir seçenektir.
// İki renk bileşeni (Cb ve Cr) bant genişliği azaltılabilir, alt örneklenebilir, sıkıştırılabilir.
createOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr;

using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpegImage);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(jpegImage.Width, jpegImage.Height),
        Aspose.Imaging.Color.Yellow,
        Aspose.Imaging.Color.Blue);

    // Resmi gri tonlamalı bir gradyanla doldurun
    graphics.FillRectangle(gradientBrush, jpegImage.Bounds);

    // Bir dosyaya kaydet.
    jpegImage.Save(dir + "output.explicitoptions.jpg");
}
```

### Ayrıca bakınız

* class [JpegOptions](../../../aspose.imaging.imageoptions/jpegoptions)
* class [JpegImage](../../jpegimage)
* ad alanı [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
