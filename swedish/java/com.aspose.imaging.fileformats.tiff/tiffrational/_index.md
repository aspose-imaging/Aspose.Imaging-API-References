---
title: "TiffRational"
second_title: "Aspose.Imaging för Java API-referens"
description: "TIFF-rational-typen."
type: docs
weight: 14
url: /sv/java/com.aspose.imaging.fileformats.tiff/tiffrational/
---
**Inheritance:**
java.lang.Object
```
public class TiffRational
```

TIFF-rational-typen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TiffRational()](#TiffRational--) | Initierar en ny instans av `TiffRational`-klassen. |
| [TiffRational(long value)](#TiffRational-long-) | Initierar en ny instans av `TiffRational`-klassen. |
| [TiffRational(long nominator, long denominator)](#TiffRational-long-long-) | Initierar en ny instans av `TiffRational`-klassen. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [EPSILON](#EPSILON) | Epsilon för bråkräkning |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [approximateFraction(double value, double epsilon)](#approximateFraction-double-double-) | Approximerar det angivna värdet till ett bråk. |
| [approximateFraction(double value)](#approximateFraction-double-) | Approximerar det angivna värdet till ett bråk. |
| [approximateFraction(float value, double epsilon)](#approximateFraction-float-double-) | Approximerar det angivna värdet till ett bråk. |
| [approximateFraction(float value)](#approximateFraction-float-) | Approximerar det angivna värdet till ett bråk. |
| [getDenominator()](#getDenominator--) | Hämtar nämnaren. |
| [getNominator()](#getNominator--) | Hämtar täljaren. |
| [getValue()](#getValue--) | Hämtar flyttalsvärdet. |
| [getValueD()](#getValueD--) | Hämtar dubbelvärdet. |
| [toString()](#toString--) | Konverterar till sträng. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om det specificerade `Object` är lika med den här instansen. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för detta objekt. |
### TiffRational() {#TiffRational--}
```
public TiffRational()
```


Initierar en ny instans av `TiffRational`-klassen.

### TiffRational(long value) {#TiffRational-long-}
```
public TiffRational(long value)
```


Initierar en ny instans av `TiffRational`-klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | long | Täljarevärdet. |

Täljaren kommer att användas som det angivna värdet och nämnaren kommer att vara lika med 1. |

### TiffRational(long nominator, long denominator) {#TiffRational-long-long-}
```
public TiffRational(long nominator, long denominator)
```


Initierar en ny instans av `TiffRational`-klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| täljare | long | Täljaren. |
| nämnare | long | Nämnaren. |

### EPSILON {#EPSILON}
```
public static final double EPSILON
```


Epsilon för bråkräkning

### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffRational approximateFraction(double value, double epsilon)
```


Approximerar det angivna värdet till ett bråk.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Värdet. |
| epsilon | double | Det tillåtna felet. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `epsilon`.
### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffRational approximateFraction(double value)
```


Approximerar det angivna värdet till ett bråk.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Värdet. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `Epsilon`.
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffRational approximateFraction(float value, double epsilon)
```


Approximerar det angivna värdet till ett bråk.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Värdet. |
| epsilon | double | Det tillåtna felet. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `epsilon`.
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffRational approximateFraction(float value)
```


Approximerar det angivna värdet till ett bråk.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Värdet. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `Epsilon`.
### getDenominator() {#getDenominator--}
```
public long getDenominator()
```


Hämtar nämnaren.

Värde: Nämnaren.

**Returns:**
long
### getNominator() {#getNominator--}
```
public long getNominator()
```


Hämtar täljaren.

Värde: Täljaren.

**Returns:**
long
### getValue() {#getValue--}
```
public float getValue()
```


Hämtar flyttalsvärdet.

Värde: Flyttalsvärdet.

**Returns:**
float
### getValueD() {#getValueD--}
```
public double getValueD()
```


Hämtar dubbelvärdet.

Värde: Det dubbla värdet.

**Returns:**
double
### toString() {#toString--}
```
public String toString()
```


Konverterar till sträng.

**Returns:**
java.lang.String - En sträng som representerar detta objekt.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om det specificerade `Object` är lika med den här instansen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Det `Object` att jämföra med den här instansen. |

**Returns:**
boolean - `true` om det angivna `Object` är lika med den här instansen; annars `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för detta objekt.

**Returns:**
int - En hashkod för denna instans, lämplig för användning i hash-algoritmer och datastrukturer som en hash‑tabell.
