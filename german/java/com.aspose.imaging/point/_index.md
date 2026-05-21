---
title: "Point"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt ein geordnetes Paar von ganzzahligen x‑ und y‑Koordinaten dar, das einen Punkt in einer zweidimensionalen Ebene definiert."
type: docs
weight: 86
url: /de/java/com.aspose.imaging/point/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Point extends Struct<Point>
```

Stellt ein geordnetes Paar von ganzzahligen x‑ und y‑Koordinaten dar, das einen Punkt in einer zweidimensionalen Ebene definiert.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | Initialisiert eine neue Instanz der `Aspose.Imaging.Point`‑Struktur mit den angegebenen Koordinaten. |
| [Point(Size size)](#Point-com.aspose.imaging.Size-) | Initialisiert eine neue Instanz der `Aspose.Imaging.Point`‑Struktur aus der `Aspose.Imaging.Size`‑Struktur. |
| [Point(int dw)](#Point-int-) | Initialisiert eine neue Instanz der `Aspose.Imaging.Point`‑Struktur unter Verwendung von Koordinaten, die durch einen ganzzahligen Wert angegeben werden. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEmpty()](#getEmpty--) | Ermittelt eine neue Instanz der `Aspose.Imaging.Point`‑Struktur, bei der die Werte `Aspose.Imaging.Point.X` und `Aspose.Imaging.Point.Y` auf Null gesetzt sind. |
| [add(Point point, Size size)](#add-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Fügt die angegebene `Aspose.Imaging.Size` zu dem angegebenen `Aspose.Imaging.Point` hinzu. |
| [subtract(Point point, Size size)](#subtract-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Gibt das Ergebnis der Subtraktion der angegebenen `Aspose.Imaging.Size` vom angegebenen `Aspose.Imaging.Point` zurück. |
| [ceiling(PointF point)](#ceiling-com.aspose.imaging.PointF-) | Konvertiert das angegebene `Aspose.Imaging.PointF` in ein `Aspose.Imaging.Point`, indem die Werte des `Aspose.Imaging.PointF` auf die nächsthöheren Ganzzahlen gerundet werden. |
| [round(PointF point)](#round-com.aspose.imaging.PointF-) | Konvertiert das angegebene `Aspose.Imaging.PointF` in ein `Aspose.Imaging.Point`-Objekt, indem die Werte des `Aspose.Imaging.Point` auf die nächste ganze Zahl gerundet werden. |
| [truncate(PointF point)](#truncate-com.aspose.imaging.PointF-) | Konvertiert das angegebene `Aspose.Imaging.PointF` in ein `Aspose.Imaging.Point`, indem die Werte des `Aspose.Imaging.Point` abgeschnitten werden. |
| [op_Addition(Point point, Size size)](#op-Addition-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Verschiebt einen `Aspose.Imaging.Point` um eine gegebene `Aspose.Imaging.Size`. |
| [op_Subtraction(Point point, Size size)](#op-Subtraction-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Verschiebt einen `Aspose.Imaging.Point` um das Negative einer gegebenen `Aspose.Imaging.Size`. |
| [op_Equality(Point point1, Point point2)](#op-Equality-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Vergleicht zwei `Aspose.Imaging.Point`-Objekte. |
| [op_Inequality(Point point1, Point point2)](#op-Inequality-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Vergleicht zwei `Aspose.Imaging.Point`-Objekte. |
| [to_Size(Point point)](#to-Size-com.aspose.imaging.Point-) | Konvertiert die angegebene `Aspose.Imaging.Point`-Struktur in eine `Aspose.Imaging.Size`-Struktur. |
| [to_PointF(Point point)](#to-PointF-com.aspose.imaging.Point-) | Konvertiert die angegebene `Point`-Struktur in die `PointF`-Struktur. |
| [fromLong(long packedPoint, int[] x, int[] y)](#fromLong-long-int---int---) | Dekonstruiert ein Point-Objekt, das in ein Long-Objekt gepackt ist, in separate X- und Y‑Int‑Werte. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.imaging.Point-com.aspose.imaging.Point-) |  |
| [isEmpty()](#isEmpty--) | Gibt einen Wert zurück, der angibt, ob dieses `Aspose.Imaging.Point` leer ist. |
| [getX()](#getX--) | Liest oder setzt die X‑Koordinate dieses `Aspose.Imaging.Point`. |
| [setX(int value)](#setX-int-) | Liest oder setzt die X‑Koordinate dieses `Aspose.Imaging.Point`. |
| [getY()](#getY--) | Liest oder setzt die Y‑Koordinate dieses `Aspose.Imaging.Point`. |
| [setY(int value)](#setY-int-) | Liest oder setzt die Y‑Koordinate dieses `Aspose.Imaging.Point`. |
| [offset(Point point)](#offset-com.aspose.imaging.Point-) | Verschiebt dieses `Aspose.Imaging.Point` um das angegebene `Aspose.Imaging.Point`. |
| [offset(int dx, int dy)](#offset-int-int-) | Verschiebt dieses `Aspose.Imaging.Point` um den angegebenen Betrag. |
| [equals(Object obj)](#equals-java.lang.Object-) | Gibt an, ob dieses `Aspose.Imaging.Point` dieselben Koordinaten wie das angegebene `System.Object` enthält. |
| [hashCode()](#hashCode--) | Gibt einen Hash‑Code für dieses `Aspose.Imaging.Point` zurück. |
| [toLong()](#toLong--) | Konvertiert dieses Point in einen einzelnen Long‑Wert, der die X‑ und Y‑Koordinaten in hohen und niedrigen Bits enthält. |
| [toString()](#toString--) | Konvertiert dieses `Aspose.Imaging.Point` in eine menschenlesbare Zeichenkette. |
| [CloneTo(Point that)](#CloneTo-com.aspose.imaging.Point-) |  |
| [Clone()](#Clone--) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


Initialisiert eine neue Instanz der `Aspose.Imaging.Point`‑Struktur mit den angegebenen Koordinaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die horizontale Position des Punktes. |
| y | int | Die vertikale Position des Punktes. |

### Point(Size size) {#Point-com.aspose.imaging.Size-}
```
public Point(Size size)
```


Initialisiert eine neue Instanz der `Aspose.Imaging.Point`‑Struktur aus der `Aspose.Imaging.Size`‑Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | Enthält die neuen Punktkoordinaten. |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


Initialisiert eine neue Instanz der `Aspose.Imaging.Point`‑Struktur unter Verwendung von Koordinaten, die durch einen ganzzahligen Wert angegeben werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dw | int | Ein 32‑Bit‑Integer, der die Koordinaten für den neuen Punkt angibt. |

### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```


