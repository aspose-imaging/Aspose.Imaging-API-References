---
title: ImageLoadersRegistry.GetFirstSupportedDescriptorByTypeName
second_title: Aspose.Imaging for .NET API Reference
description: ImageLoadersRegistry method. Gets the first supported descriptor by its type name
type: docs
weight: 60
url: /net/aspose.imaging/imageloadersregistry/getfirstsupporteddescriptorbytypename/
---
## ImageLoadersRegistry.GetFirstSupportedDescriptorByTypeName method

Gets the first supported descriptor by its type name.

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptorByTypeName(
    string descriptorTypeName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| descriptorTypeName | String | The descriptor type name. |

### Return Value

The first found loader descriptor or null if not such descriptor is found.

## Remarks

The first loader descriptor will be actually the last registered.

### See Also

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.Imaging](../../imageloadersregistry/)
* assembly [Aspose.Imaging](../../../)


