---
title: ResizeCanvas
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ändert die Leinwandgröße.
type: docs
weight: 50
url: /de/net/aspose.imaging.fileformats.emf/metaimage/resizecanvas/
---
## MetaImage.ResizeCanvas method

Ändert die Leinwandgröße.

```csharp
public abstract void ResizeCanvas(Rectangle newRectangle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newRectangle | Rectangle | Das neue Rechteck. |

### Beispiele

Das folgende Beispiel zeigt, wie Sie einen Rahmen mit den angegebenen Rändern um eine Metadatei (WMF und EMF) hinzufügen.

```csharp
[C#]

int borderLeft = 50;
int borderTop = 50;
int borderRight = 50;
int borderBottom = 50;

string dir = "c:\\aspose.imaging\\issues\\net\\3280\\";
string[] fileNames = new[] { "image1.emf", "image2.wmf" };
foreach (string fileName in fileNames)
{
    string inputFilePath = dir + fileName;
    string outputFilePath = dir + "AddBorder_" + fileName;
    using (Aspose.Imaging.FileFormats.Emf.MetaImage image = (Aspose.Imaging.FileFormats.Emf.MetaImage)Aspose.Imaging.Image.Load(inputFilePath))
    {
        image.ResizeCanvas(new Aspose.Imaging.Rectangle(-borderLeft, -borderTop, image.Width + borderLeft + borderRight, image.Height + borderTop + borderBottom));
        image.Save(outputFilePath);
    }
}
```

### Siehe auch

* struct [Rectangle](../../../aspose.imaging/rectangle)
* class [MetaImage](../../metaimage)
* namensraum [Aspose.Imaging.FileFormats.Emf](../../metaimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
