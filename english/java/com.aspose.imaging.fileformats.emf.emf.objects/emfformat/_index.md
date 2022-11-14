---
title: EmfFormat
second_title: Aspose.Imaging for Java API Reference
description: The EmrFormat object contains information that identifies the format of image data in an EMR_COMMENT_MULTIFORMATS recordsection 2.3.3.4.3.
type: docs
weight: 15
url: /java/com.aspose.imaging.fileformats.emf.emf.objects/emfformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfFormat extends EmfObject
```

The EmrFormat object contains information that identifies the format of image data in an EMR\_COMMENT\_MULTIFORMATS record(section 2.3.3.4.3).
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfFormat()](#EmfFormat--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getSignature()](#getSignature--) | Gets or sets a 32-bit unsigned integer that specifies the format of the image data. |
| [setSignature(int value)](#setSignature-int-) | Gets or sets a 32-bit unsigned integer that specifies the format of the image data. |
| [getVersion()](#getVersion--) | Gets or sets a 32-bit unsigned integer that specifies the format version number. |
| [setVersion(int value)](#setVersion-int-) | Gets or sets a 32-bit unsigned integer that specifies the format version number. |
| [getSizeData()](#getSizeData--) | Gets or sets a 32-bit unsigned integer that specifies the size of the data in bytes |
| [setSizeData(int value)](#setSizeData-int-) | Gets or sets a 32-bit unsigned integer that specifies the size of the data in bytes |
| [getOffData()](#getOffData--) | Gets or sets 32-bit unsigned integer that specifies the offset to the data from the start of the identifier field in an EMR\_COMMENT\_PUBLIC record (section 2.3.3.4). |
| [setOffData(int value)](#setOffData-int-) | Gets or sets 32-bit unsigned integer that specifies the offset to the data from the start of the identifier field in an EMR\_COMMENT\_PUBLIC record (section 2.3.3.4). |
### EmfFormat() {#EmfFormat--}
```
public EmfFormat()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


Gets or sets a 32-bit unsigned integer that specifies the format of the image data. This value MUST be in the FormatSignature enumeration (section 2.1.14).

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the format of the image data. This value MUST be in the FormatSignature enumeration (section 2.1.14).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Gets or sets a 32-bit unsigned integer that specifies the format version number. If the Signature field specifies encapsulated PostScript (EPS), this value MUST be 0x00000001; otherwise, this value MUST be ignored

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the format version number. If the Signature field specifies encapsulated PostScript (EPS), this value MUST be 0x00000001; otherwise, this value MUST be ignored

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSizeData() {#getSizeData--}
```
public int getSizeData()
```


Gets or sets a 32-bit unsigned integer that specifies the size of the data in bytes

**Returns:**
int
### setSizeData(int value) {#setSizeData-int-}
```
public void setSizeData(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the size of the data in bytes

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getOffData() {#getOffData--}
```
public int getOffData()
```


Gets or sets 32-bit unsigned integer that specifies the offset to the data from the start of the identifier field in an EMR\_COMMENT\_PUBLIC record (section 2.3.3.4). The offset MUST be 32-bit aligned.

**Returns:**
int
### setOffData(int value) {#setOffData-int-}
```
public void setOffData(int value)
```


Gets or sets 32-bit unsigned integer that specifies the offset to the data from the start of the identifier field in an EMR\_COMMENT\_PUBLIC record (section 2.3.3.4). The offset MUST be 32-bit aligned.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

