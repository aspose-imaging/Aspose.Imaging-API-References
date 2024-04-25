---
title: EmfSetArcDirection
second_title: Aspose.Imaging for Java API Reference
description: The EMR_SETARCDIRECTION record specifies the drawing direction to be used for arc and rectangle output.
type: docs
weight: 115
url: /com.aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetArcDirection extends EmfStateRecordType
```

The EMR\_SETARCDIRECTION record specifies the drawing direction to be used for arc and rectangle output.

The EMR\_SETARCDIRECTION record affects the direction in which the following records draw: - EMR\_ARC (section 2.3.5.2) - EMR\_ARCTO (section 2.3.5.3) - EMR\_CHORD (section 2.3.5.4) - EMR\_ELLIPSE (section 2.3.5.5) - EMR\_PIE (section 2.3.5.15) - EMR\_RECTANGLE (section 2.3.5.34) - EMR\_ROUNDRECT (section 2.3.5.35)
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfSetArcDirection(EmfRecord source)](#EmfSetArcDirection-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfSetArcDirection` class. |
| [EmfSetArcDirection()](#EmfSetArcDirection--) | Initializes a new instance of the `EmfSetArcDirection` class. |
## Methods

| Method | Description |
| --- | --- |
| [getArcDirection()](#getArcDirection--) | Gets or sets a 32-bit unsigned integer that specifies the arc direction. |
| [setArcDirection(int value)](#setArcDirection-int-) | Gets or sets a 32-bit unsigned integer that specifies the arc direction. |
### EmfSetArcDirection(EmfRecord source) {#EmfSetArcDirection-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetArcDirection(EmfRecord source)
```


Initializes a new instance of the `EmfSetArcDirection` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfSetArcDirection() {#EmfSetArcDirection--}
```
public EmfSetArcDirection()
```


Initializes a new instance of the `EmfSetArcDirection` class.

### getArcDirection() {#getArcDirection--}
```
public int getArcDirection()
```


Gets or sets a 32-bit unsigned integer that specifies the arc direction. The value MUST be in the ArcDirection enumeration (section 2.1.2). The default direction is counterclockwise.

**Returns:**
int
### setArcDirection(int value) {#setArcDirection-int-}
```
public void setArcDirection(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the arc direction. The value MUST be in the ArcDirection enumeration (section 2.1.2). The default direction is counterclockwise.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

