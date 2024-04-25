---
title: GifFrameBlock
second_title: Aspose.Imaging for .NET API Referansı
description: Yeni bir örneğini başlatırGifFrameBlockaspose.imaging.fileformats.gif.blocks/gifframeblock sınıf.
type: docs
weight: 10
url: /tr/aspose.imaging.fileformats.gif.blocks/gifframeblock/gifframeblock/
---
## GifFrameBlock(ushort, ushort) {#constructor_9}

Yeni bir örneğini başlatır[`GifFrameBlock`](../../gifframeblock) sınıf.

```csharp
public GifFrameBlock(ushort width, ushort height)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| width | UInt16 | Görüntü genişliği. |
| height | UInt16 | Görüntü yüksekliği. |

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

* class [GifFrameBlock](../../gifframeblock)
* ad alanı [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* toplantı [Aspose.Imaging](../../../)

---

## GifFrameBlock(ushort, ushort, ushort, ushort) {#constructor_10}

Yeni bir örneğini başlatır[`GifFrameBlock`](../../gifframeblock) sınıf.

```csharp
public GifFrameBlock(ushort left, ushort top, ushort width, ushort height)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| left | UInt16 | Sol görüntü konumu. |
| top | UInt16 | Üst görüntü konumu. |
| width | UInt16 | Görüntü genişliği. |
| height | UInt16 | Görüntü yüksekliği. |

### Ayrıca bakınız

