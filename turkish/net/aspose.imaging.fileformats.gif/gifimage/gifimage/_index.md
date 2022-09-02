---
title: GifImage
second_title: Aspose.Imaging for .NET API Referansı
description: Yeni bir örneğini başlatırGifImageaspose.imaging.fileformats.gif/gifimage sınıf.
type: docs
weight: 10
url: /tr/net/aspose.imaging.fileformats.gif/gifimage/gifimage/
---
## GifImage(GifFrameBlock, IColorPalette) {#constructor_1}

Yeni bir örneğini başlatır[`GifImage`](../../gifimage) sınıf.

```csharp
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| firstFrame | GifFrameBlock | gif görüntüsünün başlatılacağı ilk kare. |
| globalPalette | IColorPalette | Kullanılacak genel palet. Her ikisi de varsa not edin*firstFrame* ve*globalPalette* null ise varsayılan genel palet kullanılır. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Çerçeve boş olamaz;firstFrame |
| ArgumentException | İlk kare zaten başka bir resme ait. Container özelliğini kontrol edin.;firstFrame |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | Belirtilen palet, 2 kuvvetine eşit girişler içermelidir. Minimum palet boyutu 2, maksimum 256'dır. |

### Örnekler

Bu örnek, özel bir paletle bir GIF görüntüsünün nasıl oluşturulacağını ve bir dosyaya nasıl kaydedileceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// 100x100 piksellik bir GIF Çerçeve bloğu oluşturun.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // Tüm bloğu kırmızı ile doldurun.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    // Görüntü boyutunu küçültmek için 4 bitlik paleti kullanın. Kalite daha da kötüleşebilir.
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.Create4Bit();

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock, palette))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

### Ayrıca bakınız

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifImage](../../gifimage)
* ad alanı [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* toplantı [Aspose.Imaging](../../../)

---

## GifImage(GifFrameBlock) {#constructor}

Yeni bir örneğini başlatır[`GifImage`](../../gifimage) sınıf.

```csharp
public GifImage(GifFrameBlock firstFrame)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| firstFrame | GifFrameBlock | gif görüntüsünün başlatılacağı ilk kare. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Çerçeve boş olamaz;firstFrame |
| ArgumentException | İlk kare zaten başka bir resme ait. Container özelliğini kontrol edin.;firstFrame |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | Belirtilen palet, 2 kuvvetine eşit girişler içermelidir. Minimum palet boyutu 2, maksimum 256'dır. |

### Örnekler

Bu örnek, bir GIF görüntüsünün nasıl oluşturulacağını ve bir dosyaya nasıl kaydedileceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// 100x100 piksellik bir GIF Çerçeve bloğu oluşturun.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // Tüm bloğu kırmızı ile doldurun.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

Aşağıdaki örnek, tek tek GIF bloklarından bir animasyonlu GIF görüntüsünün nasıl oluşturulacağını gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// 100 x 100 piksellik bir GIF görüntüsü oluşturun.
// İlk blok varsayılan olarak tamamen siyahtır.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
    // İlk daire kırmızı
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // İkinci daire siyah
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // Kırmızı yay şeklinin açısını kademeli olarak artırın.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush1, block.Bounds, 0, angle);

        gifImage.AddBlock(block);
    }

    // Siyah yayın açısını kademeli olarak artırın ve kırmızı yayı silin.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush2, block.Bounds, 0, angle);
        gr.FillPie(brush1, block.Bounds, angle, 360 - angle);

        gifImage.AddBlock(block);
    }

    gifImage.Save(dir + "animated_radar.gif");
}
```

### Ayrıca bakınız

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* class [GifImage](../../gifimage)
* ad alanı [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* toplantı [Aspose.Imaging](../../../)

---

## GifImage(GifFrameBlock, IColorPalette, bool, byte, byte, byte, bool) {#constructor_2}

Yeni bir örneğini başlatır[`GifImage`](../../gifimage) sınıf.

```csharp
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, bool isPaletteSorted, 
    byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, 
    bool hasTrailer)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| firstFrame | GifFrameBlock | gif görüntüsünün başlatılacağı ilk kare. |
| globalPalette | IColorPalette | Kullanılacak genel palet. Her ikisi de varsa not edin*firstFrame* ve*globalPalette* null ise varsayılan genel palet kullanılır. |
| isPaletteSorted | Boolean | ayarlanırsa`doğru` palet sıralanır. Parametrenin ne zaman kullanıldığını unutmayın.*globalPalette* boş değil. |
| paletteColorResolution | Byte | Palet renk çözünürlüğü. Parametrenin ne zaman kullanıldığını unutmayın.*globalPalette* boş değil. |
| paletteBackgroundColorIndex | Byte | Palet arka plan rengi dizini. |
| aspectRatio | Byte | En boy oranı. |
| hasTrailer | Boolean | ayarlanırsa`doğru` gif resminin fragmanı vardır, aksi takdirde akışın sonunda fragman yazılmaz. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Çerçeve boş olamaz;firstFrame |
| ArgumentException | İlk kare zaten başka bir resme ait. Container özelliğini kontrol edin.;firstFrame |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | Belirtilen palet, 2 kuvvetine eşit girişler içermelidir. Minimum palet boyutu 2, maksimum 256'dır. |

### Ayrıca bakınız

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifImage](../../gifimage)
* ad alanı [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
