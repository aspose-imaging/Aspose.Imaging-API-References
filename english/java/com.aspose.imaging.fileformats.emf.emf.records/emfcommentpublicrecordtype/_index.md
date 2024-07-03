---
title: EmfCommentPublicRecordType
second_title: Aspose.Imaging for Java API Reference
description: The EMR_COMMENT_PUBLIC record types specify extensions to EMF processing.
type: docs
weight: 31
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public abstract class EmfCommentPublicRecordType extends EmfCommentRecordType
```

The EMR\_COMMENT\_PUBLIC record types specify extensions to EMF processing.
## Methods

| Method | Description |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Gets or sets a 32-bit unsigned integer that identifies this comment record as specifying public data. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Gets or sets a 32-bit unsigned integer that identifies this comment record as specifying public data. |
| [getPublicCommentIdentifier()](#getPublicCommentIdentifier--) | Gets or sets a 32-bit unsigned integer that identifies the type of public comment record. |
| [setPublicCommentIdentifier(long value)](#setPublicCommentIdentifier-long-) | Gets or sets a 32-bit unsigned integer that identifies the type of public comment record. |
### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Gets or sets a 32-bit unsigned integer that identifies this comment record as specifying public data. The value 0x43494447, which is the ASCII string "CIDG", identifies this as an EMR\_COMMENT\_PUBLIC record.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Gets or sets a 32-bit unsigned integer that identifies this comment record as specifying public data. The value 0x43494447, which is the ASCII string "CIDG", identifies this as an EMR\_COMMENT\_PUBLIC record.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPublicCommentIdentifier() {#getPublicCommentIdentifier--}
```
public long getPublicCommentIdentifier()
```


Gets or sets a 32-bit unsigned integer that identifies the type of public comment record. This SHOULD be one of the values listed in the preceding table, which are specified in the EmrComment enumeration (section 2.1.10), unless additional public comment record types have been implemented on the print server.

**Returns:**
long
### setPublicCommentIdentifier(long value) {#setPublicCommentIdentifier-long-}
```
public void setPublicCommentIdentifier(long value)
```


Gets or sets a 32-bit unsigned integer that identifies the type of public comment record. This SHOULD be one of the values listed in the preceding table, which are specified in the EmrComment enumeration (section 2.1.10), unless additional public comment record types have been implemented on the print server.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

