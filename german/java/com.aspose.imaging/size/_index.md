---
title: "Größe"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt die Größe dar."
type: docs
weight: 104
url: /de/java/com.aspose.imaging/size/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Size extends Struct<Size>
```

Stellt die Größe dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point point)](#Size-com.aspose.imaging.Point-) | Initialisiert eine neue Instanz der `Aspose.Imaging.Size`-Struktur aus dem angegebenen `Aspose.Imaging.Point`. |
| [Size(int width, int height)](#Size-int-int-) | Initialisiert eine neue Instanz der `Aspose.Imaging.Size`-Struktur aus den angegebenen Abmessungen. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEmpty()](#getEmpty--) | Gibt eine neue Instanz der `Aspose.Imaging.Size`-Struktur zurück, deren Werte `Aspose.Imaging.Size.Width` und `Aspose.Imaging.Size.Height` auf Null gesetzt sind. |
| [to_SizeF(Size size)](#to-SizeF-com.aspose.imaging.Size-) | Konvertiert das angegebene `Aspose.Imaging.Size` in ein `Aspose.Imaging.SizeF`. |
| [op_Addition(Size size1, Size size2)](#op-Addition-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Addiert die Breite und Höhe einer `Aspose.Imaging.Size`-Struktur zur Breite und Höhe einer anderen `Aspose.Imaging.Size`-Struktur. |
| [op_Subtraction(Size size1, Size size2)](#op-Subtraction-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Subtrahiert die Breite und Höhe einer `Aspose.Imaging.Size`-Struktur von der Breite und Höhe einer anderen `Aspose.Imaging.Size`-Struktur. |
| [op_Equality(Size size1, Size size2)](#op-Equality-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Prüft, ob zwei `Aspose.Imaging.Size`-Strukturen gleich sind. |
| [op_Inequality(Size size1, Size size2)](#op-Inequality-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Prüft, ob zwei `Aspose.Imaging.Size`-Strukturen unterschiedlich sind. |
| [to_Point(Size size)](#to-Point-com.aspose.imaging.Size-) | Konvertiert das angegebene `Aspose.Imaging.Size` in einen `Aspose.Imaging.Point`. |
| [add(Size size1, Size size2)](#add-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Addiert die Breite und Höhe einer `Aspose.Imaging.Size`-Struktur zur Breite und Höhe einer anderen `Aspose.Imaging.Size`-Struktur. |
| [ceiling(SizeF size)](#ceiling-com.aspose.imaging.SizeF-) | Konvertiert die angegebene `Aspose.Imaging.SizeF`-Struktur in eine `Aspose.Imaging.Size`-Struktur, indem die Werte der `Aspose.Imaging.SizeF`-Struktur auf die nächsthöheren Ganzzahlen gerundet werden. |
| [subtract(Size size1, Size size2)](#subtract-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Subtrahiert die Breite und Höhe einer `Aspose.Imaging.Size`-Struktur von der Breite und Höhe einer anderen `Aspose.Imaging.Size`-Struktur. |
| [truncate(SizeF size)](#truncate-com.aspose.imaging.SizeF-) | Konvertiert die angegebene `Aspose.Imaging.SizeF`-Struktur in eine `Aspose.Imaging.Size`-Struktur, indem die Werte der `Aspose.Imaging.SizeF`-Struktur auf die nächstniedrigeren Ganzzahlen abgeschnitten werden. |
| [round(SizeF size)](#round-com.aspose.imaging.SizeF-) | Konvertiert die angegebene `Aspose.Imaging.SizeF`-Struktur in eine `Aspose.Imaging.Size`-Struktur, indem die Werte der `Aspose.Imaging.SizeF`-Struktur auf die nächstgelegenen Ganzzahlen gerundet werden. |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.imaging.Size-com.aspose.imaging.Size-) |  |
| [isEmpty()](#isEmpty--) | Gibt einen Wert zurück, der angibt, ob dieses `Aspose.Imaging.Size` eine Breite und Höhe von 0 hat. |
| [getWidth()](#getWidth--) | Liest oder legt die horizontale Komponente dieses `Aspose.Imaging.Size` fest. |
| [setWidth(int value)](#setWidth-int-) | Liest oder legt die horizontale Komponente dieses `Aspose.Imaging.Size` fest. |
| [getHeight()](#getHeight--) | Liest oder setzt die vertikale Komponente dieses `Aspose.Imaging.Size`. |
| [setHeight(int value)](#setHeight-int-) | Liest oder setzt die vertikale Komponente dieses `Aspose.Imaging.Size`. |
| [equals(Object obj)](#equals-java.lang.Object-) | Prüft, ob das angegebene Objekt ein `Aspose.Imaging.Size` mit denselben Abmessungen wie dieses `Aspose.Imaging.Size` ist. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diese `Aspose.Imaging.Size`-Struktur zurück. |
| [toString()](#toString--) | Erstellt eine menschenlesbare Zeichenkette, die dieses `Aspose.Imaging.Size` darstellt. |
| [CloneTo(Size that)](#CloneTo-com.aspose.imaging.Size-) |  |
| [Clone()](#Clone--) |  |
### Size() {#Size--}
```
public Size()
```


### Size(Point point) {#Size-com.aspose.imaging.Point-}
```
public Size(Point point)
```


Initialisiert eine neue Instanz der `Aspose.Imaging.Size`-Struktur aus dem angegebenen `Aspose.Imaging.Point`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Der `Aspose.Imaging.Point`, aus dem dieses `Aspose.Imaging.Size` initialisiert wird. |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Initialisiert eine neue Instanz der `Aspose.Imaging.Size`-Struktur aus den angegebenen Abmessungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die Breitenkomponente des neuen `Aspose.Imaging.Size`. |
| Höhe | int | Die Höhenkomponente des neuen `Aspose.Imaging.Size`. |

### getEmpty() {#getEmpty--}
```
public static Size getEmpty()
```


Gibt eine neue Instanz der `Aspose.Imaging.Size`-Struktur zurück, deren Werte `Aspose.Imaging.Size.Width` und `Aspose.Imaging.Size.Height` auf Null gesetzt sind.

**Returns:**
[Size](../../com.aspose.imaging/size)
### to_SizeF(Size size) {#to-SizeF-com.aspose.imaging.Size-}
```
public static SizeF to_SizeF(Size size)
```


Konvertiert das angegebene `Aspose.Imaging.Size` in ein `Aspose.Imaging.SizeF`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | Das `Aspose.Imaging.Size`, das konvertiert werden soll. |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - The `Aspose.Imaging.SizeF` structure to which this operator converts.
### op_Addition(Size size1, Size size2) {#op-Addition-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size op_Addition(Size size1, Size size2)
```


