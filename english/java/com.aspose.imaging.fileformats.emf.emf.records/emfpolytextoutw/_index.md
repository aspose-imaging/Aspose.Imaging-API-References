---
title: EmfPolyTextOutW
second_title: Aspose.Imaging for Java API Reference
description: The EMR_POLYTEXTOUTW record draws one or more Unicode text strings using the current font and text colors.
type: docs
weight: 98
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPolyTextOutW extends EmfDrawingRecordType
```

The EMR\_POLYTEXTOUTW record draws one or more Unicode text strings using the current font and text colors.

The font and text colors used for output are specified by properties in the current state of the playback device context. EMR\_POLYTEXTOUTW SHOULD be emulated with a series of EMR\_EXTTEXTOUTW records (section 2.3.5.7), one per string.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPolyTextOutW(EmfRecord source)](#EmfPolyTextOutW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfPolyTextOutW` class. |
| [EmfPolyTextOutW()](#EmfPolyTextOutW--) | Initializes a new instance of the `EmfPolyTextOutW` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19), which specifies the bounding rectangle in device units. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19), which specifies the bounding rectangle in device units. |
| [getIGraphicsMode()](#getIGraphicsMode--) | Gets or sets a 32-bit unsigned integer that specifies the current graphics mode, from the GraphicsMode enumeration (section 2.1.16). |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | Gets or sets a 32-bit unsigned integer that specifies the current graphics mode, from the GraphicsMode enumeration (section 2.1.16). |
| [getExScale()](#getExScale--) | Gets or sets a 32-bit floating-point value that specifies the X scale from page units to .01mm units if graphics mode is GM\_COMPATIBLE. |
| [setExScale(float value)](#setExScale-float-) | Gets or sets a 32-bit floating-point value that specifies the X scale from page units to .01mm units if graphics mode is GM\_COMPATIBLE. |
| [getEyScale()](#getEyScale--) | Gets or sets a 32-bit floating-point value that specifies the Y scale from page units to .01mm units if graphics mode is GM\_COMPATIBLE. |
| [setEyScale(float value)](#setEyScale-float-) | Gets or sets a 32-bit floating-point value that specifies the Y scale from page units to .01mm units if graphics mode is GM\_COMPATIBLE. |
| [getWEmrText()](#getWEmrText--) | Gets or sets an array of EmrText objects (section 2.2.5) that specify the output strings in 16-bit Unicode UTF16-LE characters, with text attributes and spacing values. |
| [setWEmrText(EmfText[] value)](#setWEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText---) | Gets or sets an array of EmrText objects (section 2.2.5) that specify the output strings in 16-bit Unicode UTF16-LE characters, with text attributes and spacing values. |
### EmfPolyTextOutW(EmfRecord source) {#EmfPolyTextOutW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyTextOutW(EmfRecord source)
```


Initializes a new instance of the `EmfPolyTextOutW` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfPolyTextOutW() {#EmfPolyTextOutW--}
```
public EmfPolyTextOutW()
```


Initializes a new instance of the `EmfPolyTextOutW` class.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19), which specifies the bounding rectangle in device units.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19), which specifies the bounding rectangle in device units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


Gets or sets a 32-bit unsigned integer that specifies the current graphics mode, from the GraphicsMode enumeration (section 2.1.16).

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the current graphics mode, from the GraphicsMode enumeration (section 2.1.16).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


Gets or sets a 32-bit floating-point value that specifies the X scale from page units to .01mm units if graphics mode is GM\_COMPATIBLE.

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


Gets or sets a 32-bit floating-point value that specifies the X scale from page units to .01mm units if graphics mode is GM\_COMPATIBLE.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


Gets or sets a 32-bit floating-point value that specifies the Y scale from page units to .01mm units if graphics mode is GM\_COMPATIBLE.

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


Gets or sets a 32-bit floating-point value that specifies the Y scale from page units to .01mm units if graphics mode is GM\_COMPATIBLE.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWEmrText() {#getWEmrText--}
```
public EmfText[] getWEmrText()
```


Gets or sets an array of EmrText objects (section 2.2.5) that specify the output strings in 16-bit Unicode UTF16-LE characters, with text attributes and spacing values. The number of EmrText objects is specified by cStrings.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfText[]
### setWEmrText(EmfText[] value) {#setWEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText---}
```
public void setWEmrText(EmfText[] value)
```


Gets or sets an array of EmrText objects (section 2.2.5) that specify the output strings in 16-bit Unicode UTF16-LE characters, with text attributes and spacing values. The number of EmrText objects is specified by cStrings.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfText\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext) |  |

