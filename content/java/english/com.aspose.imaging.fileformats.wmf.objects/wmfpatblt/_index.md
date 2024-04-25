---
title: WmfPatBlt
second_title: Aspose.Imaging for Java API Reference
description: The META_PATBLT record paints a specified rectangle using the brush that     is defined in the playback device context.
type: docs
weight: 52
url: /com.aspose.imaging.fileformats.wmf.objects/wmfpatblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfPointObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfpointobject)
```
public class WmfPatBlt extends WmfPointObject
```

The META\_PATBLT record paints a specified rectangle using the brush that is defined in the playback device context. The brush color and the surface color or colors are combined using the specified raster operation.
## Constructors

| Constructor | Description |
| --- | --- |
| [WmfPatBlt()](#WmfPatBlt--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | Gets or sets the raster operation. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | Gets or sets the raster operation. |
| [getHeight()](#getHeight--) | Gets or sets the height. |
| [setHeight(short value)](#setHeight-short-) | Gets or sets the height. |
| [getWidth()](#getWidth--) | Gets or sets the width. |
| [setWidth(short value)](#setWidth-short-) | Gets or sets the width. |
### WmfPatBlt() {#WmfPatBlt--}
```
public WmfPatBlt()
```


### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


Gets or sets the raster operation.

Value: The raster operation code. This code MUST be one of the values in the Ternary Raster Operation enumeration table.

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


Gets or sets the raster operation.

Value: The raster operation code. This code MUST be one of the values in the Ternary Raster Operation enumeration table.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public short getHeight()
```


Gets or sets the height.

Value: The height, in logical units, of the rectangle.

**Returns:**
short
### setHeight(short value) {#setHeight-short-}
```
public void setHeight(short value)
```


Gets or sets the height.

Value: The height, in logical units, of the rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getWidth() {#getWidth--}
```
public short getWidth()
```


Gets or sets the width.

Value: The width, in logical units, of the rectangle.

**Returns:**
short
### setWidth(short value) {#setWidth-short-}
```
public void setWidth(short value)
```


Gets or sets the width.

Value: The width, in logical units, of the rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

