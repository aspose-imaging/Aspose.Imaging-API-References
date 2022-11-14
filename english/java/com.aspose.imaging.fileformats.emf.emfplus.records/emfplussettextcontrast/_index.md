---
title: EmfPlusSetTextContrast
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusSetTextContrast record specifies text contrast according to the gamma correction value.
type: docs
weight: 64
url: /java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussettextcontrast/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusPropertyRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluspropertyrecordtype)
```
public final class EmfPlusSetTextContrast extends EmfPlusPropertyRecordType
```

The EmfPlusSetTextContrast record specifies text contrast according to the gamma correction value.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusSetTextContrast(EmfPlusRecord source)](#EmfPlusSetTextContrast-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusSetTextContrast` class. |
## Methods

| Method | Description |
| --- | --- |
| [getTextContrast()](#getTextContrast--) | Gets or sets the gamma correction value X 1000, which will be applied to subsequent text rendering operations. |
| [setTextContrast(short value)](#setTextContrast-short-) | Gets or sets the gamma correction value X 1000, which will be applied to subsequent text rendering operations. |
### EmfPlusSetTextContrast(EmfPlusRecord source) {#EmfPlusSetTextContrast-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetTextContrast(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusSetTextContrast` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getTextContrast() {#getTextContrast--}
```
public short getTextContrast()
```


Gets or sets the gamma correction value X 1000, which will be applied to subsequent text rendering operations. The allowable range is 1000 to 2200, representing text gamma values of 1.0 to 2.2.

**Returns:**
short
### setTextContrast(short value) {#setTextContrast-short-}
```
public void setTextContrast(short value)
```


Gets or sets the gamma correction value X 1000, which will be applied to subsequent text rendering operations. The allowable range is 1000 to 2200, representing text gamma values of 1.0 to 2.2.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

