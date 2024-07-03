---
title: EmfMetafileHeaderExtension1
second_title: Aspose.Imaging for Java API Reference
description: The EmfMetafileHeaderExtension1 record is the header record used in the first extension to EMF metafiles.
type: docs
weight: 71
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader)
```
public class EmfMetafileHeaderExtension1 extends EmfMetafileHeader
```

The EmfMetafileHeaderExtension1 record is the header record used in the first extension to EMF metafiles. Following the EmfHeaderExtension1 field, the remaining fields are optional and can be present in any order.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfMetafileHeaderExtension1(EmfMetafileHeader header)](#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | Initializes a new instance of the `EmfMetafileHeaderExtension1` class. |
| [EmfMetafileHeaderExtension1(EmfMetafileHeaderExtension1 header)](#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension1-) | Initializes a new instance of the `EmfMetafileHeaderExtension1` class. |
## Methods

| Method | Description |
| --- | --- |
| [getEmfHeaderExtension1()](#getEmfHeaderExtension1--) | Gets or sets a HeaderExtension1 object, which specifies additional information about the image in the metafile. |
| [setEmfHeaderExtension1(EmfHeaderExtension1 value)](#setEmfHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension1-) | Gets or sets a HeaderExtension1 object, which specifies additional information about the image in the metafile. |
| [getEmfPixelFormatBuffer()](#getEmfPixelFormatBuffer--) | Gets or sets an optional array of bytes that contains the EMF pixel format descriptor, which is not required to be contiguous with the fixed portion of the EmfMetafileHeaderExtension1 record or with the EMF description string. |
| [setEmfPixelFormatBuffer(byte[] value)](#setEmfPixelFormatBuffer-byte---) | Gets or sets an optional array of bytes that contains the EMF pixel format descriptor, which is not required to be contiguous with the fixed portion of the EmfMetafileHeaderExtension1 record or with the EMF description string. |
### EmfMetafileHeaderExtension1(EmfMetafileHeader header) {#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public EmfMetafileHeaderExtension1(EmfMetafileHeader header)
```


Initializes a new instance of the `EmfMetafileHeaderExtension1` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| header | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) | The header. |

### EmfMetafileHeaderExtension1(EmfMetafileHeaderExtension1 header) {#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension1-}
```
public EmfMetafileHeaderExtension1(EmfMetafileHeaderExtension1 header)
```


Initializes a new instance of the `EmfMetafileHeaderExtension1` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| header | [EmfMetafileHeaderExtension1](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1) | The header. |

### getEmfHeaderExtension1() {#getEmfHeaderExtension1--}
```
public EmfHeaderExtension1 getEmfHeaderExtension1()
```


Gets or sets a HeaderExtension1 object, which specifies additional information about the image in the metafile.

**Returns:**
[EmfHeaderExtension1](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1)
### setEmfHeaderExtension1(EmfHeaderExtension1 value) {#setEmfHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension1-}
```
public void setEmfHeaderExtension1(EmfHeaderExtension1 value)
```


Gets or sets a HeaderExtension1 object, which specifies additional information about the image in the metafile.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfHeaderExtension1](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1) |  |

### getEmfPixelFormatBuffer() {#getEmfPixelFormatBuffer--}
```
public byte[] getEmfPixelFormatBuffer()
```


Gets or sets an optional array of bytes that contains the EMF pixel format descriptor, which is not required to be contiguous with the fixed portion of the EmfMetafileHeaderExtension1 record or with the EMF description string. Accordingly, the field in this buffer that is labeled "UndefinedSpace" is optional and MUST be ignored

**Returns:**
byte[]
### setEmfPixelFormatBuffer(byte[] value) {#setEmfPixelFormatBuffer-byte---}
```
public void setEmfPixelFormatBuffer(byte[] value)
```


Gets or sets an optional array of bytes that contains the EMF pixel format descriptor, which is not required to be contiguous with the fixed portion of the EmfMetafileHeaderExtension1 record or with the EMF description string. Accordingly, the field in this buffer that is labeled "UndefinedSpace" is optional and MUST be ignored

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

