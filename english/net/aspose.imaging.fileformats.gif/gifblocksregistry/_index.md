---
title: Class GifBlocksRegistry
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Gif.GifBlocksRegistry class. Represents the gif blocks openers registry
type: docs
weight: 6790
url: /net/aspose.imaging.fileformats.gif/gifblocksregistry/
---
## GifBlocksRegistry class

Represents the gif blocks openers registry.

```csharp
public static class GifBlocksRegistry
```

## Properties

| Name | Description |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.imaging.fileformats.gif/gifblocksregistry/registereddescriptors/) { get; } | Gets the registered descriptors. |

## Methods

| Name | Description |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.imaging.fileformats.gif/gifblocksregistry/getfirstsupporteddescriptor/)(Stream) | Gets the first supported opener descriptor. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.imaging.fileformats.gif/gifblocksregistry/getfirstsupporteddescriptorbytypename/)(string) | Gets the first supported descriptor by its type name. |
| static [LoadBlockByFirstSupportedDescriptor](../../aspose.imaging.fileformats.gif/gifblocksregistry/loadblockbyfirstsupporteddescriptor/)(Stream, IColorPalette) | Loads gif block using first found opener suitable for the specified *stream*. |
| static [RegisterOpener](../../aspose.imaging.fileformats.gif/gifblocksregistry/registeropener/)(IGifBlockLoaderDescriptor) | Registers the opener. |
| static [UnregisterOpener](../../aspose.imaging.fileformats.gif/gifblocksregistry/unregisteropener/)(IGifBlockLoaderDescriptor) | Unregisters the opener. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Gif](../../aspose.imaging.fileformats.gif/)
* assembly [Aspose.Imaging](../../)


