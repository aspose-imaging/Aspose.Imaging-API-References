---
title: EmfSetTextJustification
second_title: Aspose.Imaging for Java API Reference
description: The EMR_SETTEXTJUSTIFICATION record specifies the amount of extra space to add to break characters for text justification.
type: docs
weight: 138
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfsettextjustification/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetTextJustification extends EmfStateRecordType
```

The EMR\_SETTEXTJUSTIFICATION record specifies the amount of extra space to add to break characters for text justification.

Instead of using an EMR\_SETTEXTJUSTIFICATION record, an implementation SHOULD use an EMR\_EXTTEXTOUTW record (section 2.3.5.8) to perform this function.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfSetTextJustification(EmfRecord source)](#EmfSetTextJustification-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfSetTextJustification` class. |
## Methods

| Method | Description |
| --- | --- |
| [getNBreakExtra()](#getNBreakExtra--) | Gets or sets a 32-bit signed integer that specifies the total amount of extra space, in logical units, to add. |
| [setNBreakExtra(int value)](#setNBreakExtra-int-) | Gets or sets a 32-bit signed integer that specifies the total amount of extra space, in logical units, to add. |
| [getNBreakCount()](#getNBreakCount--) | Gets or sets a 32-bit signed integer that specifies the number of break characters. |
| [setNBreakCount(int value)](#setNBreakCount-int-) | Gets or sets a 32-bit signed integer that specifies the number of break characters. |
### EmfSetTextJustification(EmfRecord source) {#EmfSetTextJustification-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetTextJustification(EmfRecord source)
```


Initializes a new instance of the `EmfSetTextJustification` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getNBreakExtra() {#getNBreakExtra--}
```
public int getNBreakExtra()
```


Gets or sets a 32-bit signed integer that specifies the total amount of extra space, in logical units, to add.

**Returns:**
int
### setNBreakExtra(int value) {#setNBreakExtra-int-}
```
public void setNBreakExtra(int value)
```


Gets or sets a 32-bit signed integer that specifies the total amount of extra space, in logical units, to add.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getNBreakCount() {#getNBreakCount--}
```
public int getNBreakCount()
```


Gets or sets a 32-bit signed integer that specifies the number of break characters.

**Returns:**
int
### setNBreakCount(int value) {#setNBreakCount-int-}
```
public void setNBreakCount(int value)
```


Gets or sets a 32-bit signed integer that specifies the number of break characters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

