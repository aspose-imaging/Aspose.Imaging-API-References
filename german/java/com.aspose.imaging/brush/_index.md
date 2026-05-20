---
title: "Brush"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Basispinselklasse."
type: docs
weight: 13
url: /de/java/com.aspose.imaging/brush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public abstract class Brush extends DisposableObject
```

Die Basispinselklasse.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Brush()](#Brush--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getOpacity()](#getOpacity--) | Liefert die Deckkraft des Pinsels. |
| [setOpacity(float value)](#setOpacity-float-) | Setzt die Deckkraft des Pinsels. |
| [deepClone()](#deepClone--) | Erstellt einen neuen tiefen Klon des aktuellen `Brush`. |
| [equals(Object o)](#equals-java.lang.Object-) | Überprüft, ob Objekte gleich sind. |
| [hashCode()](#hashCode--) | Gibt den Hashcode des aktuellen Objekts zurück. |
### Brush() {#Brush--}
```
public Brush()
```


### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Liefert die Deckkraft des Pinsels. Der Wert sollte zwischen 0 und 1 liegen. Ein Wert von 0 bedeutet, dass der Pinsel vollständig sichtbar ist, ein Wert von 1 bedeutet, dass der Pinsel vollständig undurchsichtig ist.

**Returns:**
float – Der Deckkraftwert des Pinsels.
### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Setzt die Deckkraft des Pinsels. Der Wert sollte zwischen 0 und 1 liegen. Ein Wert von 0 bedeutet, dass der Pinsel vollständig sichtbar ist, ein Wert von 1 bedeutet, dass der Pinsel vollständig undurchsichtig ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Der Deckkraftwert des Pinsels. |

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


Erstellt einen neuen tiefen Klon des aktuellen `Brush`.

**Returns:**
[Brush](../../com.aspose.imaging/brush) - A new `Brush` which is the deep clone of this `Brush` instance.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Überprüft, ob Objekte gleich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| o | java.lang.Object | Das andere Objekt. |

**Returns:**
boolean - Das Ergebnis des Gleichheitsvergleichs.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode des aktuellen Objekts zurück.

**Returns:**
int - Der Hashcode.
