---
title: "Rechteck"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Speichert ein Set von vier Ganzzahlen, das die Position und Größe eines Rechtecks darstellt."
type: docs
weight: 93
url: /de/java/com.aspose.imaging/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Rectangle extends Struct<Rectangle>
```

Speichert ein Set von vier Ganzzahlen, das die Position und Größe eines Rechtecks darstellt.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | Initialisiert eine neue Instanz der `com.aspose.imaging.Rectangle`-Struktur mit dem angegebenen Ort und der Größe. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Initialisiert eine neue Instanz der `com.aspose.imaging.Rectangle`-Struktur mit dem angegebenen Ort und der Größe. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEmpty()](#getEmpty--) | Gibt eine neue Instanz der `com.aspose.imaging.Rectangle`-Struktur zurück, deren Werte `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` und `com.aspose.imaging.Rectangle.Height` auf Null gesetzt sind. |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Erstellt ein neues `Rectangle` aus zwei angegebenen Punkten. |
| [ceiling(RectangleF value)](#ceiling-com.aspose.imaging.RectangleF-) | Konvertiert die angegebene `com.aspose.imaging.RectangleF`-Struktur in eine `com.aspose.imaging.Rectangle`-Struktur, indem die Werte von `com.aspose.imaging.RectangleF` auf die nächsthöheren Ganzzahlen gerundet werden. |
| [truncate(RectangleF value)](#truncate-com.aspose.imaging.RectangleF-) | Konvertiert das angegebene `com.aspose.imaging.RectangleF` in ein `com.aspose.imaging.Rectangle`, indem die Werte von `com.aspose.imaging.RectangleF` abgeschnitten werden. |
| [round(RectangleF value)](#round-com.aspose.imaging.RectangleF-) | Konvertiert das angegebene `com.aspose.imaging.RectangleF` in ein `com.aspose.imaging.Rectangle`, indem die Werte des `com.aspose.imaging.RectangleF` auf die nächsten Ganzzahlen gerundet werden. |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.imaging.Rectangle-int-int-) | Erstellt und gibt eine aufgeblähte Kopie der angegebenen `com.aspose.imaging.Rectangle`-Struktur zurück. |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | Gibt eine dritte `com.aspose.imaging.Rectangle`-Struktur zurück, die die Schnittmenge zweier anderer `com.aspose.imaging.Rectangle`-Strukturen darstellt. |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | Liefert eine `com.aspose.imaging.Rectangle`-Struktur, die die Vereinigung zweier `com.aspose.imaging.Rectangle`-Strukturen enthält. |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | Prüft, ob zwei `com.aspose.imaging.Rectangle`-Strukturen die gleiche Position und Größe haben. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | Prüft, ob sich zwei `com.aspose.imaging.Rectangle`-Strukturen in Position oder Größe unterscheiden. |
| [fromLeftTopRightBottom(int left, int top, int right, int bottom)](#fromLeftTopRightBottom-int-int-int-int-) | Erstellt eine `com.aspose.imaging.Rectangle`-Struktur mit den angegebenen Kantenpositionen. |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) |  |
| [getLocation()](#getLocation--) | Liest oder setzt die Koordinaten der oberen linken Ecke dieser `com.aspose.imaging.Rectangle`-Struktur. |
| [setLocation(Point value)](#setLocation-com.aspose.imaging.Point-) | Liest oder setzt die Koordinaten der oberen linken Ecke dieser `com.aspose.imaging.Rectangle`-Struktur. |
| [getSize()](#getSize--) | Liest oder setzt die Größe dieses `com.aspose.imaging.Rectangle`. |
| [setSize(Size value)](#setSize-com.aspose.imaging.Size-) | Liest oder setzt die Größe dieses `com.aspose.imaging.Rectangle`. |
| [getX()](#getX--) | Liest oder setzt die x-Koordinate der oberen linken Ecke dieser `com.aspose.imaging.Rectangle`-Struktur. |
| [setX(int value)](#setX-int-) | Liest oder setzt die x-Koordinate der oberen linken Ecke dieser `com.aspose.imaging.Rectangle`-Struktur. |
| [getY()](#getY--) | Liest oder setzt die y-Koordinate der oberen linken Ecke dieser `com.aspose.imaging.Rectangle`-Struktur. |
| [setY(int value)](#setY-int-) | Liest oder setzt die y-Koordinate der oberen linken Ecke dieser `com.aspose.imaging.Rectangle`-Struktur. |
| [getWidth()](#getWidth--) | Liest die Breite dieser `com.aspose.imaging.Rectangle`-Struktur. |
| [setWidth(int value)](#setWidth-int-) | Setzt die Breite dieser `com.aspose.imaging.Rectangle`-Struktur. |
| [getHeight()](#getHeight--) | Liest oder setzt die Höhe dieser `com.aspose.imaging.Rectangle`-Struktur. |
| [setHeight(int value)](#setHeight-int-) | Liest oder setzt die Höhe dieser `com.aspose.imaging.Rectangle`-Struktur. |
| [getLeft()](#getLeft--) | Liest oder setzt die x-Koordinate der linken Kante dieser `com.aspose.imaging.Rectangle`-Struktur. |
| [setLeft(int value)](#setLeft-int-) | Liest oder setzt die x-Koordinate der linken Kante dieser `com.aspose.imaging.Rectangle`-Struktur. |
| [getTop()](#getTop--) | Liest oder setzt die y-Koordinate der oberen Kante dieser `com.aspose.imaging.Rectangle`-Struktur. |
| [setTop(int value)](#setTop-int-) | Liest oder setzt die y-Koordinate der oberen Kante dieser `com.aspose.imaging.Rectangle`-Struktur. |
| [getRight()](#getRight--) | Liest oder setzt die x-Koordinate, die die Summe der Eigenschaften `com.aspose.imaging.Rectangle.X` und `com.aspose.imaging.Rectangle.Width` dieser `com.aspose.imaging.Rectangle`-Struktur ist. |
| [setRight(int value)](#setRight-int-) | Liest oder setzt die x-Koordinate, die die Summe der Eigenschaften `com.aspose.imaging.Rectangle.X` und `com.aspose.imaging.Rectangle.Width` dieser `com.aspose.imaging.Rectangle`-Struktur ist. |
| [getBottom()](#getBottom--) | Liest oder setzt die y-Koordinate, die die Summe der Eigenschaften `com.aspose.imaging.Rectangle.Y` und `com.aspose.imaging.Rectangle.Height` dieser `com.aspose.imaging.Rectangle`-Struktur ist. |
| [setBottom(int value)](#setBottom-int-) | Liest oder setzt die y-Koordinate, die die Summe der Eigenschaften `com.aspose.imaging.Rectangle.Y` und `com.aspose.imaging.Rectangle.Height` dieser `com.aspose.imaging.Rectangle`-Struktur ist. |
| [isEmpty()](#isEmpty--) | Liest einen Wert, der angibt, ob alle numerischen Eigenschaften dieses `com.aspose.imaging.Rectangle` den Wert Null haben. |
| [contains(int x, int y)](#contains-int-int-) | Bestimmt, ob der angegebene Punkt innerhalb dieser `com.aspose.imaging.Rectangle`-Struktur liegt. |
| [contains(Point point)](#contains-com.aspose.imaging.Point-) | Bestimmt, ob der angegebene Punkt innerhalb dieser `com.aspose.imaging.Rectangle`-Struktur liegt. |
| [contains(Rectangle rect)](#contains-com.aspose.imaging.Rectangle-) | Bestimmt, ob der durch `rect` dargestellte rechteckige Bereich vollständig innerhalb dieser `com.aspose.imaging.Rectangle`-Struktur liegt. |
| [inflate(int width, int height)](#inflate-int-int-) | Bläht dieses `com.aspose.imaging.Rectangle` um den angegebenen Betrag auf. |
| [inflate(Size size)](#inflate-com.aspose.imaging.Size-) | Bläht dieses `com.aspose.imaging.Rectangle` um den angegebenen Betrag auf. |
| [intersect(Rectangle rect)](#intersect-com.aspose.imaging.Rectangle-) | Ersetzt dieses `com.aspose.imaging.Rectangle` durch die Schnittmenge von sich selbst und dem angegebenen `com.aspose.imaging.Rectangle`. |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.imaging.Rectangle-) | Bestimmt, ob dieses Rechteck mit `rect` schneidet. |
| [offset(Point pos)](#offset-com.aspose.imaging.Point-) | Passt die Position dieses Rechtecks um den angegebenen Betrag an. |
| [offset(int x, int y)](#offset-int-int-) | Passt die Position dieses Rechtecks um den angegebenen Betrag an. |
| [normalize()](#normalize--) | Normalisiert das Rechteck, indem Breite und Höhe positiv gemacht werden, links kleiner als rechts und oben kleiner als unten ist. |
| [equals(Object obj)](#equals-java.lang.Object-) | Prüft, ob `obj` eine `com.aspose.imaging.Rectangle`-Struktur mit derselben Position und Größe wie diese `com.aspose.imaging.Rectangle`-Struktur ist. |
| [hashCode()](#hashCode--) | Gibt den Hashcode für diese `com.aspose.imaging.Rectangle`-Struktur zurück. |
| [toString()](#toString--) | Konvertiert die Attribute dieser `com.aspose.imaging.Rectangle` in einen menschenlesbaren String. |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.imaging.Rectangle-) |  |
| [Clone()](#Clone--) |  |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


Initialisiert eine neue Instanz der `com.aspose.imaging.Rectangle`-Struktur mit dem angegebenen Ort und der Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x‑Koordinate der oberen linken Ecke des Rechtecks. |
| y | int | Die y‑Koordinate der oberen linken Ecke des Rechtecks. |
| Breite | int | Die Breite des Rechtecks. |
| Höhe | int | Die Höhe des Rechtecks. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public Rectangle(Point location, Size size)
```


