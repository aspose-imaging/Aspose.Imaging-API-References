---
title: EmfPlusSetAntiAliasMode
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusSetAntiAliasMode record specifies the anti-aliasing mode for text output.
type: docs
weight: 54
url: /java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusPropertyRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluspropertyrecordtype)
```
public final class EmfPlusSetAntiAliasMode extends EmfPlusPropertyRecordType
```

The EmfPlusSetAntiAliasMode record specifies the anti-aliasing mode for text output.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusSetAntiAliasMode(EmfPlusRecord source)](#EmfPlusSetAntiAliasMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusSetAntiAliasMode` class. |
## Methods

| Method | Description |
| --- | --- |
| [getSmoothingMode()](#getSmoothingMode--) | Gets or sets the smoothing mode |
| [setSmoothingMode(byte value)](#setSmoothingMode-byte-) | Gets or sets the smoothing mode |
| [getAntiAliasing()](#getAntiAliasing--) | Gets or sets a value indicating whether [anti aliasing]. |
| [setAntiAliasing(boolean value)](#setAntiAliasing-boolean-) | Gets or sets a value indicating whether [anti aliasing]. |
### EmfPlusSetAntiAliasMode(EmfPlusRecord source) {#EmfPlusSetAntiAliasMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetAntiAliasMode(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusSetAntiAliasMode` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getSmoothingMode() {#getSmoothingMode--}
```
public byte getSmoothingMode()
```


Gets or sets the smoothing mode. (7 bits): The smoothing mode value, from the SmoothingMode enumeration (section 2.1.1.28)

Value: The smoothing mode.

**Returns:**
byte
### setSmoothingMode(byte value) {#setSmoothingMode-byte-}
```
public void setSmoothingMode(byte value)
```


Gets or sets the smoothing mode. (7 bits): The smoothing mode value, from the SmoothingMode enumeration (section 2.1.1.28)

Value: The smoothing mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAntiAliasing() {#getAntiAliasing--}
```
public boolean getAntiAliasing()
```


Gets or sets a value indicating whether [anti aliasing]. If set, anti-aliasing SHOULD be performed. If clear, anti-aliasing SHOULD NOT be performed.

Value: `true` if [anti aliasing]; otherwise, `false`.

**Returns:**
boolean
### setAntiAliasing(boolean value) {#setAntiAliasing-boolean-}
```
public void setAntiAliasing(boolean value)
```


Gets or sets a value indicating whether [anti aliasing]. If set, anti-aliasing SHOULD be performed. If clear, anti-aliasing SHOULD NOT be performed.

Value: `true` if [anti aliasing]; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

