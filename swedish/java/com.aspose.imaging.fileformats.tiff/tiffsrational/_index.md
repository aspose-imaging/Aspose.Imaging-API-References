---
title: "TiffSRational"
second_title: "Aspose.Imaging för Java API-referens"
description: "TIFF-rational-typen."
type: docs
weight: 15
url: /sv/java/com.aspose.imaging.fileformats.tiff/tiffsrational/
---
**Inheritance:**
java.lang.Object
```
public class TiffSRational
```

TIFF-rational-typen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TiffSRational()](#TiffSRational--) | Initierar en ny instans av klassen `TiffSRational`. |
| [TiffSRational(int value)](#TiffSRational-int-) | Initierar en ny instans av klassen [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational). |
| [TiffSRational(int nominator, int denominator)](#TiffSRational-int-int-) | Initierar en ny instans av klassen `TiffSRational`. |
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
| [toString()](#toString--) | Returnerar en `System.String` som representerar denna instans. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om det angivna `Object` är lika med detta objekt. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för detta objekt. |
### TiffSRational() {#TiffSRational--}
```
public TiffSRational()
```


Initierar en ny instans av klassen `TiffSRational`.

### TiffSRational(int value) {#TiffSRational-int-}
```
public TiffSRational(int value)
```


Initierar en ny instans av klassen [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Täljarevärdet. |

### TiffSRational(int nominator, int denominator) {#TiffSRational-int-int-}
```
public TiffSRational(int nominator, int denominator)
```


Initierar en ny instans av klassen `TiffSRational`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| täljare | int | Täljaren. |
| nämnare | int | Nämnaren. |

### EPSILON {#EPSILON}
```
public static final double EPSILON
```


Epsilon för bråkräkning

### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffSRational approximateFraction(double value, double epsilon)
```


Approximerar det angivna värdet till ett bråk.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Värdet. |
| epsilon | double | Det tillåtna felet. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `epsilon`.
### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffSRational approximateFraction(double value)
```


Approximerar det angivna värdet till ett bråk.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Värdet. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `Epsilon`.
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffSRational approximateFraction(float value, double epsilon)
```


Approximerar det angivna värdet till ett bråk.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Värdet. |
| epsilon | double | Det tillåtna felet. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `epsilon`.
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffSRational approximateFraction(float value)
```


Approximerar det angivna värdet till ett bråk.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Värdet. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `Epsilon`.
### getDenominator() {#getDenominator--}
```
public int getDenominator()
```


Hämtar nämnaren.

Värde: Nämnaren.

**Returns:**
int
### getNominator() {#getNominator--}
```
public int getNominator()
```


Hämtar täljaren.

Värde: Täljaren.

**Returns:**
int
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


Returnerar en `System.String` som representerar denna instans.

**Returns:**
java.lang.String - En `System.String` som representerar denna instans.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om det angivna `Object` är lika med detta objekt.

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