* class [GifFrameBlock](../../gifframeblock)
* ad alanı [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* toplantı [Aspose.Imaging](../../../)

---

## GifFrameBlock(ushort, ushort, ushort, ushort, IColorPalette, bool, bool, byte) {#constructor_11}

Yeni bir örneğini başlatır[`GifFrameBlock`](../../gifframeblock) sınıf.

```csharp
public GifFrameBlock(ushort left, ushort top, ushort width, ushort height, 
    IColorPalette colorPalette, bool isPaletteSorted, bool isGifFrameInterlaced, byte bitsPerPixel)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| left | UInt16 | Sol görüntü konumu. |
| top | UInt16 | Üst görüntü konumu. |
| width | UInt16 | Görüntü Genişliği. |
| height | UInt16 | Görüntü Yüksekliği. |
| colorPalette | IColorPalette | Renk paleti. |
| isPaletteSorted | Boolean | ayarlanırsa`doğru` renk paleti sıralanır. |
| isGifFrameInterlaced | Boolean | ayarlanırsa`doğru` GIF çerçevesi iç içedir. |
| bitsPerPixel | Byte | Piksel başına bit. |

### Ayrıca bakınız

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifFrameBlock](../../gifframeblock)
* ad alanı [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* toplantı [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage) {#constructor}

Yeni bir örneğini başlatır[`GifFrameBlock`](../../gifframeblock) sınıf.

```csharp
public GifFrameBlock(RasterImage image)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| image | RasterImage | Çerçeve pikseli ve palet verilerinin başlatılacağı görüntü. |

### Ayrıca bakınız

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifFrameBlock](../../gifframeblock)
* ad alanı [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* toplantı [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage, ushort, ushort) {#constructor_1}

Yeni bir örneğini başlatır[`GifFrameBlock`](../../gifframeblock) sınıf.

```csharp
public GifFrameBlock(RasterImage image, ushort left, ushort top)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| image | RasterImage | Çerçeve pikseli ve palet verilerinin başlatılacağı görüntü. |
| left | UInt16 | Sol görüntü konumu. |
| top | UInt16 | Üst görüntü konumu. |

### Ayrıca bakınız

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifFrameBlock](../../gifframeblock)
* ad alanı [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* toplantı [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage, ushort, ushort, bool, bool, byte) {#constructor_2}

Yeni bir örneğini başlatır[`GifFrameBlock`](../../gifframeblock) sınıf.

```csharp
public GifFrameBlock(RasterImage image, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| image | RasterImage | Çerçeve pikseli ve palet verilerinin başlatılacağı görüntü. |
| left | UInt16 | Sol görüntü konumu. |
| top | UInt16 | Üst görüntü konumu. |
| isPaletteSorted | Boolean | ayarlanırsa`doğru` renk paleti sıralanır. |
| isGifFrameInterlaced | Boolean | ayarlanırsa`doğru` GIF çerçevesi iç içedir. |
| lzwCodeSize | Byte | Piksel başına bit. |

### Ayrıca bakınız

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifFrameBlock](../../gifframeblock)
* ad alanı [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* toplantı [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream) {#constructor_3}

Yeni bir örneğini başlatır[`GifFrameBlock`](../../gifframeblock) sınıf.

```csharp
public GifFrameBlock(Stream stream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Çerçeve pikseli ve palet verisinden bir görüntü yüklemek ve bunu başlatmak için akış. |

### Ayrıca bakınız

* class [GifFrameBlock](../../gifframeblock)
* ad alanı [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* toplantı [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream, ushort, ushort) {#constructor_4}

Yeni bir örneğini başlatır[`GifFrameBlock`](../../gifframeblock) sınıf.

```csharp
public GifFrameBlock(Stream stream, ushort left, ushort top)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Çerçeve pikseli ve palet verisinden bir görüntü yüklemek ve bunu başlatmak için akış. |
| left | UInt16 | Sol görüntü konumu. |
| top | UInt16 | Üst görüntü konumu. |

### Ayrıca bakınız

* class [GifFrameBlock](../../gifframeblock)
* ad alanı [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* toplantı [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream, ushort, ushort, bool, bool, byte) {#constructor_5}

Yeni bir örneğini başlatır[`GifFrameBlock`](../../gifframeblock) sınıf.

```csharp
public GifFrameBlock(Stream stream, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Çerçeve pikseli ve palet verisinden bir görüntü yüklemek ve bunu başlatmak için akış. |
| left | UInt16 | Sol görüntü konumu. |
| top | UInt16 | Üst görüntü konumu. |
| isPaletteSorted | Boolean | ayarlanırsa`doğru` renk paleti sıralanır. |
| isGifFrameInterlaced | Boolean | ayarlanırsa`doğru` GIF çerçevesi iç içedir. |
| lzwCodeSize | Byte | Piksel başına bit. |

### Ayrıca bakınız

* class [GifFrameBlock](../../gifframeblock)
* ad alanı [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* toplantı [Aspose.Imaging](../../../)

---

## GifFrameBlock(string) {#constructor_6}

Yeni bir örneğini başlatır[`GifFrameBlock`](../../gifframeblock) sınıf.

```csharp
public GifFrameBlock(string path)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| path | String | Çerçeve pikseli ve palet verisinden bir görüntü yükleme ve bununla başlatma yolu. |

### Ayrıca bakınız

* class [GifFrameBlock](../../gifframeblock)
* ad alanı [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* toplantı [Aspose.Imaging](../../../)

---

## GifFrameBlock(string, ushort, ushort) {#constructor_7}

Yeni bir örneğini başlatır[`GifFrameBlock`](../../gifframeblock) sınıf.

```csharp
public GifFrameBlock(string path, ushort left, ushort top)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| path | String | Çerçeve pikseli ve palet verisinden bir görüntü yükleme ve bununla başlatma yolu. |
| left | UInt16 | Sol görüntü konumu. |
| top | UInt16 | Üst görüntü konumu. |

### Ayrıca bakınız

* class [GifFrameBlock](../../gifframeblock)
* ad alanı [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* toplantı [Aspose.Imaging](../../../)

---

## GifFrameBlock(string, ushort, ushort, bool, bool, byte) {#constructor_8}

Yeni bir örneğini başlatır[`GifFrameBlock`](../../gifframeblock) sınıf.

```csharp
public GifFrameBlock(string path, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| path | String | Çerçeve pikseli ve palet verisinden bir görüntü yükleme ve bununla başlatma yolu. |
| left | UInt16 | Sol görüntü konumu. |
| top | UInt16 | Üst görüntü konumu. |
| isPaletteSorted | Boolean | ayarlanırsa`doğru` renk paleti sıralanır. |
| isGifFrameInterlaced | Boolean | ayarlanırsa`doğru` GIF çerçevesi iç içedir. |
| lzwCodeSize | Byte | Piksel başına bit. |

### Ayrıca bakınız

* class [GifFrameBlock](../../gifframeblock)
* ad alanı [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
