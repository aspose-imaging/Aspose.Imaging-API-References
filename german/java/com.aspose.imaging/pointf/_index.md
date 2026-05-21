---
title: "PointF"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt ein geordnetes Paar von Gleitkomma‑x‑ und y‑Koordinaten dar, das einen Punkt in einer zweidimensionalen Ebene definiert."
type: docs
weight: 87
url: /de/java/com.aspose.imaging/pointf/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public final class PointF extends Struct<PointF>
```

Stellt ein geordnetes Paar von Gleitkomma‑x‑ und y‑Koordinaten dar, das einen Punkt in einer zweidimensionalen Ebene definiert.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PointF()](#PointF--) |  |
| [PointF(float x, float y)](#PointF-float-float-) | Initialisiert eine neue Instanz der `com.aspose.imaging.PointF`‑Struktur mit den angegebenen Koordinaten. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEmpty()](#getEmpty--) | Liefert eine neue Instanz der `com.aspose.imaging.PointF`‑Struktur, bei der die Werte `com.aspose.imaging.PointF.X` und `com.aspose.imaging.PointF.Y` auf Null gesetzt sind. |
| [op_Addition(PointF point, Size size)](#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Verschiebt ein `com.aspose.imaging.PointF` um ein angegebenes `com.aspose.imaging.Size`. |
| [op_Subtraction(PointF point, Size size)](#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Verschiebt ein `com.aspose.imaging.PointF` um das Negative eines angegebenen `com.aspose.imaging.Size`. |
| [op_Addition(PointF point, SizeF size)](#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Verschiebt das `com.aspose.imaging.PointF` um das angegebene `com.aspose.imaging.SizeF`. |
| [op_Subtraction(PointF point, SizeF size)](#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Verschiebt ein `com.aspose.imaging.PointF` um das Negative eines angegebenen `com.aspose.imaging.SizeF`. |
| [op_Equality(PointF point1, PointF point2)](#op-Equality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Vergleicht zwei `com.aspose.imaging.PointF`‑Strukturen. |
| [op_Inequality(PointF point1, PointF point2)](#op-Inequality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Bestimmt, ob die Koordinaten der angegebenen Punkte ungleich sind. |
| [add(PointF point, Size size)](#add-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Verschiebt ein angegebenes `com.aspose.imaging.PointF` um das angegebene `com.aspose.imaging.Size`. |
| [subtract(PointF point, Size size)](#subtract-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Verschiebt ein `com.aspose.imaging.PointF` um das Negative einer angegebenen Größe. |
| [add(PointF point, SizeF size)](#add-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Verschiebt ein angegebenes `com.aspose.imaging.PointF` um ein angegebenes `com.aspose.imaging.SizeF`. |
| [subtract(PointF point, SizeF size)](#subtract-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Verschiebt ein `com.aspose.imaging.PointF` um das Negative einer angegebenen Größe. |
| [isEquals(PointF obj1, PointF obj2)](#isEquals-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) |  |
| [isEmpty()](#isEmpty--) | Liefert einen Wert, der angibt, ob dieses `com.aspose.imaging.PointF` leer ist. |
| [getX()](#getX--) | Liest oder legt die X‑Koordinate dieses `com.aspose.imaging.PointF` fest. |
| [setX(float value)](#setX-float-) | Liest oder legt die X‑Koordinate dieses `com.aspose.imaging.PointF` fest. |
| [getY()](#getY--) | Liest oder legt die Y‑Koordinate dieses `com.aspose.imaging.PointF` fest. |
| [setY(float value)](#setY-float-) | Liest oder legt die Y‑Koordinate dieses `com.aspose.imaging.PointF` fest. |
| [equals(Object obj)](#equals-java.lang.Object-) | Gibt an, ob dieses `com.aspose.imaging.PointF` dieselben Koordinaten wie das angegebene `System.Object` enthält. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diese `com.aspose.imaging.PointF`‑Struktur zurück. |
| [toString()](#toString--) | Konvertiert dieses `com.aspose.imaging.PointF` in eine menschenlesbare Zeichenkette. |
| [CloneTo(PointF that)](#CloneTo-com.aspose.imaging.PointF-) |  |
| [Clone()](#Clone--) |  |
### PointF() {#PointF--}
```
public PointF()
```


### PointF(float x, float y) {#PointF-float-float-}
```
public PointF(float x, float y)
```


Initialisiert eine neue Instanz der `com.aspose.imaging.PointF`‑Struktur mit den angegebenen Koordinaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die horizontale Position des Punktes. |
| y | float | Die vertikale Position des Punktes. |

### getEmpty() {#getEmpty--}
```
public static PointF getEmpty()
```


Liefert eine neue Instanz der `com.aspose.imaging.PointF`‑Struktur, bei der die Werte `com.aspose.imaging.PointF.X` und `com.aspose.imaging.PointF.Y` auf Null gesetzt sind.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### op_Addition(PointF point, Size size) {#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF op_Addition(PointF point, Size size)
```


