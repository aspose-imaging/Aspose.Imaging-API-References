---
title: TgaImage
second_title: Aspose.Imaging för .NET API-referens
description: Initierar en ny instans avTgaImageaspose.imaging.fileformats.tga/tgaimage class.
type: docs
weight: 10
url: /sv/net/aspose.imaging.fileformats.tga/tgaimage/tgaimage/
---
## TgaImage(string) {#constructor_2}

Initierar en ny instans av[`TgaImage`](../../tgaimage) class.

```csharp
public TgaImage(string path)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | String | Sökvägen för att ladda en bild. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Den angivna sökvägen är null. |

### Se även

* class [TgaImage](../../tgaimage)
* namnutrymme [Aspose.Imaging.FileFormats.Tga](../../tgaimage)
* hopsättning [Aspose.Imaging](../../../)

---

## TgaImage(RasterImage) {#constructor}

Initierar en ny instans av[`TgaImage`](../../tgaimage) class.

```csharp
public TgaImage(RasterImage rasterImage)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rasterImage | RasterImage | Rasterbilden. |

### Exempel

Laddar PNG-bilden, konvertering av den till TgaImage och sparar som en TGA-bild.

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

### Se även

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [TgaImage](../../tgaimage)
* namnutrymme [Aspose.Imaging.FileFormats.Tga](../../tgaimage)
* hopsättning [Aspose.Imaging](../../../)

---

## TgaImage(Stream) {#constructor_1}

Initierar en ny instans av[`TgaImage`](../../tgaimage) class.

```csharp
public TgaImage(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Streamen för att ladda en bild. |

### Se även

* class [TgaImage](../../tgaimage)
* namnutrymme [Aspose.Imaging.FileFormats.Tga](../../tgaimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