Initialisiert eine neue Instanz der `com.aspose.imaging.Rectangle`-Struktur mit dem angegebenen Ort und der Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| location | [Point](../../com.aspose.imaging/point) | Ein `com.aspose.imaging.Point`, das die obere linke Ecke des rechteckigen Bereichs darstellt. |
| size | [Size](../../com.aspose.imaging/size) | Ein `com.aspose.imaging.Size`, das die Breite und Höhe des rechteckigen Bereichs darstellt. |

### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


Gibt eine neue Instanz der `com.aspose.imaging.Rectangle`-Struktur zurück, deren Werte `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` und `com.aspose.imaging.Rectangle.Height` auf Null gesetzt sind.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


Erstellt ein neues `Rectangle` aus zwei angegebenen Punkten. Die beiden Vertikalen des erstellten `Rectangle` entsprechen den übergebenen `point1` und `point2`. Diese sind typischerweise die gegenüberliegenden Eckpunkte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Der erste `Point` für das neue Rechteck. |
| point2 | [Point](../../com.aspose.imaging/point) | Der zweite `Point` für das neue Rechteck. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A newly created `Rectangle`.
### ceiling(RectangleF value) {#ceiling-com.aspose.imaging.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


Konvertiert die angegebene `com.aspose.imaging.RectangleF`-Struktur in eine `com.aspose.imaging.Rectangle`-Struktur, indem die Werte von `com.aspose.imaging.RectangleF` auf die nächsthöheren Ganzzahlen gerundet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | Die zu konvertierende `com.aspose.imaging.RectangleF`-Struktur. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - Returns a `com.aspose.imaging.Rectangle`.
### truncate(RectangleF value) {#truncate-com.aspose.imaging.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