Verschiebt ein `com.aspose.imaging.PointF` um ein angegebenes `com.aspose.imaging.Size`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Das `com.aspose.imaging.PointF` zum Übersetzen. |
| size | [Size](../../com.aspose.imaging/size) | Ein `com.aspose.imaging.Size`, das das Zahlenpaar angibt, das zu den Koordinaten von `point` hinzugefügt werden soll. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - Returns the translated `com.aspose.imaging.PointF`.
### op_Subtraction(PointF point, Size size) {#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF op_Subtraction(PointF point, Size size)
```


Verschiebt ein `com.aspose.imaging.PointF` um das Negative eines angegebenen `com.aspose.imaging.Size`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Ein `com.aspose.imaging.PointF` zum Übersetzen. |
| size | [Size](../../com.aspose.imaging/size) | Ein `com.aspose.imaging.Size`, das die Zahlen angibt, die von den x- und y-Koordinaten des `point` subtrahiert werden sollen. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### op_Addition(PointF point, SizeF size) {#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF op_Addition(PointF point, SizeF size)
```


Verschiebt das `com.aspose.imaging.PointF` um das angegebene `com.aspose.imaging.SizeF`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Das `com.aspose.imaging.PointF` zum Übersetzen. |
| size | [SizeF](../../com.aspose.imaging/sizef) | Das `com.aspose.imaging.SizeF`, das die Zahlen angibt, die zu den x- und y-Koordinaten des `point` hinzugefügt werden sollen. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### op_Subtraction(PointF point, SizeF size) {#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF op_Subtraction(PointF point, SizeF size)
```


Verschiebt ein `com.aspose.imaging.PointF` um das Negative eines angegebenen `com.aspose.imaging.SizeF`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Das `com.aspose.imaging.PointF` zum Übersetzen. |
| size | [SizeF](../../com.aspose.imaging/sizef) | Das `com.aspose.imaging.SizeF`, das die Zahlen angibt, die von den Koordinaten von `point` subtrahiert werden sollen. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### op_Equality(PointF point1, PointF point2) {#op-Equality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static boolean op_Equality(PointF point1, PointF point2)
```


Vergleicht zwei `com.aspose.imaging.PointF`-Strukturen. Das Ergebnis gibt an, ob die Werte der Eigenschaften `com.aspose.imaging.PointF.X` und `com.aspose.imaging.PointF.Y` der beiden `com.aspose.imaging.PointF`-Strukturen gleich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | Ein erstes `com.aspose.imaging.PointF` zum Vergleichen. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | Ein zweites `com.aspose.imaging.PointF` zum Vergleichen. |

**Returns:**
boolean - Wahr, wenn die Werte `com.aspose.imaging.PointF.X` und `com.aspose.imaging.PointF.Y` der ersten und zweiten `com.aspose.imaging.PointF`-Strukturen gleich sind; andernfalls falsch.
### op_Inequality(PointF point1, PointF point2) {#op-Inequality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static boolean op_Inequality(PointF point1, PointF point2)
```


Bestimmt, ob die Koordinaten der angegebenen Punkte ungleich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | Ein erstes `com.aspose.imaging.PointF` zum Vergleichen. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | Ein zweites `com.aspose.imaging.PointF` zum Vergleichen. |

**Returns:**
boolean - Wahr, um anzuzeigen, dass die Werte `com.aspose.imaging.PointF.X` und `com.aspose.imaging.PointF.Y` von `point1` und `point2` nicht gleich sind; andernfalls falsch.
### add(PointF point, Size size) {#add-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF add(PointF point, Size size)
```


