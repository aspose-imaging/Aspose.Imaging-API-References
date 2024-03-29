---
title: GetEmbeddedImages
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ruft die eingebetteten Bilder ab.
type: docs
weight: 60
url: /de/net/aspose.imaging/vectorimage/getembeddedimages/
---
## VectorImage.GetEmbeddedImages method

Ruft die eingebetteten Bilder ab.

```csharp
public virtual EmbeddedImage[] GetEmbeddedImages()
```

### Rückgabewert

Reihe von Bildern

### Beispiele

Unterstützt das Extrahieren eingebetteter Rasterbilder aus einem Vektorbild

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

### Siehe auch

* class [EmbeddedImage](../../embeddedimage)
* class [VectorImage](../../vectorimage)
* namensraum [Aspose.Imaging](../../vectorimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
