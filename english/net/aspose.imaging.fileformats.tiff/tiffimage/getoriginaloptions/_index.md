---
title: TiffImage.GetOriginalOptions
second_title: Aspose.Imaging for .NET API Reference
description: TiffImage method. Retrieve options derived from the original file settings facilitating seamless preservation of key parameters such as bitdepth and other essential attributes of the original image. Utilize this method to maintain fidelity and consistency in image processing tasks ensuring optimal results without unnecessary alterations. For example if we load a blackwhite PNG image with 1 bit per pixel and then save it using the Save method the output PNG image with 8bit per pixel will be produced. To avoid it and save PNG image with 1bit per pixel use this method to get corresponding saving options and pass them to the Save method as the second parameter
type: docs
weight: 260
url: /net/aspose.imaging.fileformats.tiff/tiffimage/getoriginaloptions/
---
## TiffImage.GetOriginalOptions method

Retrieve options derived from the original file settings, facilitating seamless preservation of key parameters such as bit-depth and other essential attributes of the original image. Utilize this method to maintain fidelity and consistency in image processing tasks, ensuring optimal results without unnecessary alterations. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../../../aspose.imaging/datastreamsupporter/save/) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](../../../aspose.imaging/image/save/) method as the second parameter.

```csharp
public override ImageOptionsBase GetOriginalOptions()
```

### Return Value

The options based on the original file settings.

### Exceptions

| exception | condition |
| --- | --- |
| [TiffImageException](../../../aspose.imaging.coreexceptions.imageformats/tiffimageexception/) | There is no original options that can be extracted from image |

### See Also

* class [ImageOptionsBase](../../../aspose.imaging/imageoptionsbase/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


