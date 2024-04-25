---
title: EmfGradientRectangle
second_title: Aspose.Imaging for Java API Reference
description: The GradientRectangle object defines a rectangle using TriVertex objects section 2.2.26 in an  EMR_GRADIENTFILL record section 2.3.5.12.
type: docs
weight: 16
url: /com.aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfGradientRectangle extends EmfObject
```

The GradientRectangle object defines a rectangle using TriVertex objects (section 2.2.26) in an EMR\_GRADIENTFILL record (section 2.3.5.12).
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfGradientRectangle()](#EmfGradientRectangle--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getUpperLeft()](#getUpperLeft--) | Gets or sets an index into an array of TriVertex objects that specifies the upper-left vertex of a rectangle. |
| [setUpperLeft(int value)](#setUpperLeft-int-) | Gets or sets an index into an array of TriVertex objects that specifies the upper-left vertex of a rectangle. |
| [getLowerRight()](#getLowerRight--) | Gets or sets an index into an array of TriVertex objects that specifies the lower-right vertex of a rectangle. |
| [setLowerRight(int value)](#setLowerRight-int-) | Gets or sets an index into an array of TriVertex objects that specifies the lower-right vertex of a rectangle. |
### EmfGradientRectangle() {#EmfGradientRectangle--}
```
public EmfGradientRectangle()
```


### getUpperLeft() {#getUpperLeft--}
```
public int getUpperLeft()
```


Gets or sets an index into an array of TriVertex objects that specifies the upper-left vertex of a rectangle. The index MUST be smaller than the size of the array, as defined by the nVer field of the EMR\_GRADIENTFILL record.

**Returns:**
int
### setUpperLeft(int value) {#setUpperLeft-int-}
```
public void setUpperLeft(int value)
```


Gets or sets an index into an array of TriVertex objects that specifies the upper-left vertex of a rectangle. The index MUST be smaller than the size of the array, as defined by the nVer field of the EMR\_GRADIENTFILL record.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLowerRight() {#getLowerRight--}
```
public int getLowerRight()
```


Gets or sets an index into an array of TriVertex objects that specifies the lower-right vertex of a rectangle. The index MUST be smaller than the size of the array, as defined by the nVer field of the EMR\_GRADIENTFILL record.

**Returns:**
int
### setLowerRight(int value) {#setLowerRight-int-}
```
public void setLowerRight(int value)
```


Gets or sets an index into an array of TriVertex objects that specifies the lower-right vertex of a rectangle. The index MUST be smaller than the size of the array, as defined by the nVer field of the EMR\_GRADIENTFILL record.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

