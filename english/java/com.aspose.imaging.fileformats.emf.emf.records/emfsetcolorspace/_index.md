---
title: EmfSetColorSpace
second_title: Aspose.Imaging for Java API Reference
description: The EMR_SETCOLORSPACE record defines the current logical color space object for graphics operations.
type: docs
weight: 123
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfsetcolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfSetColorSpace extends EmfObjectManipulationRecordType
```

The EMR\_SETCOLORSPACE record defines the current logical color space object for graphics operations.

The logical color space object defined by this record MUST be used in drawing operations that are specified by subsequent EMF records, until either a different logical color space object is specified by another EMR\_SETCOLORSPACE record, or the object is removed by a EMR\_DELETECOLORSPACE record.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfSetColorSpace(EmfRecord source)](#EmfSetColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfSetColorSpace` class. |
## Methods

| Method | Description |
| --- | --- |
| [getIhCS()](#getIhCS--) | Gets or sets a 32-bit unsigned integer that specifies the index of a logical color space object in the EMF Object Table (section 3.1.1.1). |
| [setIhCS(int value)](#setIhCS-int-) | Gets or sets a 32-bit unsigned integer that specifies the index of a logical color space object in the EMF Object Table (section 3.1.1.1). |
### EmfSetColorSpace(EmfRecord source) {#EmfSetColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetColorSpace(EmfRecord source)
```


Initializes a new instance of the `EmfSetColorSpace` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getIhCS() {#getIhCS--}
```
public int getIhCS()
```


Gets or sets a 32-bit unsigned integer that specifies the index of a logical color space object in the EMF Object Table (section 3.1.1.1).

This object is either a WMF LogColorSpace or LogColorSpaceW object ([MS-WMF] sections 2.2.2.11 and 2.2.2.12, respectively).

**Returns:**
int
### setIhCS(int value) {#setIhCS-int-}
```
public void setIhCS(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the index of a logical color space object in the EMF Object Table (section 3.1.1.1).

This object is either a WMF LogColorSpace or LogColorSpaceW object ([MS-WMF] sections 2.2.2.11 and 2.2.2.12, respectively).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

