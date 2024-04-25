---
title: EmfNamedEscape
second_title: Aspose.Imaging for Java API Reference
description: The MR_NAMEDESCAPE record passes arbitrary information to a specified printer driver.
type: docs
weight: 74
url: /com.aspose.imaging.fileformats.emf.emf.records/emfnamedescape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfEscapeRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype)
```
public final class EmfNamedEscape extends EmfEscapeRecordType
```

The MR\_NAMEDESCAPE record passes arbitrary information to a specified printer driver.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfNamedEscape(EmfRecord source)](#EmfNamedEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfNamedEscape` class. |
## Methods

| Method | Description |
| --- | --- |
| [getCjDriver()](#getCjDriver--) | Gets or sets A 32-bit unsigned integer that specifies the number of bytes in the DriverName field. |
| [setCjDriver(int value)](#setCjDriver-int-) | Gets or sets A 32-bit unsigned integer that specifies the number of bytes in the DriverName field. |
| [getCjIn()](#getCjIn--) | Gets or sets A 32-bit unsigned integer specifying the number of bytes to pass to the printer driver. |
| [setCjIn(int value)](#setCjIn-int-) | Gets or sets A 32-bit unsigned integer specifying the number of bytes to pass to the printer driver. |
| [getDriverName()](#getDriverName--) | Gets or sets A string of 16-bit Unicode characters that specifies the name of the printer driver that will receive data. |
| [setDriverName(String value)](#setDriverName-java.lang.String-) | Gets or sets A string of 16-bit Unicode characters that specifies the name of the printer driver that will receive data. |
| [getData()](#getData--) | Gets or sets The data to pass to the printer driver. |
| [setData(byte[] value)](#setData-byte---) | Gets or sets The data to pass to the printer driver. |
### EmfNamedEscape(EmfRecord source) {#EmfNamedEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfNamedEscape(EmfRecord source)
```


Initializes a new instance of the `EmfNamedEscape` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getCjDriver() {#getCjDriver--}
```
public int getCjDriver()
```


Gets or sets A 32-bit unsigned integer that specifies the number of bytes in the DriverName field. This value MUST be an even number.

**Returns:**
int
### setCjDriver(int value) {#setCjDriver-int-}
```
public void setCjDriver(int value)
```


Gets or sets A 32-bit unsigned integer that specifies the number of bytes in the DriverName field. This value MUST be an even number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCjIn() {#getCjIn--}
```
public int getCjIn()
```


Gets or sets A 32-bit unsigned integer specifying the number of bytes to pass to the printer driver.

**Returns:**
int
### setCjIn(int value) {#setCjIn-int-}
```
public void setCjIn(int value)
```


Gets or sets A 32-bit unsigned integer specifying the number of bytes to pass to the printer driver.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDriverName() {#getDriverName--}
```
public String getDriverName()
```


Gets or sets A string of 16-bit Unicode characters that specifies the name of the printer driver that will receive data. This value MUST be cjDriver bytes long, and it MUST be terminated with a null character.

**Returns:**
java.lang.String
### setDriverName(String value) {#setDriverName-java.lang.String-}
```
public void setDriverName(String value)
```


Gets or sets A string of 16-bit Unicode characters that specifies the name of the printer driver that will receive data. This value MUST be cjDriver bytes long, and it MUST be terminated with a null character.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public byte[] getData()
```


Gets or sets The data to pass to the printer driver. There MUST be cjIn bytes available.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Gets or sets The data to pass to the printer driver. There MUST be cjIn bytes available.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

