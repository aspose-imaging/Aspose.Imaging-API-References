---
title: "ColorBlend"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Definiert Arrays von Farben und Positionen, die für die Interpolation von Farbmischungen in einem mehrfarbigen Verlauf verwendet werden."
type: docs
weight: 22
url: /de/java/com.aspose.imaging/colorblend/
---
**Inheritance:**
java.lang.Object
```
public final class ColorBlend
```

Definiert Arrays von Farben und Positionen, die zum Interpolieren von Farbmischungen in einem mehrfarbigen Verlauf verwendet werden. Diese Klasse kann nicht vererbt werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ColorBlend()](#ColorBlend--) | Initialisiert eine neue Instanz der `com.aspose.imaging.ColorBlend`-Klasse. |
| [ColorBlend(int count)](#ColorBlend-int-) | Initialisiert eine neue Instanz der `com.aspose.imaging.ColorBlend`-Klasse mit der angegebenen Anzahl von Farben und Positionen. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getColors()](#getColors--) | Liest oder legt ein Array von Farben fest, das die Farben darstellt, die an den entsprechenden Positionen entlang eines Farbverlaufs verwendet werden sollen. |
| [setColors(Color[] value)](#setColors-com.aspose.imaging.Color---) |  |
| [getPositions()](#getPositions--) | Liest oder legt die Positionen entlang einer Verlaufs‑linie fest. |
| [setPositions(float[] value)](#setPositions-float---) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Prüft, ob das angegebene Objekt eine `com.aspose.imaging.ColorBlend`‑Klasse ist und dieser `com.aspose.imaging.ColorBlend`‑Klasse entspricht. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diese Instanz zurück. |
### ColorBlend() {#ColorBlend--}
```
public ColorBlend()
```


Initialisiert eine neue Instanz der `com.aspose.imaging.ColorBlend`-Klasse.

### ColorBlend(int count) {#ColorBlend-int-}
```
public ColorBlend(int count)
```


Initialisiert eine neue Instanz der `com.aspose.imaging.ColorBlend`-Klasse mit der angegebenen Anzahl von Farben und Positionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| count | int | Die Anzahl der Farben und Positionen in diesem `com.aspose.imaging.ColorBlend`. |

### getColors() {#getColors--}
```
public Color[] getColors()
```


Liest oder legt ein Array von Farben fest, das die Farben darstellt, die an den entsprechenden Positionen entlang eines Farbverlaufs verwendet werden sollen.

**Returns:**
com.aspose.imaging.Color[] – Ein Array von `com.aspose.imaging.Color`‑Strukturen, das die Farben darstellt, die an den entsprechenden Positionen entlang eines Farbverlaufs verwendet werden sollen.
### setColors(Color[] value) {#setColors-com.aspose.imaging.Color---}
```
public void setColors(Color[] value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.imaging/color) |  |

### getPositions() {#getPositions--}
```
public float[] getPositions()
```


Liest oder legt die Positionen entlang einer Verlaufs‑linie fest.

**Returns:**
float[] – Ein Array von Werten, die Prozentsätze der Entfernung entlang der Verlaufs‑linie angeben.
### setPositions(float[] value) {#setPositions-float---}
```
public void setPositions(float[] value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float[] |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Prüft, ob das angegebene Objekt eine `com.aspose.imaging.ColorBlend`‑Klasse ist und dieser `com.aspose.imaging.ColorBlend`‑Klasse entspricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das zu testende Objekt. |

**Returns:**
boolean – Wahr, wenn `obj` eine `com.aspose.imaging.ColorBlend`‑Klasse ist, die dieser `com.aspose.imaging.ColorBlend`‑Klasse entspricht; andernfalls falsch.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für diese Instanz zurück.

**Returns:**
int – Ein Hashcode für diese Instanz, geeignet für den Einsatz in Hash‑Algorithmen und Datenstrukturen wie einer Hashtabelle.
