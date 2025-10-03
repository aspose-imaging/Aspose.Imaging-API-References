---
title: Class ImageExportersRegistry
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.ImageExportersRegistry class. Represents the image exporters registry
type: docs
weight: 9860
url: /net/aspose.imaging/imageexportersregistry/
---
## ImageExportersRegistry class

Represents the image exporters registry.

```csharp
public static class ImageExportersRegistry
```

## Properties

| Name | Description |
| --- | --- |
| static [RegisteredExporterDescriptors](../../aspose.imaging/imageexportersregistry/registeredexporterdescriptors/) { get; } | Gets the registered exporter descriptors. |
| static [RegisteredFormats](../../aspose.imaging/imageexportersregistry/registeredformats/) { get; } | Gets the registered export formats. |

## Methods

| Name | Description |
| --- | --- |
| static [CreateFirstSupportedExporter](../../aspose.imaging/imageexportersregistry/createfirstsupportedexporter/)(Image, ImageOptionsBase) | Creates the first found exporter suitable for the specified save options and image. |
| static [GetFirstSupportedDescriptor](../../aspose.imaging/imageexportersregistry/getfirstsupporteddescriptor/)(Image, ImageOptionsBase) | Gets the fist found supported descriptor suitable for the specified save options and image. |
| static [Register](../../aspose.imaging/imageexportersregistry/register/)(IImageExporterDescriptor) | Registers the specified image exporter descriptor. |
| static [RegisterExporter](../../aspose.imaging/imageexportersregistry/registerexporter/)(IImageExporterDescriptor) | Registers the exporter. |
| static [UnregisterExporter](../../aspose.imaging/imageexportersregistry/unregisterexporter/)(IImageExporterDescriptor) | Unregisters the exporter. |

### See Also

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


