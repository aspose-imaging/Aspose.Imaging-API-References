---
title: "TiffSRational"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der TIFF‑Rational‑Typ."
type: docs
weight: 15
url: /de/java/com.aspose.imaging.fileformats.tiff/tiffsrational/
---
**Inheritance:**
java.lang.Object
```
public class TiffSRational
```

Der TIFF‑Rational‑Typ.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TiffSRational()](#TiffSRational--) | Initialisiert eine neue Instanz der `TiffSRational`-Klasse. |
| [TiffSRational(int value)](#TiffSRational-int-) | Initialisiert eine neue Instanz der [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)-Klasse. |
| [TiffSRational(int nominator, int denominator)](#TiffSRational-int-int-) | Initialisiert eine neue Instanz der `TiffSRational`-Klasse. |
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
| [toString()](#toString--) | Gibt einen `System.String` zurück, der diese Instanz darstellt. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene `Object` gleich dieser Instanz ist. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diese Instanz zurück. |
### TiffSRational() {#TiffSRational--}
```
public TiffSRational()
```


Initialisiert eine neue Instanz der `TiffSRational`-Klasse.

### TiffSRational(int value) {#TiffSRational-int-}
```
public TiffSRational(int value)
```


Initialisiert eine neue Instanz der [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der Zählerwert. |

### TiffSRational(int nominator, int denominator) {#TiffSRational-int-int-}
```
public TiffSRational(int nominator, int denominator)
```


Initialisiert eine neue Instanz der `TiffSRational`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Zähler | int | Der Zähler. |
| Nenner | int | Der Nenner. |

### EPSILON {#EPSILON}
```
public static final double EPSILON
```


Das Epsilon für die Bruchberechnung

### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffSRational approximateFraction(double value, double epsilon)
```


Annähert den angegebenen Wert an einen Bruch.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double | Der Wert. |
| Epsilon | double | Der zulässige Fehler. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `epsilon`.
### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffSRational approximateFraction(double value)
```


Annähert den angegebenen Wert an einen Bruch.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double | Der Wert. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `Epsilon`.
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffSRational approximateFraction(float value, double epsilon)
```


Annähert den angegebenen Wert an einen Bruch.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Der Wert. |
| Epsilon | double | Der zulässige Fehler. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `epsilon`.
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffSRational approximateFraction(float value)
```


Annähert den angegebenen Wert an einen Bruch.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Der Wert. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `Epsilon`.
### getDenominator() {#getDenominator--}
```
public int getDenominator()
```


Gibt den Nenner zurück.

Wert: Der Nenner.

**Returns:**
int
### getNominator() {#getNominator--}
```
public int getNominator()
```


Gibt den Zähler zurück.

Wert: Der Zähler.

**Returns:**
int
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


Gibt einen `System.String` zurück, der diese Instanz darstellt.

**Returns:**
java.lang.String - Ein `System.String`, der diese Instanz darstellt.
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
