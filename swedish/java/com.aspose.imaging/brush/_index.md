---
title: "Pensel"
second_title: "Aspose.Imaging för Java API-referens"
description: "Baspenselklassen."
type: docs
weight: 13
url: /sv/java/com.aspose.imaging/brush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public abstract class Brush extends DisposableObject
```

Baspenselklassen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Brush()](#Brush--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getOpacity()](#getOpacity--) | Hämtar penselns opacitet. |
| [setOpacity(float value)](#setOpacity-float-) | Ställer in penselns opacitet. |
| [deepClone()](#deepClone--) | Skapar en ny djupklon av den aktuella `Brush`. |
| [equals(Object o)](#equals-java.lang.Object-) | Kontrollera om objekt är lika. |
| [hashCode()](#hashCode--) | Hämta hashkoden för det aktuella objektet. |
### Brush() {#Brush--}
```
public Brush()
```


### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Hämtar penselns opacitet. Värdet bör vara mellan 0 och 1. Värde 0 betyder att penseln är helt synlig, värde 1 betyder att penseln är helt ogenomskinlig.

**Returns:**
float - Penselns opacitetsvärde.
### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Ställer in penselns opacitet. Värdet bör vara mellan 0 och 1. Värde 0 betyder att penseln är helt synlig, värde 1 betyder att penseln är helt ogenomskinlig.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Penselns opacitetsvärde. |

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


Skapar en ny djupklon av den aktuella `Brush`.

**Returns:**
[Brush](../../com.aspose.imaging/brush) - A new `Brush` which is the deep clone of this `Brush` instance.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Kontrollera om objekt är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| o | java.lang.Object | Det andra objektet. |

**Returns:**
boolean - Resultatet av likhetsjämförelsen.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hämta hashkoden för det aktuella objektet.

**Returns:**
int - Hashkoden.
