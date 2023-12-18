---
title: StringFormat
second_title: Aspose.Imaging for Java API Reference
description: Encapsulates text layout information such as alignment orientation and tab stops display manipulations such as ellipsis insertion and national digit substitution and OpenType features.
type: docs
weight: 113
url: /java/com.aspose.imaging/stringformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public final class StringFormat extends DisposableObject
```

Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.
## Constructors

| Constructor | Description |
| --- | --- |
| [StringFormat()](#StringFormat--) | Initializes a new `com.aspose.imaging.StringFormat` object. |
| [StringFormat(int options)](#StringFormat-int-) | Initializes a new `com.aspose.imaging.StringFormat` object with the specified `com.aspose.imaging.StringFormatFlags` enumeration and language. |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.imaging.StringFormat-) | Initializes a new `com.aspose.imaging.StringFormat` object from the specified existing `com.aspose.imaging.StringFormat` object. |
## Methods

| Method | Description |
| --- | --- |
| [getGenericDefault()](#getGenericDefault--) | Gets a generic default `com.aspose.imaging.StringFormat` object. |
| [getGenericTypographic()](#getGenericTypographic--) | Gets a generic typographic `com.aspose.imaging.StringFormat` object. |
| [getFormatFlags()](#getFormatFlags--) | Gets a `com.aspose.imaging.StringFormatFlags` enumeration that contains formatting information. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | Sets a `com.aspose.imaging.StringFormatFlags` enumeration that contains formatting information. |
| [getAlignment()](#getAlignment--) | Gets text alignment information on the vertical plane. |
| [setAlignment(int value)](#setAlignment-int-) | Sets text alignment information on the vertical plane. |
| [getLineAlignment()](#getLineAlignment--) | Gets the line alignment on the horizontal plane. |
| [setLineAlignment(int value)](#setLineAlignment-int-) | Sets the line alignment on the horizontal plane. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Gets the `com.aspose.imaging.HotkeyPrefix` object for this `com.aspose.imaging.StringFormat` object. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Sets the `com.aspose.imaging.HotkeyPrefix` object for this `com.aspose.imaging.StringFormat` object. |
| [getTrimming()](#getTrimming--) | Gets the `com.aspose.imaging.StringTrimming` enumeration for this `com.aspose.imaging.StringFormat` object. |
| [setTrimming(int value)](#setTrimming-int-) | Sets the `com.aspose.imaging.StringTrimming` enumeration for this `com.aspose.imaging.StringFormat` object. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | Gets the method to be used for digit substitution. |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) | Sets the method to be used for digit substitution. |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | Gets the language that is used when local digits are substituted for western digits. |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) | Sets the language that is used when local digits are substituted for western digits. |
| [getFirstTabOffset()](#getFirstTabOffset--) | Gets the number of spaces between the beginning of a line of text and the first tab stop. |
| [getTabStops()](#getTabStops--) | Gets an array of distances between tab stops in the units specified by the `P:Aspose.Imaging.getGraphics().PageUnit` property. |
| [getCustomCharIdent()](#getCustomCharIdent--) | Gets the custom character ident. |
| [setCustomCharIdent(PointF value)](#setCustomCharIdent-com.aspose.imaging.PointF-) | Sets the custom character ident. |
| [deepClone()](#deepClone--) | Creates a deep clone of this `com.aspose.imaging.StringFormat` object. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | Sets tab stops for this `com.aspose.imaging.StringFormat` object. |
| [toString()](#toString--) | Converts this `com.aspose.imaging.StringFormat` object to a human-readable string. |
| [equals(Object o)](#equals-java.lang.Object-) | Check if objects are equal. |
| [hashCode()](#hashCode--) | Get hash code of the current object. |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


Initializes a new `com.aspose.imaging.StringFormat` object.

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


Initializes a new `com.aspose.imaging.StringFormat` object with the specified `com.aspose.imaging.StringFormatFlags` enumeration and language.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | int | The `com.aspose.imaging.StringFormatFlags` enumeration for the new `com.aspose.imaging.StringFormat` object. |

### StringFormat(StringFormat format) {#StringFormat-com.aspose.imaging.StringFormat-}
```
public StringFormat(StringFormat format)
```


Initializes a new `com.aspose.imaging.StringFormat` object from the specified existing `com.aspose.imaging.StringFormat` object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.imaging/stringformat) | The `com.aspose.imaging.StringFormat` object from which to initialize the new `com.aspose.imaging.StringFormat` object. |

### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


Gets a generic default `com.aspose.imaging.StringFormat` object.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat) - The generic default `com.aspose.imaging.StringFormat` object.
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


Gets a generic typographic `com.aspose.imaging.StringFormat` object.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat) - A generic typographic `com.aspose.imaging.StringFormat` object.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


Gets a `com.aspose.imaging.StringFormatFlags` enumeration that contains formatting information.

**Returns:**
int - A `com.aspose.imaging.StringFormatFlags` enumeration that contains formatting information.
### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


Sets a `com.aspose.imaging.StringFormatFlags` enumeration that contains formatting information.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | A `com.aspose.imaging.StringFormatFlags` enumeration that contains formatting information. |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Gets text alignment information on the vertical plane.

**Returns:**
int - A `com.aspose.imaging.StringAlignment` enumeration that specifies text alignment information.
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Sets text alignment information on the vertical plane.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | A `com.aspose.imaging.StringAlignment` enumeration that specifies text alignment information. |

### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


Gets the line alignment on the horizontal plane.

**Returns:**
int - A `com.aspose.imaging.StringAlignment` enumeration that represents the line alignment.
### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


Sets the line alignment on the horizontal plane.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | A `com.aspose.imaging.StringAlignment` enumeration that represents the line alignment. |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Gets the `com.aspose.imaging.HotkeyPrefix` object for this `com.aspose.imaging.StringFormat` object.

**Returns:**
int - The `com.aspose.imaging.HotkeyPrefix` object for this `com.aspose.imaging.StringFormat` object, the default is `F:Aspose.Imaging.HotkeyPrefix.None`.
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Sets the `com.aspose.imaging.HotkeyPrefix` object for this `com.aspose.imaging.StringFormat` object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The `com.aspose.imaging.HotkeyPrefix` object for this `com.aspose.imaging.StringFormat` object, the default is `F:Aspose.Imaging.HotkeyPrefix.None`. |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Gets the `com.aspose.imaging.StringTrimming` enumeration for this `com.aspose.imaging.StringFormat` object.

**Returns:**
int - A `com.aspose.imaging.StringTrimming` enumeration that indicates how text drawn with this `com.aspose.imaging.StringFormat` object is trimmed when it exceeds the edges of the layout rectangle.
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Sets the `com.aspose.imaging.StringTrimming` enumeration for this `com.aspose.imaging.StringFormat` object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | A `com.aspose.imaging.StringTrimming` enumeration that indicates how text drawn with this `com.aspose.imaging.StringFormat` object is trimmed when it exceeds the edges of the layout rectangle. |

### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


Gets the method to be used for digit substitution.

**Returns:**
int - A `com.aspose.imaging.StringDigitSubstitute` enumeration value that specifies how to substitute characters in a string that cannot be displayed because they are not supported by the current font.

The setter is introduced for the obsolete method SetDigitSubstitution.
### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```