Konvertiert das angegebene `com.aspose.imaging.RectangleF` in ein `com.aspose.imaging.Rectangle`, indem die Werte von `com.aspose.imaging.RectangleF` abgeschnitten werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | Das zu konvertierende `com.aspose.imaging.RectangleF`. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A new `com.aspose.imaging.Rectangle`.
### round(RectangleF value) {#round-com.aspose.imaging.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


Konvertiert das angegebene `com.aspose.imaging.RectangleF` in ein `com.aspose.imaging.Rectangle`, indem die Werte des `com.aspose.imaging.RectangleF` auf die nächsten Ganzzahlen gerundet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | Das zu konvertierende `com.aspose.imaging.RectangleF`. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A new `com.aspose.imaging.Rectangle`.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.imaging.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```


Erstellt und gibt eine aufgeblähte Kopie der angegebenen `com.aspose.imaging.Rectangle`-Struktur zurück. Die Kopie wird um den angegebenen Betrag aufgebläht. Die ursprüngliche `com.aspose.imaging.Rectangle`-Struktur bleibt unverändert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Das `com.aspose.imaging.Rectangle`, mit dem gestartet werden soll. Dieses Rechteck wird nicht verändert. |
| x | int | Der Betrag, um den dieses `com.aspose.imaging.Rectangle` horizontal aufgebläht wird. |
| y | int | Der Betrag, um den dieses `com.aspose.imaging.Rectangle` vertikal aufgebläht wird. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The inflated `com.aspose.imaging.Rectangle`.
### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


Gibt eine dritte `com.aspose.imaging.Rectangle`-Struktur zurück, die die Schnittmenge zweier anderer `com.aspose.imaging.Rectangle`-Strukturen darstellt. Wenn keine Schnittmenge existiert, wird ein leeres `com.aspose.imaging.Rectangle` zurückgegeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.imaging/rectangle) | Ein erstes Rechteck zum Überschneiden. |
| b | [Rectangle](../../com.aspose.imaging/rectangle) | Ein zweites Rechteck zum Überschneiden. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A `com.aspose.imaging.Rectangle` that represents the intersection of `a` and `b`.
### union(Rectangle a, Rectangle b) {#union-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


Liefert eine `com.aspose.imaging.Rectangle`-Struktur, die die Vereinigung zweier `com.aspose.imaging.Rectangle`-Strukturen enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.imaging/rectangle) | Ein erstes Rechteck zur Vereinigung. |
| b | [Rectangle](../../com.aspose.imaging/rectangle) | Ein zweites Rechteck zur Vereinigung. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A `com.aspose.imaging.Rectangle` structure that bounds the union of the two `com.aspose.imaging.Rectangle` structures.
### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


Prüft, ob zwei `com.aspose.imaging.Rectangle`-Strukturen die gleiche Position und Größe haben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.imaging/rectangle) | Die `com.aspose.imaging.Rectangle`-Struktur, die links vom Gleichheitsoperator steht. |
| right | [Rectangle](../../com.aspose.imaging/rectangle) | Die `com.aspose.imaging.Rectangle`-Struktur, die rechts vom Gleichheitsoperator steht. |

**Returns:**
boolean – Dieser Operator gibt true zurück, wenn die beiden `com.aspose.imaging.Rectangle`-Strukturen gleiche `com.aspose.imaging.Rectangle.X`-, `com.aspose.imaging.Rectangle.Y`-, `com.aspose.imaging.Rectangle.Width`- und `com.aspose.imaging.Rectangle.Height`-Eigenschaften haben.
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


Prüft, ob sich zwei `com.aspose.imaging.Rectangle`-Strukturen in Position oder Größe unterscheiden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.imaging/rectangle) | Die `com.aspose.imaging.Rectangle`-Struktur, die links vom Ungleichheitsoperator steht. |
| right | [Rectangle](../../com.aspose.imaging/rectangle) | Die `com.aspose.imaging.Rectangle`-Struktur, die rechts vom Ungleichheitsoperator steht. |

**Returns:**
boolean – Dieser Operator gibt true zurück, wenn irgendeine der `com.aspose.imaging.Rectangle.X`-, `com.aspose.imaging.Rectangle.Y`-, `com.aspose.imaging.Rectangle.Width`- oder `com.aspose.imaging.Rectangle.Height`-Eigenschaften der beiden `com.aspose.imaging.Rectangle`-Strukturen ungleich ist; andernfalls false.
### fromLeftTopRightBottom(int left, int top, int right, int bottom) {#fromLeftTopRightBottom-int-int-int-int-}
```
public static Rectangle fromLeftTopRightBottom(int left, int top, int right, int bottom)
```


Erstellt eine `com.aspose.imaging.Rectangle`-Struktur mit den angegebenen Kantenpositionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| links | int | Die x-Koordinate der oberen linken Ecke dieser `com.aspose.imaging.Rectangle`-Struktur. |
| oben | int | Die y-Koordinate der oberen linken Ecke dieser `com.aspose.imaging.Rectangle`-Struktur. |
| rechts | int | Die x-Koordinate der unteren rechten Ecke dieser `com.aspose.imaging.Rectangle`-Struktur. |
| unten | int | Die y-Koordinate der unteren rechten Ecke dieser `com.aspose.imaging.Rectangle`-Struktur. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The new `com.aspose.imaging.Rectangle` that this method creates.
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.imaging/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.imaging/rectangle) |  |

**Returns:**
boolean
### getLocation() {#getLocation--}
```
public Point getLocation()
```


Liest oder setzt die Koordinaten der oberen linken Ecke dieser `com.aspose.imaging.Rectangle`-Struktur.

**Returns:**
[Point](../../com.aspose.imaging/point) - A `com.aspose.imaging.Point` that represents the upper-left corner of this `com.aspose.imaging.Rectangle` structure.
### setLocation(Point value) {#setLocation-com.aspose.imaging.Point-}
```
public void setLocation(Point value)
```


Liest oder setzt die Koordinaten der oberen linken Ecke dieser `com.aspose.imaging.Rectangle`-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) | Ein `Point`, das die obere linke Ecke dieser `com.aspose.imaging.Rectangle`-Struktur darstellt. |

### getSize() {#getSize--}
```
public Size getSize()
```


Liest oder setzt die Größe dieses `com.aspose.imaging.Rectangle`.

**Returns:**
[Size](../../com.aspose.imaging/size) - A `com.aspose.imaging.Size` that represents the width and height of this `com.aspose.imaging.Rectangle` structure.
### setSize(Size value) {#setSize-com.aspose.imaging.Size-}
```
public void setSize(Size value)
```


Liest oder setzt die Größe dieses `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) | Ein `com.aspose.imaging.Size`, das die Breite und Höhe dieser `com.aspose.imaging.Rectangle`-Struktur darstellt. |

