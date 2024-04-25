---
title: EmfColorMatchToTargetW
second_title: Aspose.Imaging for Java API Reference
description: The EMR_COLORMATCHTOTargetW record specifies whether to perform color matching with a color profile that is specified in a file with a name consisting of Unicode characters.
type: docs
weight: 23
url: /com.aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfColorMatchToTargetW extends EmfStateRecordType
```

The EMR\_COLORMATCHTOTargetW record specifies whether to perform color matching with a color profile that is specified in a file with a name consisting of Unicode characters.

An EMR\_COLORMATCHTOTargetW record can be used to control whether to apply the current color transform in the playback device context. If the dwAction value is CS\_ENABLE, color mapping is enabled, and the current color transform SHOULD be applied to subsequent graphics operations. If dwAction is set to CS\_DISABLE, the color transform SHOULD NOT be applied. While color mapping to the target is enabled by a dwAction value of CS\_ENABLE, changes to the color space or color gamut mapping are not applied. However, those changes MUST take effect when color mapping to the target is disabled. The dwAction field SHOULD NOT be set to CS\_DELETE\_TRANSFORM unless color management has already been enabled with an EMR\_SETICMMODE record (section 2.3.11.14).
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfColorMatchToTargetW(EmfRecord source)](#EmfColorMatchToTargetW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfColorMatchToTargetW` class. |
## Methods

| Method | Description |
| --- | --- |
| [getDwAction()](#getDwAction--) | Gets or sets a 32-bit unsigned integer that specifies a value from the ColorSpace enumeration (section 2.1.7). |
| [setDwAction(int value)](#setDwAction-int-) | Gets or sets a 32-bit unsigned integer that specifies a value from the ColorSpace enumeration (section 2.1.7). |
| [getDwFlags()](#getDwFlags--) | Gets or sets a 32-bit unsigned integer that specifies a value from the ColorMatchToTarget enumeration (section 2.1.6). |
| [setDwFlags(int value)](#setDwFlags-int-) | Gets or sets a 32-bit unsigned integer that specifies a value from the ColorMatchToTarget enumeration (section 2.1.6). |
| [getCbName()](#getCbName--) | Gets or sets a 32-bit unsigned integer that specifies the number of bytes in the Unicode UTF16-LE name of the desired color profile. |
| [setCbName(int value)](#setCbName-int-) | Gets or sets a 32-bit unsigned integer that specifies the number of bytes in the Unicode UTF16-LE name of the desired color profile. |
| [getCbData()](#getCbData--) | Gets or sets a 32-bit unsigned integer that specifies the size of the raw data of the target color profile, if it is contained in the Data field. |
| [setCbData(int value)](#setCbData-int-) | Gets or sets a 32-bit unsigned integer that specifies the size of the raw data of the target color profile, if it is contained in the Data field. |
| [getData()](#getData--) | Gets or sets an array of size (cbName + cbData) in bytes, which specifies the UTF16-LE name and raw data of the desired color profile. |
| [setData(byte[] value)](#setData-byte---) | Gets or sets an array of size (cbName + cbData) in bytes, which specifies the UTF16-LE name and raw data of the desired color profile. |
| [getName()](#getName--) | Gets the name |
| [getRawData()](#getRawData--) | Gets the raw data |
### EmfColorMatchToTargetW(EmfRecord source) {#EmfColorMatchToTargetW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfColorMatchToTargetW(EmfRecord source)
```


Initializes a new instance of the `EmfColorMatchToTargetW` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getDwAction() {#getDwAction--}
```
public int getDwAction()
```


Gets or sets a 32-bit unsigned integer that specifies a value from the ColorSpace enumeration (section 2.1.7).

**Returns:**
int
### setDwAction(int value) {#setDwAction-int-}
```
public void setDwAction(int value)
```


Gets or sets a 32-bit unsigned integer that specifies a value from the ColorSpace enumeration (section 2.1.7).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Gets or sets a 32-bit unsigned integer that specifies a value from the ColorMatchToTarget enumeration (section 2.1.6).

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Gets or sets a 32-bit unsigned integer that specifies a value from the ColorMatchToTarget enumeration (section 2.1.6).

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


Gets or sets a 32-bit unsigned integer that specifies the size of the raw data of the target color profile, if it is contained in the Data field.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the size of the raw data of the target color profile, if it is contained in the Data field.

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
