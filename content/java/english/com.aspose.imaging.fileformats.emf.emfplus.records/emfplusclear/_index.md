---
title: EmfPlusClear
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusClear record clears the output coordinate space and initializes it with a background color and transparency
type: docs
weight: 12
url: /com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclear/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusClear extends EmfPlusDrawingRecordType
```

The EmfPlusClear record clears the output coordinate space and initializes it with a background color and transparency
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusClear(EmfPlusRecord source)](#EmfPlusClear-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusClear` class. |
## Methods

| Method | Description |
| --- | --- |
| [getArgb32Color()](#getArgb32Color--) | Gets or sets the color. |
| [setArgb32Color(int value)](#setArgb32Color-int-) | Gets or sets the color. |
### EmfPlusClear(EmfPlusRecord source) {#EmfPlusClear-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusClear(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusClear` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getArgb32Color() {#getArgb32Color--}
```
public int getArgb32Color()
```


Gets or sets the color. An EmfPlusARGB object (section 2.2.2.1) that defines the color to paint the screen. All colors are specified in [IEC-RGB], unless otherwise noted.

Value: The color.

**Returns:**
int
### setArgb32Color(int value) {#setArgb32Color-int-}
```
public void setArgb32Color(int value)
```


Gets or sets the color. An EmfPlusARGB object (section 2.2.2.1) that defines the color to paint the screen. All colors are specified in [IEC-RGB], unless otherwise noted.

Value: The color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