### getX() {#getX--}
```
public int getX()
```


Liest oder setzt die x-Koordinate der oberen linken Ecke dieser `com.aspose.imaging.Rectangle`-Struktur.

**Returns:**
int – Die x-Koordinate der oberen linken Ecke dieser `com.aspose.imaging.Rectangle`-Struktur.
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Liest oder setzt die x-Koordinate der oberen linken Ecke dieser `com.aspose.imaging.Rectangle`-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die x-Koordinate der oberen linken Ecke dieser `com.aspose.imaging.Rectangle`-Struktur. |

### getY() {#getY--}
```
public int getY()
```


Liest oder setzt die y-Koordinate der oberen linken Ecke dieser `com.aspose.imaging.Rectangle`-Struktur.

**Returns:**
int - Die y-Koordinate der oberen linken Ecke dieser `com.aspose.imaging.Rectangle`-Struktur.
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Liest oder setzt die y-Koordinate der oberen linken Ecke dieser `com.aspose.imaging.Rectangle`-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die y-Koordinate der oberen linken Ecke dieser `com.aspose.imaging.Rectangle`-Struktur. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Liest die Breite dieser `com.aspose.imaging.Rectangle`-Struktur.

**Returns:**
int - Die Breite dieser `com.aspose.imaging.Rectangle`-Struktur.
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Setzt die Breite dieser `com.aspose.imaging.Rectangle`-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Breite dieser `com.aspose.imaging.Rectangle`-Struktur. |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Liest oder setzt die Höhe dieser `com.aspose.imaging.Rectangle`-Struktur.

