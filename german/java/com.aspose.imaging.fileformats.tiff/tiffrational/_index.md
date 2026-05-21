---
title: "TiffRational"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der TIFF‑Rational‑Typ."
type: docs
weight: 14
url: /de/java/com.aspose.imaging.fileformats.tiff/tiffrational/
---
**Inheritance:**
java.lang.Object
```
public class TiffRational
```

Der TIFF‑Rational‑Typ.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TiffRational()](#TiffRational--) | Initialisiert eine neue Instanz der `TiffRational`-Klasse. |
| [TiffRational(long value)](#TiffRational-long-) | Initialisiert eine neue Instanz der `TiffRational`-Klasse. |
| [TiffRational(long nominator, long denominator)](#TiffRational-long-long-) | Initialisiert eine neue Instanz der `TiffRational`-Klasse. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [EPSILON](#EPSILON) | Das Epsilon für die Bruchberechnung |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [approximateFraction(double value, double epsilon)](#approximateFraction-double-double-) | Annähert den angegebenen Wert an einen Bruch. |
| [approximateFraction(double value)](#approximateFraction-double-) | Annähert den angegebenen Wert an einen Bruch. |
| [approximateFraction(float value, double epsilon)](#approximateFraction-float-double-) | Annähert den angegebenen Wert an einen Bruch. |
| [approximateFraction(float value)](#approximateFraction-float-) | Annähert den angegebenen Wert an einen Bruch. |
| [getDenominator()](#getDenominator--) | Gibt den Nenner zurück. |
| [getNominator()](#getNominator--) | Gibt den Zähler zurück. |
| [getValue()](#getValue--) | Gibt den Float-Wert zurück. |
| [getValueD()](#getValueD--) | Gibt den Double-Wert zurück. |
| [toString()](#toString--) | Konvertiert in einen String. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene `Object` gleich dieser Instanz ist. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diese Instanz zurück. |
### TiffRational() {#TiffRational--}
```
public TiffRational()
```


Initialisiert eine neue Instanz der `TiffRational`-Klasse.

### TiffRational(long value) {#TiffRational-long-}
```
public TiffRational(long value)
```


Initialisiert eine neue Instanz der `TiffRational`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | long | Der Zählerwert. |

Der Zähler wird als der angegebene Wert verwendet und der Nenner ist gleich 1. |

### TiffRational(long nominator, long denominator) {#TiffRational-long-long-}
```
public TiffRational(long nominator, long denominator)
```


Initialisiert eine neue Instanz der `TiffRational`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Zähler | long | Der Zähler. |
| Nenner | long | Der Nenner. |

### EPSILON {#EPSILON}
```
public static final double EPSILON
```


Das Epsilon für die Bruchberechnung

### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffRational approximateFraction(double value, double epsilon)
```


Annähert den angegebenen Wert an einen Bruch.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double | Der Wert. |
| Epsilon | double | Der zulässige Fehler. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `epsilon`.
### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffRational approximateFraction(double value)
```


Annähert den angegebenen Wert an einen Bruch.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double | Der Wert. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `Epsilon`.
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffRational approximateFraction(float value, double epsilon)
```


Annähert den angegebenen Wert an einen Bruch.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Der Wert. |
| Epsilon | double | Der zulässige Fehler. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `epsilon`.
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffRational approximateFraction(float value)
```


Annähert den angegebenen Wert an einen Bruch.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Der Wert. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `Epsilon`.
### getDenominator() {#getDenominator--}
```
public long getDenominator()
```


Gibt den Nenner zurück.

Wert: Der Nenner.

**Returns:**
long
### getNominator() {#getNominator--}
```
public long getNominator()
```


Gibt den Zähler zurück.

Wert: Der Zähler.

**Returns:**
long
### getValue() {#getValue--}
```
public float getValue()
```


Gibt den Float-Wert zurück.

Wert: Der Float-Wert.

**Returns:**
float
### getValueD() {#getValueD--}
```
public double getValueD()
```


Gibt den Double-Wert zurück.

Wert: Der double-Wert.

**Returns:**
double
### toString() {#toString--}
```
public String toString()
```


Konvertiert in einen String.

**Returns:**
java.lang.String - Ein String, der diese Instanz darstellt.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene `Object` gleich dieser Instanz ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das `Object` zum Vergleich mit dieser Instanz. |

**Returns:**
boolean - `true` wenn das angegebene `Object` dieser Instanz gleich ist; andernfalls `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für diese Instanz zurück.

**Returns:**
int – Ein Hashcode für diese Instanz, geeignet für den Einsatz in Hash‑Algorithmen und Datenstrukturen wie einer Hashtabelle.
