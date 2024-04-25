---
title: EmfPlusBitmapData
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusBitmapData object specifies a bitmap image with pixel data.
type: docs
weight: 15
url: /com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmapdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
```
public final class EmfPlusBitmapData extends EmfPlusBaseBitmapData
```

The EmfPlusBitmapData object specifies a bitmap image with pixel data.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusBitmapData()](#EmfPlusBitmapData--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getColors()](#getColors--) | Gets or sets the palette colors Colors (variable): An optional `EmfPlusPalette` object (section 2.2.2.28), which specifies the palette of colors used in the pixel data. |
| [setColors(EmfPlusPalette value)](#setColors-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-) | Gets or sets the palette colors Colors (variable): An optional `EmfPlusPalette` object (section 2.2.2.28), which specifies the palette of colors used in the pixel data. |
| [getPixelData()](#getPixelData--) | Gets or sets pixel data PixelData (variable): An array of bytes that specify the pixel data. |
| [setPixelData(byte[] value)](#setPixelData-byte---) | Gets or sets pixel data PixelData (variable): An array of bytes that specify the pixel data. |
### EmfPlusBitmapData() {#EmfPlusBitmapData--}
```
public EmfPlusBitmapData()
```


### getColors() {#getColors--}
```
public EmfPlusPalette getColors()
```


Gets or sets the palette colors Colors (variable): An optional `EmfPlusPalette` object (section 2.2.2.28), which specifies the palette of colors used in the pixel data. This field MUST be present if the I flag is set in the PixelFormat field of the `EmfPlusBitmap` object.

Value: The colors.

**Returns:**
[EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette)
### setColors(EmfPlusPalette value) {#setColors-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-}
```
public void setColors(EmfPlusPalette value)
```


Gets or sets the palette colors Colors (variable): An optional `EmfPlusPalette` object (section 2.2.2.28), which specifies the palette of colors used in the pixel data. This field MUST be present if the I flag is set in the PixelFormat field of the `EmfPlusBitmap` object.

Value: The colors.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette) |  |

### getPixelData() {#getPixelData--}
```
public byte[] getPixelData()
```


Gets or sets pixel data PixelData (variable): An array of bytes that specify the pixel data. The size and format of this data can be computed from fields in the EmfPlusBitmap object, including the pixel format from the `Consts.EmfPlusPixelFormat` enumeration (section 2.1.1.25).

Value: The pixel data.

**Returns:**
byte[]
### setPixelData(byte[] value) {#setPixelData-byte---}
```
public void setPixelData(byte[] value)
```


Gets or sets pixel data PixelData (variable): An array of bytes that specify the pixel data. The size and format of this data can be computed from fields in the EmfPlusBitmap object, including the pixel format from the `Consts.EmfPlusPixelFormat` enumeration (section 2.1.1.25).

Value: The pixel data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

