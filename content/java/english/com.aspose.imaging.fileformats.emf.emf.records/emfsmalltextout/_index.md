---
title: EmfSmallTextOut
second_title: Aspose.Imaging for Java API Reference
description: The EMR_SMALLTEXTOUT record outputs a string.
type: docs
weight: 144
url: /com.aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfSmallTextOut extends EmfDrawingRecordType
```

The EMR\_SMALLTEXTOUT record outputs a string.

If ETO\_SMALL\_CHARS is set in the fuOptions field, TextString contains 8-bit codes for characters, derived from the low bytes of 16-bit Unicode UTF16-LE character codes, in which the high byte is assumed to be 0. If ETO\_NO\_RECT is set in the fuOptions field, the Bounds field is not included in the record.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfSmallTextOut(EmfRecord source)](#EmfSmallTextOut-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfSmallTextOut` class. |
## Methods

| Method | Description |
| --- | --- |
| [getX()](#getX--) | Gets or sets a 32-bit signed integer specifying the x-coordinate of where to place the string. |
| [setX(int value)](#setX-int-) | Gets or sets a 32-bit signed integer specifying the x-coordinate of where to place the string. |
| [getY()](#getY--) | Gets or sets a 32-bit signed integer specifying the y-coordinate of where to place the string. |
| [setY(int value)](#setY-int-) | Gets or sets a 32-bit signed integer specifying the y-coordinate of where to place the string. |
| [getCChars()](#getCChars--) | Gets or sets a 32-bit unsigned integer specifying the number of 16-bit characters in the string. |
| [setCChars(int value)](#setCChars-int-) | Gets or sets a 32-bit unsigned integer specifying the number of 16-bit characters in the string. |
| [getFuOptions()](#getFuOptions--) | Gets or sets a 32-bit unsigned integer specifying the text output options to use. |
| [setFuOptions(int value)](#setFuOptions-int-) | Gets or sets a 32-bit unsigned integer specifying the text output options to use. |
| [getIGraphicsMode()](#getIGraphicsMode--) | Gets or sets a 32-bit unsigned integer specifying the graphics mode, from the GraphicsMode enumeration (section 2.1.16). |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | Gets or sets a 32-bit unsigned integer specifying the graphics mode, from the GraphicsMode enumeration (section 2.1.16). |
| [getExScale()](#getExScale--) | Gets or sets a 32-bit floating-point value that specifies how much to scale the text in the x-direction. |
| [setExScale(float value)](#setExScale-float-) | Gets or sets a 32-bit floating-point value that specifies how much to scale the text in the x-direction. |
| [getEyScale()](#getEyScale--) | Gets or sets a 32-bit floating-point value that specifies how much to scale the text in the y-direction. |
| [setEyScale(float value)](#setEyScale-float-) | Gets or sets a 32-bit floating-point value that specifies how much to scale the text in the y-direction. |
| [getBounds()](#getBounds--) | Gets or sets an optional, 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle in device units. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Gets or sets an optional, 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle in device units. |
| [getTextString()](#getTextString--) | Gets or sets a variable-length string that contains the text string to draw, in either 8-bit or 16-bit character codes, according to the value of the fuOptions field. |
| [setTextString(String value)](#setTextString-java.lang.String-) | Gets or sets a variable-length string that contains the text string to draw, in either 8-bit or 16-bit character codes, according to the value of the fuOptions field. |
### EmfSmallTextOut(EmfRecord source) {#EmfSmallTextOut-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSmallTextOut(EmfRecord source)
```


Initializes a new instance of the `EmfSmallTextOut` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getX() {#getX--}
```
public int getX()
```


Gets or sets a 32-bit signed integer specifying the x-coordinate of where to place the string.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Gets or sets a 32-bit signed integer specifying the x-coordinate of where to place the string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public int getY()
```


Gets or sets a 32-bit signed integer specifying the y-coordinate of where to place the string.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Gets or sets a 32-bit signed integer specifying the y-coordinate of where to place the string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCChars() {#getCChars--}
```
public int getCChars()
```


Gets or sets a 32-bit unsigned integer specifying the number of 16-bit characters in the string. The string is NOT null-terminated.

**Returns:**
int
### setCChars(int value) {#setCChars-int-}
```
public void setCChars(int value)
```


Gets or sets a 32-bit unsigned integer specifying the number of 16-bit characters in the string. The string is NOT null-terminated.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFuOptions() {#getFuOptions--}
```
public int getFuOptions()
```


Gets or sets a 32-bit unsigned integer specifying the text output options to use. These options are specified by one or a combination of values from the ExtTextOutOptions enumeration (section 2.1.11).

**Returns:**
int
### setFuOptions(int value) {#setFuOptions-int-}
```
public void setFuOptions(int value)
```


Gets or sets a 32-bit unsigned integer specifying the text output options to use. These options are specified by one or a combination of values from the ExtTextOutOptions enumeration (section 2.1.11).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


Gets or sets a 32-bit unsigned integer specifying the graphics mode, from the GraphicsMode enumeration (section 2.1.16).

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


Gets or sets a 32-bit unsigned integer specifying the graphics mode, from the GraphicsMode enumeration (section 2.1.16).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


Gets or sets a 32-bit floating-point value that specifies how much to scale the text in the x-direction.

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


Gets or sets a 32-bit floating-point value that specifies how much to scale the text in the x-direction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


Gets or sets a 32-bit floating-point value that specifies how much to scale the text in the y-direction.

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


Gets or sets a 32-bit floating-point value that specifies how much to scale the text in the y-direction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Gets or sets an optional, 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle in device units.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Gets or sets an optional, 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle in device units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getTextString() {#getTextString--}
```
public String getTextString()
```


Gets or sets a variable-length string that contains the text string to draw, in either 8-bit or 16-bit character codes, according to the value of the fuOptions field.

**Returns:**
java.lang.String
### setTextString(String value) {#setTextString-java.lang.String-}
```
public void setTextString(String value)
```


Gets or sets a variable-length string that contains the text string to draw, in either 8-bit or 16-bit character codes, according to the value of the fuOptions field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

