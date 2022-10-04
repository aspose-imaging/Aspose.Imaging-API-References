---
title: Resize
second_title: Aspose.Imaging för .NET API-referens
description: Ändrar storlek på bilden.
type: docs
weight: 60
url: /sv/net/aspose.imaging.fileformats.opendocument/odgimage/resize/
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

### Se även

* class [ImageResizeSettings](../../../aspose.imaging/imageresizesettings)
* class [OdgImage](../../odgimage)
* namnutrymme [Aspose.Imaging.FileFormats.OpenDocument](../../odgimage)
* hopsättning [Aspose.Imaging](../../../)

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

### Exempel

Det här exemplet läser in en ODG-bild med flera sidor och ändrar storleken på den med olika storleksändringsmetoder.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.OpenDocument.OdgImage image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
{
    // Skala upp 2 gånger med omsampling av närmaste granne.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // Spara till PNG med standardalternativ.
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.OpenDocument.OdgImage image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
{
    // Skala ner två gånger med omsampling av närmaste granne.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // Spara till PNG med standardalternativ.
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.OpenDocument.OdgImage image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
{
    // Skala upp 2 gånger med hjälp av bilinjär omsampling.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // Spara till PNG med standardalternativ.
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.OpenDocument.OdgImage image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
{
    // Skala ner med 2 gånger med bilinjär omsampling.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // Spara till PNG med standardalternativ.
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Se även

* enum [ResizeType](../../../aspose.imaging/resizetype)
* class [OdgImage](../../odgimage)
* namnutrymme [Aspose.Imaging.FileFormats.OpenDocument](../../odgimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->