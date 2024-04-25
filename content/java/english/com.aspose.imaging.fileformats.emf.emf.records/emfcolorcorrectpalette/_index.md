---
title: EmfColorCorrectPalette
second_title: Aspose.Imaging for Java API Reference
description: The EMR_COLORCORRECTPALETTE record specifies how to correct the entries of a logical palette object using WCS 1.0 values.
type: docs
weight: 22
url: /com.aspose.imaging.fileformats.emf.emf.records/emfcolorcorrectpalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfColorCorrectPalette extends EmfObjectManipulationRecordType
```

The EMR\_COLORCORRECTPALETTE record specifies how to correct the entries of a logical palette object using WCS 1.0 values.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfColorCorrectPalette(EmfRecord source)](#EmfColorCorrectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfColorCorrectPalette` class. |
## Methods

| Method | Description |
| --- | --- |
| [getIhPalette()](#getIhPalette--) | Gets a 32-bit unsigned integer that specifies index of a logical palette object (section 2.2.17) in the EMF Object Table (section 3.1.1.1). |
| [setIhPalette(int value)](#setIhPalette-int-) | Sets a 32-bit unsigned integer that specifies index of a logical palette object (section 2.2.17) in the EMF Object Table (section 3.1.1.1). |
| [getNFirstEntry()](#getNFirstEntry--) | Gets a 32-bit unsigned integer that specifies the index of the first entry to correct. |
| [setNFirstEntry(int value)](#setNFirstEntry-int-) | Sets a 32-bit unsigned integer that specifies the index of the first entry to correct. |
| [getNPalEntries()](#getNPalEntries--) | Gets a 32-bit unsigned integer that specifies the number of palette entries to correct. |
| [setNPalEntries(int value)](#setNPalEntries-int-) | Sets a 32-bit unsigned integer that specifies the number of palette entries to correct. |
### EmfColorCorrectPalette(EmfRecord source) {#EmfColorCorrectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfColorCorrectPalette(EmfRecord source)
```


Initializes a new instance of the `EmfColorCorrectPalette` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getIhPalette() {#getIhPalette--}
```
public int getIhPalette()
```


Gets a 32-bit unsigned integer that specifies index of a logical palette object (section 2.2.17) in the EMF Object Table (section 3.1.1.1).

**Returns:**
int
### setIhPalette(int value) {#setIhPalette-int-}
```
public void setIhPalette(int value)
```


Sets a 32-bit unsigned integer that specifies index of a logical palette object (section 2.2.17) in the EMF Object Table (section 3.1.1.1).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getNFirstEntry() {#getNFirstEntry--}
```
public int getNFirstEntry()
```


Gets a 32-bit unsigned integer that specifies the index of the first entry to correct.

**Returns:**
int
### setNFirstEntry(int value) {#setNFirstEntry-int-}
```
public void setNFirstEntry(int value)
```


Sets a 32-bit unsigned integer that specifies the index of the first entry to correct.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getNPalEntries() {#getNPalEntries--}
```
public int getNPalEntries()
```


Gets a 32-bit unsigned integer that specifies the number of palette entries to correct.

**Returns:**
int
### setNPalEntries(int value) {#setNPalEntries-int-}
```
public void setNPalEntries(int value)
```


Sets a 32-bit unsigned integer that specifies the number of palette entries to correct.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

