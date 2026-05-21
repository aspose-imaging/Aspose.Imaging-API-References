---
title: "ColorBlend"
second_title: "Aspose.Imaging för Java API-referens"
description: "Definierar arrayer av färger och positioner som används för interpolering av färgblandning i en flerfärgsgradient."
type: docs
weight: 22
url: /sv/java/com.aspose.imaging/colorblend/
---
**Inheritance:**
java.lang.Object
```
public final class ColorBlend
```

Definierar arrayer av färger och positioner som används för interpolering av färgblandning i en flerfärgsgradient. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ColorBlend()](#ColorBlend--) | Initierar en ny instans av klassen `com.aspose.imaging.ColorBlend`. |
| [ColorBlend(int count)](#ColorBlend-int-) | Initierar en ny instans av klassen `com.aspose.imaging.ColorBlend` med det angivna antalet färger och positioner. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getColors()](#getColors--) | Hämtar eller anger en array av färger som representerar färgerna som ska användas på motsvarande positioner längs en gradient. |
| [setColors(Color[] value)](#setColors-com.aspose.imaging.Color---) |  |
| [getPositions()](#getPositions--) | Hämtar eller anger positionerna längs en gradientlinje. |
| [setPositions(float[] value)](#setPositions-float---) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Testar om det angivna objektet är en `com.aspose.imaging.ColorBlend`-klass och är ekvivalent med denna `com.aspose.imaging.ColorBlend`-klass. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för detta objekt. |
### ColorBlend() {#ColorBlend--}
```
public ColorBlend()
```


Initierar en ny instans av klassen `com.aspose.imaging.ColorBlend`.

### ColorBlend(int count) {#ColorBlend-int-}
```
public ColorBlend(int count)
```


Initierar en ny instans av klassen `com.aspose.imaging.ColorBlend` med det angivna antalet färger och positioner.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| antal | int | Antalet färger och positioner i detta `com.aspose.imaging.ColorBlend`. |

### getColors() {#getColors--}
```
public Color[] getColors()
```


Hämtar eller anger en array av färger som representerar färgerna som ska användas på motsvarande positioner längs en gradient.

**Returns:**
com.aspose.imaging.Color[] - En array av `com.aspose.imaging.Color`-strukturer som representerar färgerna som ska användas på motsvarande positioner längs en gradient.
### setColors(Color[] value) {#setColors-com.aspose.imaging.Color---}
```
public void setColors(Color[] value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.imaging/color) |  |

### getPositions() {#getPositions--}
```
public float[] getPositions()
```


Hämtar eller anger positionerna längs en gradientlinje.

**Returns:**
float[] - En array av värden som specificerar procentandelar av avståndet längs gradientlinjen.
### setPositions(float[] value) {#setPositions-float---}
```
public void setPositions(float[] value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float[] |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Testar om det angivna objektet är en `com.aspose.imaging.ColorBlend`-klass och är ekvivalent med denna `com.aspose.imaging.ColorBlend`-klass.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objektet att testa. |

**Returns:**
boolean - Sant om `obj` är en `com.aspose.imaging.ColorBlend`-klass som är ekvivalent med denna `com.aspose.imaging.ColorBlend`-klass; annars falskt.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för detta objekt.

**Returns:**
int - En hashkod för denna instans, lämplig för användning i hash-algoritmer och datastrukturer som en hash‑tabell.
