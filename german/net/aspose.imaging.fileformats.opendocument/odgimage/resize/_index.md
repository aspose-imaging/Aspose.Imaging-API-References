---
title: Resize
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ändert die Bildgröße.
type: docs
weight: 60
url: /de/net/aspose.imaging.fileformats.opendocument/odgimage/resize/
---
## Resize(int, int, ImageResizeSettings) {#resize_1}

Ändert die Bildgröße.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | Int32 | Die neue Breite. |
| newHeight | Int32 | Die neue Höhe. |
| settings | ImageResizeSettings | Die Größenänderungseinstellungen. |

### Siehe auch

* class [ImageResizeSettings](../../../aspose.imaging/imageresizesettings)
* class [OdgImage](../../odgimage)
* namensraum [Aspose.Imaging.FileFormats.OpenDocument](../../odgimage)
* Montage [Aspose.Imaging](../../../)

---

## Resize(int, int, ResizeType) {#resize_2}

Ändert die Bildgröße.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | Int32 | Die neue Breite. |
| newHeight | Int32 | Die neue Höhe. |
| resizeType | ResizeType | Der Größenänderungstyp. |

### Beispiele

In diesem Beispiel wird ein mehrseitiges ODG-Bild geladen und mit verschiedenen Methoden zur Größenänderung in der Größe angepasst.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.OpenDocument.OdgImage image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
{
    // Auf das Zweifache skalieren mit Nearest Neighbor Resampling.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // Mit Standardoptionen in PNG speichern.
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.OpenDocument.OdgImage image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
{
    // Mit Nearest Neighbor Resampling um das Zweifache herunterskalieren.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // Mit Standardoptionen in PNG speichern.
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.OpenDocument.OdgImage image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
{
    // Mit bilinearem Resampling um das Zweifache hochskalieren.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // Mit Standardoptionen in PNG speichern.
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.OpenDocument.OdgImage image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
{
    // Mit bilinearem Resampling um das Zweifache herunterskalieren.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // Mit Standardoptionen in PNG speichern.
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Siehe auch

* enum [ResizeType](../../../aspose.imaging/resizetype)
* class [OdgImage](../../odgimage)
* namensraum [Aspose.Imaging.FileFormats.OpenDocument](../../odgimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
