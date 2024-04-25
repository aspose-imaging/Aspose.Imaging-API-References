---
title: Font
second_title: Aspose.Imaging for Java API Reference
description: Defines a particular format for text including font face size and style attributes.
type: docs
weight: 48
url: /com.aspose.imaging/font/
---
**Inheritance:**
java.lang.Object
```
public final class Font
```

Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.
## Constructors

| Constructor | Description |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.imaging.Font-int-) | Initializes a new `com.aspose.imaging.Font` that uses the specified existing `com.aspose.imaging.Font` and `com.aspose.imaging.FontStyle` enumeration. |
| [Font(String fontName, float emSize)](#Font-java.lang.String-float-) | Initializes a new `com.aspose.imaging.Font` using a specified size. |
| [Font(String fontName, float emSize, int style)](#Font-java.lang.String-float-int-) | Initializes a new `com.aspose.imaging.Font` using a specified size and style. |
| [Font(String fontName, float emSize, int style, int unit, int characterSet)](#Font-java.lang.String-float-int-int-int-) | Initializes a new `com.aspose.imaging.Font` using a specified size, style, unit, and character set. |
| [Font(String fontName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | Initializes a new `com.aspose.imaging.Font` using a specified size, style, and unit. |
## Methods

| Method | Description |
| --- | --- |
| [makeFontWithGraphUnit(String fontName, float emSize, int unit)](#makeFontWithGraphUnit-java.lang.String-float-int-) | Initializes a new `com.aspose.imaging.Font` using a specified size and unit. |
| [getBold()](#getBold--) | Gets a value indicating whether this `Font` is bold. |
| [getCharacterSet()](#getCharacterSet--) | Gets a byte value that specifies the character set that this `Font` uses. |
| [getItalic()](#getItalic--) | Gets a value indicating whether this `Font` is italic. |
| [getName()](#getName--) | Gets the face name of this `Font`. |
| [getStrikeout()](#getStrikeout--) | Gets a value indicating whether this `Font` specifies a horizontal line through the font. |
| [getUnderline()](#getUnderline--) | Gets a value indicating whether this `Font` is underlined. |
| [getStyle()](#getStyle--) | Gets style information for this `Font`. |
| [getSize()](#getSize--) | Gets the em-size of this `Font` measured in the units specified by the `P:Aspose.Imaging.Font.Unit` property. |
| [getUnit()](#getUnit--) | Gets the unit of measure for this `Font`. |
| [deepClone()](#deepClone--) | Creates an exact deep copy of this `Font`. |
| [equals(Object obj)](#equals-java.lang.Object-) | Indicates whether the specified object is a `com.aspose.imaging.Font` and has the same property values as this `com.aspose.imaging.Font`. |
| [hashCode()](#hashCode--) | Gets the hash code for this `com.aspose.imaging.Font`. |
| [toString()](#toString--) | Returns a human-readable string representation of this `com.aspose.imaging.Font`. |

## Example: This example demonstrates the use of Font and SolidBrush class to draw strings on Image surface.
This example demonstrates the use of Font and SolidBrush class to draw strings on Image surface. The example creates a new Image and draw shapes using Figures and GraphicsPath
``` java
//Creates an instance of BmpOptions and set its various properties
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//Create an instance of FileCreateSource and assign it as Source for the instance of BmpOptions
//Second Boolean parameter determines if the file to be created IsTemporal or not
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

//Creates an instance of Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //Creates and initialize an instance of Graphics class
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //Clears Graphics surface
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //Creates an instance of Font
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Times New Roman", 16);

    //Create an instance of SolidBrush having Red Color
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    //Draw a String
    graphics.drawString("Created by Aspose.Imaging for Java", font, brush, new com.aspose.imaging.PointF(100, 100));

    // save all changes
    image.save();
} finally {
    image.dispose();
}
```

### Font(Font prototype, int newStyle) {#Font-com.aspose.imaging.Font-int-}
```
public Font(Font prototype, int newStyle)
```


Initializes a new `com.aspose.imaging.Font` that uses the specified existing `com.aspose.imaging.Font` and `com.aspose.imaging.FontStyle` enumeration.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.imaging/font) | The existing `com.aspose.imaging.Font` from which to create the new `com.aspose.imaging.Font`. |
| newStyle | int | The `com.aspose.imaging.FontStyle` to apply to the new `com.aspose.imaging.Font`. Multiple values of the `com.aspose.imaging.FontStyle` enumeration can be combined with the OR operator. |

### Font(String fontName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String fontName, float emSize)
```


Initializes a new `com.aspose.imaging.Font` using a specified size. The character set is set to `F:Aspose.Imaging.CharacterSet.Default`, the graphics unit to `F:Aspose.Imaging.GraphicsUnit.Point`, the font style to `F:Aspose.Imaging.FontStyle.Regular`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | A string representation of the `com.aspose.imaging.Font` name. |
| emSize | float | The em-size, in points, of the new font. |

### Font(String fontName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontName, float emSize, int style)
```


Initializes a new `com.aspose.imaging.Font` using a specified size and style. The character set is set to `F:Aspose.Imaging.CharacterSet.Default`, the graphics unit to `F:Aspose.Imaging.GraphicsUnit.Point`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | A string representation of the `com.aspose.imaging.Font` name. |
| emSize | float | The em-size, in points, of the new font. |
| style | int | The `com.aspose.imaging.FontStyle` of the new font. |

### Font(String fontName, float emSize, int style, int unit, int characterSet) {#Font-java.lang.String-float-int-int-int-}
```
public Font(String fontName, float emSize, int style, int unit, int characterSet)
```


Initializes a new `com.aspose.imaging.Font` using a specified size, style, unit, and character set.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | A string representation of the `com.aspose.imaging.Font` name. |
| emSize | float | The em-size of the new font in the units specified by the `unit` parameter. |
| style | int | The `com.aspose.imaging.FontStyle` of the new font. |
| unit | int | The `com.aspose.imaging.GraphicsUnit` of the new font. |
| characterSet | int | A character set to use for this font. |

### Font(String fontName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String fontName, float emSize, int style, int unit)
```


Initializes a new `com.aspose.imaging.Font` using a specified size, style, and unit.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | A string representation of the `com.aspose.imaging.Font` name. |
| emSize | float | The em-size of the new font in the units specified by the `unit` parameter. |
| style | int | The `com.aspose.imaging.FontStyle` of the new font. |
| unit | int | The `com.aspose.imaging.GraphicsUnit` of the new font. |

### makeFontWithGraphUnit(String fontName, float emSize, int unit) {#makeFontWithGraphUnit-java.lang.String-float-int-}
```
public static Font makeFontWithGraphUnit(String fontName, float emSize, int unit)
```


Initializes a new `com.aspose.imaging.Font` using a specified size and unit. The character set is set to `F:Aspose.Imaging.CharacterSet.Default`, the style is set to `F:Aspose.Imaging.FontStyle.Regular`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | A string representation of the `com.aspose.imaging.Font` name. |
| emSize | float | The em-size of the new font in the units specified by the `unit` parameter. |
| unit | int | The `com.aspose.imaging.GraphicsUnit` of the new font. |

**Returns:**
[Font](../../com.aspose.imaging/font)
### getBold() {#getBold--}
```
public boolean getBold()
```


Gets a value indicating whether this `Font` is bold.

**Returns:**
boolean - True if this `Font` is bold; otherwise, false.
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


Gets a byte value that specifies the character set that this `Font` uses.

**Returns:**
int - A character set that this `Font` uses.
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


Gets a value indicating whether this `Font` is italic.

**Returns:**
boolean - True if this `Font` is italic; otherwise, false.
### getName() {#getName--}
```
public String getName()
```


Gets the face name of this `Font`.

**Returns:**
java.lang.String - A string representation of the face name of this `Font`.
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


Gets a value indicating whether this `Font` specifies a horizontal line through the font.

**Returns:**
boolean - True if this `Font` has a horizontal line through it; otherwise, false.
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


Gets a value indicating whether this `Font` is underlined.

**Returns:**
boolean - True if this `Font` is underlined; otherwise, false.
### getStyle() {#getStyle--}
```
public int getStyle()
```


Gets style information for this `Font`.

**Returns:**
int - A `FontStyle` enumeration that contains style information for this `Font`.
### getSize() {#getSize--}
```
public float getSize()
```


Gets the em-size of this `Font` measured in the units specified by the `P:Aspose.Imaging.Font.Unit` property.

**Returns:**
float - The em-size of this `Font`.
### getUnit() {#getUnit--}
```
public int getUnit()
```


Gets the unit of measure for this `Font`.

**Returns:**
int - A `GraphicsUnit` that represents the unit of measure for this `Font`.
### deepClone() {#deepClone--}
```
public Font deepClone()
```


Creates an exact deep copy of this `Font`.

**Returns:**
[Font](../../com.aspose.imaging/font) - The `Font` this method creates.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Indicates whether the specified object is a `com.aspose.imaging.Font` and has the same property values as this `com.aspose.imaging.Font`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The object to test. |

**Returns:**
boolean - True if the `obj` parameter is a `com.aspose.imaging.Font` and has the same property values as this `com.aspose.imaging.Font`; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gets the hash code for this `com.aspose.imaging.Font`.

**Returns:**
int - The hash code for this `com.aspose.imaging.Font`.
### toString() {#toString--}
```
public String toString()
```


Returns a human-readable string representation of this `com.aspose.imaging.Font`.

**Returns:**
java.lang.String - A string that represents this `com.aspose.imaging.Font`.
