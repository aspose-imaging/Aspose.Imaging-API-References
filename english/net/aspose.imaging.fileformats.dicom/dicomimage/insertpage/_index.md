---
title: DicomImage.InsertPage
second_title: Aspose.Imaging for .NET API Reference
description: DicomImage method. Insert a new page into the images page list at a specified index with this intuitive method. Ideal for developers seeking precise control over the arrangement of pages in multipage images ensuring seamless organization and customization of image content
type: docs
weight: 240
url: /net/aspose.imaging.fileformats.dicom/dicomimage/insertpage/
---
## DicomImage.InsertPage method

Insert a new page into the image's page list at a specified index with this intuitive method. Ideal for developers seeking precise control over the arrangement of pages in multi-page images, ensuring seamless organization and customization of image content.

```csharp
public DicomPage InsertPage(int pageIndex)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageIndex | Int32 | Index of the page. |

### Return Value

The newly created [`DicomPage`](../../dicompage/).

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *pageIndex* is out of range. |

## Examples

Create a multi-page Dicom image.

```csharp
[C#]

using (DicomImage image = (DicomImage)Image.Create(
        new DicomOptions() { Source = new StreamSource(new MemoryStream()) },
        100,
        100))
{
    // Draw something using vector graphics
    Graphics graphics = new Graphics(image);
    graphics.FillRectangle(new SolidBrush(Color.BlueViolet), image.Bounds);
    graphics.FillRectangle(new SolidBrush(Color.Aqua), 10, 20, 50, 20);
    graphics.FillEllipse(new SolidBrush(Color.Orange), 30, 50, 70, 30);

    // Save the pixels of the drawn image. They are now on the first page of the Dicom image.
    int[] pixels = image.LoadArgb32Pixels(image.Bounds);

    // Add a few pages after, making them darker
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.AddPage();
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(i * 30);
    }

    // Add a few pages in front of the main page, making them brighter
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.InsertPage(0);
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(-i * 30);
    }

    // Save the created multi-page image to the output file
    image.Save("MultiPage.dcm");
}
```

### See Also

* class [DicomPage](../../dicompage/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


