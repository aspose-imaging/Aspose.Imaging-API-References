---
title: "VectorImage.GetEmbeddedImages"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة VectorImage. يحصل على الصور المضمنة"
type: docs
weight: 80
url: /ar/net/aspose.imaging/vectorimage/getembeddedimages/
---
## VectorImage.GetEmbeddedImages method

يحصل على الصور المضمنة.

```csharp
public virtual EmbeddedImage[] GetEmbeddedImages()
```

### قيمة الإرجاع

مصفوفة من الصور

## أمثلة

دعم استخراج الصور النقطية المضمنة من صورة متجهية

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

### انظر أيضًا

* class [EmbeddedImage](../../embeddedimage/)
* class [VectorImage](../)
* namespace [Aspose.Imaging](../../vectorimage/)
* assembly [Aspose.Imaging](../../../)