Addiert die Breite und Höhe einer `Aspose.Imaging.Size`-Struktur zur Breite und Höhe einer anderen `Aspose.Imaging.Size`-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | Das erste `Aspose.Imaging.Size`, das hinzugefügt werden soll. |
| size2 | [Size](../../com.aspose.imaging/size) | Das zweite `Aspose.Imaging.Size`, das hinzugefügt werden soll. |

**Returns:**
[Size](../../com.aspose.imaging/size) - A `Aspose.Imaging.Size` structure that is the result of the addition operation.
### op_Subtraction(Size size1, Size size2) {#op-Subtraction-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size op_Subtraction(Size size1, Size size2)
```


Subtrahiert die Breite und Höhe einer `Aspose.Imaging.Size`-Struktur von der Breite und Höhe einer anderen `Aspose.Imaging.Size`-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | Die `Aspose.Imaging.Size`-Struktur auf der linken Seite des Subtraktionsoperators. |
| size2 | [Size](../../com.aspose.imaging/size) | Die `Aspose.Imaging.Size`-Struktur auf der rechten Seite des Subtraktionsoperators. |

**Returns:**
[Size](../../com.aspose.imaging/size) - A `Aspose.Imaging.Size` structure that is the result of the subtraction operation.
### op_Equality(Size size1, Size size2) {#op-Equality-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static boolean op_Equality(Size size1, Size size2)
```


Prüft, ob zwei `Aspose.Imaging.Size`-Strukturen gleich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | Die `Aspose.Imaging.Size`-Struktur auf der linken Seite des Gleichheitsoperators. |
| size2 | [Size](../../com.aspose.imaging/size) | Die `Aspose.Imaging.Size`-Struktur auf der rechten Seite des Gleichheitsoperators. |

