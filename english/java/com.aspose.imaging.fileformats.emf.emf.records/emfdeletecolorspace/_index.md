---
title: EmfDeleteColorSpace
second_title: Aspose.Imaging for Java API Reference
description: The EMR_DELETECOLORSPACE record deletes a logical color space object.
type: docs
weight: 42
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfdeletecolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfDeleteColorSpace extends EmfObjectManipulationRecordType
```

The EMR\_DELETECOLORSPACE record deletes a logical color space object.

An EMR\_DELETEOBJECT record SHOULD be used instead of EMR\_DELETECOLORSPACE to delete a logical color space object.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfDeleteColorSpace(EmfRecord source)](#EmfDeleteColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfDeleteColorSpace` class. |
## Methods

| Method | Description |
| --- | --- |
| [getIhCS()](#getIhCS--) | Gets or sets a 32-bit unsigned integer that specifies the index of a logical color space object in the EMF Object Table (section 3.1.1.1). |
| [setIhCS(int value)](#setIhCS-int-) | Gets or sets a 32-bit unsigned integer that specifies the index of a logical color space object in the EMF Object Table (section 3.1.1.1). |
### EmfDeleteColorSpace(EmfRecord source) {#EmfDeleteColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfDeleteColorSpace(EmfRecord source)
```


Initializes a new instance of the `EmfDeleteColorSpace` class.

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

