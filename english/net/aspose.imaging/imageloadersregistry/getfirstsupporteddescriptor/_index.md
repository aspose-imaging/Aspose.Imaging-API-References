---
title: ImageLoadersRegistry.GetFirstSupportedDescriptor
second_title: Aspose.Imaging for .NET API Reference
description: ImageLoadersRegistry method. Gets the fist found supported descriptor suitable for the specified stream and optionally the loadOptions
type: docs
weight: 40
url: /net/aspose.imaging/imageloadersregistry/getfirstsupporteddescriptor/
---
## ImageLoadersRegistry.GetFirstSupportedDescriptor method

Gets the fist found supported descriptor suitable for the specified *stream* and optionally the *loadOptions*.

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptor(Stream stream, 
    LoadOptions loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream. |
| loadOptions | LoadOptions | The load options. |

### Return Value

The loader descriptor which supports the specified *stream* and *loadOptions* or null if no such descriptor is found.

## Remarks

The first loader descriptor will be actually the last registered.

### See Also

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.Imaging](../../imageloadersregistry/)
* assembly [Aspose.Imaging](../../../)


