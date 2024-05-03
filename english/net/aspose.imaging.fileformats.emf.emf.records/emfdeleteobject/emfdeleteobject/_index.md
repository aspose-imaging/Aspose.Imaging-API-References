---
title: EmfDeleteObject.EmfDeleteObject
second_title: Aspose.Imaging for .NET API Reference
description: EmfDeleteObject constructor. Initializes a new instance of the EmfDeleteObject class
type: docs
weight: 10
url: /net/aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/emfdeleteobject/
---
## EmfDeleteObject(EmfRecord) {#constructor_1}

Initializes a new instance of the [`EmfDeleteObject`](../) class.

```csharp
public EmfDeleteObject(EmfRecord record)
```

| Parameter | Type | Description |
| --- | --- | --- |
| record | EmfRecord | The record. |

### See Also

* class [EmfRecord](../../emfrecord/)
* class [EmfDeleteObject](../)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../emfdeleteobject/)
* assembly [Aspose.Imaging](../../../)

---

## EmfDeleteObject() {#constructor}

Initializes a new instance of the [`EmfDeleteObject`](../) class.

```csharp
public EmfDeleteObject()
```

## Examples

The following example shows how set the background color for EMF. It actually puts a rectangle of the background color before drawing all other objects.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3280\\";
string inputFilePath = dir + "image1.emf";
string outputFilePath = dir + "ChangeBackground_" + "image1.emf";

using (Aspose.Imaging.FileFormats.Emf.MetaImage image = (Aspose.Imaging.FileFormats.Emf.MetaImage)Aspose.Imaging.Image.Load(inputFilePath))
{
    AddBackgroundRectangleEmf((Aspose.Imaging.FileFormats.Emf.EmfImage)image, Aspose.Imaging.Color.Blue);

    image.Save(outputFilePath);
}
    
/// <summary>
/// Helper method to change EMF background.
/// </summary>
public static void AddBackgroundRectangleEmf(Aspose.Imaging.FileFormats.Emf.EmfImage image, Aspose.Imaging.Color color)
{
    image.CacheData();
    if (image.Records.Count < 1)
    {
        return;
    }

    //Set Rectangle
    Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfRectangle rectangle = new Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfRectangle();
    rectangle.Box = image.Header.EmfHeader.Bounds;

    //Set Brush
    Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCreateBrushIndirect brush = new Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCreateBrushIndirect();
    brush.LogBrush = new Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfLogBrushEx();
    brush.LogBrush.Argb32ColorRef = color.ToArgb();

    // Object indexes start at 1; zero is reserved for references to the metafile itself, see
    // https://docs.microsoft.com/en-us/openspecs/windows_protocols/ms-emf/e4fa4e63-9096-4cdc-b776-85e2a1e4e1f4
    brush.IhBrush = 1;

    //Select brush
    Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSelectObject selectObject = new Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSelectObject();
    selectObject.ObjectHandle = 1;

    //Remove brush
    Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfDeleteObject deleteObject = new Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfDeleteObject();
    deleteObject.ObjectHandle = 1;

    //Add records
    image.Records.Insert(1, brush);
    image.Records.Insert(2, selectObject);
    image.Records.Insert(3, rectangle);
    image.Records.Insert(4, deleteObject);
}
```

### See Also

* class [EmfDeleteObject](../)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../emfdeleteobject/)
* assembly [Aspose.Imaging](../../../)


