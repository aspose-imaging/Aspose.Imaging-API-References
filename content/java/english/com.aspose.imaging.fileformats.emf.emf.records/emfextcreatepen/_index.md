---
title: EmfExtCreatePen
second_title: Aspose.Imaging for Java API Reference
description: The EMR_EXTCREATEPEN record defines an extended logical pen for graphics operations.
type: docs
weight: 51
url: /com.aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfExtCreatePen extends EmfObjectCreationRecordType
```

The EMR\_EXTCREATEPEN record defines an extended logical pen for graphics operations. An optional DIB can be specified to use as the line style.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfExtCreatePen(EmfRecord record)](#EmfExtCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfExtCreatePen` class. |
| [EmfExtCreatePen()](#EmfExtCreatePen--) | Initializes a new instance of the `EmfExtCreatePen` class. |
## Methods

| Method | Description |
| --- | --- |
| [getIhPen()](#getIhPen--) | Gets or sets 32-bit unsigned integer that specifies the index of the extended logical pen object in the EMF Object Table (section 3.1.1.1). |
| [setIhPen(int value)](#setIhPen-int-) | Gets or sets 32-bit unsigned integer that specifies the index of the extended logical pen object in the EMF Object Table (section 3.1.1.1). |
| [getElp()](#getElp--) | Gets or sets a LogPenEx object (section 2.2.20) that specifies an extended logical pen with attributes including an optional line style array. |
| [setElp(EmfLogPenEx value)](#setElp-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPenEx-) | Gets or sets a LogPenEx object (section 2.2.20) that specifies an extended logical pen with attributes including an optional line style array. |
| [getBitmapBuffer()](#getBitmapBuffer--) | Gets or sets an optional buffer containing a packed DIB in the form of a WMF DeviceIndependentBitmap object ([MS-WMF] section 2.2.2.9). |
| [setBitmapBuffer(WmfDeviceIndependentBitmap value)](#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Gets or sets an optional buffer containing a packed DIB in the form of a WMF DeviceIndependentBitmap object ([MS-WMF] section 2.2.2.9). |
### EmfExtCreatePen(EmfRecord record) {#EmfExtCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtCreatePen(EmfRecord record)
```


Initializes a new instance of the `EmfExtCreatePen` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The record. |

### EmfExtCreatePen() {#EmfExtCreatePen--}
```
public EmfExtCreatePen()
```


Initializes a new instance of the `EmfExtCreatePen` class.

### getIhPen() {#getIhPen--}
```
public int getIhPen()
```


Gets or sets 32-bit unsigned integer that specifies the index of the extended logical pen object in the EMF Object Table (section 3.1.1.1). This index MUST be saved so that this object can be reused or modified.

**Returns:**
int
### setIhPen(int value) {#setIhPen-int-}
```
public void setIhPen(int value)
```


Gets or sets 32-bit unsigned integer that specifies the index of the extended logical pen object in the EMF Object Table (section 3.1.1.1). This index MUST be saved so that this object can be reused or modified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getElp() {#getElp--}
```
public EmfLogPenEx getElp()
```


Gets or sets a LogPenEx object (section 2.2.20) that specifies an extended logical pen with attributes including an optional line style array.

**Returns:**
[EmfLogPenEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpenex)
### setElp(EmfLogPenEx value) {#setElp-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPenEx-}
```
public void setElp(EmfLogPenEx value)
```


Gets or sets a LogPenEx object (section 2.2.20) that specifies an extended logical pen with attributes including an optional line style array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfLogPenEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpenex) |  |

### getBitmapBuffer() {#getBitmapBuffer--}
```
public WmfDeviceIndependentBitmap getBitmapBuffer()
```


Gets or sets an optional buffer containing a packed DIB in the form of a WMF DeviceIndependentBitmap object ([MS-WMF] section 2.2.2.9). It is not required to be contiguous with the fixed portion of the EMR\_EXTCREATEPEN record

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBitmapBuffer(WmfDeviceIndependentBitmap value) {#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBitmapBuffer(WmfDeviceIndependentBitmap value)
```


Gets or sets an optional buffer containing a packed DIB in the form of a WMF DeviceIndependentBitmap object ([MS-WMF] section 2.2.2.9). It is not required to be contiguous with the fixed portion of the EMR\_EXTCREATEPEN record

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