Ermittelt eine neue Instanz der `Aspose.Imaging.Point`‑Struktur, bei der die Werte `Aspose.Imaging.Point.X` und `Aspose.Imaging.Point.Y` auf Null gesetzt sind.

**Returns:**
[Point](../../com.aspose.imaging/point)
### add(Point point, Size size) {#add-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point add(Point point, Size size)
```


Fügt die angegebene `Aspose.Imaging.Size` zu dem angegebenen `Aspose.Imaging.Point` hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Der `Aspose.Imaging.Point`, zu dem hinzugefügt werden soll. |
| size | [Size](../../com.aspose.imaging/size) | Die `Aspose.Imaging.Size`, die zum `point` hinzugefügt werden soll. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` that is the result of the addition operation.
### subtract(Point point, Size size) {#subtract-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point subtract(Point point, Size size)
```


Gibt das Ergebnis der Subtraktion der angegebenen `Aspose.Imaging.Size` vom angegebenen `Aspose.Imaging.Point` zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Der `Aspose.Imaging.Point`, von dem subtrahiert wird. |
| size | [Size](../../com.aspose.imaging/size) | Der `Aspose.Imaging.Size`, von dem der `point` subtrahiert wird. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` that is the result of the subtraction operation.
### ceiling(PointF point) {#ceiling-com.aspose.imaging.PointF-}
```
public static Point ceiling(PointF point)
```


