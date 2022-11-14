---
title: EmfSetIcmProfileW
second_title: Aspose.Imaging for Java API Reference
description: The EMR_SETICMPROFILEW record specifies a color profile in a file with a name consisting of Unicode characters for graphics output.
type: docs
weight: 124
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetIcmProfileW extends EmfStateRecordType
```

The EMR\_SETICMPROFILEW record specifies a color profile in a file with a name consisting of Unicode characters, for graphics output.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfSetIcmProfileW(EmfRecord source)](#EmfSetIcmProfileW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfSetIcmProfileW` class. |
## Methods

| Method | Description |
| --- | --- |
| [getDwFlags()](#getDwFlags--) | Gets or sets a 32-bit unsigned integer that contains color profile flags. |
| [setDwFlags(int value)](#setDwFlags-int-) | Gets or sets a 32-bit unsigned integer that contains color profile flags. |
| [getCbName()](#getCbName--) | Gets or sets a 32-bit unsigned integer that specifies the number of bytes in the Unicode UTF16-LE name of the desired color profile. |
| [setCbName(int value)](#setCbName-int-) | Gets or sets a 32-bit unsigned integer that specifies the number of bytes in the Unicode UTF16-LE name of the desired color profile. |
| [getCbData()](#getCbData--) | Gets or sets a 32-bit unsigned integer that specifies the size of color profile data, if attached. |
| [setCbData(int value)](#setCbData-int-) | Gets or sets a 32-bit unsigned integer that specifies the size of color profile data, if attached. |
| [getData()](#getData--) | Gets or sets an array of size (cbName + cbData) in bytes, which specifies the UTF16-LE name and raw data of the desired color profile. |
| [setData(byte[] value)](#setData-byte---) | Gets or sets an array of size (cbName + cbData) in bytes, which specifies the UTF16-LE name and raw data of the desired color profile. |
| [getName()](#getName--) | Gets the name |
| [getRawData()](#getRawData--) | Gets the raw data |
### EmfSetIcmProfileW(EmfRecord source) {#EmfSetIcmProfileW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetIcmProfileW(EmfRecord source)
```


Initializes a new instance of the `EmfSetIcmProfileW` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Gets or sets a 32-bit unsigned integer that contains color profile flags.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Gets or sets a 32-bit unsigned integer that contains color profile flags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCbName() {#getCbName--}
```
public int getCbName()
```


Gets or sets a 32-bit unsigned integer that specifies the number of bytes in the Unicode UTF16-LE name of the desired color profile.

**Returns:**
int
### setCbName(int value) {#setCbName-int-}
```
public void setCbName(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the number of bytes in the Unicode UTF16-LE name of the desired color profile.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Gets or sets a 32-bit unsigned integer that specifies the size of color profile data, if attached.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the size of color profile data, if attached.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Gets or sets an array of size (cbName + cbData) in bytes, which specifies the UTF16-LE name and raw data of the desired color profile.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Gets or sets an array of size (cbName + cbData) in bytes, which specifies the UTF16-LE name and raw data of the desired color profile.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### getName() {#getName--}
```
public String getName()
```


Gets the name

**Returns:**
java.lang.String
### getRawData() {#getRawData--}
```
public byte[] getRawData()
```


Gets the raw data

**Returns:**
byte[]
