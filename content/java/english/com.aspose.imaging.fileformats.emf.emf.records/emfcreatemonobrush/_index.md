---
title: EmfCreateMonoBrush
second_title: Aspose.Imaging for Java API Reference
description: The EMR_CREATEMONOBRUSH record defines a monochrome pattern brush for graphics operations.
type: docs
weight: 38
url: /com.aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateMonoBrush extends EmfObjectCreationRecordType
```

The EMR\_CREATEMONOBRUSH record defines a monochrome pattern brush for graphics operations. The pattern is specified by a monochrome DIB.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfCreateMonoBrush(EmfRecord source)](#EmfCreateMonoBrush-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfCreateMonoBrush` class. |
## Methods

| Method | Description |
| --- | --- |
| [getIhBrush()](#getIhBrush--) | Gets or sets a 32-bit unsigned integer that specifies the index of the monochrome pattern brush object in the EMF Object Table (section 3.1.1.1). |
| [setIhBrush(int value)](#setIhBrush-int-) | Gets or sets a 32-bit unsigned integer that specifies the index of the monochrome pattern brush object in the EMF Object Table (section 3.1.1.1). |
| [getUsage()](#getUsage--) | Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the DIB header. |
| [setUsage(int value)](#setUsage-int-) | Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the DIB header. |
| [getBitmapBuffer()](#getBitmapBuffer--) | Gets or sets a buffer containing a packed DIB in the form of a WMF DeviceIndependentBitmap object ([MS-WMF] section 2.2.2.9). |
| [setBitmapBuffer(WmfDeviceIndependentBitmap value)](#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Gets or sets a buffer containing a packed DIB in the form of a WMF DeviceIndependentBitmap object ([MS-WMF] section 2.2.2.9). |
### EmfCreateMonoBrush(EmfRecord source) {#EmfCreateMonoBrush-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateMonoBrush(EmfRecord source)
```


Initializes a new instance of the `EmfCreateMonoBrush` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Gets or sets a 32-bit unsigned integer that specifies the index of the monochrome pattern brush object in the EMF Object Table (section 3.1.1.1). This index MUST be saved so that this object can be reused or modified.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the index of the monochrome pattern brush object in the EMF Object Table (section 3.1.1.1). This index MUST be saved so that this object can be reused or modified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getUsage() {#getUsage--}
```
public int getUsage()
```


Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the DIB header. This value MUST be in the DIBColors enumeration (section 2.1.9).

**Returns:**
int
### setUsage(int value) {#setUsage-int-}
```
public void setUsage(int value)
```


Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the DIB header. This value MUST be in the DIBColors enumeration (section 2.1.9).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBitmapBuffer() {#getBitmapBuffer--}
```
public WmfDeviceIndependentBitmap getBitmapBuffer()
```


Gets or sets a buffer containing a packed DIB in the form of a WMF DeviceIndependentBitmap object ([MS-WMF] section 2.2.2.9). It is not required to be contiguous with the fixed portion of the EMR\_CREATEDIBPATTERNBRUSHPT record.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBitmapBuffer(WmfDeviceIndependentBitmap value) {#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBitmapBuffer(WmfDeviceIndependentBitmap value)
```


Gets or sets a buffer containing a packed DIB in the form of a WMF DeviceIndependentBitmap object ([MS-WMF] section 2.2.2.9). It is not required to be contiguous with the fixed portion of the EMR\_CREATEDIBPATTERNBRUSHPT record.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