**Returns:**
int - Die Höhe dieser `com.aspose.imaging.Rectangle`-Struktur.
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Liest oder setzt die Höhe dieser `com.aspose.imaging.Rectangle`-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Höhe dieser `com.aspose.imaging.Rectangle`-Struktur. |

### getLeft() {#getLeft--}
```
public int getLeft()
```


Liest oder setzt die x-Koordinate der linken Kante dieser `com.aspose.imaging.Rectangle`-Struktur.

**Returns:**
int - Die x-Koordinate der linken Kante dieser `com.aspose.imaging.Rectangle`-Struktur.
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Liest oder setzt die x-Koordinate der linken Kante dieser `com.aspose.imaging.Rectangle`-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die x-Koordinate der linken Kante dieser `com.aspose.imaging.Rectangle`-Struktur. |

### getTop() {#getTop--}
```
public int getTop()
```


Liest oder setzt die y-Koordinate der oberen Kante dieser `com.aspose.imaging.Rectangle`-Struktur.

**Returns:**
int - Die y-Koordinate der oberen Kante dieser `com.aspose.imaging.Rectangle`-Struktur.
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Liest oder setzt die y-Koordinate der oberen Kante dieser `com.aspose.imaging.Rectangle`-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die y-Koordinate der oberen Kante dieser `com.aspose.imaging.Rectangle`-Struktur. |

