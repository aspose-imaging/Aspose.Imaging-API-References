---
title: ResizeWidthProportionally
second_title: Aspose.Imaging for .NET API Referansı
description: Genişliği orantılı olarak yeniden boyutlandırır.
type: docs
weight: 360
url: /tr/net/aspose.imaging.fileformats.tiff/tiffimage/resizewidthproportionally/
---
## TiffImage.ResizeWidthProportionally method

Genişliği orantılı olarak yeniden boyutlandırır.

```csharp
public override void ResizeWidthProportionally(int newWidth, ResizeType resizeType)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| newWidth | Int32 | Yeni genişlik. |
| resizeType | ResizeType | Yeniden boyutlandırma türü. |

### Örnekler

Bu örnek, bir TIFF görüntüsü yükler ve çeşitli yeniden boyutlandırma yöntemlerini kullanarak onu orantılı olarak yeniden boyutlandırır. Yalnızca genişlik belirtilir, yükseklik otomatik olarak hesaplanır.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // En Yakın Komşu yeniden örneklemeyi kullanarak 2 kat büyütün.
    image.ResizeWidthProportionally(image.Width* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // Varsayılan seçeneklerle PNG'ye kaydedin.
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // En Yakın Komşu yeniden örneklemeyi kullanarak 2 kat küçült.
    image.ResizeWidthProportionally(image.Width / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // Varsayılan seçeneklerle PNG'ye kaydedin.
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // Bilinear yeniden örneklemeyi kullanarak 2 kez ölçeklendirin.
    image.ResizeWidthProportionally(image.Width* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // Varsayılan seçeneklerle PNG'ye kaydedin.
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // Bilineer yeniden örneklemeyi kullanarak 2 kat küçültün.
    image.ResizeWidthProportionally(image.Width / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // Varsayılan seçeneklerle PNG'ye kaydedin.
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Ayrıca bakınız

* enum [ResizeType](../../../aspose.imaging/resizetype)
* class [TiffImage](../../tiffimage)
* ad alanı [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->