---
title: Resize
second_title: Aspose.Imaging för .NET API-referens
description: Ändrar storlek på bilden.
type: docs
weight: 150
url: /sv/net/aspose.imaging.fileformats.wmf/wmfimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

Ändrar storlek på bilden.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | Int32 | Den nya bredden. |
| newHeight | Int32 | Den nya höjden. |
| resizeType | ResizeType | Ändra storlek. |

### Undantag

| undantag | skick |
| --- | --- |
| NotImplementedException |  |

### Exempel

Det här exemplet läser in en WMF-bild och ändrar storlek på den med olika storleksändringsmetoder.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Wmf.WmfImage image = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "sample.wmf"))
{
    // Skala upp 2 gånger med omsampling av närmaste granne.
    image.Resize(image.Width * 2, image.Height * 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
}

using (Aspose.Imaging.FileFormats.Wmf.WmfImage image = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "sample.wmf"))
{
    // Skala ner två gånger med omsampling av närmaste granne.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
}

using (Aspose.Imaging.FileFormats.Wmf.WmfImage image = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "sample.wmf"))
{
    // Skala upp 2 gånger med hjälp av bilinjär omsampling.
    image.Resize(image.Width * 2, image.Height * 2, Aspose.Imaging.ResizeType.BilinearResample);
}

using (Aspose.Imaging.FileFormats.Wmf.WmfImage image = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "sample.wmf"))
{
    // Skala ner med 2 gånger med bilinjär omsampling.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
}
```

### Se även

* enum [ResizeType](../../../aspose.imaging/resizetype)
* class [WmfImage](../../wmfimage)
* namnutrymme [Aspose.Imaging.FileFormats.Wmf](../../wmfimage)
* hopsättning [Aspose.Imaging](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Ändrar storlek på bilden.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | Int32 | Den nya bredden. |
| newHeight | Int32 | Den nya höjden. |
| settings | ImageResizeSettings | Ändra storleksinställningar. |

### Undantag

| undantag | skick |
| --- | --- |
| NotImplementedException |  |

### Se även

* class [ImageResizeSettings](../../../aspose.imaging/imageresizesettings)
* class [WmfImage](../../wmfimage)
* namnutrymme [Aspose.Imaging.FileFormats.Wmf](../../wmfimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
