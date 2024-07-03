---
title: EmfCommentEmfPlus
second_title: Aspose.Imaging for Java API Reference
description: The EMR_COMMENT_EMFPLUS record contains embedded EMF records.
type: docs
weight: 27
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public final class EmfCommentEmfPlus extends EmfCommentRecordType
```

The EMR\_COMMENT\_EMFPLUS record contains embedded EMF+ records. Note Fields that are not described in this section are specified in section 2.3.3.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfCommentEmfPlus(EmfRecord source)](#EmfCommentEmfPlus-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfCommentEmfPlus` class. |
## Methods

| Method | Description |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Gets or sets a 32-bit unsigned integer that identifies this comment record as containing EMF+ records. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Gets or sets a 32-bit unsigned integer that identifies this comment record as containing EMF+ records. |
| [getEmfPlusRecords()](#getEmfPlusRecords--) | Gets or sets an array of bytes that contains one or more EMF+ records ([MS-EMFPLUS] section 2.3.1). |
| [setEmfPlusRecords(EmfPlusRecord[] value)](#setEmfPlusRecords-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord---) | Gets or sets an array of bytes that contains one or more EMF+ records ([MS-EMFPLUS] section 2.3.1). |
### EmfCommentEmfPlus(EmfRecord source) {#EmfCommentEmfPlus-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentEmfPlus(EmfRecord source)
```


Initializes a new instance of the `EmfCommentEmfPlus` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Gets or sets a 32-bit unsigned integer that identifies this comment record as containing EMF+ records. The value 0x2B464D45, which is the ASCII string "+FME", identifies this as an EMR\_COMMENT\_EMFPLUS record.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Gets or sets a 32-bit unsigned integer that identifies this comment record as containing EMF+ records. The value 0x2B464D45, which is the ASCII string "+FME", identifies this as an EMR\_COMMENT\_EMFPLUS record.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEmfPlusRecords() {#getEmfPlusRecords--}
```
public EmfPlusRecord[] getEmfPlusRecords()
```


Gets or sets an array of bytes that contains one or more EMF+ records ([MS-EMFPLUS] section 2.3.1).

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord[]
### setEmfPlusRecords(EmfPlusRecord[] value) {#setEmfPlusRecords-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord---}
```
public void setEmfPlusRecords(EmfPlusRecord[] value)
```


Gets or sets an array of bytes that contains one or more EMF+ records ([MS-EMFPLUS] section 2.3.1).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusRecord\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) |  |

