---
title: TiffCommonArrayType
second_title: Aspose.Imaging for Java API Reference
description: The tiff common array type.
type: docs
weight: 12
url: /java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffcommonarraytype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype)
```
public abstract class TiffCommonArrayType extends TiffDataType
```

The tiff common array type.
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffCommonArrayType()](#TiffCommonArrayType--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getElementSize()](#getElementSize--) | Gets the element size in bytes. |
| [getValuesContainer()](#getValuesContainer--) | Gets the values container. |
| [getCount()](#getCount--) | Gets the count of elements. |
| [getDataSize()](#getDataSize--) | Gets the additional data size in bytes (in case the 12 bytes is not enough to fit the tag data). |
### TiffCommonArrayType() {#TiffCommonArrayType--}
```
public TiffCommonArrayType()
```


### getElementSize() {#getElementSize--}
```
public abstract long getElementSize()
```


Gets the element size in bytes.

**Returns:**
long - The element size in bytes.
### getValuesContainer() {#getValuesContainer--}
```
public abstract System.Array getValuesContainer()
```


Gets the values container.

**Returns:**
com.aspose.ms.System.Array - The values container.
### getCount() {#getCount--}
```
public final long getCount()
```


Gets the count of elements.

**Returns:**
long - The count of elements.
### getDataSize() {#getDataSize--}
```
public final long getDataSize()
```


Gets the additional data size in bytes (in case the 12 bytes is not enough to fit the tag data).

**Returns:**
long - The additional data size in bytes.
