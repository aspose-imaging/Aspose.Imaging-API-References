---
title: GetCloseImagePalette
second_title: Aspose.Imaging for .NET API Referansı
description: Görüntünün olmaması durumunda raster görüntüden renk paleti alır görüntüyü paletler. Palet mevcutsa hesaplamalar yapmak yerine kullanılacaktır.
type: docs
weight: 60
url: /tr/aspose.imaging/colorpalettehelper/getcloseimagepalette/
---
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_3}

Görüntünün olmaması durumunda raster görüntüden renk paleti alır (görüntüyü paletler). Palet mevcutsa, hesaplamalar yapmak yerine kullanılacaktır.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| image | RasterImage | Raster görüntü. |
| entriesCount | Int32 | İstenen girişler sayılır. |

### Geri dönüş değeri

En sık kullanılan renklerle başlayan renk paleti.*image* ve içerir*entriesCount* girişler.

### Örnekler

Aşağıdaki örnek, bir BMP görüntüsünü yükler ve çeşitli kaydetme seçeneklerini kullanarak onu BMP'ye geri kaydeder.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // BmpOptions Oluştur
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Çıktı görüntüsünün boyutunu küçültmek için piksel başına 8 bit kullanın.
    saveOptions.BitsPerPixel = 8;

    // Maksimum görüntü pikseli sayısını kapsayan en yakın 8 bitlik renk paletini ayarlayın, böylece paletlenmiş bir görüntü
    // paletlenmemiş olandan neredeyse görsel olarak ayırt edilemez.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(rasterImage, 256);

    // Sıkıştırmadan kaydet.
    // Çıktı görüntüsünün boyutunu küçültmek için RLE-8 sıkıştırmasını da kullanabilirsiniz.
    saveOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

    // Yatay ve dikey çözünürlüğü 96 dpi olarak ayarlayın.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    image.Save(dir + "sample.bmpoptions.bmp", saveOptions);
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

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* class [ColorPaletteHelper](../../colorpalettehelper)
* ad alanı [Aspose.Imaging](../../colorpalettehelper)
* toplantı [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, int, PaletteMiningMethod) {#getcloseimagepalette_4}

Görüntünün olmaması durumunda raster görüntüden renk paleti alır (görüntüyü paletler). Palet, daha iyi dizine alınmış görüntü kalitesi için optimize edilmek üzere veya PaletteMiningMethod.UseCurrentPalette kullanıldığında "OLDUĞU GİBİ" alınacak.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount, 
    PaletteMiningMethod paletteMiningMethod)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| image | RasterImage | Raster görüntü. |
| entriesCount | Int32 | İstenen girişler sayılır. |
| paletteMiningMethod | PaletteMiningMethod | Palet madenciliği yöntemi. |

### Geri dönüş değeri

En sık kullanılan renklerle başlayan renk paleti.*image* ve içerir*entriesCount* girişler.

### Örnekler

Aşağıdaki örnek, en uygun paletle dizine alınmış renk kullanılarak PNG görüntüsünün nasıl sıkıştırılacağını gösterir.

```csharp
[C#]

// png görüntüsünü yükler        
    string  sourceFilePath="OriginalRings.png";
    string  outputFilePath="OriginalRingsOutput.png";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new Aspose.Imaging.ImageOptions.PngOptions()
    {
         Progressive = true,
             // Dizine alınmış renk türünü kullan
         ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.IndexedColor,
             // Maksimum sıkıştırmayı kullan
         CompressionLevel = 9,
      // Mümkün olduğu kadar çok pikseli kapsayan en yakın 8 bitlik renk paletini alın, böylece paletlenmiş bir görüntü
         // paletlenmemiş olandan neredeyse görsel olarak ayırt edilemez.
         Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette((Aspose.Imaging.RasterImage)image, 256, Aspose.Imaging.PaletteMiningMethod.Histogram)
    });
}
    // Çıktı dosyası boyutu önemli ölçüde azaltılmalıdır
```

### Ayrıca bakınız

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* enum [PaletteMiningMethod](../../paletteminingmethod)
* class [ColorPaletteHelper](../../colorpalettehelper)
* ad alanı [Aspose.Imaging](../../colorpalettehelper)
* toplantı [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

Görüntünün olmaması durumunda raster görüntüden renk paleti alır (görüntüyü paletler). Palet mevcutsa, hesaplamalar yapmak yerine kullanılacaktır.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| image | RasterImage | Raster görüntü. |
| destBounds | Rectangle | Hedef görüntü sınırları. |
| entriesCount | Int32 | İstenen girişler sayılır. |

### Geri dönüş değeri

En sık kullanılan renklerle başlayan renk paleti.*image* ve içerir*entriesCount* girişler.

### Ayrıca bakınız

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* class [ColorPaletteHelper](../../colorpalettehelper)
* ad alanı [Aspose.Imaging](../../colorpalettehelper)
* toplantı [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

Görüntünün olmaması durumunda raster görüntüden renk paleti alır (görüntüyü paletler). Palet mevcutsa, hesaplamalar yapmak yerine kullanılacaktır.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| image | RasterImage | Raster görüntü. |
| destBounds | Rectangle | Hedef görüntü sınırları. |
| entriesCount | Int32 | İstenen girişler sayılır. |
| useImagePalette | Boolean | Ayarlanırsa, varsa kendi resim paletini kullanır. |

### Geri dönüş değeri

En sık kullanılan renklerle başlayan renk paleti.*image* ve içerir*entriesCount* girişler.

### Ayrıca bakınız

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* class [ColorPaletteHelper](../../colorpalettehelper)
* ad alanı [Aspose.Imaging](../../colorpalettehelper)
* toplantı [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool, Color) {#getcloseimagepalette_2}

Görüntünün olmaması durumunda raster görüntüden renk paleti alır (görüntüyü paletler). Palet mevcutsa, hesaplamalar yapmak yerine kullanılacaktır.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette, Color alphaBlendInColor)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| image | RasterImage | Raster görüntü. |
| destBounds | Rectangle | Hedef görüntü sınırları. |
| entriesCount | Int32 | İstenen girişler sayılır. |
| useImagePalette | Boolean | Ayarlanırsa, varsa kendi resim paletini kullanır. |
| alphaBlendInColor | Color | Yarı saydam alfa değişimi için arka plan rengi olarak kullanılması gereken renk. |

### Geri dönüş değeri

En sık kullanılan renklerle başlayan renk paleti.*image* ve içerir*entriesCount* girişler.

### Ayrıca bakınız

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* struct [Color](../../color)
* class [ColorPaletteHelper](../../colorpalettehelper)
* ad alanı [Aspose.Imaging](../../colorpalettehelper)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
