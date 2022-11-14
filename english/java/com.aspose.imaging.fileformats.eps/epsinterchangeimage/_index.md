---
title: EpsInterchangeImage
second_title: Aspose.Imaging for Java API Reference
description: Class for Encapsulated PostScript Interchange format
type: docs
weight: 12
url: /java/com.aspose.imaging.fileformats.eps/epsinterchangeimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.fileformats.eps.EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage)
```
public class EpsInterchangeImage extends EpsImage
```

Class for Encapsulated PostScript Interchange format
## Methods

| Method | Description |
| --- | --- |
| [getEpsType()](#getEpsType--) | Gets EPS subtype value |
| [hasRasterPreview()](#hasRasterPreview--) | Gets a value indicating whether this instance has format-specific raster preview |
| [getRasterPreview()](#getRasterPreview--) | Gets b/w raster preview (if present) or null |
| [getPreviewWidth()](#getPreviewWidth--) | Gets the width of the preview image |
| [getPreviewHeight()](#getPreviewHeight--) | Gets the height of the preview image |
| [to_EpsInterchangeImage(EpsBinaryImage basicImage)](#to-EpsInterchangeImage-com.aspose.imaging.fileformats.eps.EpsBinaryImage-) | Performs an explicit conversion from `EpsBinaryImage` to `EpsInterchangeImage` |
| [convertToBinary()](#convertToBinary--) | Converts this instance to `EpsBinaryImage` |
### getEpsType() {#getEpsType--}
```
public int getEpsType()
```


Gets EPS subtype value

**Returns:**
int
### hasRasterPreview() {#hasRasterPreview--}
```
public boolean hasRasterPreview()
```


Gets a value indicating whether this instance has format-specific raster preview

**Returns:**
boolean - `true` if this instance has format-specific raster preview; otherwise, `false`.
### getRasterPreview() {#getRasterPreview--}
```
public RasterImage getRasterPreview()
```


Gets b/w raster preview (if present) or null

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - B/W raster preview
### getPreviewWidth() {#getPreviewWidth--}
```
public int getPreviewWidth()
```


Gets the width of the preview image

**Returns:**
int - The width of the preview image
### getPreviewHeight() {#getPreviewHeight--}
```
public int getPreviewHeight()
```


Gets the height of the preview image

**Returns:**
int - The height of the preview image
### to_EpsInterchangeImage(EpsBinaryImage basicImage) {#to-EpsInterchangeImage-com.aspose.imaging.fileformats.eps.EpsBinaryImage-}
```
public static EpsInterchangeImage to_EpsInterchangeImage(EpsBinaryImage basicImage)
```


Performs an explicit conversion from `EpsBinaryImage` to `EpsInterchangeImage`

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| basicImage | [EpsBinaryImage](../../com.aspose.imaging.fileformats.eps/epsbinaryimage) | The basic image |

**Returns:**
[EpsInterchangeImage](../../com.aspose.imaging.fileformats.eps/epsinterchangeimage) - The result of the conversion
### convertToBinary() {#convertToBinary--}
```
public EpsBinaryImage convertToBinary()
```


Converts this instance to `EpsBinaryImage`

**Returns:**
[EpsBinaryImage](../../com.aspose.imaging.fileformats.eps/epsbinaryimage) - Result as `EpsBinaryImage`