**Returns:**
boolean - Wahr, wenn `size1` und `size2` gleiche Breite und Höhe haben; andernfalls falsch.
### op_Inequality(Size size1, Size size2) {#op-Inequality-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static boolean op_Inequality(Size size1, Size size2)
```


Prüft, ob zwei `Aspose.Imaging.Size`-Strukturen unterschiedlich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | Die `Aspose.Imaging.Size`-Struktur auf der linken Seite des Ungleichheitsoperators. |
| size2 | [Size](../../com.aspose.imaging/size) | Die `Aspose.Imaging.Size`-Struktur auf der rechten Seite des Ungleichheitsoperators. |

**Returns:**
boolean - Wahr, wenn `size1` und `size2` sich entweder in der Breite oder Höhe unterscheiden; falsch, wenn `size1` und `size2` gleich sind.
### to_Point(Size size) {#to-Point-com.aspose.imaging.Size-}
```
public static Point to_Point(Size size)
```


Konvertiert das angegebene `Aspose.Imaging.Size` in einen `Aspose.Imaging.Point`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | Das `Aspose.Imaging.Size`, das konvertiert werden soll. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` structure to which this operator converts.
### add(Size size1, Size size2) {#add-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size add(Size size1, Size size2)
```


Addiert die Breite und Höhe einer `Aspose.Imaging.Size`-Struktur zur Breite und Höhe einer anderen `Aspose.Imaging.Size`-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | Das erste `Aspose.Imaging.Size`, das hinzugefügt werden soll. |
| size2 | [Size](../../com.aspose.imaging/size) | Das zweite `Aspose.Imaging.Size`, das hinzugefügt werden soll. |

**Returns:**
[Size](../../com.aspose.imaging/size) - A `Aspose.Imaging.Size` structure that is the result of the addition operation.
### ceiling(SizeF size) {#ceiling-com.aspose.imaging.SizeF-}
```
public static Size ceiling(SizeF size)
```


Konvertiert die angegebene `Aspose.Imaging.SizeF`-Struktur in eine `Aspose.Imaging.Size`-Struktur, indem die Werte der `Aspose.Imaging.SizeF`-Struktur auf die nächsthöheren Ganzzahlen gerundet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | Die `Aspose.Imaging.SizeF`-Struktur, die konvertiert werden soll. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` structure this method converts to.
### subtract(Size size1, Size size2) {#subtract-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size subtract(Size size1, Size size2)
```


Subtrahiert die Breite und Höhe einer `Aspose.Imaging.Size`-Struktur von der Breite und Höhe einer anderen `Aspose.Imaging.Size`-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | Die `Aspose.Imaging.Size`-Struktur auf der linken Seite des Subtraktionsoperators. |
| size2 | [Size](../../com.aspose.imaging/size) | Die `Aspose.Imaging.Size`-Struktur auf der rechten Seite des Subtraktionsoperators. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` that is a result of the subtraction operation.
### truncate(SizeF size) {#truncate-com.aspose.imaging.SizeF-}
```
public static Size truncate(SizeF size)
```


Konvertiert die angegebene `Aspose.Imaging.SizeF`-Struktur in eine `Aspose.Imaging.Size`-Struktur, indem die Werte der `Aspose.Imaging.SizeF`-Struktur auf die nächstniedrigeren Ganzzahlen abgeschnitten werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | Die `Aspose.Imaging.SizeF`-Struktur, die konvertiert werden soll. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` structure this method converts to.
### round(SizeF size) {#round-com.aspose.imaging.SizeF-}
```
public static Size round(SizeF size)
```


Konvertiert die angegebene `Aspose.Imaging.SizeF`-Struktur in eine `Aspose.Imaging.Size`-Struktur, indem die Werte der `Aspose.Imaging.SizeF`-Struktur auf die nächstgelegenen Ganzzahlen gerundet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | Die `Aspose.Imaging.SizeF`-Struktur, die konvertiert werden soll. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` structure this method converts to.
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj1 | [Size](../../com.aspose.imaging/size) |  |
| obj2 | [Size](../../com.aspose.imaging/size) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Gibt einen Wert zurück, der angibt, ob dieses `Aspose.Imaging.Size` eine Breite und Höhe von 0 hat.

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public int getWidth()
```


Liest oder legt die horizontale Komponente dieses `Aspose.Imaging.Size` fest.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Liest oder legt die horizontale Komponente dieses `Aspose.Imaging.Size` fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Liest oder setzt die vertikale Komponente dieses `Aspose.Imaging.Size`.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Liest oder setzt die vertikale Komponente dieses `Aspose.Imaging.Size`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Prüft, ob das angegebene Objekt ein `Aspose.Imaging.Size` mit denselben Abmessungen wie dieses `Aspose.Imaging.Size` ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das `System.Object` zum Testen. |

**Returns:**
boolean - Wahr, wenn `obj` ein `Aspose.Imaging.Size` ist und dieselbe Breite und Höhe wie dieses `Aspose.Imaging.Size` hat; andernfalls falsch.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für diese `Aspose.Imaging.Size`-Struktur zurück.

**Returns:**
int - Ein ganzzahliger Wert, der einen Hashwert für diese `Aspose.Imaging.Size`-Struktur angibt.
### toString() {#toString--}
```
public String toString()
```


Erstellt eine menschenlesbare Zeichenkette, die dieses `Aspose.Imaging.Size` darstellt.

**Returns:**
java.lang.String - Eine Zeichenkette, die dieses `Aspose.Imaging.Size` darstellt.
### CloneTo(Size that) {#CloneTo-com.aspose.imaging.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| that | [Size](../../com.aspose.imaging/size) |  |

### Clone() {#Clone--}
```
public Size Clone()
```




**Returns:**
[Size](../../com.aspose.imaging/size)
