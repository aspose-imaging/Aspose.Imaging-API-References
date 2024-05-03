---
title: DjvuImage.DjvuImage
second_title: Aspose.Imaging for .NET API Reference
description: DjvuImage constructor. Start working with DjVu images by initializing a new instance of the DjvuImage class using a Stream parameter. Perfect for developers who want seamless integration of DjVu image processing into their projects
type: docs
weight: 10
url: /net/aspose.imaging.fileformats.djvu/djvuimage/djvuimage/
---
## DjvuImage(Stream) {#constructor}

Start working with DjVu images by initializing a new instance of the [`DjvuImage`](../) class using a Stream parameter. Perfect for developers who want seamless integration of DjVu image processing into their projects.

```csharp
public DjvuImage(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream. |

### Exceptions

| exception | condition |
| --- | --- |
| [DjvuImageException](../../../aspose.imaging.coreexceptions.imageformats/djvuimageexception/) | Stream is empty |

## Examples

This example shows how to load a DJVU image from a file stream.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a DJVU image from a file stream.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.djvu"))
{
    using (Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = new Aspose.Imaging.FileFormats.Djvu.DjvuImage(stream))
    {
        // Save each page as an individual PNG image.
        foreach (Aspose.Imaging.FileFormats.Djvu.DjvuPage djvuPage in djvuImage.Pages)
        {
            // Generate a file name based on the page number.
            string fileName = string.Format("sample.{0}.png", djvuPage.PageNumber);
            djvuPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

### See Also

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)

---

## DjvuImage(Stream, LoadOptions) {#constructor_1}

Start working with DjVu images seamlessly with this constructor, which initializes a new [`DjvuImage`](../) class instance using a Stream and LoadOptions parameters. Perfect for developers who want precise control over DjVu image loading options while maintaining simplicity and efficiency.

```csharp
public DjvuImage(Stream stream, LoadOptions loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to load from. |
| loadOptions | LoadOptions | The load options. |

### Exceptions

| exception | condition |
| --- | --- |
| [DjvuImageException](../../../aspose.imaging.coreexceptions.imageformats/djvuimageexception/) | Stream is empty |

## Examples

This example shows how to load a DJVU image from a file stream to stay within the specified memory limit.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a DJVU image from a file stream.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.djvu"))
{
    // The max allowed size for all internal buffers is 1MB.
    Aspose.Imaging.LoadOptions loadOptions = new Aspose.Imaging.LoadOptions();
    loadOptions.BufferSizeHint = 1 * 1024 * 1024;

    using (Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = new Aspose.Imaging.FileFormats.Djvu.DjvuImage(stream, loadOptions))
    {
        // Save each page as an individual PNG image.
        foreach (Aspose.Imaging.FileFormats.Djvu.DjvuPage djvuPage in djvuImage.Pages)
        {
            // Generate a file name based on the page number.
            string fileName = string.Format("sample.{0}.png", djvuPage.PageNumber);
            djvuPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

### See Also

* class [LoadOptions](../../../aspose.imaging/loadoptions/)
* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


