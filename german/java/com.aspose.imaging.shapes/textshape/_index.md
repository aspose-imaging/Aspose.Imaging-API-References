---
title: "TextShape"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt eine Textform dar."
type: docs
weight: 18
url: /de/java/com.aspose.imaging.shapes/textshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.RectangleProjectedShape](../../com.aspose.imaging.shapes/rectangleprojectedshape)
```
public final class TextShape extends RectangleProjectedShape
```

Stellt eine Textform dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextShape()](#TextShape--) | Initialisiert eine neue Instanz der `TextShape`-Klasse. |
| [TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)](#TextShape-java.lang.String-com.aspose.imaging.RectangleF-com.aspose.imaging.Font-com.aspose.imaging.StringFormat-) | Initialisiert eine neue Instanz der `TextShape`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getText()](#getText--) | Liest oder setzt den gezeichneten Text. |
| [setText(String value)](#setText-java.lang.String-) | Liest oder setzt den gezeichneten Text. |
| [getFont()](#getFont--) | Liest oder setzt die zum Zeichnen des Textes verwendete Schriftart. |
| [setFont(Font value)](#setFont-com.aspose.imaging.Font-) | Liest oder setzt die zum Zeichnen des Textes verwendete Schriftart. |
| [getTextFormat()](#getTextFormat--) | Liest oder setzt das Textformat. |
| [setTextFormat(StringFormat value)](#setTextFormat-com.aspose.imaging.StringFormat-) | Liest oder setzt das Textformat. |
| [getCenter()](#getCenter--) | Liefert das Zentrum der Form. |
| [getBounds()](#getBounds--) | Ruft die Begrenzungen des Objekts ab. |
| [getSegments()](#getSegments--) | Liefert die Segmente der Form. |
| [hasSegments()](#hasSegments--) | Liefert einen Wert, der angibt, ob die Form Segmente hat. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Ruft die Begrenzungen des Objekts ab. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Ruft die Begrenzungen des Objekts ab. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Wendet die angegebene Transformation auf die Form an. |
| [equals(Object o)](#equals-java.lang.Object-) | Überprüft, ob Objekte gleich sind. |
| [hashCode()](#hashCode--) | Gibt den Hashcode des aktuellen Objekts zurück. |
### TextShape() {#TextShape--}
```
public TextShape()
```


Initialisiert eine neue Instanz der `TextShape`-Klasse.

### TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat) {#TextShape-java.lang.String-com.aspose.imaging.RectangleF-com.aspose.imaging.Font-com.aspose.imaging.StringFormat-}
```
public TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)
```


Initialisiert eine neue Instanz der `TextShape`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Der Text zum Zeichnen. |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Das Textrechteck. |
| font | [Font](../../com.aspose.imaging/font) | Die zu verwendende Schriftart. |
| stringFormat | [StringFormat](../../com.aspose.imaging/stringformat) | Das Zeichenkettenformat. |

### getText() {#getText--}
```
public String getText()
```


Liest oder setzt den gezeichneten Text.

Wert: Der gezeichnete Text.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Liest oder setzt den gezeichneten Text.

Wert: Der gezeichnete Text.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getFont() {#getFont--}
```
public Font getFont()
```


Liest oder setzt die zum Zeichnen des Textes verwendete Schriftart.

Wert: Die zum Zeichnen des Textes verwendete Schriftart.

**Returns:**
[Font](../../com.aspose.imaging/font)
### setFont(Font value) {#setFont-com.aspose.imaging.Font-}
```
public void setFont(Font value)
```


Liest oder setzt die zum Zeichnen des Textes verwendete Schriftart.

Wert: Die zum Zeichnen des Textes verwendete Schriftart.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Font](../../com.aspose.imaging/font) |  |

### getTextFormat() {#getTextFormat--}
```
public StringFormat getTextFormat()
```


Liest oder setzt das Textformat.

Wert: Das Textformat.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat)
### setTextFormat(StringFormat value) {#setTextFormat-com.aspose.imaging.StringFormat-}
```
public void setTextFormat(StringFormat value)
```


Liest oder setzt das Textformat.

Wert: Das Textformat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [StringFormat](../../com.aspose.imaging/stringformat) |  |

### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Liefert das Zentrum der Form.

Wert: Der Mittelpunkt der Form.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Ruft die Begrenzungen des Objekts ab.

Wert: Die Begrenzungen des Objekts.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Liefert die Segmente der Form.

Wert: Die Formsegmente.

**Returns:**
com.aspose.imaging.ShapeSegment[]
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Liefert einen Wert, der angibt, ob die Form Segmente hat.

Wert: `True`, wenn die Form Segmente hat; andernfalls `false`.

**Returns:**
boolean
### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Ruft die Begrenzungen des Objekts ab.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Die Matrix, die angewendet wird, bevor die Begrenzungen berechnet werden. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Ruft die Begrenzungen des Objekts ab.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Die Matrix, die angewendet wird, bevor die Begrenzungen berechnet werden. |
| pen | [Pen](../../com.aspose.imaging/pen) | Der Stift, der für das Objekt verwendet wird. Dies kann die Größe der Objektgrenzen beeinflussen. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


Wendet die angegebene Transformation auf die Form an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | Die anzuwendende Transformation. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Überprüft, ob Objekte gleich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| o | java.lang.Object | Das andere Objekt. |

**Returns:**
boolean - Das Ergebnis des Gleichheitsvergleichs.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode des aktuellen Objekts zurück.

**Returns:**
int - Der Hashcode.
