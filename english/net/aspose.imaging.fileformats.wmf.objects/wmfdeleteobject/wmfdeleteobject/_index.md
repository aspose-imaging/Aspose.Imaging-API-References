---
title: WmfDeleteObject.WmfDeleteObject
second_title: Aspose.Imaging for .NET API Reference
description: WmfDeleteObject constructor. Initializes a new instance of the WmfDeleteObject class
type: docs
weight: 10
url: /net/aspose.imaging.fileformats.wmf.objects/wmfdeleteobject/wmfdeleteobject/
---
## WmfDeleteObject(WmfGraphicObject) {#constructor_1}

Initializes a new instance of the [`WmfDeleteObject`](../) class.

```csharp
public WmfDeleteObject(WmfGraphicObject deletedObject)
```

| Parameter | Type | Description |
| --- | --- | --- |
| deletedObject | WmfGraphicObject | The deleted object. |

### See Also

* class [WmfGraphicObject](../../wmfgraphicobject/)
* class [WmfDeleteObject](../)
* namespace [Aspose.Imaging.FileFormats.Wmf.Objects](../../wmfdeleteobject/)
* assembly [Aspose.Imaging](../../../)

---

## WmfDeleteObject() {#constructor}

Initializes a new instance of the [`WmfDeleteObject`](../) class.

```csharp
public WmfDeleteObject()
```

## Examples

The following example shows how set the background color for WMF. Actually it draws a rectangle of the background color before drawing all other objects.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3280\\";
string inputFilePath = dir + "image2.wmf";
string outputFilePath = dir + "ChangeBackground_" + "image2.wmf";

using (Aspose.Imaging.FileFormats.Emf.MetaImage image = (Aspose.Imaging.FileFormats.Emf.MetaImage)Aspose.Imaging.Image.Load(inputFilePath))
{
    AddBackgroundRectangleWmf((Aspose.Imaging.FileFormats.Wmf.WmfImage)image, Aspose.Imaging.Color.Blue);
    image.Save(outputFilePath);
}

/// <summary>
/// Helper method to change WMF background. 
/// </summary>
public static void AddBackgroundRectangleWmf(Aspose.Imaging.FileFormats.Wmf.WmfImage image, Aspose.Imaging.Color color)
{
    image.CacheData();
    if (image.Records.Count < 1)
    {
        return;
    }

    //Set Rectangle
    Aspose.Imaging.FileFormats.Wmf.Objects.WmfRectangle rectangle = new Aspose.Imaging.FileFormats.Wmf.Objects.WmfRectangle();
    rectangle.Rectangle = image.FrameBounds;

    //Set Brush
    Aspose.Imaging.FileFormats.Wmf.Objects.WmfCreateBrushInDirect brush = new Aspose.Imaging.FileFormats.Wmf.Objects.WmfCreateBrushInDirect();
    brush.LogBrush = new Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfLogBrushEx();
    brush.LogBrush.Argb32ColorRef = color.ToArgb();

    //Select brush
    Aspose.Imaging.FileFormats.Wmf.Objects.WmfSelectObject selectObject = new Aspose.Imaging.FileFormats.Wmf.Objects.WmfSelectObject(brush);

    //Remove brush
    Aspose.Imaging.FileFormats.Wmf.Objects.WmfDeleteObject deleteObject = new Aspose.Imaging.FileFormats.Wmf.Objects.WmfDeleteObject(brush);

    //Add records
    image.Records.Insert(0, brush);
    image.Records.Insert(1, selectObject);
    image.Records.Insert(2, rectangle);
    image.Records.Insert(3, deleteObject);
}
```

### See Also

* class [WmfDeleteObject](../)
* namespace [Aspose.Imaging.FileFormats.Wmf.Objects](../../wmfdeleteobject/)
* assembly [Aspose.Imaging](../../../)


