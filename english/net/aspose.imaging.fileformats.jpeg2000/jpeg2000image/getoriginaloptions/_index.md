---
title: Jpeg2000Image.GetOriginalOptions
second_title: Aspose.Imaging for .NET API Reference
description: Jpeg2000Image method. Retrieve the image options based on the original file settings. This method is beneficial for maintaining the bitdepth and other parameters of the original image ensuring consistency and preserving the integrity of the image data. Accessing these options facilitates seamless handling and processing of the image while retaining its original characteristics. For example if we load a blackwhite PNG image with 1 bit per pixel and then save it using the Save method the output PNG image with 8bit per pixel will be produced. To avoid it and save PNG image with 1bit per pixel use this method to get corresponding saving options and pass them to the Save method as the second parameter
type: docs
weight: 120
url: /net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/getoriginaloptions/
---
## Jpeg2000Image.GetOriginalOptions method

Retrieve the image options based on the original file settings. This method is beneficial for maintaining the bit-depth and other parameters of the original image, ensuring consistency and preserving the integrity of the image data. Accessing these options facilitates seamless handling and processing of the image while retaining its original characteristics. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../../../aspose.imaging/datastreamsupporter/save/) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](../../../aspose.imaging/image/save/) method as the second parameter.

```csharp
public override ImageOptionsBase GetOriginalOptions()
```

### Return Value

The options based on the original file settings.

### See Also

* class [ImageOptionsBase](../../../aspose.imaging/imageoptionsbase/)
* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)


