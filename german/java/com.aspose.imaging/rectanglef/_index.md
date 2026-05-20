---
title: "RectangleF"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Speichert ein Set von vier Gleitkommazahlen, das die Position und Größe eines Rechtecks darstellt."
type: docs
weight: 94
url: /de/java/com.aspose.imaging/rectanglef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class RectangleF extends Struct<RectangleF>
```

Speichert ein Set von vier Gleitkommazahlen, das die Position und Größe eines Rechtecks darstellt.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | Initialisiert eine neue Instanz der `com.aspose.imaging.RectangleF`-Struktur mit dem angegebenen Ort und der Größe. |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Initialisiert eine neue Instanz der `com.aspose.imaging.RectangleF`-Struktur mit dem angegebenen Ort und der Größe. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEmpty()](#getEmpty--) | Gibt eine neue Instanz der `com.aspose.imaging.RectangleF`-Struktur zurück, deren Werte `com.aspose.imaging.RectangleF.X`, `com.aspose.imaging.RectangleF.Y`, `com.aspose.imaging.RectangleF.Width` und `com.aspose.imaging.RectangleF.Height` auf Null gesetzt sind. |
| [getLocation()](#getLocation--) | Liest oder setzt die Koordinaten der oberen linken Ecke dieser `com.aspose.imaging.RectangleF`-Struktur. |
| [setLocation(PointF value)](#setLocation-com.aspose.imaging.PointF-) | Liest oder setzt die Koordinaten der oberen linken Ecke dieser `com.aspose.imaging.RectangleF`-Struktur. |
| [getSize()](#getSize--) | Liest oder setzt die Größe dieser `com.aspose.imaging.RectangleF`. |
| [setSize(SizeF value)](#setSize-com.aspose.imaging.SizeF-) | Liest oder setzt die Größe dieser `com.aspose.imaging.RectangleF`. |
| [getX()](#getX--) | Liest oder setzt die X‑Koordinate der oberen linken Ecke dieser `com.aspose.imaging.RectangleF`-Struktur. |
| [setX(float value)](#setX-float-) | Liest oder setzt die X‑Koordinate der oberen linken Ecke dieser `com.aspose.imaging.RectangleF`-Struktur. |
| [getY()](#getY--) | Liest oder setzt die Y‑Koordinate der oberen linken Ecke dieser `com.aspose.imaging.RectangleF`-Struktur. |
| [setY(float value)](#setY-float-) | Liest oder setzt die Y‑Koordinate der oberen linken Ecke dieser `com.aspose.imaging.RectangleF`-Struktur. |
| [getWidth()](#getWidth--) | Liest oder setzt die Breite dieser `com.aspose.imaging.RectangleF`-Struktur. |
| [setWidth(float value)](#setWidth-float-) | Liest oder setzt die Breite dieser `com.aspose.imaging.RectangleF`-Struktur. |
| [getHeight()](#getHeight--) | Liest oder setzt die Höhe dieser `com.aspose.imaging.RectangleF`-Struktur. |
| [setHeight(float value)](#setHeight-float-) | Liest oder setzt die Höhe dieser `com.aspose.imaging.RectangleF`-Struktur. |
| [getLeft()](#getLeft--) | Liest oder setzt die X‑Koordinate der linken Kante dieser `com.aspose.imaging.RectangleF`-Struktur. |
| [setLeft(float value)](#setLeft-float-) | Liest oder setzt die X‑Koordinate der linken Kante dieser `com.aspose.imaging.RectangleF`-Struktur. |
| [getTop()](#getTop--) | Liest oder setzt die Y‑Koordinate der oberen Kante dieser `com.aspose.imaging.RectangleF`-Struktur. |
| [setTop(float value)](#setTop-float-) | Liest oder setzt die Y‑Koordinate der oberen Kante dieser `com.aspose.imaging.RectangleF`-Struktur. |
| [getRight()](#getRight--) | Liest oder setzt die X‑Koordinate, die die Summe von `com.aspose.imaging.RectangleF.X` und `com.aspose.imaging.RectangleF.Width` dieser `com.aspose.imaging.RectangleF`-Struktur ist. |
| [setRight(float value)](#setRight-float-) | Liest oder setzt die X‑Koordinate, die die Summe von `com.aspose.imaging.RectangleF.X` und `com.aspose.imaging.RectangleF.Width` dieser `com.aspose.imaging.RectangleF`-Struktur ist. |
| [getBottom()](#getBottom--) | Liest oder setzt die Y‑Koordinate, die die Summe von `com.aspose.imaging.RectangleF.Y` und `com.aspose.imaging.RectangleF.Height` dieser `com.aspose.imaging.RectangleF`-Struktur ist. |
| [setBottom(float value)](#setBottom-float-) | Liest oder setzt die Y‑Koordinate, die die Summe von `com.aspose.imaging.RectangleF.Y` und `com.aspose.imaging.RectangleF.Height` dieser `com.aspose.imaging.RectangleF`-Struktur ist. |
| [isEmpty()](#isEmpty--) | Gibt einen Wert zurück, der angibt, ob die Eigenschaft `com.aspose.imaging.RectangleF.Width` oder `com.aspose.imaging.RectangleF.Height` dieses `com.aspose.imaging.RectangleF` den Wert Null hat. |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Erstellt ein neues `Rectangle` aus zwei angegebenen Punkten. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.imaging.RectangleF-float-float-) | Erstellt und gibt eine aufgeblähte Kopie der angegebenen `com.aspose.imaging.RectangleF`-Struktur zurück. |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Gibt eine `com.aspose.imaging.RectangleF`-Struktur zurück, die die Schnittmenge zweier Rechtecke darstellt. |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Erstellt das kleinste mögliche dritte Rechteck, das beide Rechtecke, die eine Vereinigung bilden, enthalten kann. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Prüft, ob zwei `com.aspose.imaging.RectangleF`-Strukturen dieselbe Position und Größe haben. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Prüft, ob sich zwei `com.aspose.imaging.RectangleF`-Strukturen in Position oder Größe unterscheiden. |
| [op_Multiply(RectangleF rectangle, float multiplier)](#op-Multiply-com.aspose.imaging.RectangleF-float-) | Implementiert den Operator \*. |
| [op_Division(RectangleF rectangle, float divider)](#op-Division-com.aspose.imaging.RectangleF-float-) | Implementiert den Operator /. |
| [to_RectangleF(Rectangle rect)](#to-RectangleF-com.aspose.imaging.Rectangle-) | Konvertiert die angegebene `com.aspose.imaging.Rectangle`-Struktur in eine `com.aspose.imaging.RectangleF`-Struktur. |
| [fromLeftTopRightBottom(float left, float top, float right, float bottom)](#fromLeftTopRightBottom-float-float-float-float-) | Erstellt eine `com.aspose.imaging.RectangleF`-Struktur mit der oberen linken und der unteren rechten Ecke an den angegebenen Positionen. |
| [normalize()](#normalize--) | Normalisiert das Rechteck, indem es seine Breite und Höhe positiv macht, links kleiner als rechts und oben kleiner als unten. |
| [contains(float x, float y)](#contains-float-float-) | Bestimmt, ob der angegebene Punkt innerhalb dieser `com.aspose.imaging.RectangleF`-Struktur liegt. |
| [contains(PointF point)](#contains-com.aspose.imaging.PointF-) | Bestimmt, ob der angegebene Punkt innerhalb dieser `com.aspose.imaging.RectangleF`-Struktur liegt. |
| [contains(RectangleF rect)](#contains-com.aspose.imaging.RectangleF-) | Bestimmt, ob der durch `rect` dargestellte rechteckige Bereich vollständig in dieser `com.aspose.imaging.RectangleF`-Struktur enthalten ist. |
| [inflate(float x, float y)](#inflate-float-float-) | Vergrößert diese `com.aspose.imaging.RectangleF`-Struktur um den angegebenen Betrag. |
| [inflate(SizeF size)](#inflate-com.aspose.imaging.SizeF-) | Vergrößert dieses `com.aspose.imaging.RectangleF` um den angegebenen Betrag. |
| [intersect(RectangleF rect)](#intersect-com.aspose.imaging.RectangleF-) | Ersetzt diese `com.aspose.imaging.RectangleF`-Struktur durch die Schnittmenge von ihr selbst und der angegebenen `com.aspose.imaging.RectangleF`-Struktur. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.imaging.RectangleF-) | Bestimmt, ob dieses Rechteck mit `rect` schneidet. |
| [offset(PointF pos)](#offset-com.aspose.imaging.PointF-) | Passt die Position dieses Rechtecks um den angegebenen Betrag an. |
| [offset(float x, float y)](#offset-float-float-) | Passt die Position dieses Rechtecks um den angegebenen Betrag an. |
| [equals(Object obj)](#equals-java.lang.Object-) | Prüft, ob `obj` ein `com.aspose.imaging.RectangleF` mit derselben Position und Größe wie dieses `com.aspose.imaging.RectangleF` ist. |
| [hashCode()](#hashCode--) | Gibt den Hashcode für diese `com.aspose.imaging.RectangleF`-Struktur zurück. |
| [toString()](#toString--) | Konvertiert die Attribute dieses `com.aspose.imaging.RectangleF` in eine menschenlesbare Zeichenkette. |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.imaging.RectangleF-) |  |
| [Clone()](#Clone--) |  |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


Initialisiert eine neue Instanz der `com.aspose.imaging.RectangleF`-Struktur mit dem angegebenen Ort und der Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x‑Koordinate der oberen linken Ecke des Rechtecks. |
| y | float | Die y‑Koordinate der oberen linken Ecke des Rechtecks. |
| Breite | float | Die Breite des Rechtecks. |
| Höhe | float | Die Höhe des Rechtecks. |

### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


Initialisiert eine neue Instanz der `com.aspose.imaging.RectangleF`-Struktur mit dem angegebenen Ort und der Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| location | [PointF](../../com.aspose.imaging/pointf) | Ein `com.aspose.imaging.PointF`, der die obere linke Ecke des rechteckigen Bereichs darstellt. |
| size | [SizeF](../../com.aspose.imaging/sizef) | Ein `com.aspose.imaging.SizeF`, der die Breite und Höhe des rechteckigen Bereichs darstellt. |

### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```