Konvertiert das angegebene `Aspose.Imaging.PointF` in ein `Aspose.Imaging.Point`, indem die Werte des `Aspose.Imaging.PointF` auf die nächsthöheren Ganzzahlen gerundet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Der `Aspose.Imaging.PointF`, der konvertiert werden soll. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` this method converts to.
### round(PointF point) {#round-com.aspose.imaging.PointF-}
```
public static Point round(PointF point)
```


Konvertiert das angegebene `Aspose.Imaging.PointF` in ein `Aspose.Imaging.Point`-Objekt, indem die Werte des `Aspose.Imaging.Point` auf die nächste ganze Zahl gerundet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Der `Aspose.Imaging.PointF`, der konvertiert werden soll. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` this method converts to.
### truncate(PointF point) {#truncate-com.aspose.imaging.PointF-}
```
public static Point truncate(PointF point)
```


Konvertiert das angegebene `Aspose.Imaging.PointF` in ein `Aspose.Imaging.Point`, indem die Werte des `Aspose.Imaging.Point` abgeschnitten werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Der `Aspose.Imaging.PointF`, der konvertiert werden soll. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` this method converts to.
### op_Addition(Point point, Size size) {#op-Addition-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point op_Addition(Point point, Size size)
```


Verschiebt einen `Aspose.Imaging.Point` um eine gegebene `Aspose.Imaging.Size`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Der `Aspose.Imaging.Point`, der übersetzt werden soll. |
| size | [Size](../../com.aspose.imaging/size) | Ein `Aspose.Imaging.Size`, der das Zahlenpaar angibt, das zu den Koordinaten von `point` hinzugefügt werden soll. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The translated `Aspose.Imaging.Point`.
### op_Subtraction(Point point, Size size) {#op-Subtraction-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point op_Subtraction(Point point, Size size)
```


Verschiebt einen `Aspose.Imaging.Point` um das Negative einer gegebenen `Aspose.Imaging.Size`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Der `Aspose.Imaging.Point`, der übersetzt werden soll. |
| size | [Size](../../com.aspose.imaging/size) | Ein `Aspose.Imaging.Size`, der das Zahlenpaar angibt, das von den Koordinaten von `point` subtrahiert werden soll. |

**Returns:**
[Point](../../com.aspose.imaging/point) - A `Aspose.Imaging.Point` structure that is translated by the negative of a given `Aspose.Imaging.Size` structure.
### op_Equality(Point point1, Point point2) {#op-Equality-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static boolean op_Equality(Point point1, Point point2)
```


Vergleicht zwei `Aspose.Imaging.Point`-Objekte. Das Ergebnis gibt an, ob die Werte der Eigenschaften `Aspose.Imaging.Point.X` und `Aspose.Imaging.Point.Y` der beiden `Aspose.Imaging.Point`-Objekte gleich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Ein erstes `Aspose.Imaging.Point` zum Vergleichen. |
| point2 | [Point](../../com.aspose.imaging/point) | Ein zweites `Aspose.Imaging.Point` zum Vergleichen. |

**Returns:**
boolean - Wahr, wenn die `Aspose.Imaging.Point.X` und `Aspose.Imaging.Point.Y` Werte von `point1` und `point2` gleich sind; andernfalls falsch.
### op_Inequality(Point point1, Point point2) {#op-Inequality-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static boolean op_Inequality(Point point1, Point point2)
```


Vergleicht zwei `Aspose.Imaging.Point`-Objekte. Das Ergebnis gibt an, ob die Werte der Eigenschaften `Aspose.Imaging.Point.X` oder `Aspose.Imaging.Point.Y` der beiden `Aspose.Imaging.Point`-Objekte ungleich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Ein erstes `Aspose.Imaging.Point` zum Vergleichen. |
| point2 | [Point](../../com.aspose.imaging/point) | Ein zweites `Aspose.Imaging.Point` zum Vergleichen. |

**Returns:**
boolean - Wahr, wenn die Werte entweder der `Aspose.Imaging.Point.X`-Eigenschaften oder der `Aspose.Imaging.Point.Y`-Eigenschaften von `point1` und `point2` unterschiedlich sind; andernfalls falsch.
### to_Size(Point point) {#to-Size-com.aspose.imaging.Point-}
```
public static Size to_Size(Point point)
```


Konvertiert die angegebene `Aspose.Imaging.Point`-Struktur in eine `Aspose.Imaging.Size`-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Der `Aspose.Imaging.Point`, der konvertiert werden soll. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` that results from the conversion.
### to_PointF(Point point) {#to-PointF-com.aspose.imaging.Point-}
```
public static PointF to_PointF(Point point)
```


