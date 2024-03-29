---
title: Crop
second_title: Aspose.Imaging für .NET-API-Referenz
description: Bild zuschneiden.
type: docs
weight: 220
url: /de/net/aspose.imaging.fileformats.djvu/djvuimage/crop/
---
## Crop(Rectangle) {#crop}

Bild zuschneiden.

```csharp
public override void Crop(Rectangle rectangle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | Rectangle | Das Rechteck. |

### Beispiele

Das folgende Beispiel beschneidet ein DJVU-Bild. Der Zuschneidebereich wird über Aspose.Imaging.Rectangle angegeben.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // Bild zuschneiden. Der Zuschneidebereich ist der rechteckige zentrale Bereich des Bildes.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(djvuImage.Width / 4, djvuImage.Height / 4, djvuImage.Width / 2, djvuImage.Height / 2);
    djvuImage.Crop(area);

    // Speichern Sie das zugeschnittene Bild in PNG
    djvuImage.Save(dir + "sample.Crop.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Siehe auch

* struct [Rectangle](../../../aspose.imaging/rectangle)
* class [DjvuImage](../../djvuimage)
* namensraum [Aspose.Imaging.FileFormats.Djvu](../../djvuimage)
* Montage [Aspose.Imaging](../../../)

---

## Crop(int, int, int, int) {#crop_1}

Bild mit Verschiebungen zuschneiden.

```csharp
public override void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| leftShift | Int32 | Die Linksverschiebung. |
| rightShift | Int32 | Die richtige Verschiebung. |
| topShift | Int32 | Die Top-Schicht. |
| bottomShift | Int32 | Die untere Schicht. |

### Siehe auch

* class [DjvuImage](../../djvuimage)
* namensraum [Aspose.Imaging.FileFormats.Djvu](../../djvuimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
