---
title: "TextShape"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar en textform."
type: docs
weight: 18
url: /sv/java/com.aspose.imaging.shapes/textshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.RectangleProjectedShape](../../com.aspose.imaging.shapes/rectangleprojectedshape)
```
public final class TextShape extends RectangleProjectedShape
```

Representerar en textform.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TextShape()](#TextShape--) | Initierar en ny instans av klassen `TextShape`. |
| [TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)](#TextShape-java.lang.String-com.aspose.imaging.RectangleF-com.aspose.imaging.Font-com.aspose.imaging.StringFormat-) | Initierar en ny instans av klassen `TextShape`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getText()](#getText--) | Hämtar eller anger den ritade texten. |
| [setText(String value)](#setText-java.lang.String-) | Hämtar eller anger den ritade texten. |
| [getFont()](#getFont--) | Hämtar eller anger teckensnittet som används för att rita texten. |
| [setFont(Font value)](#setFont-com.aspose.imaging.Font-) | Hämtar eller anger teckensnittet som används för att rita texten. |
| [getTextFormat()](#getTextFormat--) | Hämtar eller anger textformatet. |
| [setTextFormat(StringFormat value)](#setTextFormat-com.aspose.imaging.StringFormat-) | Hämtar eller anger textformatet. |
| [getCenter()](#getCenter--) | Hämtar formens centrum. |
| [getBounds()](#getBounds--) | Hämtar objektets gränser. |
| [getSegments()](#getSegments--) | Hämtar formens segment. |
| [hasSegments()](#hasSegments--) | Hämtar ett värde som indikerar om formen har segment. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Hämtar objektets gränser. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Hämtar objektets gränser. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Tillämpar den angivna transformationen på formen. |
| [equals(Object o)](#equals-java.lang.Object-) | Kontrollera om objekt är lika. |
| [hashCode()](#hashCode--) | Hämta hashkoden för det aktuella objektet. |
### TextShape() {#TextShape--}
```
public TextShape()
```


Initierar en ny instans av klassen `TextShape`.

### TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat) {#TextShape-java.lang.String-com.aspose.imaging.RectangleF-com.aspose.imaging.Font-com.aspose.imaging.StringFormat-}
```
public TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)
```


Initierar en ny instans av klassen `TextShape`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Texten att rita. |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Textrektangeln. |
| font | [Font](../../com.aspose.imaging/font) | Typsnittet att använda. |
| stringFormat | [StringFormat](../../com.aspose.imaging/stringformat) | Strängformatet. |

### getText() {#getText--}
```
public String getText()
```


Hämtar eller anger den ritade texten.

Värde: Den ritade texten.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Hämtar eller anger den ritade texten.

Värde: Den ritade texten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getFont() {#getFont--}
```
public Font getFont()
```


Hämtar eller anger teckensnittet som används för att rita texten.

Värde: Typsnittet som används för att rita texten.

**Returns:**
[Font](../../com.aspose.imaging/font)
### setFont(Font value) {#setFont-com.aspose.imaging.Font-}
```
public void setFont(Font value)
```


Hämtar eller anger teckensnittet som används för att rita texten.

Värde: Typsnittet som används för att rita texten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Font](../../com.aspose.imaging/font) |  |

### getTextFormat() {#getTextFormat--}
```
public StringFormat getTextFormat()
```


Hämtar eller anger textformatet.

Värde: Textformatet.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat)
### setTextFormat(StringFormat value) {#setTextFormat-com.aspose.imaging.StringFormat-}
```
public void setTextFormat(StringFormat value)
```


Hämtar eller anger textformatet.

Värde: Textformatet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StringFormat](../../com.aspose.imaging/stringformat) |  |

### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Hämtar formens centrum.

Värde: Formens centrum.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Hämtar objektets gränser.

Värde: Objektets gränser.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Hämtar formens segment.

Värde: Formens segment.

**Returns:**
com.aspose.imaging.ShapeSegment[]
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Hämtar ett värde som indikerar om formen har segment.

Värde: `True` om formen har segment; annars `false`.

**Returns:**
boolean
### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Hämtar objektets gränser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Matriser att tillämpa innan gränser beräknas. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Hämtar objektets gränser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Matriser att tillämpa innan gränser beräknas. |
| pen | [Pen](../../com.aspose.imaging/pen) | Pennan att använda för objektet. Detta kan påverka objektets gränsstorlek. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


Tillämpar den angivna transformationen på formen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | Transformationen att tillämpa. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Kontrollera om objekt är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| o | java.lang.Object | Det andra objektet. |

**Returns:**
boolean - Resultatet av likhetsjämförelsen.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hämta hashkoden för det aktuella objektet.

**Returns:**
int - Hashkoden.
