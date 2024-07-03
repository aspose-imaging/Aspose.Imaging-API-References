---
title: EmfCommentBeginGroup
second_title: Aspose.Imaging for Java API Reference
description: The EMR_COMMENT_BEGINGROUP record specifies the beginning of a group of drawing records.
type: docs
weight: 26
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentbegingroup/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype)
```
public final class EmfCommentBeginGroup extends EmfCommentPublicRecordType
```

The EMR\_COMMENT\_BEGINGROUP record specifies the beginning of a group of drawing records.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfCommentBeginGroup(EmfRecord source)](#EmfCommentBeginGroup-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfCommentBeginGroup` class. |
## Methods

| Method | Description |
| --- | --- |
| [getRectangle()](#getRectangle--) | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the output rectangle in logical coordinates. |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.imaging.Rectangle-) | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the output rectangle in logical coordinates. |
| [getNDescription()](#getNDescription--) | Gets or sets the number of Unicode characters in the optional description string that follows. |
| [setNDescription(int value)](#setNDescription-int-) | Gets or sets the number of Unicode characters in the optional description string that follows. |
| [getDescription()](#getDescription--) | Gets or sets an optional, null-terminated Unicode string that describes this group of records. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Gets or sets an optional, null-terminated Unicode string that describes this group of records. |
### EmfCommentBeginGroup(EmfRecord source) {#EmfCommentBeginGroup-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentBeginGroup(EmfRecord source)
```


Initializes a new instance of the `EmfCommentBeginGroup` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the output rectangle in logical coordinates.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setRectangle(Rectangle value) {#setRectangle-com.aspose.imaging.Rectangle-}
```
public void setRectangle(Rectangle value)
```


Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the output rectangle in logical coordinates.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getNDescription() {#getNDescription--}
```
public int getNDescription()
```


Gets or sets the number of Unicode characters in the optional description string that follows.

**Returns:**
int
### setNDescription(int value) {#setNDescription-int-}
```
public void setNDescription(int value)
```


Gets or sets the number of Unicode characters in the optional description string that follows.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDescription() {#getDescription--}
```
public String getDescription()
```


Gets or sets an optional, null-terminated Unicode string that describes this group of records.

**Returns:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


Gets or sets an optional, null-terminated Unicode string that describes this group of records.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

