---
title: ResizeHeightProportionally
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ändert die Breite proportional.
type: docs
weight: 340
url: /de/net/aspose.imaging.fileformats.tiff/tiffimage/resizeheightproportionally/
---
## TiffImage.ResizeHeightProportionally method

Ändert die Breite proportional.

```csharp
public override void ResizeHeightProportionally(int newHeight, ResizeType resizeType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newHeight | Int32 | Die neue Höhe. |
| resizeType | ResizeType | Art der Größenänderung. |

### Beispiele

In diesem Beispiel wird ein TIFF-Bild geladen und mithilfe verschiedener Methoden zur Größenänderung proportional in der Größe geändert. Es wird nur die Höhe angegeben, die Breite wird automatisch berechnet.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // Auf das Zweifache skalieren mit Nearest Neighbor Resampling.
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // Mit den Standardoptionen in PNG speichern.
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // Mit Nearest Neighbor Resampling um das Zweifache herunterskalieren.
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // Mit den Standardoptionen in PNG speichern.
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // Mit bilinearem Resampling um das Zweifache hochskalieren.
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // Mit den Standardoptionen in PNG speichern.
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // Mit bilinearem Resampling um das Zweifache herunterskalieren.
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // Mit den Standardoptionen in PNG speichern.
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Siehe auch

* enum [ResizeType](../../../aspose.imaging/resizetype)
* class [TiffImage](../../tiffimage)
* namensraum [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
