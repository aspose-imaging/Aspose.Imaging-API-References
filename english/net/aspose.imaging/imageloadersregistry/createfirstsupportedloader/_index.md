---
title: CreateFirstSupportedLoader
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 30
url: /net/aspose.imaging/imageloadersregistry/createfirstsupportedloader/
---
## ImageLoadersRegistry.CreateFirstSupportedLoader method

Creates the first found loader suitable for the specified *stream* and optionally the *loadOptions*.

```csharp
public static IImageLoader CreateFirstSupportedLoader(Stream stream, LoadOptions loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream. |
| loadOptions | LoadOptions | The load options. |

### Return Value

The loader which supports the specified *stream* and *loadOptions* or null if no such loader is found.

### Remarks

The first loader will be actually the last registered.

### See Also

* interface [IImageLoader](../../iimageloader)
* class [LoadOptions](../../loadoptions)
* class [ImageLoadersRegistry](../../imageloadersregistry)
* namespace [Aspose.Imaging](../../imageloadersregistry)
* assembly [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
