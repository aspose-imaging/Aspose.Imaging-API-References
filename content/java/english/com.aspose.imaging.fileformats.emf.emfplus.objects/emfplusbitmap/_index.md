---
title: EmfPlusBitmap
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusBitmap object specifies a bitmap that contains a graphics image.
type: docs
weight: 14
url: /com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata)
```
public final class EmfPlusBitmap extends EmfPlusBaseImageData
```

The EmfPlusBitmap object specifies a bitmap that contains a graphics image.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusBitmap()](#EmfPlusBitmap--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getBitmapData()](#getBitmapData--) | Gets or sets bitmap data BitmapData (variable): Variable-length data that defines the bitmap data object specified in the Type field. |
| [setBitmapData(EmfPlusBaseBitmapData value)](#setBitmapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData-) | Gets or sets bitmap data BitmapData (variable): Variable-length data that defines the bitmap data object specified in the Type field. |
| [getHeight()](#getHeight--) | Gets or sets bitmap height Height (4 bytes): A 32-bit signed integer that specifies the height in pixels of the area occupied by the bitmap. |
| [setHeight(int value)](#setHeight-int-) | Gets or sets bitmap height Height (4 bytes): A 32-bit signed integer that specifies the height in pixels of the area occupied by the bitmap. |
| [getPixelFormat()](#getPixelFormat--) | Gets or sets pixel format PixelFormat (4 bytes): A 32-bit unsigned integer that specifies the format of the pixels that make up the bitmap image. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Gets or sets pixel format PixelFormat (4 bytes): A 32-bit unsigned integer that specifies the format of the pixels that make up the bitmap image. |
| [getStride()](#getStride--) | Gets or sets stride of the image Stride (4 bytes): A 32-bit signed integer that specifies the byte offset between the beginning of one scan-line and the next. |
| [setStride(int value)](#setStride-int-) | Gets or sets stride of the image Stride (4 bytes): A 32-bit signed integer that specifies the byte offset between the beginning of one scan-line and the next. |
| [getType()](#getType--) | Gets or sets type of the image Type (4 bytes): A 32-bit unsigned integer that specifies the type of data in the BitmapData field. |
| [setType(int value)](#setType-int-) | Gets or sets type of the image Type (4 bytes): A 32-bit unsigned integer that specifies the type of data in the BitmapData field. |
| [getWidth()](#getWidth--) | Gets or sets image Width Width (4 bytes): A 32-bit signed integer that specifies the width in pixels of the area occupied by the bitmap. |
| [setWidth(int value)](#setWidth-int-) | Gets or sets image Width Width (4 bytes): A 32-bit signed integer that specifies the width in pixels of the area occupied by the bitmap. |
### EmfPlusBitmap() {#EmfPlusBitmap--}
```
public EmfPlusBitmap()
```


### getBitmapData() {#getBitmapData--}
```
public EmfPlusBaseBitmapData getBitmapData()
```


Gets or sets bitmap data BitmapData (variable): Variable-length data that defines the bitmap data object specified in the Type field. The content and format of the data can be different for every bitmap type.

Value: The bitmap data.

**Returns:**
[EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
### setBitmapData(EmfPlusBaseBitmapData value) {#setBitmapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData-}
```
public void setBitmapData(EmfPlusBaseBitmapData value)
```


Gets or sets bitmap data BitmapData (variable): Variable-length data that defines the bitmap data object specified in the Type field. The content and format of the data can be different for every bitmap type.

Value: The bitmap data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata) |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets or sets bitmap height Height (4 bytes): A 32-bit signed integer that specifies the height in pixels of the area occupied by the bitmap. If the image is compressed, according to the Type field, this value is undefined and MUST be ignored.

Value: The height.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Gets or sets bitmap height Height (4 bytes): A 32-bit signed integer that specifies the height in pixels of the area occupied by the bitmap. If the image is compressed, according to the Type field, this value is undefined and MUST be ignored.

Value: The height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Gets or sets pixel format PixelFormat (4 bytes): A 32-bit unsigned integer that specifies the format of the pixels that make up the bitmap image. The supported pixel formats are specified in the `EmfPlusPixelFormat` enumeration (section 2.1.1.25). If the image is compressed, according to the Type field, this value is undefined and MUST be ignored.

Value: The pixel format.

**Returns:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public void setPixelFormat(int value)
```


Gets or sets pixel format PixelFormat (4 bytes): A 32-bit unsigned integer that specifies the format of the pixels that make up the bitmap image. The supported pixel formats are specified in the `EmfPlusPixelFormat` enumeration (section 2.1.1.25). If the image is compressed, according to the Type field, this value is undefined and MUST be ignored.

Value: The pixel format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getStride() {#getStride--}
```
public int getStride()
```


Gets or sets stride of the image Stride (4 bytes): A 32-bit signed integer that specifies the byte offset between the beginning of one scan-line and the next. This value is the number of bytes per pixel, which is specified in the PixelFormat field, multiplied by the width in pixels, which is specified in the Width field. The value of this field MUST be a multiple of four. If the image is compressed, according to the Type field, this value is undefined and MUST be ignored.

Value: The stride.

**Returns:**
int
### setStride(int value) {#setStride-int-}
```
public void setStride(int value)
```


Gets or sets stride of the image Stride (4 bytes): A 32-bit signed integer that specifies the byte offset between the beginning of one scan-line and the next. This value is the number of bytes per pixel, which is specified in the PixelFormat field, multiplied by the width in pixels, which is specified in the Width field. The value of this field MUST be a multiple of four. If the image is compressed, according to the Type field, this value is undefined and MUST be ignored.

Value: The stride.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public int getType()
```


Gets or sets type of the image Type (4 bytes): A 32-bit unsigned integer that specifies the type of data in the BitmapData field. This value MUST be defined in the `EmfPlusBitmapDataType` enumeration (section 2.1.1.2).

Value: The type.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Gets or sets type of the image Type (4 bytes): A 32-bit unsigned integer that specifies the type of data in the BitmapData field. This value MUST be defined in the `EmfPlusBitmapDataType` enumeration (section 2.1.1.2).

Value: The type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets or sets image Width Width (4 bytes): A 32-bit signed integer that specifies the width in pixels of the area occupied by the bitmap. If the image is compressed, according to the Type field, this value is undefined and MUST be ignored.

Value: The width.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Gets or sets image Width Width (4 bytes): A 32-bit signed integer that specifies the width in pixels of the area occupied by the bitmap. If the image is compressed, according to the Type field, this value is undefined and MUST be ignored.

Value: The width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

