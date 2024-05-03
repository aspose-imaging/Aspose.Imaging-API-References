---
title: ImageLoadersRegistry.GetFirstSupportedDescriptorByFileFormat
second_title: Aspose.Imaging for .NET API Reference
description: ImageLoadersRegistry method. Gets the first supported file format by its type name
type: docs
weight: 50
url: /net/aspose.imaging/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/
---
## ImageLoadersRegistry.GetFirstSupportedDescriptorByFileFormat method

Gets the first supported file format by its type name.

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptorByFileFormat(FileFormat fileFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileFormat | FileFormat | The supported descriptor file format. |

### Return Value

The first found loader descriptor or null if not such descriptor is found.

## Remarks

The first loader descriptor will be actually the last registered.

### See Also

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* enum [FileFormat](../../fileformat/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.Imaging](../../imageloadersregistry/)
* assembly [Aspose.Imaging](../../../)


