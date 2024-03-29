---
title: GetEmbeddedImages
second_title: Aspose.Imaging för .NET API-referens
description: Hämtar de inbäddade bilderna.
type: docs
weight: 60
url: /sv/net/aspose.imaging/vectorimage/getembeddedimages/
---
## VectorImage.GetEmbeddedImages method

Hämtar de inbäddade bilderna.

```csharp
public virtual EmbeddedImage[] GetEmbeddedImages()
```

### Returvärde

En rad bilder

### Exempel

Stöd extrahera inbäddade rasterbilder från en vektorbild

```csharp
[C#]

var inputFileName = "test.cdr";
using (var image = Aspose.Imaging.Image.Load(inputFileName))        
{
    var vectorImage = ((Aspose.Imaging.VectorImage) image);
    var images = vectorImage.GetEmbeddedImages();
    var i = 0;
    foreach (var im in images)
    {
        var outFileName = string.Format("image{0}.png", i++);
        using (im)
        {
            im.Image.Save(outFileName, new PngOptions());
        }
    }
}
```

### Se även

* class [EmbeddedImage](../../embeddedimage)
* class [VectorImage](../../vectorimage)
* namnutrymme [Aspose.Imaging](../../vectorimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