Verschiebt ein angegebenes `com.aspose.imaging.PointF` um das angegebene `com.aspose.imaging.Size`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Das `com.aspose.imaging.PointF` zum Übersetzen. |
| size | [Size](../../com.aspose.imaging/size) | Das `com.aspose.imaging.Size`, das die Zahlen angibt, die zu den Koordinaten von `point` hinzugefügt werden sollen. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### subtract(PointF point, Size size) {#subtract-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF subtract(PointF point, Size size)
```


Verschiebt ein `com.aspose.imaging.PointF` um das Negative einer angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Das `com.aspose.imaging.PointF` zum Übersetzen. |
| size | [Size](../../com.aspose.imaging/size) | Das `com.aspose.imaging.Size`, das die Zahlen angibt, die von den Koordinaten von `point` subtrahiert werden sollen. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### add(PointF point, SizeF size) {#add-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF add(PointF point, SizeF size)
```


Verschiebt ein angegebenes `com.aspose.imaging.PointF` um ein angegebenes `com.aspose.imaging.SizeF`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Das `com.aspose.imaging.PointF` zum Übersetzen. |
| size | [SizeF](../../com.aspose.imaging/sizef) | Das `com.aspose.imaging.SizeF`, das die Zahlen angibt, die zu den Koordinaten von `point` hinzugefügt werden sollen. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### subtract(PointF point, SizeF size) {#subtract-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF subtract(PointF point, SizeF size)
```


Verschiebt ein `com.aspose.imaging.PointF` um das Negative einer angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Das `com.aspose.imaging.PointF` zum Übersetzen. |
| size | [SizeF](../../com.aspose.imaging/sizef) | Das `com.aspose.imaging.SizeF`, das die Zahlen angibt, die von den Koordinaten von `point` subtrahiert werden sollen. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### isEquals(PointF obj1, PointF obj2) {#isEquals-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static boolean isEquals(PointF obj1, PointF obj2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj1 | [PointF](../../com.aspose.imaging/pointf) |  |
| obj2 | [PointF](../../com.aspose.imaging/pointf) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Liefert einen Wert, der angibt, ob dieses `com.aspose.imaging.PointF` leer ist.

**Returns:**
boolean - Wahr, wenn sowohl `com.aspose.imaging.PointF.X` als auch `com.aspose.imaging.PointF.Y` 0 sind; andernfalls falsch.
### getX() {#getX--}
```
public float getX()
```


Liest oder legt die X‑Koordinate dieses `com.aspose.imaging.PointF` fest.

**Returns:**
float
### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Liest oder legt die X‑Koordinate dieses `com.aspose.imaging.PointF` fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getY() {#getY--}
```
public float getY()
```


Liest oder legt die Y‑Koordinate dieses `com.aspose.imaging.PointF` fest.

**Returns:**
float
### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Liest oder legt die Y‑Koordinate dieses `com.aspose.imaging.PointF` fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Gibt an, ob dieses `com.aspose.imaging.PointF` dieselben Koordinaten wie das angegebene `System.Object` enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das `System.Object` zum Testen. |

**Returns:**
boolean - Diese Methode gibt wahr zurück, wenn `obj` ein `com.aspose.imaging.PointF` ist und dieselben Koordinaten wie dieses `com.aspose.imaging.Point` hat.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für diese `com.aspose.imaging.PointF`‑Struktur zurück.

**Returns:**
int - Ein ganzzahliger Wert, der einen Hashwert für diese `com.aspose.imaging.PointF`-Struktur angibt.
### toString() {#toString--}
```
public String toString()
```


Konvertiert dieses `com.aspose.imaging.PointF` in eine menschenlesbare Zeichenkette.

**Returns:**
java.lang.String - Eine Zeichenkette, die dieses `com.aspose.imaging.PointF` darstellt.
### CloneTo(PointF that) {#CloneTo-com.aspose.imaging.PointF-}
```
public void CloneTo(PointF that)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| that | [PointF](../../com.aspose.imaging/pointf) |  |

### Clone() {#Clone--}
```
public PointF Clone()
```




**Returns:**
[PointF](../../com.aspose.imaging/pointf)