### getRight() {#getRight--}
```
public int getRight()
```


Liest oder setzt die x-Koordinate, die die Summe der Eigenschaften `com.aspose.imaging.Rectangle.X` und `com.aspose.imaging.Rectangle.Width` dieser `com.aspose.imaging.Rectangle`-Struktur ist.

**Returns:**
int - Die x-Koordinate, die die Summe von `com.aspose.imaging.Rectangle.X` und `com.aspose.imaging.Rectangle.Width` dieses `com.aspose.imaging.Rectangle` ist.
### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


Liest oder setzt die x-Koordinate, die die Summe der Eigenschaften `com.aspose.imaging.Rectangle.X` und `com.aspose.imaging.Rectangle.Width` dieser `com.aspose.imaging.Rectangle`-Struktur ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die x-Koordinate, die die Summe von `com.aspose.imaging.Rectangle.X` und `com.aspose.imaging.Rectangle.Width` dieses `com.aspose.imaging.Rectangle` ist. |

### getBottom() {#getBottom--}
```
public int getBottom()
```


Liest oder setzt die y-Koordinate, die die Summe der Eigenschaften `com.aspose.imaging.Rectangle.Y` und `com.aspose.imaging.Rectangle.Height` dieser `com.aspose.imaging.Rectangle`-Struktur ist.

**Returns:**
int - Die y-Koordinate, die die Summe von `com.aspose.imaging.Rectangle.Y` und `com.aspose.imaging.Rectangle.Height` dieses `com.aspose.imaging.Rectangle` ist.
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Liest oder setzt die y-Koordinate, die die Summe der Eigenschaften `com.aspose.imaging.Rectangle.Y` und `com.aspose.imaging.Rectangle.Height` dieser `com.aspose.imaging.Rectangle`-Struktur ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die y-Koordinate, die die Summe von `com.aspose.imaging.Rectangle.Y` und `com.aspose.imaging.Rectangle.Height` dieses `com.aspose.imaging.Rectangle` ist. |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Liest einen Wert, der angibt, ob alle numerischen Eigenschaften dieses `com.aspose.imaging.Rectangle` den Wert Null haben.

**Returns:**
boolean - Diese Eigenschaft gibt true zurück, wenn die Eigenschaften `com.aspose.imaging.Rectangle.Width`, `com.aspose.imaging.Rectangle.Height`, `com.aspose.imaging.Rectangle.X` und `com.aspose.imaging.Rectangle.Y` dieses `com.aspose.imaging.Rectangle` alle den Wert null haben; andernfalls false.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Bestimmt, ob der angegebene Punkt innerhalb dieser `com.aspose.imaging.Rectangle`-Struktur liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x-Koordinate des zu testenden Punktes. |
| y | int | Die y-Koordinate des zu testenden Punktes. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der durch `x` und `y` definierte Punkt innerhalb dieser `com.aspose.imaging.Rectangle`-Struktur liegt; andernfalls false.
### contains(Point point) {#contains-com.aspose.imaging.Point-}
```
public boolean contains(Point point)
```


