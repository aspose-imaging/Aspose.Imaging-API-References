---
title: EmfCreateColorSpaceW
second_title: Aspose.Imaging for Java API Reference
description: The EMR_CREATECOLORSPACEW record creates a logical color space object from a color profile with a name consisting of Unicode characters.
type: docs
weight: 36
url: /com.aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateColorSpaceW extends EmfObjectCreationRecordType
```

The EMR\_CREATECOLORSPACEW record creates a logical color space object from a color profile with a name consisting of Unicode characters.

The logical color space object defined by this record can be selected into the playback device context by an EMR\_SETCOLORSPACE record (section 2.3.8.7), which defines the logical color space to use in subsequent graphics operations.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfCreateColorSpaceW(EmfRecord source)](#EmfCreateColorSpaceW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfCreateColorSpaceW` class. |
## Methods

| Method | Description |
| --- | --- |
| [getIhCS()](#getIhCS--) | Gets or sets a 32-bit unsigned integer that specifies the index of the logical color space object in the EMF object table (section 3.1.1.1). |
| [setIhCS(int value)](#setIhCS-int-) | Gets or sets a 32-bit unsigned integer that specifies the index of the logical color space object in the EMF object table (section 3.1.1.1). |
| [getLcs()](#getLcs--) | Gets or sets a WMF LogColorSpaceW object ([MS-WMF] section 2.2.2.12) that can specify the name of a color profile in Unicode UTF16-LE characters |
| [setLcs(WmfLogColorSpaceW value)](#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpaceW-) | Gets or sets a WMF LogColorSpaceW object ([MS-WMF] section 2.2.2.12) that can specify the name of a color profile in Unicode UTF16-LE characters |
| [getDwFlags()](#getDwFlags--) | Gets or sets a 32-bit unsigned integer that provides information about the data in this record. |
| [setDwFlags(int value)](#setDwFlags-int-) | Gets or sets a 32-bit unsigned integer that provides information about the data in this record. |
| [getCbData()](#getCbData--) | Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the Data field. |
| [setCbData(int value)](#setCbData-int-) | Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the Data field. |
| [getData()](#getData--) | Gets or sets an optional array of bytes that specifies color profile data. |
| [setData(byte[] value)](#setData-byte---) | Gets or sets an optional array of bytes that specifies color profile data. |
### EmfCreateColorSpaceW(EmfRecord source) {#EmfCreateColorSpaceW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateColorSpaceW(EmfRecord source)
```


Initializes a new instance of the `EmfCreateColorSpaceW` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getIhCS() {#getIhCS--}
```
public int getIhCS()
```


Gets or sets a 32-bit unsigned integer that specifies the index of the logical color space object in the EMF object table (section 3.1.1.1). This index MUST be saved so that this object can be reused or modified.

**Returns:**
int
### setIhCS(int value) {#setIhCS-int-}
```
public void setIhCS(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the index of the logical color space object in the EMF object table (section 3.1.1.1). This index MUST be saved so that this object can be reused or modified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLcs() {#getLcs--}
```
public WmfLogColorSpaceW getLcs()
```


Gets or sets a WMF LogColorSpaceW object ([MS-WMF] section 2.2.2.12) that can specify the name of a color profile in Unicode UTF16-LE characters

**Returns:**
[WmfLogColorSpaceW](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew)
### setLcs(WmfLogColorSpaceW value) {#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpaceW-}
```
public void setLcs(WmfLogColorSpaceW value)
```


Gets or sets a WMF LogColorSpaceW object ([MS-WMF] section 2.2.2.12) that can specify the name of a color profile in Unicode UTF16-LE characters

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WmfLogColorSpaceW](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew) |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Gets or sets a 32-bit unsigned integer that provides information about the data in this record.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Gets or sets a 32-bit unsigned integer that provides information about the data in this record.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the Data field.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the Data field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Gets or sets an optional array of bytes that specifies color profile data.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Gets or sets an optional array of bytes that specifies color profile data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

