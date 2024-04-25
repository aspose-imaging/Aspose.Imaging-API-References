---
title: EmfExtCreateFontIndirectW
second_title: Aspose.Imaging for Java API Reference
description: The EMR_EXTCREATEFONTINDIRECTW record defines a logical font for graphics operations.
type: docs
weight: 50
url: /com.aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfExtCreateFontIndirectW extends EmfObjectCreationRecordType
```

The EMR\_EXTCREATEFONTINDIRECTW record defines a logical font for graphics operations.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfExtCreateFontIndirectW(EmfRecord source)](#EmfExtCreateFontIndirectW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfExtCreateFontIndirectW` class. |
| [EmfExtCreateFontIndirectW()](#EmfExtCreateFontIndirectW--) | Initializes a new instance of the `EmfExtCreateFontIndirectW` class. |
## Methods

| Method | Description |
| --- | --- |
| [getIhFonts()](#getIhFonts--) | Gets or sets a 32-bit unsigned integer that specifies the index of the logical font object in the EMF Object Table (section 3.1.1.1). |
| [setIhFonts(int value)](#setIhFonts-int-) | Gets or sets a 32-bit unsigned integer that specifies the index of the logical font object in the EMF Object Table (section 3.1.1.1). |
| [getElw()](#getElw--) | Gets or sets a LogFontExDv object (section 2.2.15), which specifies the logical font. |
| [setElw(EmfLogFont value)](#setElw-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-) | Gets or sets a LogFontExDv object (section 2.2.15), which specifies the logical font. |
### EmfExtCreateFontIndirectW(EmfRecord source) {#EmfExtCreateFontIndirectW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtCreateFontIndirectW(EmfRecord source)
```


Initializes a new instance of the `EmfExtCreateFontIndirectW` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfExtCreateFontIndirectW() {#EmfExtCreateFontIndirectW--}
```
public EmfExtCreateFontIndirectW()
```


Initializes a new instance of the `EmfExtCreateFontIndirectW` class.

### getIhFonts() {#getIhFonts--}
```
public int getIhFonts()
```


Gets or sets a 32-bit unsigned integer that specifies the index of the logical font object in the EMF Object Table (section 3.1.1.1). This index MUST be saved so that this object can be reused or modified.

**Returns:**
int
### setIhFonts(int value) {#setIhFonts-int-}
```
public void setIhFonts(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the index of the logical font object in the EMF Object Table (section 3.1.1.1). This index MUST be saved so that this object can be reused or modified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getElw() {#getElw--}
```
public EmfLogFont getElw()
```


Gets or sets a LogFontExDv object (section 2.2.15), which specifies the logical font. A LogFont object 2.2.13 MAY be present instead.[90]The process for determining the type of object in this field is described below.

**Returns:**
[EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont)
### setElw(EmfLogFont value) {#setElw-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-}
```
public void setElw(EmfLogFont value)
```


Gets or sets a LogFontExDv object (section 2.2.15), which specifies the logical font. A LogFont object 2.2.13 MAY be present instead.[90]The process for determining the type of object in this field is described below.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont) |  |

