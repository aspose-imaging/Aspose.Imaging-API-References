---
title: IImageExporterDescriptor
second_title: Aspose.Imaging for Java API Reference
description: Represents the image exporter descriptor.
type: docs
weight: 132
url: /java/com.aspose.imaging/iimageexporterdescriptor/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IImageDescriptor](../../com.aspose.imaging/iimagedescriptor)
```
public interface IImageExporterDescriptor extends IImageDescriptor
```

Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance in memory and multithreading issues.
## Methods

| Method | Description |
| --- | --- |
| [canExport(Image image, ImageOptionsBase optionsBase)](#canExport-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | Determines whether image exporter can export the specified image to the specified image format specified by save options. |
| [createInstance()](#createInstance--) | Creates a new exporter instance. |
### canExport(Image image, ImageOptionsBase optionsBase) {#canExport-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public abstract boolean canExport(Image image, ImageOptionsBase optionsBase)
```


Determines whether image exporter can export the specified image to the specified image format specified by save options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | The image to export. |
| optionsBase | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | The options base. |

**Returns:**
boolean - `true` if exporter created by this descriptor can export the specified image to the specified file format; otherwise, `false`.
### createInstance() {#createInstance--}
```
public abstract IImageExporter createInstance()
```


Creates a new exporter instance.

**Returns:**
[IImageExporter](../../com.aspose.imaging/iimageexporter) - A new exporter instance.
