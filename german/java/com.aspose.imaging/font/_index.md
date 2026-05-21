---
title: "Schriftart"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Definiert ein bestimmtes Format für Text, einschließlich Schriftart, Größe und Stil-Attribute."
type: docs
weight: 48
url: /de/java/com.aspose.imaging/font/
---
**Inheritance:**
java.lang.Object
```
public final class Font
```

Definiert ein bestimmtes Format für Text, einschließlich Schriftart, Größe und Stil-Attribute. Diese Klasse kann nicht vererbt werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.imaging.Font-int-) | Initialisiert ein neues `com.aspose.imaging.Font`, das die angegebene vorhandene `com.aspose.imaging.Font` und die Aufzählung `com.aspose.imaging.FontStyle` verwendet. |
| [Font(String fontName, float emSize)](#Font-java.lang.String-float-) | Initialisiert ein neues `com.aspose.imaging.Font` mit einer angegebenen Größe. |
| [Font(String fontName, float emSize, int style)](#Font-java.lang.String-float-int-) | Initialisiert ein neues `com.aspose.imaging.Font` mit einer angegebenen Größe und einem Stil. |
| [Font(String fontName, float emSize, int style, int unit, int characterSet)](#Font-java.lang.String-float-int-int-int-) | Initialisiert ein neues `com.aspose.imaging.Font` mit einer angegebenen Größe, Stil, Einheit und Zeichensatz. |
| [Font(String fontName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | Initialisiert ein neues `com.aspose.imaging.Font` mit einer angegebenen Größe, Stil und Einheit. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [makeFontWithGraphUnit(String fontName, float emSize, int unit)](#makeFontWithGraphUnit-java.lang.String-float-int-) | Initialisiert ein neues `com.aspose.imaging.Font` mit einer angegebenen Größe und Einheit. |
| [getBold()](#getBold--) | Gibt einen Wert zurück, der angibt, ob diese `Font` fett ist. |
| [getCharacterSet()](#getCharacterSet--) | Gibt einen Byte-Wert zurück, der den Zeichensatz angibt, den diese `Font` verwendet. |
| [getItalic()](#getItalic--) | Gibt einen Wert zurück, der angibt, ob diese `Font` kursiv ist. |
| [getName()](#getName--) | Gibt den Namen der Schriftart dieser `Font` zurück. |
| [getStrikeout()](#getStrikeout--) | Gibt einen Wert zurück, der angibt, ob diese `Font` einen horizontalen Strich durch die Schriftart definiert. |
| [getUnderline()](#getUnderline--) | Gibt einen Wert zurück, der angibt, ob diese `Font` unterstrichen ist. |
| [getStyle()](#getStyle--) | Gibt Stilinformationen für diese `Font` zurück. |
| [getSize()](#getSize--) | Gibt die Em-Größe dieser `Font` zurück, gemessen in den Einheiten, die durch die Eigenschaft `P:Aspose.Imaging.Font.Unit` angegeben sind. |
| [getUnit()](#getUnit--) | Ermittelt die Maßeinheit für dieses `Font`. |
| [deepClone()](#deepClone--) | Erstellt eine exakte Tiefenkopie dieses `Font`. |
| [equals(Object obj)](#equals-java.lang.Object-) | Gibt an, ob das angegebene Objekt ein `com.aspose.imaging.Font` ist und dieselben Eigenschaftswerte wie dieses `com.aspose.imaging.Font` hat. |
| [hashCode()](#hashCode--) | Ermittelt den Hashcode für dieses `com.aspose.imaging.Font`. |
| [toString()](#toString--) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses `com.aspose.imaging.Font` zurück. |

## Example: This example demonstrates the use of Font and SolidBrush class to draw strings on Image surface.
Dieses Beispiel demonstriert die Verwendung der Klassen Font und SolidBrush, um Zeichenketten auf einer Image-Oberfläche zu zeichnen. Das Beispiel erstellt ein neues Image und zeichnet Formen mit Figures und GraphicsPath
``` java
//Erstellt eine Instanz von BmpOptions und setzt deren verschiedene Eigenschaften
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//Erstellen Sie eine Instanz von FileCreateSource und weisen Sie sie als Source für die Instanz von BmpOptions zu
//Der zweite boolesche Parameter bestimmt, ob die zu erstellende Datei IsTemporal ist oder nicht
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

//Erstellt eine Instanz von Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //Erstellt und initialisiert eine Instanz der Klasse Graphics
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //Löscht die Graphics-Oberfläche
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //Erstellt eine Instanz von Font
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Times New Roman", 16);

    //Erstellt eine Instanz von SolidBrush mit roter Farbe
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    //Zeichnet eine Zeichenkette
    graphics.drawString("Created by Aspose.Imaging for Java", font, brush, new com.aspose.imaging.PointF(100, 100));

    // Alle Änderungen speichern
    image.save();
} finally {
    image.dispose();
}
```

### Font(Font prototype, int newStyle) {#Font-com.aspose.imaging.Font-int-}
```
public Font(Font prototype, int newStyle)
```


Initialisiert ein neues `com.aspose.imaging.Font`, das die angegebene vorhandene `com.aspose.imaging.Font` und die Aufzählung `com.aspose.imaging.FontStyle` verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.imaging/font) | Das vorhandene `com.aspose.imaging.Font`, aus dem das neue `com.aspose.imaging.Font` erstellt werden soll. |
| newStyle | int | Der `com.aspose.imaging.FontStyle`, der auf das neue `com.aspose.imaging.Font` angewendet werden soll. Mehrere Werte der Aufzählung `com.aspose.imaging.FontStyle` können mit dem ODER-Operator kombiniert werden. |

### Font(String fontName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String fontName, float emSize)
```


Initialisiert ein neues `com.aspose.imaging.Font` mit einer angegebenen Größe. Der Zeichensatz wird auf `F:Aspose.Imaging.CharacterSet.Default` gesetzt, die Grafikeinheit auf `F:Aspose.Imaging.GraphicsUnit.Point` und der Schriftstil auf `F:Aspose.Imaging.FontStyle.Regular`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | java.lang.String | Eine Zeichenkettenrepräsentation des Namens des `com.aspose.imaging.Font`. |
| emSize | float | Die Em-Größe des neuen Fonts in Punkten. |

### Font(String fontName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontName, float emSize, int style)
```


Initialisiert ein neues `com.aspose.imaging.Font` mit einer angegebenen Größe und einem Stil. Der Zeichensatz wird auf `F:Aspose.Imaging.CharacterSet.Default` gesetzt, die Grafikeinheit auf `F:Aspose.Imaging.GraphicsUnit.Point`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | java.lang.String | Eine Zeichenkettenrepräsentation des Namens des `com.aspose.imaging.Font`. |
| emSize | float | Die Em-Größe des neuen Fonts in Punkten. |
| style | int | Der `com.aspose.imaging.FontStyle` des neuen Fonts. |

### Font(String fontName, float emSize, int style, int unit, int characterSet) {#Font-java.lang.String-float-int-int-int-}
```
public Font(String fontName, float emSize, int style, int unit, int characterSet)
```


Initialisiert ein neues `com.aspose.imaging.Font` mit einer angegebenen Größe, Stil, Einheit und Zeichensatz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | java.lang.String | Eine Zeichenkettenrepräsentation des Namens des `com.aspose.imaging.Font`. |
| emSize | float | Die Em-Größe des neuen Fonts in den durch den Parameter `unit` angegebenen Einheiten. |
| style | int | Der `com.aspose.imaging.FontStyle` des neuen Fonts. |
| unit | int | Der `com.aspose.imaging.GraphicsUnit` der neuen Schriftart. |
| characterSet | int | Ein Zeichensatz, der für diese Schriftart verwendet wird. |

### Font(String fontName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String fontName, float emSize, int style, int unit)
```


Initialisiert ein neues `com.aspose.imaging.Font` mit einer angegebenen Größe, Stil und Einheit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | java.lang.String | Eine Zeichenkettenrepräsentation des Namens des `com.aspose.imaging.Font`. |
| emSize | float | Die Em-Größe des neuen Fonts in den durch den Parameter `unit` angegebenen Einheiten. |
| style | int | Der `com.aspose.imaging.FontStyle` des neuen Fonts. |
| unit | int | Der `com.aspose.imaging.GraphicsUnit` der neuen Schriftart. |

### makeFontWithGraphUnit(String fontName, float emSize, int unit) {#makeFontWithGraphUnit-java.lang.String-float-int-}
```
public static Font makeFontWithGraphUnit(String fontName, float emSize, int unit)
```


Initialisiert ein neues `com.aspose.imaging.Font` mit einer angegebenen Größe und Einheit. Der Zeichensatz wird auf `F:Aspose.Imaging.CharacterSet.Default` gesetzt, der Stil wird auf `F:Aspose.Imaging.FontStyle.Regular` gesetzt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | java.lang.String | Eine Zeichenkettenrepräsentation des Namens des `com.aspose.imaging.Font`. |
| emSize | float | Die Em-Größe des neuen Fonts in den durch den Parameter `unit` angegebenen Einheiten. |
| unit | int | Der `com.aspose.imaging.GraphicsUnit` der neuen Schriftart. |

**Returns:**
[Font](../../com.aspose.imaging/font)
### getBold() {#getBold--}
```
public boolean getBold()
```


Gibt einen Wert zurück, der angibt, ob diese `Font` fett ist.

**Returns:**
boolean - True, wenn diese `Font` fett ist; ansonsten false.
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


Gibt einen Byte-Wert zurück, der den Zeichensatz angibt, den diese `Font` verwendet.

**Returns:**
int - Ein Zeichensatz, den diese `Font` verwendet.
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


Gibt einen Wert zurück, der angibt, ob diese `Font` kursiv ist.

**Returns:**
boolean - True, wenn diese `Font` kursiv ist; ansonsten false.
### getName() {#getName--}
```
public String getName()
```


Gibt den Namen der Schriftart dieser `Font` zurück.

**Returns:**
java.lang.String - Eine Zeichenketten-Darstellung des Schriftartnamens dieser `Font`.
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


Gibt einen Wert zurück, der angibt, ob diese `Font` einen horizontalen Strich durch die Schriftart definiert.

**Returns:**
boolean - True, wenn diese `Font` eine horizontale Linie durch sie hat; ansonsten false.
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


Gibt einen Wert zurück, der angibt, ob diese `Font` unterstrichen ist.

**Returns:**
boolean - True, wenn diese `Font` unterstrichen ist; ansonsten false.
### getStyle() {#getStyle--}
```
public int getStyle()
```


Gibt Stilinformationen für diese `Font` zurück.

**Returns:**
int - Eine `FontStyle`-Aufzählung, die Stilinformationen für diese `Font` enthält.
### getSize() {#getSize--}
```
public float getSize()
```


Gibt die Em-Größe dieser `Font` zurück, gemessen in den Einheiten, die durch die Eigenschaft `P:Aspose.Imaging.Font.Unit` angegeben sind.

**Returns:**
float - Die Em-Größe dieser `Font`.
### getUnit() {#getUnit--}
```
public int getUnit()
```


Ermittelt die Maßeinheit für dieses `Font`.

**Returns:**
int - Ein `GraphicsUnit`, das die Maßeinheit für diese `Font` darstellt.
### deepClone() {#deepClone--}
```
public Font deepClone()
```


Erstellt eine exakte Tiefenkopie dieses `Font`.

**Returns:**
[Font](../../com.aspose.imaging/font) - The `Font` this method creates.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Gibt an, ob das angegebene Objekt ein `com.aspose.imaging.Font` ist und dieselben Eigenschaftswerte wie dieses `com.aspose.imaging.Font` hat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das zu testende Objekt. |

**Returns:**
boolean - True, wenn der Parameter `obj` ein `com.aspose.imaging.Font` ist und dieselben Eigenschaftswerte wie dieses `com.aspose.imaging.Font` hat; ansonsten false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Ermittelt den Hashcode für dieses `com.aspose.imaging.Font`.

**Returns:**
int - Der Hashcode für dieses `com.aspose.imaging.Font`.
### toString() {#toString--}
```
public String toString()
```


Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses `com.aspose.imaging.Font` zurück.

**Returns:**
java.lang.String - Eine Zeichenkette, die dieses `com.aspose.imaging.Font` darstellt.
