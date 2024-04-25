---
title: BmpImage
second_title: Aspose.Imaging for .NET API Referansı
description: Yeni bir örneğini başlatırBmpImageaspose.imaging.fileformats.bmp/bmpimage sınıf.
type: docs
weight: 10
url: /tr/aspose.imaging.fileformats.bmp/bmpimage/bmpimage/
---
## BmpImage(string) {#constructor_7}

Yeni bir örneğini başlatır[`BmpImage`](../../bmpimage) sınıf.

```csharp
public BmpImage(string path)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| path | String | Görüntüyü yükleme ve piksel ve palet verilerini başlatma yolu. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | raster görüntü boş;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Yükseklik pozitif olmalıdır. |
| ArgumentException | Piksel başına 8 bit veya daha az olan resimler için palet belirtilmelidir.; palet |

### Örnekler

Örnek, bir dosyadan bir BmpImage'ın nasıl yükleneceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// Bir dosyadan bir BMP görüntüsü yükleyin.
// Gerekirse kaynak pikseller 32-bpp formatına dönüştürülecektir.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(dir + "sample.bmp"))
{
    // Biraz görüntü işleme yapın.
    // Başka bir BMP dosyasına kaydedin.
    bmpImage.Save(dir + "sample.output.32bpp.bmp");
}
```

### Ayrıca bakınız

