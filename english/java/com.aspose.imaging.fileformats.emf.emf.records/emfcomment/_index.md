---
title: EmfComment
second_title: Aspose.Imaging for Java API Reference
description: The EMR_COMMENT record contains arbitrary private data.
type: docs
weight: 25
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfcomment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public final class EmfComment extends EmfCommentRecordType
```

The EMR\_COMMENT record contains arbitrary private data. Note Fields that are not described in this section are specified in section 2.3.3.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfComment(EmfRecord source)](#EmfComment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfComment` class. |
## Methods

| Method | Description |
| --- | --- |
| [getPrivateData()](#getPrivateData--) | Gets or sets an optional array of bytes that specifies the private data. |
| [setPrivateData(byte[] value)](#setPrivateData-byte---) | Gets or sets an optional array of bytes that specifies the private data. |
| [getCommentIdentifier()](#getCommentIdentifier--) | Gets or sets the comment identifier. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Gets or sets the comment identifier. |
### EmfComment(EmfRecord source) {#EmfComment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfComment(EmfRecord source)
```


Initializes a new instance of the `EmfComment` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getPrivateData() {#getPrivateData--}
```
public byte[] getPrivateData()
```


Gets or sets an optional array of bytes that specifies the private data. The first DWORD of this data MUST NOT be one of the predefined comment identifier values specified in section 2.3.3. Private data is unknown to EMF; it is meaningful only to applications that know the format of the data and how to use it. EMR\_COMMENT private data records MAY be ignored.

**Returns:**
byte[]
### setPrivateData(byte[] value) {#setPrivateData-byte---}
```
public void setPrivateData(byte[] value)
```


Gets or sets an optional array of bytes that specifies the private data. The first DWORD of this data MUST NOT be one of the predefined comment identifier values specified in section 2.3.3. Private data is unknown to EMF; it is meaningful only to applications that know the format of the data and how to use it. EMR\_COMMENT private data records MAY be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Gets or sets the comment identifier.

Value: The comment identifier.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Gets or sets the comment identifier.

Value: The comment identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

