---
title: EmfHeaderObject
second_title: Aspose.Imaging for Java API Reference
description: The Header object defines the EMF metafile header.
type: docs
weight: 20
url: /com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public class EmfHeaderObject extends EmfObject
```

The Header object defines the EMF metafile header. It specifies properties of the device on which the image in the metafile was created.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfHeaderObject()](#EmfHeaderObject--) | Initializes a new instance of the `EmfHeaderObject` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the rectangular inclusive-inclusive bounds in device units of the smallest rectangle that can be drawn around the image stored in the metafile |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the rectangular inclusive-inclusive bounds in device units of the smallest rectangle that can be drawn around the image stored in the metafile |
| [getFrame()](#getFrame--) | Gets or sets a WMF RectL object that specifies the rectangular inclusive-inclusive dimensions, in .01 millimeter units, of a rectangle that surrounds the image stored in the metafile |
| [setFrame(Rectangle value)](#setFrame-com.aspose.imaging.Rectangle-) | Gets or sets a WMF RectL object that specifies the rectangular inclusive-inclusive dimensions, in .01 millimeter units, of a rectangle that surrounds the image stored in the metafile |
| [getRecordSignature()](#getRecordSignature--) | Gets or sets a 32-bit unsigned integer that specifies the record signature. |
| [setRecordSignature(int value)](#setRecordSignature-int-) | Gets or sets a 32-bit unsigned integer that specifies the record signature. |
| [getVersion()](#getVersion--) | Gets or sets Version (4 bytes): A 32-bit unsigned integer that specifies EMF metafile interoperability. |
| [setVersion(int value)](#setVersion-int-) | Gets or sets Version (4 bytes): A 32-bit unsigned integer that specifies EMF metafile interoperability. |
| [getBytes()](#getBytes--) | Gets or sets 32-bit unsigned integer that specifies the size of the metafile, in bytes. |
| [setBytes(int value)](#setBytes-int-) | Gets or sets 32-bit unsigned integer that specifies the size of the metafile, in bytes. |
| [getRecords()](#getRecords--) | Gets or sets a 32-bit unsigned integer that specifies the number of records in the metafile |
| [setRecords(int value)](#setRecords-int-) | Gets or sets a 32-bit unsigned integer that specifies the number of records in the metafile |
| [getHandles()](#getHandles--) | Gets or sets a 16-bit unsigned integer that specifies the number of graphics objects that will be used during the processing of the metafile |
| [setHandles(short value)](#setHandles-short-) | Gets or sets a 16-bit unsigned integer that specifies the number of graphics objects that will be used during the processing of the metafile |
| [getReserved()](#getReserved--) | Gets or sets a 16-bit unsigned integer that MUST be 0x0000 and MUST be ignored |
| [setReserved(short value)](#setReserved-short-) | Gets or sets a 16-bit unsigned integer that MUST be 0x0000 and MUST be ignored |
| [getNDesription()](#getNDesription--) | Gets or sets a 32-bit unsigned integer that specifies the number of characters in the array that contains the description of the metafile's contents. |
| [setNDesription(int value)](#setNDesription-int-) | Gets or sets a 32-bit unsigned integer that specifies the number of characters in the array that contains the description of the metafile's contents. |
| [getOffDescription()](#getOffDescription--) | Gets or sets a 32-bit unsigned integer that specifies the offset from the beginning of this record to the array that contains the description of the metafile's contents |
| [setOffDescription(int value)](#setOffDescription-int-) | Gets or sets a 32-bit unsigned integer that specifies the offset from the beginning of this record to the array that contains the description of the metafile's contents |
| [getNPalEntries()](#getNPalEntries--) | Gets or sets a 32-bit unsigned integer that specifies the number of entries in the metafile palette. |
| [setNPalEntries(int value)](#setNPalEntries-int-) | Gets or sets a 32-bit unsigned integer that specifies the number of entries in the metafile palette. |
| [getDevice()](#getDevice--) | Gets or sets a WMF SizeL object ([MS-WMF] section 2.2.2.22) that specifies the size of the reference device, in pixels |
| [setDevice(Size value)](#setDevice-com.aspose.imaging.Size-) | Gets or sets a WMF SizeL object ([MS-WMF] section 2.2.2.22) that specifies the size of the reference device, in pixels |
| [getMillimeters()](#getMillimeters--) | Gets or sets a WMF SizeL object that specifies the size of the reference device, in millimeters |
| [setMillimeters(Size value)](#setMillimeters-com.aspose.imaging.Size-) | Gets or sets a WMF SizeL object that specifies the size of the reference device, in millimeters |
| [getValid()](#getValid--) | Gets a value indicating whether this `EmfHeaderObject` is valid. |
### EmfHeaderObject() {#EmfHeaderObject--}
```
public EmfHeaderObject()
```


Initializes a new instance of the `EmfHeaderObject` class.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the rectangular inclusive-inclusive bounds in device units of the smallest rectangle that can be drawn around the image stored in the metafile

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the rectangular inclusive-inclusive bounds in device units of the smallest rectangle that can be drawn around the image stored in the metafile

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getFrame() {#getFrame--}
```
public Rectangle getFrame()
```


Gets or sets a WMF RectL object that specifies the rectangular inclusive-inclusive dimensions, in .01 millimeter units, of a rectangle that surrounds the image stored in the metafile

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setFrame(Rectangle value) {#setFrame-com.aspose.imaging.Rectangle-}
```
public void setFrame(Rectangle value)
```


Gets or sets a WMF RectL object that specifies the rectangular inclusive-inclusive dimensions, in .01 millimeter units, of a rectangle that surrounds the image stored in the metafile

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRecordSignature() {#getRecordSignature--}
```
public int getRecordSignature()
```


Gets or sets a 32-bit unsigned integer that specifies the record signature. This MUST be ENHMETA\_SIGNATURE, from the FormatSignature enumeration (section 2.1.14).

**Returns:**
int
### setRecordSignature(int value) {#setRecordSignature-int-}
```
public void setRecordSignature(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the record signature. This MUST be ENHMETA\_SIGNATURE, from the FormatSignature enumeration (section 2.1.14).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Gets or sets Version (4 bytes): A 32-bit unsigned integer that specifies EMF metafile interoperability. This SHOULD be 0x00010000

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Gets or sets Version (4 bytes): A 32-bit unsigned integer that specifies EMF metafile interoperability. This SHOULD be 0x00010000

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBytes() {#getBytes--}
```
public int getBytes()
```


Gets or sets 32-bit unsigned integer that specifies the size of the metafile, in bytes.

**Returns:**
int
### setBytes(int value) {#setBytes-int-}
```
public void setBytes(int value)
```


Gets or sets 32-bit unsigned integer that specifies the size of the metafile, in bytes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRecords() {#getRecords--}
```
public int getRecords()
```


Gets or sets a 32-bit unsigned integer that specifies the number of records in the metafile

**Returns:**
int
### setRecords(int value) {#setRecords-int-}
```
public void setRecords(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the number of records in the metafile

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHandles() {#getHandles--}
```
public short getHandles()
```


Gets or sets a 16-bit unsigned integer that specifies the number of graphics objects that will be used during the processing of the metafile

**Returns:**
short
### setHandles(short value) {#setHandles-short-}
```
public void setHandles(short value)
```


Gets or sets a 16-bit unsigned integer that specifies the number of graphics objects that will be used during the processing of the metafile

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getReserved() {#getReserved--}
```
public short getReserved()
```


Gets or sets a 16-bit unsigned integer that MUST be 0x0000 and MUST be ignored

**Returns:**
short
### setReserved(short value) {#setReserved-short-}
```
public void setReserved(short value)
```


Gets or sets a 16-bit unsigned integer that MUST be 0x0000 and MUST be ignored

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getNDesription() {#getNDesription--}
```
public int getNDesription()
```


Gets or sets a 32-bit unsigned integer that specifies the number of characters in the array that contains the description of the metafile's contents. This is zero if there is no description string.

**Returns:**
int
### setNDesription(int value) {#setNDesription-int-}
```
public void setNDesription(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the number of characters in the array that contains the description of the metafile's contents. This is zero if there is no description string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getOffDescription() {#getOffDescription--}
```
public int getOffDescription()
```


Gets or sets a 32-bit unsigned integer that specifies the offset from the beginning of this record to the array that contains the description of the metafile's contents

**Returns:**
int
### setOffDescription(int value) {#setOffDescription-int-}
```
public void setOffDescription(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the offset from the beginning of this record to the array that contains the description of the metafile's contents

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getNPalEntries() {#getNPalEntries--}
```
public int getNPalEntries()
```


Gets or sets a 32-bit unsigned integer that specifies the number of entries in the metafile palette. The palette is located in the EMR\_EOF record

**Returns:**
int
### setNPalEntries(int value) {#setNPalEntries-int-}
```
public void setNPalEntries(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the number of entries in the metafile palette. The palette is located in the EMR\_EOF record

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDevice() {#getDevice--}
```
public Size getDevice()
```


Gets or sets a WMF SizeL object ([MS-WMF] section 2.2.2.22) that specifies the size of the reference device, in pixels

**Returns:**
[Size](../../com.aspose.imaging/size)
### setDevice(Size value) {#setDevice-com.aspose.imaging.Size-}
```
public void setDevice(Size value)
```


Gets or sets a WMF SizeL object ([MS-WMF] section 2.2.2.22) that specifies the size of the reference device, in pixels

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

### getMillimeters() {#getMillimeters--}
```
public Size getMillimeters()
```


Gets or sets a WMF SizeL object that specifies the size of the reference device, in millimeters

**Returns:**
[Size](../../com.aspose.imaging/size)
### setMillimeters(Size value) {#setMillimeters-com.aspose.imaging.Size-}
```
public void setMillimeters(Size value)
```


Gets or sets a WMF SizeL object that specifies the size of the reference device, in millimeters

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

### getValid() {#getValid--}
```
public boolean getValid()
```


Gets a value indicating whether this `EmfHeaderObject` is valid.

Value: `true` if valid; otherwise, `false`.

**Returns:**
boolean
