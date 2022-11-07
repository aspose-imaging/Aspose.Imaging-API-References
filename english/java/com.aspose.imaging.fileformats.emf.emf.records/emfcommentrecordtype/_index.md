---
title: EmfCommentRecordType
second_title: Aspose.Imaging for Java API Reference
description: The comment record types define formats for specifying arbitrary private data embedding records in other metafile formats and adding new or special-purpose commands.
type: docs
weight: 31
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public abstract class EmfCommentRecordType extends EmfRecord
```

The comment record types define formats for specifying arbitrary private data, embedding records in other metafile formats, and adding new or special-purpose commands.
## Methods

| Method | Description |
| --- | --- |
| [getDataSize()](#getDataSize--) | Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the CommentIdentifier and CommentRecordParm fields in the RecordBuffer field that follows. |
| [setDataSize(int value)](#setDataSize-int-) | Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the CommentIdentifier and CommentRecordParm fields in the RecordBuffer field that follows. |
| [getCommentIdentifier()](#getCommentIdentifier--) | Gets or sets the comment identifier. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Gets or sets the comment identifier. |
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the CommentIdentifier and CommentRecordParm fields in the RecordBuffer field that follows. It MUST NOT include the size of itself or the size of the AlignmentPadding field, if present

**Returns:**
int
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the CommentIdentifier and CommentRecordParm fields in the RecordBuffer field that follows. It MUST NOT include the size of itself or the size of the AlignmentPadding field, if present

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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