Bestimmt, ob der angegebene Punkt innerhalb dieser `com.aspose.imaging.Rectangle`-Struktur liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Der `com.aspose.imaging.Point` zum Testen. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der durch `point` dargestellte Punkt innerhalb dieser `com.aspose.imaging.Rectangle`-Struktur liegt; andernfalls false.
### contains(Rectangle rect) {#contains-com.aspose.imaging.Rectangle-}
```
public boolean contains(Rectangle rect)
```


Bestimmt, ob der durch `rect` dargestellte rechteckige Bereich vollständig innerhalb dieser `com.aspose.imaging.Rectangle`-Struktur liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Das `com.aspose.imaging.Rectangle` zum Testen. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der durch `rect` dargestellte rechteckige Bereich vollständig innerhalb dieser `com.aspose.imaging.Rectangle`-Struktur liegt; andernfalls false.
### inflate(int width, int height) {#inflate-int-int-}
```
public void inflate(int width, int height)
```


Bläht dieses `com.aspose.imaging.Rectangle` um den angegebenen Betrag auf.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Der Betrag, um den dieses `com.aspose.imaging.Rectangle` horizontal aufgebläht wird. |
| Höhe | int | Der Betrag, um den dieses `com.aspose.imaging.Rectangle` vertikal aufgebläht wird. |

### inflate(Size size) {#inflate-com.aspose.imaging.Size-}
```
public void inflate(Size size)
```


Bläht dieses `com.aspose.imaging.Rectangle` um den angegebenen Betrag auf.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | Der Betrag, um den dieses Rechteck aufgebläht werden soll. |

### intersect(Rectangle rect) {#intersect-com.aspose.imaging.Rectangle-}
```
public void intersect(Rectangle rect)
```


Ersetzt dieses `com.aspose.imaging.Rectangle` durch die Schnittmenge von sich selbst und dem angegebenen `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Das `com.aspose.imaging.Rectangle`, mit dem geschnitten werden soll. |

### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.imaging.Rectangle-}
```
public boolean intersectsWith(Rectangle rect)
```


Bestimmt, ob dieses Rechteck mit `rect` schneidet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck zum Testen. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn irgendeine Schnittmenge existiert, andernfalls false.
### offset(Point pos) {#offset-com.aspose.imaging.Point-}
```
public void offset(Point pos)
```


Passt die Position dieses Rechtecks um den angegebenen Betrag an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pos | [Point](../../com.aspose.imaging/point) | Betrag, um die Position zu verschieben. |

### offset(int x, int y) {#offset-int-int-}
```
public void offset(int x, int y)
```


Passt die Position dieses Rechtecks um den angegebenen Betrag an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Der horizontale Versatz. |
| y | int | Der vertikale Versatz. |

### normalize() {#normalize--}
```
public void normalize()
```


Normalisiert das Rechteck, indem Breite und Höhe positiv gemacht werden, links kleiner als rechts und oben kleiner als unten ist.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Prüft, ob `obj` eine `com.aspose.imaging.Rectangle`-Struktur mit derselben Position und Größe wie diese `com.aspose.imaging.Rectangle`-Struktur ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das `System.Object` zum Testen. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn `obj` eine `com.aspose.imaging.Rectangle`-Struktur ist und deren Eigenschaften `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` und `com.aspose.imaging.Rectangle.Height` den entsprechenden Eigenschaften dieser `com.aspose.imaging.Rectangle`-Struktur entsprechen; andernfalls false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode für diese `com.aspose.imaging.Rectangle`-Struktur zurück.

**Returns:**
int - Eine Ganzzahl, die den Hashcode für dieses Rechteck darstellt.
### toString() {#toString--}
```
public String toString()
```


Konvertiert die Attribute dieser `com.aspose.imaging.Rectangle` in einen menschenlesbaren String.

**Returns:**
java.lang.String - Eine Zeichenkette, die die Position, Breite und Höhe dieser `com.aspose.imaging.Rectangle`-Struktur enthält.
### CloneTo(Rectangle that) {#CloneTo-com.aspose.imaging.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
