---
title: EmfCommentEmfSpool
second_title: Aspose.Imaging for Java API Reference
description: The EMR_COMMENT_EMFSPOOL record contains embedded EMFSPOOL records.
type: docs
weight: 28
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public final class EmfCommentEmfSpool extends EmfCommentRecordType
```

The EMR\_COMMENT\_EMFSPOOL record contains embedded EMFSPOOL records. Note Fields that are not described in this section are specified in section 2.3.3.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfCommentEmfSpool(EmfRecord source)](#EmfCommentEmfSpool-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfCommentEmfSpool` class. |
| [EmfCommentEmfSpool()](#EmfCommentEmfSpool--) | Initializes a new instance of the `EmfCommentEmfSpool` class. |
## Methods

| Method | Description |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Gets or sets a 32-bit unsigned integer that identifies this comment record as containing EMFSPOOL records. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Gets or sets a 32-bit unsigned integer that identifies this comment record as containing EMFSPOOL records. |
| [getEmfSpoolRecordIdentifier()](#getEmfSpoolRecordIdentifier--) | Gets or sets a 32-bit unsigned integer that identifies the type of EMR\_COMMENT\_EMFSPOOL record. |
| [setEmfSpoolRecordIdentifier(int value)](#setEmfSpoolRecordIdentifier-int-) | Gets or sets a 32-bit unsigned integer that identifies the type of EMR\_COMMENT\_EMFSPOOL record. |
| [getEmfSpoolRecords()](#getEmfSpoolRecords--) | Gets or sets a variable-length array of bytes that contains one or more EMFSPOOL font definition records ([MS-EMFSPOOL] section 2.2.3.3). |
| [setEmfSpoolRecords(EmfSpoolFontDefinitionRecordType[] value)](#setEmfSpoolRecords-com.aspose.imaging.fileformats.emf.emfspool.records.EmfSpoolFontDefinitionRecordType---) | Gets or sets a variable-length array of bytes that contains one or more EMFSPOOL font definition records ([MS-EMFSPOOL] section 2.2.3.3). |
### EmfCommentEmfSpool(EmfRecord source) {#EmfCommentEmfSpool-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentEmfSpool(EmfRecord source)
```


Initializes a new instance of the `EmfCommentEmfSpool` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfCommentEmfSpool() {#EmfCommentEmfSpool--}
```
public EmfCommentEmfSpool()
```


Initializes a new instance of the `EmfCommentEmfSpool` class.

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Gets or sets a 32-bit unsigned integer that identifies this comment record as containing EMFSPOOL records. The value 0x00000000 identifies this as an EMR\_COMMENT\_EMFSPOOL record.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Gets or sets a 32-bit unsigned integer that identifies this comment record as containing EMFSPOOL records. The value 0x00000000 identifies this as an EMR\_COMMENT\_EMFSPOOL record.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEmfSpoolRecordIdentifier() {#getEmfSpoolRecordIdentifier--}
```
public int getEmfSpoolRecordIdentifier()
```


Gets or sets a 32-bit unsigned integer that identifies the type of EMR\_COMMENT\_EMFSPOOL record.

**Returns:**
int
### setEmfSpoolRecordIdentifier(int value) {#setEmfSpoolRecordIdentifier-int-}
```
public void setEmfSpoolRecordIdentifier(int value)
```


Gets or sets a 32-bit unsigned integer that identifies the type of EMR\_COMMENT\_EMFSPOOL record.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEmfSpoolRecords() {#getEmfSpoolRecords--}
```
public EmfSpoolFontDefinitionRecordType[] getEmfSpoolRecords()
```


Gets or sets a variable-length array of bytes that contains one or more EMFSPOOL font definition records ([MS-EMFSPOOL] section 2.2.3.3).

**Returns:**
com.aspose.imaging.fileformats.emf.emfspool.records.EmfSpoolFontDefinitionRecordType[]
### setEmfSpoolRecords(EmfSpoolFontDefinitionRecordType[] value) {#setEmfSpoolRecords-com.aspose.imaging.fileformats.emf.emfspool.records.EmfSpoolFontDefinitionRecordType---}
```
public void setEmfSpoolRecords(EmfSpoolFontDefinitionRecordType[] value)
```


Gets or sets a variable-length array of bytes that contains one or more EMFSPOOL font definition records ([MS-EMFSPOOL] section 2.2.3.3).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfSpoolFontDefinitionRecordType\[\]](../../com.aspose.imaging.fileformats.emf.emfspool.records/emfspoolfontdefinitionrecordtype) |  |

