---
title: GifBlocksRegistry.LoadBlockByFirstSupportedDescriptor
second_title: Aspose.Imaging for .NET API Reference
description: GifBlocksRegistry method. Loads gif block using first found opener suitable for the specified stream
type: docs
weight: 40
url: /net/aspose.imaging.fileformats.gif/gifblocksregistry/loadblockbyfirstsupporteddescriptor/
---
## GifBlocksRegistry.LoadBlockByFirstSupportedDescriptor method

Loads gif block using first found opener suitable for the specified *stream*.

```csharp
public static IGifBlock LoadBlockByFirstSupportedDescriptor(Stream stream, 
    IColorPalette containerPalette)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream. |
| containerPalette | IColorPalette | The container palette. |

### Return Value

The loaded gif block or null if no opener is found.

## Remarks

The first opener will be actually the last registered.

### See Also

* interface [IGifBlock](../../igifblock/)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [GifBlocksRegistry](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifblocksregistry/)
* assembly [Aspose.Imaging](../../../)


