---
title: EmfMetafileHeader
second_title: Aspose.Imaging for Java API Reference
description: The EMR_HEADER record types define the starting points of EMF metafiles and specify properties of the device on which the image in the metafile was created.
type: docs
weight: 69
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public class EmfMetafileHeader extends EmfRecord
```

The EMR\_HEADER record types define the starting points of EMF metafiles and specify properties of the device on which the image in the metafile was created. The information in the header record makes it possible for EMF metafiles to be independent of any specific output device. The value of the Size field can be used to distinguish between the different EMR\_HEADER record types listed earlier in this section. There are three possible headers: The base header, which is the EmfMetafileHeader record. The fixed-size part of this header is 88 bytes, and it contains a Header object. The first extension header, which is the EmfMetafileHeaderExtension1 record. The fixed-size part of this header is 100 bytes, and it contains a Header object and a HeaderExtension1 object (section 2.2.10). The second extension header, which is the EmfMetafileHeaderExtension2 record. The fixed-size part of this header is 108 bytes, and it contains a Header object, a HeaderExtension1 object, and a HeaderExtension2 object (section 2.2.11).
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfMetafileHeader(EmfRecord record)](#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfMetafileHeader` class. |
| [EmfMetafileHeader()](#EmfMetafileHeader--) | Initializes a new instance of the `EmfMetafileHeader` class. |
| [EmfMetafileHeader(EmfMetafileHeader header)](#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | Initializes a new instance of the `EmfMetafileHeader` class. |
## Methods

| Method | Description |
| --- | --- |
| [getEmfHeader()](#getEmfHeader--) | Gets a Header object (section 2.2.9), which contains information about the content and structure of the metafile |
| [setEmfHeader(EmfHeaderObject value)](#setEmfHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject-) | Sets a Header object (section 2.2.9), which contains information about the content and structure of the metafile |
| [getEmfHeaderRecordBuffer()](#getEmfHeaderRecordBuffer--) | Gets an optional array of bytes that contains the remainder of the EMF header record. |
| [setEmfHeaderRecordBuffer(byte[] value)](#setEmfHeaderRecordBuffer-byte---) | Sets an optional array of bytes that contains the remainder of the EMF header record. |
| [getEmfDescriptionBuffer()](#getEmfDescriptionBuffer--) | Gets the EMF description buffer An optional array of bytes that contains the EMF description string, which is not required to be contiguous with the fixed portion of the EmfMetafileHeader record. |
| [setEmfDescriptionBuffer(byte[] value)](#setEmfDescriptionBuffer-byte---) | Sets the EMF description buffer An optional array of bytes that contains the EMF description string, which is not required to be contiguous with the fixed portion of the EmfMetafileHeader record. |
| [getEmfDescription()](#getEmfDescription--) | Gets the EMF description An optional, null-terminated Unicode UTF16-LE string of arbitrary length and content. |
| [setEmfDescription(String value)](#setEmfDescription-java.lang.String-) | Sets the EMF description An optional, null-terminated Unicode UTF16-LE string of arbitrary length and content. |
### EmfMetafileHeader(EmfRecord record) {#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfMetafileHeader(EmfRecord record)
```


Initializes a new instance of the `EmfMetafileHeader` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The record. |

### EmfMetafileHeader() {#EmfMetafileHeader--}
```
public EmfMetafileHeader()
```


Initializes a new instance of the `EmfMetafileHeader` class.

### EmfMetafileHeader(EmfMetafileHeader header) {#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public EmfMetafileHeader(EmfMetafileHeader header)
```


Initializes a new instance of the `EmfMetafileHeader` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| header | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) | The header. |

### getEmfHeader() {#getEmfHeader--}
```
public EmfHeaderObject getEmfHeader()
```


Gets a Header object (section 2.2.9), which contains information about the content and structure of the metafile

**Returns:**
[EmfHeaderObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject)
### setEmfHeader(EmfHeaderObject value) {#setEmfHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject-}
```
public void setEmfHeader(EmfHeaderObject value)
```


Sets a Header object (section 2.2.9), which contains information about the content and structure of the metafile

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfHeaderObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject) |  |

### getEmfHeaderRecordBuffer() {#getEmfHeaderRecordBuffer--}
```
public byte[] getEmfHeaderRecordBuffer()
```


Gets an optional array of bytes that contains the remainder of the EMF header record. The size of this field MUST be a multiple of 4 bytes

**Returns:**
byte[]
### setEmfHeaderRecordBuffer(byte[] value) {#setEmfHeaderRecordBuffer-byte---}
```
public void setEmfHeaderRecordBuffer(byte[] value)
```


Sets an optional array of bytes that contains the remainder of the EMF header record. The size of this field MUST be a multiple of 4 bytes

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### getEmfDescriptionBuffer() {#getEmfDescriptionBuffer--}
```
public byte[] getEmfDescriptionBuffer()
```


Gets the EMF description buffer An optional array of bytes that contains the EMF description string, which is not required to be contiguous with the fixed portion of the EmfMetafileHeader record. Accordingly, the field in this buffer that is labeled "UndefinedSpace" is optional and MUST be ignored.

**Returns:**
byte[]
### setEmfDescriptionBuffer(byte[] value) {#setEmfDescriptionBuffer-byte---}
```
public void setEmfDescriptionBuffer(byte[] value)
```


Sets the EMF description buffer An optional array of bytes that contains the EMF description string, which is not required to be contiguous with the fixed portion of the EmfMetafileHeader record. Accordingly, the field in this buffer that is labeled "UndefinedSpace" is optional and MUST be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### getEmfDescription() {#getEmfDescription--}
```
public String getEmfDescription()
```


Gets the EMF description An optional, null-terminated Unicode UTF16-LE string of arbitrary length and content. Its location in the record and number of characters are specified by the offDescription and nDescription fields, respectively, in EmfHeader. If the value of either field is zero, no description string is present.

**Returns:**
java.lang.String
### setEmfDescription(String value) {#setEmfDescription-java.lang.String-}
```
public void setEmfDescription(String value)
```


Sets the EMF description An optional, null-terminated Unicode UTF16-LE string of arbitrary length and content. Its location in the record and number of characters are specified by the offDescription and nDescription fields, respectively, in EmfHeader. If the value of either field is zero, no description string is present.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

