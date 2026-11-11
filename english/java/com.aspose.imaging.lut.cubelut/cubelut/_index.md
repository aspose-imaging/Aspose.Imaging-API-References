---
title: CubeLut
second_title: Aspose.Imaging for Java API Reference
description: Represents a 3u2011dimensional lookup table LUT loaded from a .cube file.
type: docs
weight: 10
url: /java/com.aspose.imaging.lut.cubelut/cubelut/
---
**Inheritance:**
java.lang.Object
```
public final class CubeLut
```

Represents a 3\\u2011dimensional lookup table (LUT) loaded from a .cube file.
## Methods

| Method | Description |
| --- | --- |
| [load(InputStream stream)](#load-java.io.InputStream-) | Loads a [CubeLut](../../com.aspose.imaging.lut.cubelut/cubelut) from the provided java.io.InputStream. |
| [load(String fileName)](#load-java.lang.String-) | Loads a [CubeLut](../../com.aspose.imaging.lut.cubelut/cubelut) from a file. |
| [getTitle()](#getTitle--) | Gets the title. |
| [getSize()](#getSize--) | Gets the size. |
| [getPointCount()](#getPointCount--) | Gets the point count. |
| [toString()](#toString--) | Returns a string that represents the current object. |
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static CubeLut load(InputStream stream)
```


Loads a [CubeLut](../../com.aspose.imaging.lut.cubelut/cubelut) from the provided java.io.InputStream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream containing the LUT data. |

**Returns:**
[CubeLut](../../com.aspose.imaging.lut.cubelut/cubelut) - A new instance of [CubeLut](../../com.aspose.imaging.lut.cubelut/cubelut).
### load(String fileName) {#load-java.lang.String-}
```
public static CubeLut load(String fileName)
```


Loads a [CubeLut](../../com.aspose.imaging.lut.cubelut/cubelut) from a file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path to the \*.cube file. |

**Returns:**
[CubeLut](../../com.aspose.imaging.lut.cubelut/cubelut) - A new instance of [CubeLut](../../com.aspose.imaging.lut.cubelut/cubelut).
### getTitle() {#getTitle--}
```
public String getTitle()
```


Gets the title.

Value: The title.

**Returns:**
java.lang.String - the title.
### getSize() {#getSize--}
```
public int getSize()
```


Gets the size.

Value: The size.

**Returns:**
int - the size.
### getPointCount() {#getPointCount--}
```
public int getPointCount()
```


Gets the point count.

Value: The point count.

**Returns:**
int - the point count.
### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - A string that represents the current object.
