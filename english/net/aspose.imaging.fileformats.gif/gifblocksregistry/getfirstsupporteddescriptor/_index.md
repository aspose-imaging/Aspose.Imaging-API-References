---
title: GetFirstSupportedDescriptor
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 20
url: /net/aspose.imaging.fileformats.gif/gifblocksregistry/getfirstsupporteddescriptor/
---
## GifBlocksRegistry.GetFirstSupportedDescriptor method

Gets the first supported opener descriptor.

```csharp
public static IGifBlockLoaderDescriptor GetFirstSupportedDescriptor(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream. |

### Return Value

The gif block opener descriptor or null if no opener descriptor supported for such stream.

### Remarks

The first opener will be actually the last registered.

### See Also

* interface [IGifBlockLoaderDescriptor](../../igifblockloaderdescriptor)
* class [GifBlocksRegistry](../../gifblocksregistry)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifblocksregistry)
* assembly [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
