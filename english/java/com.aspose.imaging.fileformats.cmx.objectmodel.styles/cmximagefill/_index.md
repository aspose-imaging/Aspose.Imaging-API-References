---
title: CmxImageFill
second_title: Aspose.Imaging for Java API Reference
description: Image fill info
type: docs
weight: 13
url: /java/com.aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/
---
**Inheritance:**
java.lang.Object
```
public class CmxImageFill
```

Image fill info
## Constructors

| Constructor | Description |
| --- | --- |
| [CmxImageFill()](#CmxImageFill--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getImages()](#getImages--) | Gets the images. |
| [setImages(CmxRasterImage[] value)](#setImages-com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage---) | Sets the images. |
| [getProcedure()](#getProcedure--) | Gets the procedure. |
| [setProcedure(CmxProcedure value)](#setProcedure-com.aspose.imaging.fileformats.cmx.objectmodel.CmxProcedure-) | Sets the procedure. |
| [getTileOffsetX()](#getTileOffsetX--) | Gets the tile offset X. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Sets the tile offset X. |
| [getTileOffsetY()](#getTileOffsetY--) | Gets the tile offset Y. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Sets the tile offset Y. |
| [getRcpOffset()](#getRcpOffset--) | Gets the relative offset between tile rows or columns (depends on `OffsetType`(\#getOffsetType.getOffsetType/\#setOffsetType(int).setOffsetType(int))). |
| [setRcpOffset(float value)](#setRcpOffset-float-) | Sets the relative offset between tile rows or columns (depends on `OffsetType`(\#getOffsetType.getOffsetType/\#setOffsetType(int).setOffsetType(int))). |
| [getOffsetType()](#getOffsetType--) | Gets the type of the offset between adjacent tiles. |
| [setOffsetType(int value)](#setOffsetType-int-) | Sets the type of the offset between adjacent tiles. |
| [getPatternWidth()](#getPatternWidth--) | Gets the width of the pattern. |
| [setPatternWidth(float value)](#setPatternWidth-float-) | Sets the width of the pattern. |
| [getPatternHeight()](#getPatternHeight--) | Gets the height of the pattern. |
| [setPatternHeight(float value)](#setPatternHeight-float-) | Sets the height of the pattern. |
| [isRelative()](#isRelative--) | Gets a value indicating whether patterns size values is relative. |
| [setRelative(boolean value)](#setRelative-boolean-) | Sets a value indicating whether patterns size values is relative. |
| [getRotate180()](#getRotate180--) | Gets a value indicating whether this [CmxImageSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec) is upside down. |
| [setRotate180(boolean value)](#setRotate180-boolean-) | Sets a value indicating whether this [CmxImageSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec) is upside down. |
| [toString()](#toString--) | Returns a String that represents this instance. |
| [equals(Object o)](#equals-java.lang.Object-) | Check if objects are equal. |
| [hashCode()](#hashCode--) | Get hash code of the current object. |
### CmxImageFill() {#CmxImageFill--}
```
public CmxImageFill()
```


### getImages() {#getImages--}
```
public final CmxRasterImage[] getImages()
```


Gets the images.

**Returns:**
com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage[] - the images.
### setImages(CmxRasterImage[] value) {#setImages-com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage---}
```
public final void setImages(CmxRasterImage[] value)
```


Sets the images.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [CmxRasterImage\[\]](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxrasterimage) | the images. |

### getProcedure() {#getProcedure--}
```
public final CmxProcedure getProcedure()
```


Gets the procedure.

**Returns:**
[CmxProcedure](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxprocedure) - the procedure.
### setProcedure(CmxProcedure value) {#setProcedure-com.aspose.imaging.fileformats.cmx.objectmodel.CmxProcedure-}
```
public final void setProcedure(CmxProcedure value)
```


Sets the procedure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [CmxProcedure](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxprocedure) | the procedure. |

### getTileOffsetX() {#getTileOffsetX--}
```
public final float getTileOffsetX()
```


Gets the tile offset X.

**Returns:**
float - the tile offset X.
### setTileOffsetX(float value) {#setTileOffsetX-float-}
```
public final void setTileOffsetX(float value)
```


Sets the tile offset X.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | the tile offset X. |

### getTileOffsetY() {#getTileOffsetY--}
```
public final float getTileOffsetY()
```


Gets the tile offset Y.

**Returns:**
float - the tile offset Y.
### setTileOffsetY(float value) {#setTileOffsetY-float-}
```
public final void setTileOffsetY(float value)
```


Sets the tile offset Y.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | the tile offset Y. |

### getRcpOffset() {#getRcpOffset--}
```
public final float getRcpOffset()
```


Gets the relative offset between tile rows or columns (depends on `OffsetType`(\#getOffsetType.getOffsetType/\#setOffsetType(int).setOffsetType(int))). Dimension is fractions of height of width.

**Returns:**
float - the relative offset between tile rows or columns (depends on `OffsetType`(\#getOffsetType.getOffsetType/\#setOffsetType(int).setOffsetType(int))).
### setRcpOffset(float value) {#setRcpOffset-float-}
```
public final void setRcpOffset(float value)
```


Sets the relative offset between tile rows or columns (depends on `OffsetType`(\#getOffsetType.getOffsetType/\#setOffsetType(int).setOffsetType(int))). Dimension is fractions of height of width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | the relative offset between tile rows or columns (depends on `OffsetType`(\#getOffsetType.getOffsetType/\#setOffsetType(int).setOffsetType(int))). |

### getOffsetType() {#getOffsetType--}
```
public final int getOffsetType()
```


Gets the type of the offset between adjacent tiles.

**Returns:**
int - the type of the offset between adjacent tiles.
### setOffsetType(int value) {#setOffsetType-int-}
```
public final void setOffsetType(int value)
```


Sets the type of the offset between adjacent tiles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the type of the offset between adjacent tiles. |

### getPatternWidth() {#getPatternWidth--}
```
public final float getPatternWidth()
```


Gets the width of the pattern. Uses common document distance measure unit in case if `IsRelative`(\#isRelative.isRelative/\#setRelative(boolean).setRelative(boolean)) is `false`, otherwise has the dimension of the image pixel width fraction.

**Returns:**
float - the width of the pattern.
### setPatternWidth(float value) {#setPatternWidth-float-}
```
public final void setPatternWidth(float value)
```


Sets the width of the pattern. Uses common document distance measure unit in case if `IsRelative`(\#isRelative.isRelative/\#setRelative(boolean).setRelative(boolean)) is `false`, otherwise has the dimension of the image pixel width fraction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | the width of the pattern. |

### getPatternHeight() {#getPatternHeight--}
```
public final float getPatternHeight()
```


Gets the height of the pattern. Uses common document distance measure unit in case if `IsRelative`(\#isRelative.isRelative/\#setRelative(boolean).setRelative(boolean)) is `false`, otherwise has the dimension of the image pixel height fraction.

**Returns:**
float - the height of the pattern.
### setPatternHeight(float value) {#setPatternHeight-float-}
```
public final void setPatternHeight(float value)
```


Sets the height of the pattern. Uses common document distance measure unit in case if `IsRelative`(\#isRelative.isRelative/\#setRelative(boolean).setRelative(boolean)) is `false`, otherwise has the dimension of the image pixel height fraction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | the height of the pattern. |

### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


Gets a value indicating whether patterns size values is relative.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public final void setRelative(boolean value)
```


Sets a value indicating whether patterns size values is relative.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRotate180() {#getRotate180--}
```
public final boolean getRotate180()
```


Gets a value indicating whether this [CmxImageSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec) is upside down.

Value: `true` if image is upside down; otherwise, `false`.

**Returns:**
boolean - a value indicating whether this [CmxImageSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec) is upside down.
### setRotate180(boolean value) {#setRotate180-boolean-}
```
public final void setRotate180(boolean value)
```


Sets a value indicating whether this [CmxImageSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec) is upside down.

Value: `true` if image is upside down; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether this [CmxImageSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec) is upside down. |

### toString() {#toString--}
```
public String toString()
```


Returns a String that represents this instance.

**Returns:**
java.lang.String - A String that represents this instance.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Check if objects are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| o | java.lang.Object | The other object. |

**Returns:**
boolean - The equality comparison result.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Get hash code of the current object.

**Returns:**
int - The hash code.
