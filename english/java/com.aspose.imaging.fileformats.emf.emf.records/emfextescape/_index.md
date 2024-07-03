---
title: EmfExtEscape
second_title: Aspose.Imaging for Java API Reference
description: The EMR_EXTESCAPE record passes arbitrary information to a printer driver.
type: docs
weight: 53
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfextescape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfEscapeRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype)
```
public final class EmfExtEscape extends EmfEscapeRecordType
```

The EMR\_EXTESCAPE record passes arbitrary information to a printer driver. The intent is that the information will not result in drawing being done.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfExtEscape(EmfRecord source)](#EmfExtEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfExtEscape` class. |
## Methods

| Method | Description |
| --- | --- |
| [getCjIn()](#getCjIn--) | Gets or sets a 32-bit unsigned integer specifying the number of bytes to pass to the printer driver. |
| [setCjIn(int value)](#setCjIn-int-) | Gets or sets a 32-bit unsigned integer specifying the number of bytes to pass to the printer driver. |
| [getData()](#getData--) | Gets or sets the data to pass to the printer driver. |
| [setData(byte[] value)](#setData-byte---) | Gets or sets the data to pass to the printer driver. |
### EmfExtEscape(EmfRecord source) {#EmfExtEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtEscape(EmfRecord source)
```


Initializes a new instance of the `EmfExtEscape` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getCjIn() {#getCjIn--}
```
public int getCjIn()
```


Gets or sets a 32-bit unsigned integer specifying the number of bytes to pass to the printer driver.

**Returns:**
int
### setCjIn(int value) {#setCjIn-int-}
```
public void setCjIn(int value)
```


Gets or sets a 32-bit unsigned integer specifying the number of bytes to pass to the printer driver.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Gets or sets the data to pass to the printer driver. There MUST be cjIn bytes available.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Gets or sets the data to pass to the printer driver. There MUST be cjIn bytes available.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

