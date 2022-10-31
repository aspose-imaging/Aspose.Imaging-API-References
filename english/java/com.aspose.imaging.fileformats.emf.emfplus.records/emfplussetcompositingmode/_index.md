---
title: EmfPlusSetCompositingMode
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusSetCompositingMode record specifies how source colors are combined with background colors.
type: docs
weight: 58
url: /java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetcompositingmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusPropertyRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluspropertyrecordtype)
```
public final class EmfPlusSetCompositingMode extends EmfPlusPropertyRecordType
```

The EmfPlusSetCompositingMode record specifies how source colors are combined with background colors.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusSetCompositingMode(EmfPlusRecord source)](#EmfPlusSetCompositingMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusSetCompositingMode` class. |
## Methods

| Method | Description |
| --- | --- |
| [getCompositingMode()](#getCompositingMode--) | Gets or sets the compositing mode value, from the CompositingMode enumeration (section 2.1.1.5). |
| [setCompositingMode(byte value)](#setCompositingMode-byte-) | Gets or sets the compositing mode value, from the CompositingMode enumeration (section 2.1.1.5). |
### EmfPlusSetCompositingMode(EmfPlusRecord source) {#EmfPlusSetCompositingMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetCompositingMode(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusSetCompositingMode` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getCompositingMode() {#getCompositingMode--}
```
public byte getCompositingMode()
```


Gets or sets the compositing mode value, from the CompositingMode enumeration (section 2.1.1.5). Compositing can be expressed as the state of alpha blending, which can either be on or off.

Value: The compositing mode.

**Returns:**
byte
### setCompositingMode(byte value) {#setCompositingMode-byte-}
```
public void setCompositingMode(byte value)
```


Gets or sets the compositing mode value, from the CompositingMode enumeration (section 2.1.1.5). Compositing can be expressed as the state of alpha blending, which can either be on or off.

Value: The compositing mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

