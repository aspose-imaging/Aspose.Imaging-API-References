---
title: DjvuImage.BinarizeFixed
second_title: Aspose.Imaging for .NET API Reference
description: DjvuImage method. Binarization with a predefined threshold simplifies complex images into binary representations where pixels are categorized as either black or white based on their intensity compared to a specified threshold value. This technique is commonly used in image processing to enhance clarity simplify analysis and prepare images for further processing steps such as optical character recognition OCR. By applying a fixed threshold you can quickly transform grayscale images into binary form making them easier to interpret and extract meaningful information from
type: docs
weight: 190
url: /net/aspose.imaging.fileformats.djvu/djvuimage/binarizefixed/
---
## DjvuImage.BinarizeFixed method

Binarization with a predefined threshold simplifies complex images into binary representations, where pixels are categorized as either black or white based on their intensity compared to a specified threshold value. This technique is commonly used in image processing to enhance clarity, simplify analysis, and prepare images for further processing steps such as optical character recognition (OCR). By applying a fixed threshold, you can quickly transform grayscale images into binary form, making them easier to interpret and extract meaningful information from.

```csharp
public override void BinarizeFixed(byte threshold)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threshold | Byte | Threshold value. If corresponding gray value of a pixel is greater than threshold, a value of 255 will be assigned to it, 0 otherwise. |

## Examples

The following example binarizes a DJVU image with the predefined threshold. Binarized images contain only 2 colors - black and white.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // Binarize the image with a threshold value of 127.
    // If a corresponding gray value of a pixel is greater than 127, a value of 255 will be assigned to it, 0 otherwise.
    djvuImage.BinarizeFixed(127);
    djvuImage.Save(dir + "sample.BinarizeFixed.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


