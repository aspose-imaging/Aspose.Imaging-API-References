---
title: EmfExtTextOutA
second_title: Aspose.Imaging for Java API Reference
description: The EMR_EXTTEXTOUTA record draws an ASCII text string using the current font and text colors.
type: docs
weight: 55
url: /com.aspose.imaging.fileformats.emf.emf.records/emfexttextouta/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfExtTextOutA extends EmfDrawingRecordType
```

The EMR\_EXTTEXTOUTA record draws an ASCII text string using the current font and text colors.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfExtTextOutA(EmfRecord source)](#EmfExtTextOutA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfExtTextOutA` class. |
| [EmfExtTextOutA()](#EmfExtTextOutA--) | Initializes a new instance of the [EmfExtTextOutA](../../com.aspose.imaging.fileformats.emf.emf.records/emfexttextouta) class. |
## Methods

| Method | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19). |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19). |
| [getIGraphicsMode()](#getIGraphicsMode--) | Gets or sets a 32-bit unsigned integer that specifies the graphics mode from the GraphicsMode enumeration (section 2.1.16). |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | Gets or sets a 32-bit unsigned integer that specifies the graphics mode from the GraphicsMode enumeration (section 2.1.16). |
| [getExScale()](#getExScale--) | Gets or sets a 32-bit floating-point value that specifies the scale factor to apply along the X axis to convert from page space units to .01mm units. |
| [setExScale(float value)](#setExScale-float-) | Gets or sets a 32-bit floating-point value that specifies the scale factor to apply along the X axis to convert from page space units to .01mm units. |
| [getEyScale()](#getEyScale--) | Gets or sets a 32-bit floating-point value that specifies the scale factor to apply along the Y axis to convert from page space units to .01mm units. |
| [setEyScale(float value)](#setEyScale-float-) | Gets or sets a 32-bit floating-point value that specifies the scale factor to apply along the Y axis to convert from page space units to .01mm units. |
| [getAEmrText()](#getAEmrText--) | Gets or sets an EmrText object (section 2.2.5) that specifies the output string in 8-bit ASCII characters, text attributes, and spacing values. |
| [setAEmrText(EmfText value)](#setAEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText-) | Gets or sets an EmrText object (section 2.2.5) that specifies the output string in 8-bit ASCII characters, text attributes, and spacing values. |
### EmfExtTextOutA(EmfRecord source) {#EmfExtTextOutA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtTextOutA(EmfRecord source)
```


Initializes a new instance of the `EmfExtTextOutA` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfExtTextOutA() {#EmfExtTextOutA--}
```
public EmfExtTextOutA()
```


Initializes a new instance of the [EmfExtTextOutA](../../com.aspose.imaging.fileformats.emf.emf.records/emfexttextouta) class.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19). It is not used and MUST be ignored on receipt.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19). It is not used and MUST be ignored on receipt.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


Gets or sets a 32-bit unsigned integer that specifies the graphics mode from the GraphicsMode enumeration (section 2.1.16).

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the graphics mode from the GraphicsMode enumeration (section 2.1.16).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


Gets or sets a 32-bit floating-point value that specifies the scale factor to apply along the X axis to convert from page space units to .01mm units. This SHOULD be used only if the graphics mode specified by iGraphicsMode is GM\_COMPATIBLE.

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


Gets or sets a 32-bit floating-point value that specifies the scale factor to apply along the X axis to convert from page space units to .01mm units. This SHOULD be used only if the graphics mode specified by iGraphicsMode is GM\_COMPATIBLE.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


Gets or sets a 32-bit floating-point value that specifies the scale factor to apply along the Y axis to convert from page space units to .01mm units. This SHOULD be used only if the graphics mode specified by iGraphicsMode is GM\_COMPATIBLE.

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


Gets or sets a 32-bit floating-point value that specifies the scale factor to apply along the Y axis to convert from page space units to .01mm units. This SHOULD be used only if the graphics mode specified by iGraphicsMode is GM\_COMPATIBLE.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getAEmrText() {#getAEmrText--}
```
public EmfText getAEmrText()
```


Gets or sets an EmrText object (section 2.2.5) that specifies the output string in 8-bit ASCII characters, text attributes, and spacing values.

**Returns:**
[EmfText](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext)
### setAEmrText(EmfText value) {#setAEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText-}
```
public void setAEmrText(EmfText value)
```


Gets or sets an EmrText object (section 2.2.5) that specifies the output string in 8-bit ASCII characters, text attributes, and spacing values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfText](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext) |  |

