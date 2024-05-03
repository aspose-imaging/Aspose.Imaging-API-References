---
title: GifBlocksRegistry.GetFirstSupportedDescriptorByTypeName
second_title: Aspose.Imaging for .NET API Reference
description: GifBlocksRegistry method. Gets the first supported descriptor by its type name
type: docs
weight: 30
url: /net/aspose.imaging.fileformats.gif/gifblocksregistry/getfirstsupporteddescriptorbytypename/
---
## GifBlocksRegistry.GetFirstSupportedDescriptorByTypeName method

Gets the first supported descriptor by its type name.

```csharp
public static IGifBlockLoaderDescriptor GetFirstSupportedDescriptorByTypeName(
    string descriptorTypeName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| descriptorTypeName | String | The descriptor type name. |

### Return Value

The first found opener descriptor or null if not such descriptor is found.

## Remarks

The first opener descriptor will be actually the last registered.

### See Also

* interface [IGifBlockLoaderDescriptor](../../igifblockloaderdescriptor/)
* class [GifBlocksRegistry](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifblocksregistry/)
* assembly [Aspose.Imaging](../../../)


