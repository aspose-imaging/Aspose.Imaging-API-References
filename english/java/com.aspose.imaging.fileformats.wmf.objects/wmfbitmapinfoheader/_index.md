---
title: WmfBitmapInfoHeader
second_title: Aspose.Imaging for Java API Reference
description: The BitmapInfoHeader Object contains information about the dimensions and color format of a device-independent     bitmap DIB.
type: docs
weight: 16
url: /java/com.aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfBitmapBaseHeader](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader)
```
public class WmfBitmapInfoHeader extends WmfBitmapBaseHeader
```

The BitmapInfoHeader Object contains information about the dimensions and color format of a device-independent bitmap (DIB).
## Constructors

| Constructor | Description |
| --- | --- |
| [WmfBitmapInfoHeader()](#WmfBitmapInfoHeader--) |  |
## Fields

| Field | Description |
| --- | --- |
| [STRUCTURE_SIZE](#STRUCTURE-SIZE) | The structure size |
## Methods

| Method | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Gets or sets a 32-bit signed integer that defines the width of the DIB, in pixels. |
| [setWidth(int value)](#setWidth-int-) | Gets or sets a 32-bit signed integer that defines the width of the DIB, in pixels. |
| [getHeight()](#getHeight--) | Gets or sets 32-bit signed integer that defines the height of the DIB, in pixels. |
| [setHeight(int value)](#setHeight-int-) | Gets or sets 32-bit signed integer that defines the height of the DIB, in pixels. |
| [getCompression()](#getCompression--) | Gets or sets a 32-bit unsigned integer that defines the compression mode of the DIB. |
| [setCompression(int value)](#setCompression-int-) | Gets or sets a 32-bit unsigned integer that defines the compression mode of the DIB. |
| [getImageSize()](#getImageSize--) | Gets or sets a 32-bit unsigned integer that defines the size, in bytes, of the image. |
| [setImageSize(int value)](#setImageSize-int-) | Gets or sets a 32-bit unsigned integer that defines the size, in bytes, of the image. |
| [getXPelsPerMeter()](#getXPelsPerMeter--) | Gets or sets a 32-bit signed integer that defines the horizontal resolution, in pixels-per-meter, of the target device for the DIB |
| [setXPelsPerMeter(int value)](#setXPelsPerMeter-int-) | Gets or sets a 32-bit signed integer that defines the horizontal resolution, in pixels-per-meter, of the target device for the DIB |
| [getYPelsPerMeter()](#getYPelsPerMeter--) | Gets or sets a 32-bit signed integer that defines the vertical resolution, in pixels-per-meter, of the target device for the DIB |
| [setYPelsPerMeter(int value)](#setYPelsPerMeter-int-) | Gets or sets a 32-bit signed integer that defines the vertical resolution, in pixels-per-meter, of the target device for the DIB |
| [getColorUsed()](#getColorUsed--) | Gets or sets a 32-bit unsigned integer that specifies the number of indexes in the color table used by the DIB, as follows: If this value is zero, the DIB uses the maximum number of colors that correspond to the BitCount value. |
| [setColorUsed(int value)](#setColorUsed-int-) | Gets or sets a 32-bit unsigned integer that specifies the number of indexes in the color table used by the DIB, as follows: If this value is zero, the DIB uses the maximum number of colors that correspond to the BitCount value. |
| [getColorImportant()](#getColorImportant--) | Gets or sets a 32-bit unsigned integer that defines the number of color indexes that are required for displaying the DIB. |
| [setColorImportant(int value)](#setColorImportant-int-) | Gets or sets a 32-bit unsigned integer that defines the number of color indexes that are required for displaying the DIB. |
### WmfBitmapInfoHeader() {#WmfBitmapInfoHeader--}
```
public WmfBitmapInfoHeader()
```


### STRUCTURE_SIZE {#STRUCTURE-SIZE}
```
public static final int STRUCTURE_SIZE
```


The structure size

### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets or sets a 32-bit signed integer that defines the width of the DIB, in pixels. This value MUST be positive. This field SHOULD specify the width of the decompressed image file, if the Compression value specifies JPEG or PNG format.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Gets or sets a 32-bit signed integer that defines the width of the DIB, in pixels. This value MUST be positive. This field SHOULD specify the width of the decompressed image file, if the Compression value specifies JPEG or PNG format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets or sets 32-bit signed integer that defines the height of the DIB, in pixels. This value MUST NOT be zero. If this value is positive, the DIB is a bottom-up bitmap, and its origin is the lower-left corner. If this value is negative, the DIB is a top-down bitmap, and its origin is the upper-left corner. Top-down bitmaps do not support compression. This field SHOULD specify the height of the decompressed image file, if the Compression value specifies JPEG or PNG format.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Gets or sets 32-bit signed integer that defines the height of the DIB, in pixels. This value MUST NOT be zero. If this value is positive, the DIB is a bottom-up bitmap, and its origin is the lower-left corner. If this value is negative, the DIB is a top-down bitmap, and its origin is the upper-left corner. Top-down bitmaps do not support compression. This field SHOULD specify the height of the decompressed image file, if the Compression value specifies JPEG or PNG format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCompression() {#getCompression--}
```
public int getCompression()
```


Gets or sets a 32-bit unsigned integer that defines the compression mode of the DIB. This value MUST be in the Compression Enumeration (section 2.1.1.7). This value MUST NOT specify a compressed format if the DIB is a top-down bitmap, as indicated by the Height value.

**Returns:**
int
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Gets or sets a 32-bit unsigned integer that defines the compression mode of the DIB. This value MUST be in the Compression Enumeration (section 2.1.1.7). This value MUST NOT specify a compressed format if the DIB is a top-down bitmap, as indicated by the Height value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getImageSize() {#getImageSize--}
```
public int getImageSize()
```


Gets or sets a 32-bit unsigned integer that defines the size, in bytes, of the image. If the Compression value is BI\_RGB, this value SHOULD be zero and MUST be ignored. If the Compression value is BI\_JPEG or BI\_PNG, this value MUST specify the size of the JPEG or PNG image buffer, respectively.

**Returns:**
int
### setImageSize(int value) {#setImageSize-int-}
```
public void setImageSize(int value)
```


Gets or sets a 32-bit unsigned integer that defines the size, in bytes, of the image. If the Compression value is BI\_RGB, this value SHOULD be zero and MUST be ignored. If the Compression value is BI\_JPEG or BI\_PNG, this value MUST specify the size of the JPEG or PNG image buffer, respectively.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getXPelsPerMeter() {#getXPelsPerMeter--}
```
public int getXPelsPerMeter()
```


Gets or sets a 32-bit signed integer that defines the horizontal resolution, in pixels-per-meter, of the target device for the DIB

**Returns:**
int
### setXPelsPerMeter(int value) {#setXPelsPerMeter-int-}
```
public void setXPelsPerMeter(int value)
```


Gets or sets a 32-bit signed integer that defines the horizontal resolution, in pixels-per-meter, of the target device for the DIB

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getYPelsPerMeter() {#getYPelsPerMeter--}
```
public int getYPelsPerMeter()
```


Gets or sets a 32-bit signed integer that defines the vertical resolution, in pixels-per-meter, of the target device for the DIB

**Returns:**
int
### setYPelsPerMeter(int value) {#setYPelsPerMeter-int-}
```
public void setYPelsPerMeter(int value)
```


Gets or sets a 32-bit signed integer that defines the vertical resolution, in pixels-per-meter, of the target device for the DIB

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColorUsed() {#getColorUsed--}
```
public int getColorUsed()
```


Gets or sets a 32-bit unsigned integer that specifies the number of indexes in the color table used by the DIB, as follows: If this value is zero, the DIB uses the maximum number of colors that correspond to the BitCount value. If this value is nonzero and the BitCount value is less than 16, this value specifies the number of colors used by the DIB. If this value is nonzero and the BitCount value is 16 or greater, this value specifies the size of the color table used to optimize performance of the system palette. Note If this value is nonzero and greater than the maximum possible size of the color table based on the BitCount value, the maximum color table size SHOULD be assumed.

**Returns:**
int
### setColorUsed(int value) {#setColorUsed-int-}
```
public void setColorUsed(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the number of indexes in the color table used by the DIB, as follows: If this value is zero, the DIB uses the maximum number of colors that correspond to the BitCount value. If this value is nonzero and the BitCount value is less than 16, this value specifies the number of colors used by the DIB. If this value is nonzero and the BitCount value is 16 or greater, this value specifies the size of the color table used to optimize performance of the system palette. Note If this value is nonzero and greater than the maximum possible size of the color table based on the BitCount value, the maximum color table size SHOULD be assumed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColorImportant() {#getColorImportant--}
```
public int getColorImportant()
```


Gets or sets a 32-bit unsigned integer that defines the number of color indexes that are required for displaying the DIB. If this value is zero, all color indexes are required

**Returns:**
int
### setColorImportant(int value) {#setColorImportant-int-}
```
public void setColorImportant(int value)
```


Gets or sets a 32-bit unsigned integer that defines the number of color indexes that are required for displaying the DIB. If this value is zero, all color indexes are required

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

