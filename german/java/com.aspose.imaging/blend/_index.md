---
title: "Blend"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Definiert ein Mischmuster."
type: docs
weight: 12
url: /de/java/com.aspose.imaging/blend/
---
**Inheritance:**
java.lang.Object
```
public final class Blend
```

Definiert ein Blend-Muster. Diese Klasse kann nicht vererbt werden.

Die typische Verwendung der Blend-Klasse besteht darin, ein Blend-Muster für einen Pinsel zu definieren. Und daher sollten die Blend-Eigenschaften sorgfältig initialisiert werden. Null-Arrays sind nicht erlaubt. Der Pinsel wirft die entsprechende Ausnahme, wenn Blend-Faktoren- oder Positionsarray leer sind oder deren Länge nicht gleich ist. Wenn im Positionsarray zwei oder mehr Elemente enthalten sind, muss das erste Element 0 und das letzte 1 sein.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Blend()](#Blend--) | Initialisiert eine neue Instanz der `Blend`-Klasse. |
| [Blend(int count)](#Blend-int-) | Initialisiert eine neue Instanz der `Blend`-Klasse mit der angegebenen Anzahl von Faktoren und Positionen. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFactors()](#getFactors--) | Gibt das Array der Blend-Faktoren für den Verlauf zurück. |
| [setFactors(float[] value)](#setFactors-float---) | Setzt das Array der Blend-Faktoren für den Verlauf. |
| [getPositions()](#getPositions--) | Gibt das Array der Blend-Positionen für den Verlauf zurück. |
| [setPositions(float[] value)](#setPositions-float---) | Setzt das Array der Blend-Positionen für den Verlauf. |
| [equals(Object obj)](#equals-java.lang.Object-) | Prüft, ob das angegebene Objekt eine `com.aspose.imaging.Blend`-Klasse ist und dieser `com.aspose.imaging.Blend`-Klasse entspricht. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diese Instanz zurück. |
### Blend() {#Blend--}
```
public Blend()
```


Initialisiert eine neue Instanz der `Blend`-Klasse. Die Anzahl der Elemente in den Faktor‑ und Blend‑Arrays wird 1 sein.

### Blend(int count) {#Blend-int-}
```
public Blend(int count)
```


Initialisiert eine neue Instanz der `Blend`-Klasse mit der angegebenen Anzahl von Faktoren und Positionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| count | int | Die Anzahl der Elemente in den Faktor‑ und Positions‑Arrays. |

### getFactors() {#getFactors--}
```
public float[] getFactors()
```


Gibt das Array der Blend-Faktoren für den Verlauf zurück.

**Returns:**
float[] – Das Array der Blend‑Faktoren, die die Prozentsätze der Start‑ und Endfarbe an der jeweiligen Position angeben.
### setFactors(float[] value) {#setFactors-float---}
```
public void setFactors(float[] value)
```


Setzt das Array der Blend-Faktoren für den Verlauf.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float[] | Das Array der Blend‑Faktoren, die die Prozentsätze der Start‑ und Endfarbe an der jeweiligen Position angeben. |

### getPositions() {#getPositions--}
```
public float[] getPositions()
```


Gibt das Array der Blend-Positionen für den Verlauf zurück.

**Returns:**
float[] – Das Array der Blend‑Positionen, die die prozentualen Entfernungen entlang der Verlaufs­linie angeben.
### setPositions(float[] value) {#setPositions-float---}
```
public void setPositions(float[] value)
```


Setzt das Array der Blend-Positionen für den Verlauf.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float[] | Das Array der Blend‑Positionen, die die prozentualen Entfernungen entlang der Verlaufs­linie angeben. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Prüft, ob das angegebene Objekt eine `com.aspose.imaging.Blend`-Klasse ist und dieser `com.aspose.imaging.Blend`-Klasse entspricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das zu testende Objekt. |

**Returns:**
boolean – Wahr, wenn `obj` eine `com.aspose.imaging.Blend`‑Klasse ist, die dieser `com.aspose.imaging.Blend`‑Klasse entspricht; andernfalls falsch.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für diese Instanz zurück.

**Returns:**
int – Ein Hashcode für diese Instanz, geeignet für den Einsatz in Hash‑Algorithmen und Datenstrukturen wie einer Hashtabelle.
