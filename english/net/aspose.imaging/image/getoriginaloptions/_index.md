---
title: Image.GetOriginalOptions
second_title: Aspose.Imaging for .NET API Reference
description: Image method. Gets the options based on the original file settings. This can be helpful to keep bitdepth and other parameters of the original image unchanged. For example if we load a blackwhite PNG image with 1 bit per pixel and then save it using the Save method the output PNG image with 8bit per pixel will be produced. To avoid it and save PNG image with 1bit per pixel use this method to get corresponding saving options and pass them to the Save method as the second parameter
type: docs
weight: 190
url: /net/aspose.imaging/image/getoriginaloptions/
---
## Image.GetOriginalOptions method

Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../../datastreamsupporter/save/) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](../save/) method as the second parameter.

```csharp
public virtual ImageOptionsBase GetOriginalOptions()
```

### Return Value

The options based on the original file settings.

### See Also

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


