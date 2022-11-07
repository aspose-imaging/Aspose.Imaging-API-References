---
title: EmfPlusStringFormat
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusStringFormat object specifies text layout display manipulations and language identification
type: docs
weight: 74
url: /java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusStringFormat extends EmfPlusGraphicsObjectType
```

The EmfPlusStringFormat object specifies text layout, display manipulations, and language identification
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusStringFormat()](#EmfPlusStringFormat--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getDigitLanguage()](#getDigitLanguage--) | Gets or sets an EmfPlusLanguageIdentifier object that specifies the language to use for numeric digits in the string. |
| [setDigitLanguage(short value)](#setDigitLanguage-short-) | Gets or sets an EmfPlusLanguageIdentifier object that specifies the language to use for numeric digits in the string. |
| [getDigitSubstitution()](#getDigitSubstitution--) | Gets or sets a 32-bit unsigned integer that specifies how to substitute numeric digits in the string according to a locale or language. |
| [setDigitSubstitution(int value)](#setDigitSubstitution-int-) | Gets or sets a 32-bit unsigned integer that specifies how to substitute numeric digits in the string according to a locale or language. |
| [getFirstTabOffset()](#getFirstTabOffset--) | Gets or sets a 32-bit floating-point value that specifies the number of spaces between the beginning of a text line and the first tab stop |
| [setFirstTabOffset(float value)](#setFirstTabOffset-float-) | Gets or sets a 32-bit floating-point value that specifies the number of spaces between the beginning of a text line and the first tab stop |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Gets or sets a 32-bit signed integer that specifies the type of processing that is performed on a string when a keyboard shortcut prefix (that is, an ampersand) is encountered. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Gets or sets a 32-bit signed integer that specifies the type of processing that is performed on a string when a keyboard shortcut prefix (that is, an ampersand) is encountered. |
| [getLanguage()](#getLanguage--) | Gets or sets an EmfPlusLanguageIdentifier object (section 2.2.2.23) that specifies the language to use for the string |
| [setLanguage(short value)](#setLanguage-short-) | Gets or sets an EmfPlusLanguageIdentifier object (section 2.2.2.23) that specifies the language to use for the string |
| [getLeadingMargin()](#getLeadingMargin--) | Gets or sets a 32-bit floating-point value that specifies the length of the space to add to the starting position of a string. |
| [setLeadingMargin(float value)](#setLeadingMargin-float-) | Gets or sets a 32-bit floating-point value that specifies the length of the space to add to the starting position of a string. |
| [getLineAlign()](#getLineAlign--) | Gets or sets a 32-bit unsigned integer that specifies how to align the string vertically in the layout rectangle. |
| [setLineAlign(int value)](#setLineAlign-int-) | Gets or sets a 32-bit unsigned integer that specifies how to align the string vertically in the layout rectangle. |
| [getRangeCount()](#getRangeCount--) | Gets or sets a 32-bit signed integer that specifies the number of EmfPlusCharacterRange objects (section 2.2.2.8) defined in the StringFormatData field. |
| [setRangeCount(int value)](#setRangeCount-int-) | Gets or sets a 32-bit signed integer that specifies the number of EmfPlusCharacterRange objects (section 2.2.2.8) defined in the StringFormatData field. |
| [getStringAlignment()](#getStringAlignment--) | Gets or sets a 32-bit unsigned integer that specifies how to align the string horizontally in the layout rectangle. |
| [setStringAlignment(int value)](#setStringAlignment-int-) | Gets or sets a 32-bit unsigned integer that specifies how to align the string horizontally in the layout rectangle. |
| [getStringFormatData()](#getStringFormatData--) | Gets or sets an EmfPlusStringFormatData object (section 2.2.2.44) that specifies optional text layout data. |
| [setStringFormatData(EmfPlusStringFormatData value)](#setStringFormatData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormatData-) | Gets or sets an EmfPlusStringFormatData object (section 2.2.2.44) that specifies optional text layout data. |
| [getStringFormatFlags()](#getStringFormatFlags--) | Gets or sets a 32-bit unsigned integer that specifies text layout options for formatting, clipping and font handling. |
| [setStringFormatFlags(long value)](#setStringFormatFlags-long-) | Gets or sets a 32-bit unsigned integer that specifies text layout options for formatting, clipping and font handling. |
| [getTabstopCount()](#getTabstopCount--) | Gets or sets a 32-bit signed integer that specifies the number of tab stops defined in the StringFormatData field. |
| [setTabstopCount(int value)](#setTabstopCount-int-) | Gets or sets a 32-bit signed integer that specifies the number of tab stops defined in the StringFormatData field. |
| [getTracking()](#getTracking--) | Gets or sets a 32-bit floating-point value that specifies the ratio of the horizontal space allotted to each character in a specified string to the font-defined width of the character. |
| [setTracking(float value)](#setTracking-float-) | Gets or sets a 32-bit floating-point value that specifies the ratio of the horizontal space allotted to each character in a specified string to the font-defined width of the character. |
| [getTrailingMargin()](#getTrailingMargin--) | Gets or sets a 32-bit floating-point value that specifies the length of the space to leave following a string. |
| [setTrailingMargin(float value)](#setTrailingMargin-float-) | Gets or sets a 32-bit floating-point value that specifies the length of the space to leave following a string. |
| [getTrimming()](#getTrimming--) | Gets or sets specifies how to trim characters from a string that is too large to fit into a layout rectangle. |
| [setTrimming(int value)](#setTrimming-int-) | Gets or sets specifies how to trim characters from a string that is too large to fit into a layout rectangle. |
### EmfPlusStringFormat() {#EmfPlusStringFormat--}
```
public EmfPlusStringFormat()
```


### getDigitLanguage() {#getDigitLanguage--}
```
public short getDigitLanguage()
```


Gets or sets an EmfPlusLanguageIdentifier object that specifies the language to use for numeric digits in the string. For example, if this string contains Arabic digits, this field MUST contain a language identifier that specifies an Arabic language

**Returns:**
short
### setDigitLanguage(short value) {#setDigitLanguage-short-}
```
public void setDigitLanguage(short value)
```


Gets or sets an EmfPlusLanguageIdentifier object that specifies the language to use for numeric digits in the string. For example, if this string contains Arabic digits, this field MUST contain a language identifier that specifies an Arabic language

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getDigitSubstitution() {#getDigitSubstitution--}
```
public int getDigitSubstitution()
```


Gets or sets a 32-bit unsigned integer that specifies how to substitute numeric digits in the string according to a locale or language. This value MUST be defined in the StringDigitSubstitution enumeration (section 2.1.1.30).

**Returns:**
int
### setDigitSubstitution(int value) {#setDigitSubstitution-int-}
```
public void setDigitSubstitution(int value)
```


Gets or sets a 32-bit unsigned integer that specifies how to substitute numeric digits in the string according to a locale or language. This value MUST be defined in the StringDigitSubstitution enumeration (section 2.1.1.30).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


Gets or sets a 32-bit floating-point value that specifies the number of spaces between the beginning of a text line and the first tab stop

**Returns:**
float
### setFirstTabOffset(float value) {#setFirstTabOffset-float-}
```
public void setFirstTabOffset(float value)
```


Gets or sets a 32-bit floating-point value that specifies the number of spaces between the beginning of a text line and the first tab stop

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Gets or sets a 32-bit signed integer that specifies the type of processing that is performed on a string when a keyboard shortcut prefix (that is, an ampersand) is encountered. Basically, this field specifies whether to display keyboard shortcut prefixes that relate to text. The value MUST be defined in the HotkeyPrefix enumeration (section 2.1.1.14).

**Returns:**
int
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Gets or sets a 32-bit signed integer that specifies the type of processing that is performed on a string when a keyboard shortcut prefix (that is, an ampersand) is encountered. Basically, this field specifies whether to display keyboard shortcut prefixes that relate to text. The value MUST be defined in the HotkeyPrefix enumeration (section 2.1.1.14).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLanguage() {#getLanguage--}
```
public short getLanguage()
```


Gets or sets an EmfPlusLanguageIdentifier object (section 2.2.2.23) that specifies the language to use for the string

**Returns:**
short
### setLanguage(short value) {#setLanguage-short-}
```
public void setLanguage(short value)
```


Gets or sets an EmfPlusLanguageIdentifier object (section 2.2.2.23) that specifies the language to use for the string

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getLeadingMargin() {#getLeadingMargin--}
```
public float getLeadingMargin()
```


Gets or sets a 32-bit floating-point value that specifies the length of the space to add to the starting position of a string. The default is 1/6 inch; for typographic fonts, the default value is 0.

**Returns:**
float
### setLeadingMargin(float value) {#setLeadingMargin-float-}
```
public void setLeadingMargin(float value)
```


Gets or sets a 32-bit floating-point value that specifies the length of the space to add to the starting position of a string. The default is 1/6 inch; for typographic fonts, the default value is 0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getLineAlign() {#getLineAlign--}
```
public int getLineAlign()
```


Gets or sets a 32-bit unsigned integer that specifies how to align the string vertically in the layout rectangle. This value MUST be defined in the StringAlignment enumeration.

**Returns:**
int
### setLineAlign(int value) {#setLineAlign-int-}
```
public void setLineAlign(int value)
```


Gets or sets a 32-bit unsigned integer that specifies how to align the string vertically in the layout rectangle. This value MUST be defined in the StringAlignment enumeration.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRangeCount() {#getRangeCount--}
```
public int getRangeCount()
```


Gets or sets a 32-bit signed integer that specifies the number of EmfPlusCharacterRange objects (section 2.2.2.8) defined in the StringFormatData field.

**Returns:**
int
### setRangeCount(int value) {#setRangeCount-int-}
```
public void setRangeCount(int value)
```


Gets or sets a 32-bit signed integer that specifies the number of EmfPlusCharacterRange objects (section 2.2.2.8) defined in the StringFormatData field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getStringAlignment() {#getStringAlignment--}
```
public int getStringAlignment()
```


Gets or sets a 32-bit unsigned integer that specifies how to align the string horizontally in the layout rectangle. This value MUST be defined in the StringAlignment enumeration (section 2.1.1.29).

**Returns:**
int
### setStringAlignment(int value) {#setStringAlignment-int-}
```
public void setStringAlignment(int value)
```


Gets or sets a 32-bit unsigned integer that specifies how to align the string horizontally in the layout rectangle. This value MUST be defined in the StringAlignment enumeration (section 2.1.1.29).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getStringFormatData() {#getStringFormatData--}
```
public EmfPlusStringFormatData getStringFormatData()
```


Gets or sets an EmfPlusStringFormatData object (section 2.2.2.44) that specifies optional text layout data.

**Returns:**
[EmfPlusStringFormatData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata)
### setStringFormatData(EmfPlusStringFormatData value) {#setStringFormatData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormatData-}
```
public void setStringFormatData(EmfPlusStringFormatData value)
```


Gets or sets an EmfPlusStringFormatData object (section 2.2.2.44) that specifies optional text layout data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusStringFormatData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata) |  |

### getStringFormatFlags() {#getStringFormatFlags--}
```
public long getStringFormatFlags()
```


Gets or sets a 32-bit unsigned integer that specifies text layout options for formatting, clipping and font handling. This value MUST be composed of StringFormat flags (section 2.1.2.8).

**Returns:**
long
### setStringFormatFlags(long value) {#setStringFormatFlags-long-}
```
public void setStringFormatFlags(long value)
```


Gets or sets a 32-bit unsigned integer that specifies text layout options for formatting, clipping and font handling. This value MUST be composed of StringFormat flags (section 2.1.2.8).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getTabstopCount() {#getTabstopCount--}
```
public int getTabstopCount()
```


Gets or sets a 32-bit signed integer that specifies the number of tab stops defined in the StringFormatData field.

**Returns:**
int
### setTabstopCount(int value) {#setTabstopCount-int-}
```
public void setTabstopCount(int value)
```


Gets or sets a 32-bit signed integer that specifies the number of tab stops defined in the StringFormatData field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTracking() {#getTracking--}
```
public float getTracking()
```


Gets or sets a 32-bit floating-point value that specifies the ratio of the horizontal space allotted to each character in a specified string to the font-defined width of the character. Large values for this property specify ample space between characters; values less than 1 can produce character overlap. The default is 1.03; for typographic fonts, the default value is 1.00.

**Returns:**
float
### setTracking(float value) {#setTracking-float-}
```
public void setTracking(float value)
```


Gets or sets a 32-bit floating-point value that specifies the ratio of the horizontal space allotted to each character in a specified string to the font-defined width of the character. Large values for this property specify ample space between characters; values less than 1 can produce character overlap. The default is 1.03; for typographic fonts, the default value is 1.00.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTrailingMargin() {#getTrailingMargin--}
```
public float getTrailingMargin()
```


Gets or sets a 32-bit floating-point value that specifies the length of the space to leave following a string. The default is 1/6 inch; for typographic fonts, the default value is 0.

**Returns:**
float
### setTrailingMargin(float value) {#setTrailingMargin-float-}
```
public void setTrailingMargin(float value)
```


Gets or sets a 32-bit floating-point value that specifies the length of the space to leave following a string. The default is 1/6 inch; for typographic fonts, the default value is 0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Gets or sets specifies how to trim characters from a string that is too large to fit into a layout rectangle. This value MUST be defined in the StringTrimming enumeration (section 2.1.1.31).

**Returns:**
int
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Gets or sets specifies how to trim characters from a string that is too large to fit into a layout rectangle. This value MUST be defined in the StringTrimming enumeration (section 2.1.1.31).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