Konvertiert die angegebene `Point`-Struktur in die `PointF`-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Der `Point`, der konvertiert werden soll. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The `PointF` that results from the conversion.
### fromLong(long packedPoint, int[] x, int[] y) {#fromLong-long-int---int---}
```
public static void fromLong(long packedPoint, int[] x, int[] y)
```


Dekonstruiert ein Point-Objekt, das in ein Long-Objekt gepackt ist, in separate X- und Y‑Int‑Werte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| packedPoint | long | Das Point-Objekt, das in einen langen Wert gepackt ist. |
| x | int[] | Der aus dem gepackten Point extrahierte X-Wert. |
| y | int[] | Der aus dem gepackten Point extrahierte Y-Wert. |

### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.imaging/point) |  |
| obj2 | [Point](../../com.aspose.imaging/point) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Gibt einen Wert zurück, der angibt, ob dieses `Aspose.Imaging.Point` leer ist.

**Returns:**
boolean - Wahr, wenn sowohl `Aspose.Imaging.Point.X` als auch `Aspose.Imaging.Point.Y` 0 sind; andernfalls falsch.
### getX() {#getX--}
```
public int getX()
```


Liest oder setzt die X‑Koordinate dieses `Aspose.Imaging.Point`.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Liest oder setzt die X‑Koordinate dieses `Aspose.Imaging.Point`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getY() {#getY--}
```
public int getY()
```


Liest oder setzt die Y‑Koordinate dieses `Aspose.Imaging.Point`.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Liest oder setzt die Y‑Koordinate dieses `Aspose.Imaging.Point`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### offset(Point point) {#offset-com.aspose.imaging.Point-}
```
public void offset(Point point)
```


Verschiebt dieses `Aspose.Imaging.Point` um das angegebene `Aspose.Imaging.Point`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Der `Aspose.Imaging.Point`, der verwendet wird, um diesen `Aspose.Imaging.Point` zu versetzen. |

### offset(int dx, int dy) {#offset-int-int-}
```
public void offset(int dx, int dy)
```


Verschiebt dieses `Aspose.Imaging.Point` um den angegebenen Betrag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dx | int | Der Betrag, um den die x-Koordinate verschoben wird. |
| dy | int | Der Betrag, um den die y-Koordinate verschoben wird. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Gibt an, ob dieses `Aspose.Imaging.Point` dieselben Koordinaten wie das angegebene `System.Object` enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das `System.Object` zum Testen. |

**Returns:**
boolean - Wahr, wenn `obj` ein `Aspose.Imaging.Point` ist und dieselben Koordinaten wie dieses `Aspose.Imaging.Point` hat.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hash‑Code für dieses `Aspose.Imaging.Point` zurück.

**Returns:**
int – Ein Hashcode für diese Instanz, geeignet für den Einsatz in Hash‑Algorithmen und Datenstrukturen wie einer Hashtabelle.
### toLong() {#toLong--}
```
public final long toLong()
```


Konvertiert dieses Point in einen einzelnen Long‑Wert, der die X‑ und Y‑Koordinaten in hohen und niedrigen Bits enthält.

**Returns:**
long - Das Point-Objekt, das in einen langen Wert gepackt ist.
### toString() {#toString--}
```
public String toString()
```


Konvertiert dieses `Aspose.Imaging.Point` in eine menschenlesbare Zeichenkette.

**Returns:**
java.lang.String - Ein `System.String`, der diese Instanz darstellt.
### CloneTo(Point that) {#CloneTo-com.aspose.imaging.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| that | [Point](../../com.aspose.imaging/point) |  |

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.imaging/point)
