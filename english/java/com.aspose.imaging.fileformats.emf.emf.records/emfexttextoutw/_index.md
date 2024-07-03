---
title: EmfExtTextOutW
second_title: Aspose.Imaging for Java API Reference
description: The EMR_EXTTEXTOUTW record draws an ASCII text string using the current font and text colors.
type: docs
weight: 57
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfExtTextOutW extends EmfDrawingRecordType
```

The EMR\_EXTTEXTOUTW record draws an ASCII text string using the current font and text colors.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfExtTextOutW(EmfRecord source)](#EmfExtTextOutW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfExtTextOutW` class. |
| [EmfExtTextOutW()](#EmfExtTextOutW--) | Initializes a new instance of the `EmfExtTextOutW` class. |
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
| [getWEmrText()](#getWEmrText--) | Gets or sets an EmrText object (section 2.2.5) that specifies the output string in 16-bit Unicode UTF16-LE characters, with text attributes and spacing values. |
| [setWEmrText(EmfText value)](#setWEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText-) | Gets or sets an EmrText object (section 2.2.5) that specifies the output string in 16-bit Unicode UTF16-LE characters, with text attributes and spacing values. |
### EmfExtTextOutW(EmfRecord source) {#EmfExtTextOutW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtTextOutW(EmfRecord source)
```


Initializes a new instance of the `EmfExtTextOutW` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfExtTextOutW() {#EmfExtTextOutW--}
```
public EmfExtTextOutW()
```


Initializes a new instance of the `EmfExtTextOutW` class.

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

### getWEmrText() {#getWEmrText--}
```
public EmfText getWEmrText()
```


Gets or sets an EmrText object (section 2.2.5) that specifies the output string in 16-bit Unicode UTF16-LE characters, with text attributes and spacing values.

**Returns:**
[EmfText](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext)
### setWEmrText(EmfText value) {#setWEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText-}
```
public void setWEmrText(EmfText value)
```


Gets or sets an EmrText object (section 2.2.5) that specifies the output string in 16-bit Unicode UTF16-LE characters, with text attributes and spacing values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfText](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext) |  |

