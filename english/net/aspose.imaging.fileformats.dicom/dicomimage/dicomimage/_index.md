---
title: DicomImage.DicomImage
second_title: Aspose.Imaging for .NET API Reference
description: DicomImage constructor. Initialize a fresh instance of the DicomImage class effortlessly with this constructor utilizing dicomOptions parameters. Perfect for developers looking to dive into DicomImage objects swiftly and efficiently in their projects
type: docs
weight: 10
url: /net/aspose.imaging.fileformats.dicom/dicomimage/dicomimage/
---
## DicomImage(DicomOptions, int, int) {#constructor}

Initialize a fresh instance of the DicomImage class effortlessly with this constructor, utilizing dicomOptions parameters. Perfect for developers looking to dive into [`DicomImage`](../) objects swiftly and efficiently in their projects.

```csharp
public DicomImage(DicomOptions dicomOptions, int width, int height)
```

| Parameter | Type | Description |
| --- | --- | --- |
| dicomOptions | DicomOptions | The dicom options. |
| width | Int32 | The width. |
| height | Int32 | The height. |

### See Also

* class [DicomOptions](../../../aspose.imaging.imageoptions/dicomoptions/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)

---

## DicomImage(Stream, LoadOptions) {#constructor_2}

Initiate a new instance of the DicomImage class smoothly by employing a stream and loadOptions parameters in this constructor. Ideal for developers eager to start working with [`DicomImage`](../) objects promptly and effectively in their projects.

```csharp
public DicomImage(Stream stream, LoadOptions loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream. |
| loadOptions | LoadOptions | The load options. |

## Examples

This example shows how to load a DICOM image from a file stream to stay within the specified memory limit.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a DICOM image from a file stream.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "multiframe.dicom"))
{
    // The max allowed size for all internal buffers is 256KB.
    Aspose.Imaging.LoadOptions loadOptions = new Aspose.Imaging.LoadOptions();
    loadOptions.BufferSizeHint = 256 * 1024;

    using (Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = new Aspose.Imaging.FileFormats.Dicom.DicomImage(stream, loadOptions))
    {
        // Save each page as an individual PNG image.
        foreach (Aspose.Imaging.FileFormats.Dicom.DicomPage dicomPage in dicomImage.DicomPages)
        {
            // Generate a file name based on the page index.
            string fileName = string.Format("multiframe.{0}.png", dicomPage.Index);

            // A DICOM page is a raster image, so all allowed operations with a raster image are applicable to a DICOM page.
            dicomPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

### See Also

* class [LoadOptions](../../../aspose.imaging/loadoptions/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)

---

## DicomImage(Stream) {#constructor_1}

Create a new instance of the DicomImage class by utilizing a stream parameter in this constructor. Perfect for developers seeking a streamlined way to initialize [`DicomImage`](../) objects from existing data streams in their projects.

```csharp
public DicomImage(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream. |

## Examples

This example shows how to load a DICOM image from a file stream.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a DICOM image from a file stream.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.dicom"))
{
    using (Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = new Aspose.Imaging.FileFormats.Dicom.DicomImage(stream))
    {
        // Save each page as an individual PNG image.                    
        foreach (Aspose.Imaging.FileFormats.Dicom.DicomPage dicomPage in dicomImage.DicomPages)
        {
            // Generate a file name based on the page index.
            string fileName = string.Format("sample.{0}.png", dicomPage.Index);

            // A DICOM page is a raster image, so all allowed operations with a raster image are applicable to a DICOM page.
            dicomPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

### See Also

* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


