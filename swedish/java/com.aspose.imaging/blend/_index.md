---
title: "Blend"
second_title: "Aspose.Imaging för Java API-referens"
description: "Definierar ett blandningsmönster."
type: docs
weight: 12
url: /sv/java/com.aspose.imaging/blend/
---
**Inheritance:**
java.lang.Object
```
public final class Blend
```

Definierar ett blandningsmönster. Denna klass kan inte ärvas.

Den typiska användningen av blend-klassen är att definiera ett blandningsmönster för penseln. Därför bör blend-egenskaperna initieras noggrant. Null-arrayer är inte tillåtna. Penseln kommer att kasta ett lämpligt undantag om blend-faktorer eller positionsarray är tomma eller deras längd inte är densamma. Om det finns två eller fler element i positionsarrayen ska det första elementet vara 0 och det sista vara 1.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Blend()](#Blend--) | Initierar en ny instans av klassen `Blend`. |
| [Blend(int count)](#Blend-int-) | Initierar en ny instans av klassen `Blend` med det angivna antalet faktorer och positioner. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFactors()](#getFactors--) | Hämtar arrayen med blend-faktorer för gradienten. |
| [setFactors(float[] value)](#setFactors-float---) | Ställer in arrayen med blend-faktorer för gradienten. |
| [getPositions()](#getPositions--) | Hämtar arrayen med blend-positioner för gradienten. |
| [setPositions(float[] value)](#setPositions-float---) | Ställer in arrayen med blend-positioner för gradienten. |
| [equals(Object obj)](#equals-java.lang.Object-) | Testar om det angivna objektet är en `com.aspose.imaging.Blend`-klass och är ekvivalent med denna `com.aspose.imaging.Blend`-klass. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för detta objekt. |
### Blend() {#Blend--}
```
public Blend()
```


Initierar en ny instans av `Blend`-klassen. Antalet element i faktor- och blandningsarrayerna kommer att vara lika med 1.

### Blend(int count) {#Blend-int-}
```
public Blend(int count)
```


Initierar en ny instans av klassen `Blend` med det angivna antalet faktorer och positioner.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| antal | int | Antalet element i faktor- och positionsarrayerna. |

### getFactors() {#getFactors--}
```
public float[] getFactors()
```


Hämtar arrayen med blend-faktorer för gradienten.

**Returns:**
float[] - Arrayen av blandningsfaktorer som specificerar procentsatserna för startfärgen och slutfärgen som ska användas på motsvarande position.
### setFactors(float[] value) {#setFactors-float---}
```
public void setFactors(float[] value)
```


Ställer in arrayen med blend-faktorer för gradienten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float[] | Arrayen av blandningsfaktorer som specificerar procentsatserna för startfärgen och slutfärgen som ska användas på motsvarande position. |

### getPositions() {#getPositions--}
```
public float[] getPositions()
```


Hämtar arrayen med blend-positioner för gradienten.

**Returns:**
float[] - Arrayen av blandningspositioner som specificerar procentsatserna av avstånd längs gradientlinjen.
### setPositions(float[] value) {#setPositions-float---}
```
public void setPositions(float[] value)
```


Ställer in arrayen med blend-positioner för gradienten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float[] | Arrayen av blandningspositioner som specificerar procentsatserna av avstånd längs gradientlinjen. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Testar om det angivna objektet är en `com.aspose.imaging.Blend`-klass och är ekvivalent med denna `com.aspose.imaging.Blend`-klass.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objektet att testa. |

**Returns:**
boolean - Sant om `obj` är en `com.aspose.imaging.Blend`-klass som är ekvivalent med denna `com.aspose.imaging.Blend`-klass; annars falskt.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för detta objekt.

**Returns:**
int - En hashkod för denna instans, lämplig för användning i hash-algoritmer och datastrukturer som en hash‑tabell.
