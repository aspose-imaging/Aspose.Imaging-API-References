---
title: Class ImageLoadersRegistry
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.ImageLoadersRegistry class. Represents the image loaders registry
type: docs
weight: 10140
url: /net/aspose.imaging/imageloadersregistry/
---
## ImageLoadersRegistry class

Represents the image loaders registry.

```csharp
public static class ImageLoadersRegistry
```

## Properties

| Name | Description |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.imaging/imageloadersregistry/registereddescriptors/) { get; } | Gets the registered descriptors. |
| static [RegisteredFormats](../../aspose.imaging/imageloadersregistry/registeredformats/) { get; } | Gets the registered image loading formats. |

## Methods

| Name | Description |
| --- | --- |
| static [CreateFirstSupportedLoader](../../aspose.imaging/imageloadersregistry/createfirstsupportedloader/)(Stream, LoadOptions) | Creates the first found loader suitable for the specified *stream* and optionally the *loadOptions*. |
| static [GetFirstSupportedDescriptor](../../aspose.imaging/imageloadersregistry/getfirstsupporteddescriptor/)(Stream, LoadOptions) | Gets the fist found supported descriptor suitable for the specified *stream* and optionally the *loadOptions*. |
| static [GetFirstSupportedDescriptorByFileFormat](../../aspose.imaging/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/)(FileFormat) | Gets the first supported file format by its type name. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.imaging/imageloadersregistry/getfirstsupporteddescriptorbytypename/)(string) | Gets the first supported descriptor by its type name. |
| static [Register](../../aspose.imaging/imageloadersregistry/register/)(IImageLoaderDescriptor) | Registers the specified image loader descriptor. |
| static [RegisterLoader](../../aspose.imaging/imageloadersregistry/registerloader/)(IImageLoaderDescriptor) | Registers the loader. |
| static [UnregisterLoader](../../aspose.imaging/imageloadersregistry/unregisterloader/)(IImageLoaderDescriptor) | Unregisters the loader. |

### See Also

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