* class [BmpImage](../../bmpimage)
* ad alanı [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* toplantı [Aspose.Imaging](../../../)

---

## BmpImage(string, ushort, BitmapCompression, double, double) {#constructor_8}

Yeni bir örneğini başlatır[`BmpImage`](../../bmpimage) sınıf.

```csharp
public BmpImage(string path, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| path | String | Görüntüyü yükleme ve piksel ve palet verilerini başlatma yolu. |
| bitsPerPixel | UInt16 | Piksel başına bit. |
| compression | BitmapCompression | Kullanılacak sıkıştırma. |
| horizontalResolution | Double | Yatay çözünürlük. Yuvarlama nedeniyle elde edilen çözünürlüğün geçenden biraz farklı olabileceğini unutmayın. |
| verticalResolution | Double | Dikey çözünürlük. Yuvarlama nedeniyle elde edilen çözünürlüğün geçenden biraz farklı olabileceğini unutmayın. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Raster görüntü boş olamaz;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Yükseklik pozitif olmalıdır. |
| ArgumentException | Piksel başına 8 bit veya daha az olan resimler için palet belirtilmelidir.; palet |

### Örnekler

Örnek, belirtilen bit derinliğine ve çözünürlüğe sahip bir dosyadan bir BmpImage'ın nasıl yükleneceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// Bir dosyadan bir BMP görüntüsü yükleyin.
// Gerekirse kaynak pikseller 24 bpp formatına dönüştürülecektir.
// Çözünürlük 96 dpi olarak ayarlanacaktır.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage =
    new Aspose.Imaging.FileFormats.Bmp.BmpImage(dir + "sample.bmp", 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
{
    // Biraz görüntü işleme yapın.
    // Başka bir BMP dosyasına kaydedin.
    bmpImage.Save(dir + "sample.output.24bpp.96dpi.bmp");
}
```

### Ayrıca bakınız

* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* ad alanı [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* toplantı [Aspose.Imaging](../../../)

---

## BmpImage(Stream) {#constructor_5}

Yeni bir örneğini başlatır[`BmpImage`](../../bmpimage) sınıf.

```csharp
public BmpImage(Stream stream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Görüntüyü yüklemek ve piksel ve palet verilerini başlatmak için akış. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Raster görüntü boş olamaz;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Yükseklik pozitif olmalıdır. |
| ArgumentException | Piksel başına 8 bit veya daha az olan resimler için palet belirtilmelidir.; palet |

### Örnekler

Örnek, bir dosya akışından bir BmpImage'ın nasıl yükleneceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// Bir dosya akışından bir BMP görüntüsü yükleyin.
// Gerekirse kaynak pikseller 32-bpp formatına dönüştürülecektir.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(stream))
    {
        // Biraz görüntü işleme yapın.
        // Başka bir BMP dosyasına kaydedin.
        bmpImage.Save(dir + "sample.output.32bpp.bmp");
    }
}
```

### Ayrıca bakınız

* class [BmpImage](../../bmpimage)
* ad alanı [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* toplantı [Aspose.Imaging](../../../)

---

## BmpImage(Stream, ushort, BitmapCompression, double, double) {#constructor_6}

Yeni bir örneğini başlatır[`BmpImage`](../../bmpimage) sınıf.

```csharp
public BmpImage(Stream stream, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Görüntüyü yüklemek ve piksel ve palet verilerini başlatmak için akış. |
| bitsPerPixel | UInt16 | Piksel başına bit. |
| compression | BitmapCompression | Kullanılacak sıkıştırma. |
| horizontalResolution | Double | Yatay çözünürlük. Yuvarlama nedeniyle elde edilen çözünürlüğün geçenden biraz farklı olabileceğini unutmayın. |
| verticalResolution | Double | Dikey çözünürlük. Yuvarlama nedeniyle elde edilen çözünürlüğün geçenden biraz farklı olabileceğini unutmayın. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Raster görüntü boş olamaz;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Yükseklik pozitif olmalıdır. |
| ArgumentException | Piksel başına 8 bit veya daha az olan resimler için palet belirtilmelidir.; palet |

### Örnekler

Örnek, belirtilen bit derinliği ve çözünürlüğü ile bir dosya akışından bir BmpImage'ın nasıl yükleneceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// Bir dosya akışından bir BMP görüntüsü yükleyin.
// Gerekirse kaynak pikseller 24 bpp formatına dönüştürülecektir.
// Çözünürlük 96 dpi olarak ayarlanacaktır.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage =
        new Aspose.Imaging.FileFormats.Bmp.BmpImage(stream, 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
    {
        // Biraz görüntü işleme yapın.
        // Başka bir BMP dosyasına kaydedin.
        bmpImage.Save(dir + "sample.output.24bpp.96dpi.bmp");
    }
}
```

### Ayrıca bakınız

* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* ad alanı [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* toplantı [Aspose.Imaging](../../../)

---

## BmpImage(RasterImage) {#constructor}

Yeni bir örneğini başlatır[`BmpImage`](../../bmpimage) sınıf.

```csharp
public BmpImage(RasterImage rasterImage)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rasterImage | RasterImage | Piksel ve palet verilerinin başlatılacağı görüntü. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Raster görüntü boş olamaz;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Yükseklik pozitif olmalıdır. |
| ArgumentException | Piksel başına 8 bit veya daha az olan resimler için palet belirtilmelidir.; palet |

### Örnekler

Örnek, başka bir RasterImage örneğinden bir BmpImage'ın nasıl yükleneceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// Yeni bir PNG görüntüsü oluşturun.
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // PNG görüntüsünün tamamını kırmızıyla doldurun.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, rasterImage.Bounds);

    // PNG görüntüsünü temel alan bir BMP görüntüsü oluşturun.
    // Gerekirse kaynak pikseller 32-bpp formatına dönüştürülecektir.
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(rasterImage))
    {
        // BMP dosyasına kaydet
        bmpImage.Save(dir + "output.32bpp.bmp");
    }
}
```

### Ayrıca bakınız

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [BmpImage](../../bmpimage)
* ad alanı [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* toplantı [Aspose.Imaging](../../../)

---

## BmpImage(RasterImage, ushort, BitmapCompression, double, double) {#constructor_1}

Yeni bir örneğini başlatır[`BmpImage`](../../bmpimage) sınıf.

```csharp
public BmpImage(RasterImage rasterImage, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rasterImage | RasterImage | Piksel ve palet verilerinin başlatılacağı görüntü. |
| bitsPerPixel | UInt16 | Piksel başına bit. |
| compression | BitmapCompression | Kullanılacak sıkıştırma. |
| horizontalResolution | Double | Yatay çözünürlük. Yuvarlama nedeniyle elde edilen çözünürlüğün geçenden biraz farklı olabileceğini unutmayın. |
| verticalResolution | Double | Dikey çözünürlük. Yuvarlama nedeniyle elde edilen çözünürlüğün geçenden biraz farklı olabileceğini unutmayın. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Raster görüntü boş olamaz;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Yükseklik pozitif olmalıdır. |
| ArgumentException | Piksel başına 8 bit veya daha az olan resimler için palet belirtilmelidir.; palet |

### Örnekler

Örnek, belirtilen bit derinliği ve sıkıştırma ile başka bir RasterImage örneğinden bir BmpImage'ın nasıl yükleneceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// Yeni bir PNG görüntüsü oluşturun.
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // PNG görüntüsünün tamamını kırmızıyla doldurun.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, rasterImage.Bounds);

    // PNG görüntüsünü temel alan bir BMP görüntüsü oluşturun.
    // Gerekirse kaynak pikseller 24 bpp formatına dönüştürülecektir.
    // Çözünürlük 96 dpi olarak ayarlanacaktır.
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(rasterImage, 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
    {
        // BMP dosyasına kaydet
        bmpImage.Save(dir + "output.24bpp.96dpi.bmp");
    }
}
```

### Ayrıca bakınız

* class [RasterImage](../../../aspose.imaging/rasterimage)
* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* ad alanı [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* toplantı [Aspose.Imaging](../../../)

---

## BmpImage(int, int) {#constructor_2}

Yeni bir örneğini başlatır[`BmpImage`](../../bmpimage) sınıf.

```csharp
public BmpImage(int width, int height)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| width | Int32 | Görüntü genişliği. |
| height | Int32 | Görüntü yüksekliği. |

### istisnalar

| istisna | şart |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Yükseklik pozitif olmalıdır. |
| ArgumentException | Piksel başına 8 bit veya daha az olan resimler için palet belirtilmelidir.; palet |

### Örnekler

Örnek, belirtilen boyutta bir BmpImage'ın nasıl oluşturulacağını gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// 100 x 100 piksellik bir 32-bpp BMP görüntüsü oluşturun.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Resmin tamamını kırmızı ile doldurun.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // BMP dosyasına kaydet
    bmpImage.Save(dir + "output.bmp");
}
```

Aşağıdaki örnek, çıktı boyutunu küçültmek için bir BMP görüntüsünün nasıl paletleneceğini gösterir.

```csharp
[C#]

// 100 x 100 piksellik bir BMP görüntüsü oluşturun.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Resmin sol üst köşesinden sağ alt köşesine doğru doğrusal gradyan.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(bmpImage.Width, bmpImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Resmin tamamını doğrusal gradyan fırçasıyla doldurun.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // Mümkün olduğu kadar çok pikseli kapsayan en yakın 8 bitlik renk paletini alın, böylece paletlenmiş bir görüntü
    // paletlenmemiş olandan neredeyse görsel olarak ayırt edilemez.
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(bmpImage, 256);

    // 8 bitlik palet en fazla 256 renk içerir.
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
    saveOptions.Palette = palette;
    saveOptions.BitsPerPixel = 8;

    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        bmpImage.Save(stream, saveOptions);
        System.Console.WriteLine("The palettized image size is {0} bytes.", stream.Length);
    }

    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        bmpImage.Save(stream);
        System.Console.WriteLine("The non-palettized image size is {0} bytes.", stream.Length);
    }
}

// Çıktı şöyle görünür:
// Paletlenmiş görüntü boyutu 11078 bayttır.
// Paletlenmemiş görüntü boyutu 40054 bayttır.
```

### Ayrıca bakınız

* class [BmpImage](../../bmpimage)
* ad alanı [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* toplantı [Aspose.Imaging](../../../)

---

## BmpImage(int, int, ushort, IColorPalette) {#constructor_3}

Yeni bir örneğini başlatır[`BmpImage`](../../bmpimage) sınıf.

```csharp
public BmpImage(int width, int height, ushort bitsPerPixel, IColorPalette palette)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| width | Int32 | Görüntü genişliği. |
| height | Int32 | Görüntü yüksekliği. |
| bitsPerPixel | UInt16 | Piksel başına bit. |
| palette | IColorPalette | Renk paleti. |

### istisnalar

| istisna | şart |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Yükseklik pozitif olmalıdır. |
| ArgumentException | Piksel başına 8 bit veya daha az olan resimler için palet belirtilmelidir.; palet |

### Örnekler

Örnek, belirtilen paletle belirtilen boyutta bir BmpImage'ın nasıl oluşturulacağını gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// Yalnızca kırmızı ve yeşil renkleri içeren tek renkli bir palet oluşturun.
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

// 100 x 100 piksellik bir monokrom 1-bpp BMP görüntüsü oluşturun.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 1, palette))
{
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

    // Resmin üst yarısını kırmızı ile doldurun.
    Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(redBrush, new Aspose.Imaging.Rectangle(0, 0, bmpImage.Width, bmpImage.Height / 2));

    // Resmin alt yarısını yeşille doldurun.
    Aspose.Imaging.Brushes.SolidBrush greenBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Green);
    gr.FillRectangle(greenBrush, new Aspose.Imaging.Rectangle(0, bmpImage.Height / 2, bmpImage.Width, bmpImage.Height / 2));

    // BMP'ye kaydet
    bmpImage.Save(dir + "output.monochrome.bmp");
}
```

### Ayrıca bakınız

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [BmpImage](../../bmpimage)
* ad alanı [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* toplantı [Aspose.Imaging](../../../)

---

## BmpImage(int, int, ushort, IColorPalette, BitmapCompression, double, double) {#constructor_4}

Yeni bir örneğini başlatır[`BmpImage`](../../bmpimage) sınıf.

```csharp
public BmpImage(int width, int height, ushort bitsPerPixel, IColorPalette palette, 
    BitmapCompression compression, double horizontalResolution, double verticalResolution)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| width | Int32 | Görüntü genişliği. |
| height | Int32 | Görüntü yüksekliği. |
| bitsPerPixel | UInt16 | Piksel başına bit. |
| palette | IColorPalette | Renk paleti. |
| compression | BitmapCompression | Kullanılacak sıkıştırma. |
| horizontalResolution | Double | Yatay çözünürlük. Yuvarlama nedeniyle elde edilen çözünürlüğün geçenden biraz farklı olabileceğini unutmayın. |
| verticalResolution | Double | Dikey çözünürlük. Yuvarlama nedeniyle elde edilen çözünürlüğün geçenden biraz farklı olabileceğini unutmayın. |

### istisnalar

| istisna | şart |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Yükseklik pozitif olmalıdır. |
| ArgumentException | Piksel başına 8 bit veya daha az olan resimler için palet belirtilmelidir.; palet |

### Örnekler

Örnek, çeşitli seçenekleri kullanarak bir BmpImage'ın nasıl oluşturulacağını gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// Yalnızca kırmızı ve yeşil renkleri içeren tek renkli bir palet oluşturun.
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

// 100 x 100 piksellik bir monokrom 1-bpp BMP görüntüsü oluşturun.
// Yatay ve dikey çözünürlük 96 dpi olarak ayarlanacaktır.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 1, palette, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
{
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

    // Resmin üst yarısını kırmızı ile doldurun.
    Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(redBrush, new Aspose.Imaging.Rectangle(0, 0, bmpImage.Width, bmpImage.Height / 2));

    // Resmin alt yarısını yeşille doldurun.
    Aspose.Imaging.Brushes.SolidBrush greenBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Green);
    gr.FillRectangle(greenBrush, new Aspose.Imaging.Rectangle(0, bmpImage.Height / 2, bmpImage.Width, bmpImage.Height / 2));

    // BMP dosyasına kaydet
    bmpImage.Save(dir + "output.monochrome.96dpi.bmp");
}
```

### Ayrıca bakınız

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* ad alanı [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