Gibt eine neue Instanz der `com.aspose.imaging.RectangleF`-Struktur zurück, deren Werte `com.aspose.imaging.RectangleF.X`, `com.aspose.imaging.RectangleF.Y`, `com.aspose.imaging.RectangleF.Width` und `com.aspose.imaging.RectangleF.Height` auf Null gesetzt sind.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getLocation() {#getLocation--}
```
public PointF getLocation()
```


Liest oder setzt die Koordinaten der oberen linken Ecke dieser `com.aspose.imaging.RectangleF`-Struktur.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - A `com.aspose.imaging.PointF` that represents the upper-left corner of this `com.aspose.imaging.RectangleF` structure.
### setLocation(PointF value) {#setLocation-com.aspose.imaging.PointF-}
```
public void setLocation(PointF value)
```


Liest oder setzt die Koordinaten der oberen linken Ecke dieser `com.aspose.imaging.RectangleF`-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getSize() {#getSize--}
```
public SizeF getSize()
```


Liest oder setzt die Größe dieser `com.aspose.imaging.RectangleF`.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - A `com.aspose.imaging.SizeF` that represents the width and height of this `com.aspose.imaging.RectangleF` structure.
### setSize(SizeF value) {#setSize-com.aspose.imaging.SizeF-}
```
public void setSize(SizeF value)
```


Liest oder setzt die Größe dieser `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.imaging/sizef) |  |

### getX() {#getX--}
```
public float getX()
```


Liest oder setzt die X‑Koordinate der oberen linken Ecke dieser `com.aspose.imaging.RectangleF`-Struktur.

**Returns:**
float - Die x‑Koordinate der oberen linken Ecke dieser `com.aspose.imaging.RectangleF`-Struktur.
### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Liest oder setzt die X‑Koordinate der oberen linken Ecke dieser `com.aspose.imaging.RectangleF`-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getY() {#getY--}
```
public float getY()
```


Liest oder setzt die Y‑Koordinate der oberen linken Ecke dieser `com.aspose.imaging.RectangleF`-Struktur.

**Returns:**
float - Die y‑Koordinate der oberen linken Ecke dieser `com.aspose.imaging.RectangleF`-Struktur.
### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Liest oder setzt die Y‑Koordinate der oberen linken Ecke dieser `com.aspose.imaging.RectangleF`-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getWidth() {#getWidth--}
```
public float getWidth()
```


Liest oder setzt die Breite dieser `com.aspose.imaging.RectangleF`-Struktur.

**Returns:**
float - Die Breite dieser `com.aspose.imaging.RectangleF`-Struktur.
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Liest oder setzt die Breite dieser `com.aspose.imaging.RectangleF`-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getHeight() {#getHeight--}
```
public float getHeight()
```


Liest oder setzt die Höhe dieser `com.aspose.imaging.RectangleF`-Struktur.

**Returns:**
float - Die Höhe dieser `com.aspose.imaging.RectangleF`-Struktur.
### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


Liest oder setzt die Höhe dieser `com.aspose.imaging.RectangleF`-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getLeft() {#getLeft--}
```
public float getLeft()
```


Liest oder setzt die X‑Koordinate der linken Kante dieser `com.aspose.imaging.RectangleF`-Struktur.

**Returns:**
float - Die x‑Koordinate der linken Kante dieser `com.aspose.imaging.RectangleF`-Struktur.
### setLeft(float value) {#setLeft-float-}
```
public void setLeft(float value)
```


Liest oder setzt die X‑Koordinate der linken Kante dieser `com.aspose.imaging.RectangleF`-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getTop() {#getTop--}
```
public float getTop()
```


Liest oder setzt die Y‑Koordinate der oberen Kante dieser `com.aspose.imaging.RectangleF`-Struktur.

**Returns:**
float - Die y‑Koordinate der oberen Kante dieser `com.aspose.imaging.RectangleF`-Struktur.
### setTop(float value) {#setTop-float-}
```
public void setTop(float value)
```


Liest oder setzt die Y‑Koordinate der oberen Kante dieser `com.aspose.imaging.RectangleF`-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getRight() {#getRight--}
```
public float getRight()
```


Liest oder setzt die X‑Koordinate, die die Summe von `com.aspose.imaging.RectangleF.X` und `com.aspose.imaging.RectangleF.Width` dieser `com.aspose.imaging.RectangleF`-Struktur ist.

**Returns:**
float - Die x-Koordinate, die die Summe von `com.aspose.imaging.RectangleF.X` und `com.aspose.imaging.RectangleF.Width` dieser `com.aspose.imaging.RectangleF`-Struktur ist.
### setRight(float value) {#setRight-float-}
```
public void setRight(float value)
```


Liest oder setzt die X‑Koordinate, die die Summe von `com.aspose.imaging.RectangleF.X` und `com.aspose.imaging.RectangleF.Width` dieser `com.aspose.imaging.RectangleF`-Struktur ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getBottom() {#getBottom--}
```
public float getBottom()
```


Liest oder setzt die Y‑Koordinate, die die Summe von `com.aspose.imaging.RectangleF.Y` und `com.aspose.imaging.RectangleF.Height` dieser `com.aspose.imaging.RectangleF`-Struktur ist.

**Returns:**
float - Die y-Koordinate, die die Summe von `com.aspose.imaging.RectangleF.Y` und `com.aspose.imaging.RectangleF.Height` dieser `com.aspose.imaging.RectangleF`-Struktur ist.
### setBottom(float value) {#setBottom-float-}
```
public void setBottom(float value)
```


Liest oder setzt die Y‑Koordinate, die die Summe von `com.aspose.imaging.RectangleF.Y` und `com.aspose.imaging.RectangleF.Height` dieser `com.aspose.imaging.RectangleF`-Struktur ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Gibt einen Wert zurück, der angibt, ob die Eigenschaft `com.aspose.imaging.RectangleF.Width` oder `com.aspose.imaging.RectangleF.Height` dieses `com.aspose.imaging.RectangleF` den Wert Null hat.

**Returns:**
boolean - Diese Eigenschaft gibt true zurück, wenn die `com.aspose.imaging.RectangleF.Width`‑ oder `com.aspose.imaging.RectangleF.Height`‑Eigenschaft dieser `com.aspose.imaging.RectangleF` den Wert null hat; andernfalls false.
### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


Erstellt ein neues `Rectangle` aus zwei angegebenen Punkten. Zwei Scheitelpunkte des erstellten `Rectangle` entsprechen den übergebenen `point1` und `point2`. Diese sind typischerweise die gegenüberliegenden Eckpunkte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | Der erste `Point` für das neue Rechteck. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | Der zweite `Point` für das neue Rechteck. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A newly created `Rectangle`.
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.imaging.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


Erstellt und gibt eine aufgeblähte Kopie der angegebenen `com.aspose.imaging.RectangleF`‑Struktur zurück. Die Kopie wird um den angegebenen Betrag aufgebläht. Das ursprüngliche Rechteck bleibt unverändert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Das zu kopierende `com.aspose.imaging.RectangleF`. Dieses Rechteck wird nicht verändert. |
| x | float | Der Betrag, um den die Kopie des Rechtecks horizontal aufgebläht wird. |
| y | float | Der Betrag, um den die Kopie des Rechtecks vertikal aufgebläht wird. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The inflated `com.aspose.imaging.RectangleF`.
### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


Gibt eine `com.aspose.imaging.RectangleF`‑Struktur zurück, die die Schnittmenge zweier Rechtecke darstellt. Wenn keine Schnittmenge existiert, wird ein leeres `com.aspose.imaging.RectangleF` zurückgegeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.imaging/rectanglef) | Ein erstes Rechteck zum Überschneiden. |
| b | [RectangleF](../../com.aspose.imaging/rectanglef) | Ein zweites Rechteck zum Überschneiden. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A third `com.aspose.imaging.RectangleF` structure the size of which represents the overlapped area of the two specified rectangles.
### union(RectangleF a, RectangleF b) {#union-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


Erstellt das kleinste mögliche dritte Rechteck, das beide Rechtecke, die eine Vereinigung bilden, enthalten kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.imaging/rectanglef) | Ein erstes Rechteck zur Vereinigung. |
| b | [RectangleF](../../com.aspose.imaging/rectanglef) | Ein zweites Rechteck zur Vereinigung. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A third `com.aspose.imaging.RectangleF` structure that contains both of the two rectangles that form the union.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


Prüft, ob zwei `com.aspose.imaging.RectangleF`-Strukturen dieselbe Position und Größe haben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.imaging/rectanglef) | Die `com.aspose.imaging.RectangleF`‑Struktur, die links vom Gleichheitsoperator steht. |
| right | [RectangleF](../../com.aspose.imaging/rectanglef) | Die `com.aspose.imaging.RectangleF`‑Struktur, die rechts vom Gleichheitsoperator steht. |

**Returns:**
boolean - Dieser Operator gibt true zurück, wenn die beiden angegebenen `com.aspose.imaging.RectangleF`‑Strukturen gleiche `com.aspose.imaging.RectangleF.X`‑, `com.aspose.imaging.RectangleF.Y`‑, `com.aspose.imaging.RectangleF.Width`‑ und `com.aspose.imaging.RectangleF.Height`‑Eigenschaften besitzen.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


Prüft, ob sich zwei `com.aspose.imaging.RectangleF`-Strukturen in Position oder Größe unterscheiden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.imaging/rectanglef) | Die `com.aspose.imaging.RectangleF`‑Struktur, die links vom Ungleichheitsoperator steht. |
| right | [RectangleF](../../com.aspose.imaging/rectanglef) | Die `com.aspose.imaging.RectangleF`‑Struktur, die rechts vom Ungleichheitsoperator steht. |

**Returns:**
boolean - Dieser Operator gibt true zurück, wenn irgendeine der `com.aspose.imaging.RectangleF.X`‑, `com.aspose.imaging.RectangleF.Y`‑, `com.aspose.imaging.RectangleF.Width`‑ oder `com.aspose.imaging.RectangleF.Height`‑Eigenschaften der beiden `com.aspose.imaging.RectangleF`‑Strukturen ungleich ist; andernfalls false.
### op_Multiply(RectangleF rectangle, float multiplier) {#op-Multiply-com.aspose.imaging.RectangleF-float-}
```
public static RectangleF op_Multiply(RectangleF rectangle, float multiplier)
```


Implementiert den Operator \*.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Das Rechteck. |
| Multiplikator | float | Der Multiplikator. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The result of the operator.
### op_Division(RectangleF rectangle, float divider) {#op-Division-com.aspose.imaging.RectangleF-float-}
```
public static RectangleF op_Division(RectangleF rectangle, float divider)
```


Implementiert den Operator /.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Das Rechteck. |
| Divisor | float | Der Divisor. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The result of the operator.
### to_RectangleF(Rectangle rect) {#to-RectangleF-com.aspose.imaging.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle rect)
```


Konvertiert die angegebene `com.aspose.imaging.Rectangle`-Struktur in eine `com.aspose.imaging.RectangleF`-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Die `com.aspose.imaging.Rectangle`-Struktur zum Konvertieren. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The `com.aspose.imaging.RectangleF` structure that is converted from the specified `com.aspose.imaging.Rectangle` structure.
### fromLeftTopRightBottom(float left, float top, float right, float bottom) {#fromLeftTopRightBottom-float-float-float-float-}
```
public static RectangleF fromLeftTopRightBottom(float left, float top, float right, float bottom)
```


Erstellt eine `com.aspose.imaging.RectangleF`-Struktur mit der oberen linken und der unteren rechten Ecke an den angegebenen Positionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| links | float | Die x-Koordinate der oberen linken Ecke des rechteckigen Bereichs. |
| oben | float | Die y-Koordinate der oberen linken Ecke des rechteckigen Bereichs. |
| rechts | float | Die x-Koordinate der unteren rechten Ecke des rechteckigen Bereichs. |
| unten | float | Die y-Koordinate der unteren rechten Ecke des rechteckigen Bereichs. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The new `com.aspose.imaging.RectangleF` that this method creates.
### normalize() {#normalize--}
```
public void normalize()
```


Normalisiert das Rechteck, indem es seine Breite und Höhe positiv macht, links kleiner als rechts und oben kleiner als unten.

### contains(float x, float y) {#contains-float-float-}
```
public boolean contains(float x, float y)
```


Bestimmt, ob der angegebene Punkt innerhalb dieser `com.aspose.imaging.RectangleF`-Struktur liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y-Koordinate des zu testenden Punktes. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der durch `x` und `y` definierte Punkt innerhalb dieser `com.aspose.imaging.RectangleF`-Struktur liegt; andernfalls false.
### contains(PointF point) {#contains-com.aspose.imaging.PointF-}
```
public boolean contains(PointF point)
```


Bestimmt, ob der angegebene Punkt innerhalb dieser `com.aspose.imaging.RectangleF`-Struktur liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Das `com.aspose.imaging.PointF` zum Testen. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der durch den Parameter `point` dargestellte Punkt innerhalb dieser `com.aspose.imaging.RectangleF`-Struktur liegt; andernfalls false.
### contains(RectangleF rect) {#contains-com.aspose.imaging.RectangleF-}
```
public boolean contains(RectangleF rect)
```


Bestimmt, ob der durch `rect` dargestellte rechteckige Bereich vollständig in dieser `com.aspose.imaging.RectangleF`-Struktur enthalten ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Das `com.aspose.imaging.RectangleF` zum Testen. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der durch `rect` dargestellte rechteckige Bereich vollständig innerhalb des durch diese `com.aspose.imaging.RectangleF` dargestellten rechteckigen Bereichs liegt; andernfalls false.
### inflate(float x, float y) {#inflate-float-float-}
```
public void inflate(float x, float y)
```


Vergrößert diese `com.aspose.imaging.RectangleF`-Struktur um den angegebenen Betrag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Der Betrag, um den diese `com.aspose.imaging.RectangleF`-Struktur horizontal aufgebläht werden soll. |
| y | float | Der Betrag, um den diese `com.aspose.imaging.RectangleF`-Struktur vertikal aufgebläht werden soll. |

### inflate(SizeF size) {#inflate-com.aspose.imaging.SizeF-}
```
public void inflate(SizeF size)
```


Vergrößert dieses `com.aspose.imaging.RectangleF` um den angegebenen Betrag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | Der Betrag, um den dieses Rechteck aufgebläht werden soll. |

### intersect(RectangleF rect) {#intersect-com.aspose.imaging.RectangleF-}
```
public void intersect(RectangleF rect)
```


Ersetzt diese `com.aspose.imaging.RectangleF`-Struktur durch die Schnittmenge von ihr selbst und der angegebenen `com.aspose.imaging.RectangleF`-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Das Rechteck zum Schneiden. |

### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.imaging.RectangleF-}
```
public boolean intersectsWith(RectangleF rect)
```


Bestimmt, ob dieses Rechteck mit `rect` schneidet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Das Rechteck zum Testen. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn irgendeine Schnittmenge besteht.
### offset(PointF pos) {#offset-com.aspose.imaging.PointF-}
```
public void offset(PointF pos)
```


Passt die Position dieses Rechtecks um den angegebenen Betrag an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.imaging/pointf) | Der Betrag, um den die Position verschoben wird. |

### offset(float x, float y) {#offset-float-float-}
```
public void offset(float x, float y)
```


Passt die Position dieses Rechtecks um den angegebenen Betrag an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Der Betrag, um den die Position horizontal verschoben wird. |
| y | float | Der Betrag, um den die Position vertikal verschoben wird. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Prüft, ob `obj` ein `com.aspose.imaging.RectangleF` mit derselben Position und Größe wie dieses `com.aspose.imaging.RectangleF` ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das `System.Object` zum Testen. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn `obj` ein `com.aspose.imaging.RectangleF` ist und seine X-, Y-, Width- und Height-Eigenschaften den entsprechenden Eigenschaften dieses `com.aspose.imaging.RectangleF` entsprechen; andernfalls false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode für diese `com.aspose.imaging.RectangleF`-Struktur zurück.

**Returns:**
int - Der Hashcode für dieses `com.aspose.imaging.RectangleF`.
### toString() {#toString--}
```
public String toString()
```


Konvertiert die Attribute dieses `com.aspose.imaging.RectangleF` in eine menschenlesbare Zeichenkette.

**Returns:**
java.lang.String - Eine Zeichenkette, die die Position, Breite und Höhe dieser `com.aspose.imaging.RectangleF`-Struktur enthält.
### CloneTo(RectangleF that) {#CloneTo-com.aspose.imaging.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.imaging/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

**Returns:**
boolean
