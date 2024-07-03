---
title: EmfCreateDibPatternBrushPt
second_title: Aspose.Imaging for Java API Reference
description: The EMR_CREATEDIBPATTERNBRUSHPT record defines a pattern brush for graphics operations.
type: docs
weight: 38
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateDibPatternBrushPt extends EmfObjectCreationRecordType
```

The EMR\_CREATEDIBPATTERNBRUSHPT record defines a pattern brush for graphics operations. The pattern is specified by a DIB.

The pattern brush object defined by this record can be selected into the playback device context by an EMR\_SELECTOBJECT record (section 2.3.8.5), which specifies the pattern brush to use in subsequent graphics operations.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfCreateDibPatternBrushPt(EmfRecord source)](#EmfCreateDibPatternBrushPt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfCreateDibPatternBrushPt` class. |
| [EmfCreateDibPatternBrushPt()](#EmfCreateDibPatternBrushPt--) | Initializes a new instance of the `EmfCreateDibPatternBrushPt` class. |
## Methods

| Method | Description |
| --- | --- |
| [getIhBrush()](#getIhBrush--) | Gets or sets a 32-bit unsigned integer that specifies the index of the pattern brush object in the EMF Object Table (section 3.1.1.1). |
| [setIhBrush(int value)](#setIhBrush-int-) | Gets or sets a 32-bit unsigned integer that specifies the index of the pattern brush object in the EMF Object Table (section 3.1.1.1). |
| [getUsage()](#getUsage--) | Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the DIB header. |
| [setUsage(int value)](#setUsage-int-) | Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the DIB header. |
| [getBitmapBuffer()](#getBitmapBuffer--) | Gets or sets a buffer containing a packed DIB in the form of a WMF DeviceIndependentBitmap object ([MS-WMF] section 2.2.2.9). |
| [setBitmapBuffer(WmfDeviceIndependentBitmap value)](#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Gets or sets a buffer containing a packed DIB in the form of a WMF DeviceIndependentBitmap object ([MS-WMF] section 2.2.2.9). |
### EmfCreateDibPatternBrushPt(EmfRecord source) {#EmfCreateDibPatternBrushPt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateDibPatternBrushPt(EmfRecord source)
```


Initializes a new instance of the `EmfCreateDibPatternBrushPt` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfCreateDibPatternBrushPt() {#EmfCreateDibPatternBrushPt--}
```
public EmfCreateDibPatternBrushPt()
```


Initializes a new instance of the `EmfCreateDibPatternBrushPt` class.

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Gets or sets a 32-bit unsigned integer that specifies the index of the pattern brush object in the EMF Object Table (section 3.1.1.1). This index MUST be saved so that this object can be reused or modified.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the index of the pattern brush object in the EMF Object Table (section 3.1.1.1). This index MUST be saved so that this object can be reused or modified.

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

