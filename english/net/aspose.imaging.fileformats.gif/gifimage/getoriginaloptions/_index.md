---
title: GifImage.GetOriginalOptions
second_title: Aspose.Imaging for .NET API Reference
description: GifImage method. Retrieve the original file settingsbased options crucial for maintaining fidelity and consistency in image processing and manipulation. This method allows seamless integration of filespecific parameters into subsequent operations ensuring accurate rendition and adherence to the images inherent characteristics. This can be helpful to keep bitdepth and other parameters of the original image unchanged. For example if we load a blackwhite PNG image with 1 bit per pixel and then save it using the Save method the output PNG image with 8bit per pixel will be produced. To avoid it and save PNG image with 1bit per pixel use this method to get corresponding saving options and pass them to the Save method as the second parameter
type: docs
weight: 310
url: /net/aspose.imaging.fileformats.gif/gifimage/getoriginaloptions/
---
## GifImage.GetOriginalOptions method

Retrieve the original file settings-based options, crucial for maintaining fidelity and consistency in image processing and manipulation. This method allows seamless integration of file-specific parameters into subsequent operations, ensuring accurate rendition and adherence to the image's inherent characteristics. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../../../aspose.imaging/datastreamsupporter/save/) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](../../../aspose.imaging/image/save/) method as the second parameter.

```csharp
public override ImageOptionsBase GetOriginalOptions()
```

### Return Value

The options based on the original file settings.

### See Also

* class [ImageOptionsBase](../../../aspose.imaging/imageoptionsbase/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


