---
title: EmfEscapeRecordType
second_title: Aspose.Imaging for Java API Reference
description: The escape record types execute printer driver functions.
type: docs
weight: 49
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public abstract class EmfEscapeRecordType extends EmfRecord
```

The escape record types execute printer driver functions.
## Methods

| Method | Description |
| --- | --- |
| [getIEscape()](#getIEscape--) | Gets or sets a 32-bit unsigned integer that specifies the printer driver escape to execute. |
| [setIEscape(int value)](#setIEscape-int-) | Gets or sets a 32-bit unsigned integer that specifies the printer driver escape to execute. |
### getIEscape() {#getIEscape--}
```
public int getIEscape()
```


Gets or sets a 32-bit unsigned integer that specifies the printer driver escape to execute. This MUST be one of the values in the WMF MetafileEscapes enumeration ([MSWMF] section 2.1.1.17).

**Returns:**
int
### setIEscape(int value) {#setIEscape-int-}
```
public void setIEscape(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the printer driver escape to execute. This MUST be one of the values in the WMF MetafileEscapes enumeration ([MSWMF] section 2.1.1.17).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

