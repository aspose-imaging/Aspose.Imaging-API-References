---
title: ActiveFrame
second_title: Aspose.Imaging for .NET API Referansı
description: Etkin çerçeveyi alır veya ayarlar.
type: docs
weight: 20
url: /tr/net/aspose.imaging.fileformats.gif/gifimage/activeframe/
---
## GifImage.ActiveFrame property

Etkin çerçeveyi alır veya ayarlar.

```csharp
public GifFrameBlock ActiveFrame { get; set; }
```

### Mülk değeri

Etkin çerçeve.

### Örnekler

Aşağıdaki örnek, bir GIF görüntüsünden tüm blokların nasıl kaldırılacağını gösterir.

```csharp
[C#]

using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
    if (gifImage.ActiveFrame != null)
    {
        System.Console.WriteLine("Active frame size: {0}", gifImage.ActiveFrame.Size);
    }
    else
    {
        System.Console.WriteLine("Active frame is not set");
    }

    System.Console.WriteLine("Clear all the blocks");
    gifImage.ClearBlocks();

    if (gifImage.ActiveFrame != null)
    {
        System.Console.WriteLine("Active frame size: {0}", gifImage.ActiveFrame.Size);
    }
    else
    {
        System.Console.WriteLine("Active frame is not set");
    }
}

// Çıktı şöyle görünür:
// Etkin çerçeve boyutu: { Genişlik = 100, Yükseklik = 100}
// Tüm blokları temizle
// Aktif çerçeve ayarlanmadı
```

### Ayrıca bakınız

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* class [GifImage](../../gifimage)
* ad alanı [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
