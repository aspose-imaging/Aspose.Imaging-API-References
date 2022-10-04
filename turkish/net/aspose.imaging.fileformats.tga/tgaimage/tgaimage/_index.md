---
title: TgaImage
second_title: Aspose.Imaging for .NET API Referansı
description: Yeni bir örneğini başlatırTgaImageaspose.imaging.fileformats.tga/tgaimage sınıf.
type: docs
weight: 10
url: /tr/net/aspose.imaging.fileformats.tga/tgaimage/tgaimage/
---
## TgaImage(string) {#constructor_2}

Yeni bir örneğini başlatır[`TgaImage`](../../tgaimage) sınıf.

```csharp
public TgaImage(string path)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| path | String | Görüntü yükleme yolu. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Belirtilen yol boş. |

### Ayrıca bakınız

* class [TgaImage](../../tgaimage)
* ad alanı [Aspose.Imaging.FileFormats.Tga](../../tgaimage)
* toplantı [Aspose.Imaging](../../../)

---

## TgaImage(RasterImage) {#constructor}

Yeni bir örneğini başlatır[`TgaImage`](../../tgaimage) sınıf.

```csharp
public TgaImage(RasterImage rasterImage)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rasterImage | RasterImage | Raster görüntü. |

### Örnekler

PNG görüntüsünün yüklenmesi, TgaImage'a dönüştürülmesi ve TGA görüntüsü olarak kaydedilmesi.

```csharp
[C#]

using (RasterImage image = (RasterImage)Image.Load("test.png"))
{
    using (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.Save("test.tga");
    }
}
```

### Ayrıca bakınız

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [TgaImage](../../tgaimage)
* ad alanı [Aspose.Imaging.FileFormats.Tga](../../tgaimage)
* toplantı [Aspose.Imaging](../../../)

---

## TgaImage(Stream) {#constructor_1}

Yeni bir örneğini başlatır[`TgaImage`](../../tgaimage) sınıf.

```csharp
public TgaImage(Stream stream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Bir görüntü yüklemek için akış. |

### Ayrıca bakınız

* class [TgaImage](../../tgaimage)
* ad alanı [Aspose.Imaging.FileFormats.Tga](../../tgaimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->