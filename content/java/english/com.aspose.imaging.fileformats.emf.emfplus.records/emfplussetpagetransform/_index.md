---
title: EmfPlusSetPageTransform
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusSetPageTransform record specifies scaling factors and units for converting page space coordinates to device space coordinates.
type: docs
weight: 61
url: /com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetPageTransform extends EmfPlusTerminalServerRecordType
```

The EmfPlusSetPageTransform record specifies scaling factors and units for converting page space coordinates to device space coordinates.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusSetPageTransform(EmfPlusRecord source)](#EmfPlusSetPageTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusSetPageTransform` class. |
## Methods

| Method | Description |
| --- | --- |
| [getPageUnit()](#getPageUnit--) | Gets the unit of measure for page space coordinates, from the UnitType enumeration (section 2.1.1.33). |
| [getPageScale()](#getPageScale--) | Gets or sets a 32-bit floating-point value that specifies the scale factor for converting page space coordinates to device space coordinates. |
| [setPageScale(float value)](#setPageScale-float-) | Gets or sets a 32-bit floating-point value that specifies the scale factor for converting page space coordinates to device space coordinates. |
### EmfPlusSetPageTransform(EmfPlusRecord source) {#EmfPlusSetPageTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetPageTransform(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusSetPageTransform` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


Gets the unit of measure for page space coordinates, from the UnitType enumeration (section 2.1.1.33). This value SHOULD NOT be UnitTypeDisplay or UnitTypeWorld.

Value: The page unit.

**Returns:**
int
### getPageScale() {#getPageScale--}
```
public float getPageScale()
```


Gets or sets a 32-bit floating-point value that specifies the scale factor for converting page space coordinates to device space coordinates.

Value: The page scale.

**Returns:**
float
### setPageScale(float value) {#setPageScale-float-}
```
public void setPageScale(float value)
```


Gets or sets a 32-bit floating-point value that specifies the scale factor for converting page space coordinates to device space coordinates.

Value: The page scale.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