Sets the method to be used for digit substitution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | A `com.aspose.imaging.StringDigitSubstitute` enumeration value that specifies how to substitute characters in a string that cannot be displayed because they are not supported by the current font.

The setter is introduced for the obsolete method SetDigitSubstitution. |

### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


Gets the language that is used when local digits are substituted for western digits.

**Returns:**
int - A National Language Support (NLS) language identifier that identifies the language that will be used when local digits are substituted for western digits. You can pass the `P:System.Globalization.CultureInfo.LCID` property of a `System.Globalization.CultureInfo` object as the NLS language identifier. For example, suppose you create a `System.Globalization.CultureInfo` object by passing the string "ar-EG" to a `System.Globalization.CultureInfo` constructor. If you pass the `P:System.Globalization.CultureInfo.LCID` property of that `System.Globalization.CultureInfo` object along with. `com.aspose.imaging.StringDigitSubstitute.Traditional` to the `com.aspose.imaging.StringFormat.setDigitSubstitution(int, com.aspose.imaging.StringDigitSubstitute)` method, then Arabic-Indic digits will be substituted for western digits at display time.

The setter is introduced for the obsolete method setDigitSubstitution.
### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```


Sets the language that is used when local digits are substituted for western digits.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | A National Language Support (NLS) language identifier that identifies the language that will be used when local digits are substituted for western digits. You can pass the `P:System.Globalization.CultureInfo.LCID` property of a `System.Globalization.CultureInfo` object as the NLS language identifier. For example, suppose you create a `System.Globalization.CultureInfo` object by passing the string "ar-EG" to a `System.Globalization.CultureInfo` constructor. If you pass the `P:System.Globalization.CultureInfo.LCID` property of that `System.Globalization.CultureInfo` object along with. `com.aspose.imaging.StringDigitSubstitute.Traditional` to the `com.aspose.imaging.StringFormat.setDigitSubstitution(int,com.aspose.imaging.StringDigitSubstitute)` method, then Arabic-Indic digits will be substituted for western digits at display time.

The setter is introduced for the obsolete method SetDigitSubstitution. |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


Gets the number of spaces between the beginning of a line of text and the first tab stop.

**Returns:**
float - The first tab offset.

The property is introduced for removed method GetTabStops.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Gets an array of distances between tab stops in the units specified by the `P:Aspose.Imaging.getGraphics().PageUnit` property.

**Returns:**
float[] - The tab stops.

The property is introduced for removed method GetTabStops.
### getCustomCharIdent() {#getCustomCharIdent--}
```
public PointF getCustomCharIdent()
```


Gets the custom character ident.

Value: The custom character ident.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - the custom character ident.
### setCustomCharIdent(PointF value) {#setCustomCharIdent-com.aspose.imaging.PointF-}
```
public void setCustomCharIdent(PointF value)
```


Sets the custom character ident.

Value: The custom character ident.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) | the custom character ident. |

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


Creates a deep clone of this `com.aspose.imaging.StringFormat` object.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat) - The deep clone of the current `com.aspose.imaging.StringFormat`.
### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


Sets tab stops for this `com.aspose.imaging.StringFormat` object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstTabOffset | float | The number of spaces between the beginning of a line of text and the first tab stop. |
| tabStops | float[] | An array of distances between tab stops in the units specified by the `com.aspose.imaging.Graphics.PageUnit` property. |

### toString() {#toString--}
```
public String toString()
```


Converts this `com.aspose.imaging.StringFormat` object to a human-readable string.

**Returns:**
java.lang.String - A string representation of this `com.aspose.imaging.StringFormat` object.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Check if objects are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| o | java.lang.Object | The other object. |

**Returns:**
boolean - The equality comparison result.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Get hash code of the current object.

**Returns:**
int - The hash code.
