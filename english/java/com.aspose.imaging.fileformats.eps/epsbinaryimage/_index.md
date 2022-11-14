---
title: EpsBinaryImage
second_title: Aspose.Imaging for Java API Reference
description: Class for Encapsulated PostScript format with binary header
type: docs
weight: 10
url: /java/com.aspose.imaging.fileformats.eps/epsbinaryimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.fileformats.eps.EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage)
```
public class EpsBinaryImage extends EpsImage
```

Class for Encapsulated PostScript format with binary header
## Methods

| Method | Description |
| --- | --- |
| [getEpsType()](#getEpsType--) | Gets EPS subtype value |
| [hasRasterPreview()](#hasRasterPreview--) | Gets a value indicating whether this instance has format-specific raster preview |
| [getWmfPreview()](#getWmfPreview--) | Gets the WMF preview. |
| [getTiffPreview()](#getTiffPreview--) | Gets the TIFF preview. |
| [to_EpsBinaryImage(EpsInterchangeImage basicImage)](#to-EpsBinaryImage-com.aspose.imaging.fileformats.eps.EpsInterchangeImage-) | Performs an explicit conversion from `EpsInterchangeImage` to `EpsBinaryImage` |
| [convertToInterchange()](#convertToInterchange--) | Converts this instance to `EpsInterchangeImage` |
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
### getWmfPreview() {#getWmfPreview--}
```
public WmfImage getWmfPreview()
```


Gets the WMF preview.

**Returns:**
[WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) - The WMF preview.
### getTiffPreview() {#getTiffPreview--}
```
public TiffImage getTiffPreview()
```


Gets the TIFF preview.

**Returns:**
[TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage) - The TIFF preview.
### to_EpsBinaryImage(EpsInterchangeImage basicImage) {#to-EpsBinaryImage-com.aspose.imaging.fileformats.eps.EpsInterchangeImage-}
```
public static EpsBinaryImage to_EpsBinaryImage(EpsInterchangeImage basicImage)
```


Performs an explicit conversion from `EpsInterchangeImage` to `EpsBinaryImage`

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| basicImage | [EpsInterchangeImage](../../com.aspose.imaging.fileformats.eps/epsinterchangeimage) | The basic image |

**Returns:**
[EpsBinaryImage](../../com.aspose.imaging.fileformats.eps/epsbinaryimage) - The result of the conversion
### convertToInterchange() {#convertToInterchange--}
```
public EpsInterchangeImage convertToInterchange()
```


Converts this instance to `EpsInterchangeImage`

**Returns:**
[EpsInterchangeImage](../../com.aspose.imaging.fileformats.eps/epsinterchangeimage) - Result as `EpsInterchangeImage`
