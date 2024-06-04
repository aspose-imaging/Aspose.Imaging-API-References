---
title: IImageExporter
second_title: Aspose.Imaging for Java API Reference
description: The image exporter.
type: docs
weight: 132
url: /java/com.aspose.imaging/iimageexporter/
---```
public interface IImageExporter
```

The image exporter. Can export data from internal Aspose.Imaging format to a specified data format.
## Methods

| Method | Description |
| --- | --- |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase)](#export-com.aspose.imaging.Image-java.io.OutputStream-com.aspose.imaging.ImageOptionsBase-) | Exports the specified image data into specified data format. |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#export-com.aspose.imaging.Image-java.io.OutputStream-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-) | Exports the specified image data into specified data format. |
### export(Image image, OutputStream stream, ImageOptionsBase optionsBase) {#export-com.aspose.imaging.Image-java.io.OutputStream-com.aspose.imaging.ImageOptionsBase-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase)
```


Exports the specified image data into specified data format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | The image data to export. |
| stream | java.io.OutputStream | The stream to export data to. |
| optionsBase | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Options for image export |

### export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#export-com.aspose.imaging.Image-java.io.OutputStream-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Exports the specified image data into specified data format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | The image data to export. |
| stream | java.io.OutputStream | The stream to export data to. |
| optionsBase | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Options for image export |
| boundsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The bounds rectangle. |

