---
title: ImageExportersRegistry.CreateFirstSupportedExporter
second_title: Aspose.Imaging for .NET API Reference
description: ImageExportersRegistry method. Creates the first found exporter suitable for the specified save options and image
type: docs
weight: 30
url: /net/aspose.imaging/imageexportersregistry/createfirstsupportedexporter/
---
## ImageExportersRegistry.CreateFirstSupportedExporter method

Creates the first found exporter suitable for the specified save options and image.

```csharp
public static IImageExporter CreateFirstSupportedExporter(Image image, ImageOptionsBase options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | Image | The image to export. |
| options | ImageOptionsBase | The save options to use for export. |

### Return Value

The exporter which supports the specified image and save options or null if no such exporter is found.

## Remarks

The first exporter will be actually the last registered.

### See Also

* interface [IImageExporter](../../iimageexporter/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* namespace [Aspose.Imaging](../../imageexportersregistry/)
* assembly [Aspose.Imaging](../../../)


