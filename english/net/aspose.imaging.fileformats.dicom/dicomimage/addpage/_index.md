---
title: DicomImage.AddPage
second_title: Aspose.Imaging for .NET API Reference
description: DicomImage method. Expand your image collection by adding a new page with this intuitive method. Ideal for developers seeking to dynamically append pages to multipage images ensuring seamless expansion and organization of image content
type: docs
weight: 100
url: /net/aspose.imaging.fileformats.dicom/dicomimage/addpage/
---
## AddPage(RasterImage) {#addpage_1}

Expand your image collection by adding a new page with this intuitive method. Ideal for developers seeking to dynamically append pages to multi-page images, ensuring seamless expansion and organization of image content.

```csharp
public void AddPage(RasterImage page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | RasterImage | The page to add. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *page* is null. |

### See Also

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)

---

## AddPage() {#addpage}

Append a new page to the end of the image's page list with this straightforward method. Ideal for developers seeking to dynamically expand multi-page images, ensuring seamless integration and organization of image content.

```csharp
public DicomPage AddPage()
```

### Return Value

The newly created [`DicomPage`](../../dicompage/).

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


