---
title: EmfCreateColorSpace
second_title: Aspose.Imaging for Java API Reference
description: The EMR_CREATECOLORSPACE record creates a logical color space object from a color profile with a name consisting of ASCII characters.
type: docs
weight: 36
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateColorSpace extends EmfObjectCreationRecordType
```

The EMR\_CREATECOLORSPACE record creates a logical color space object from a color profile with a name consisting of ASCII characters.

The logical color space object defined by this record can be selected into the playback device context by an EMR\_SETCOLORSPACE record (section 2.3.8.7), which defines the logical color space to use in subsequent graphics operations.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfCreateColorSpace(EmfRecord source)](#EmfCreateColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfCreateColorSpace` class. |
## Methods

| Method | Description |
| --- | --- |
| [getIhCS()](#getIhCS--) | Gets or sets a 32-bit unsigned integer that specifies the index of the logical color space object in the EMF object table (section 3.1.1.1). |
| [setIhCS(int value)](#setIhCS-int-) | Gets or sets a 32-bit unsigned integer that specifies the index of the logical color space object in the EMF object table (section 3.1.1.1). |
| [getLcs()](#getLcs--) | Gets or sets a WMF LogColorSpace object ([MS-WMF] section 2.2.2.11), which can specify the name of a color profile in ASCII characters. |
| [setLcs(WmfLogColorSpace value)](#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpace-) | Gets or sets a WMF LogColorSpace object ([MS-WMF] section 2.2.2.11), which can specify the name of a color profile in ASCII characters. |
### EmfCreateColorSpace(EmfRecord source) {#EmfCreateColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateColorSpace(EmfRecord source)
```


Initializes a new instance of the `EmfCreateColorSpace` class.

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
public WmfLogColorSpace getLcs()
```


Gets or sets a WMF LogColorSpace object ([MS-WMF] section 2.2.2.11), which can specify the name of a color profile in ASCII characters.

**Returns:**
[WmfLogColorSpace](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspace)
### setLcs(WmfLogColorSpace value) {#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpace-}
```
public void setLcs(WmfLogColorSpace value)
```


Gets or sets a WMF LogColorSpace object ([MS-WMF] section 2.2.2.11), which can specify the name of a color profile in ASCII characters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WmfLogColorSpace](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspace) |  |

