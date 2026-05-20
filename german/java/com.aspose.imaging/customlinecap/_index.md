---
title: "CustomLineCap"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Kapselt eine benutzerdefinierte Linienendkappe."
type: docs
weight: 35
url: /de/java/com.aspose.imaging/customlinecap/
---
**Inheritance:**
java.lang.Object
```
public class CustomLineCap
```

Kapselt eine benutzerdefinierte Linienendkappe.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-) | Initialisiert eine neue Instanz der `CustomLineCap`-Klasse mit der angegebenen Kontur und Füllung. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-) | Initialisiert eine neue Instanz der `CustomLineCap`-Klasse aus der angegebenen vorhandenen `LineCap`-Aufzählung mit der angegebenen Kontur und Füllung. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-float-) | Initialisiert eine neue Instanz der `CustomLineCap`-Klasse aus der angegebenen vorhandenen `LineCap`-Aufzählung mit der angegebenen Kontur, Füllung und Einrückung. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFillPath()](#getFillPath--) | Ruft das Objekt ab, das die Füllung für die benutzerdefinierte Kappe definiert. |
| [setFillPath(GraphicsPath value)](#setFillPath-com.aspose.imaging.GraphicsPath-) | Legt das Objekt fest, das die Füllung für die benutzerdefinierte Kappe definiert. |
| [getStrokePath()](#getStrokePath--) | Ruft das Objekt ab, das die Kontur der benutzerdefinierten Kappe definiert. |
| [setStrokePath(GraphicsPath value)](#setStrokePath-com.aspose.imaging.GraphicsPath-) | Legt das Objekt fest, das die Kontur der benutzerdefinierten Kappe definiert. |
| [getStrokeJoin()](#getStrokeJoin--) | Ruft die `LineJoin`-Aufzählung ab, die bestimmt, wie Linien, die dieses `CustomLineCap`-Objekt bilden, verbunden werden. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Legt die `LineJoin`-Aufzählung fest, die bestimmt, wie Linien, die dieses `CustomLineCap`-Objekt bilden, verbunden werden. |
| [getBaseCap()](#getBaseCap--) | Ruft die `LineCap`-Aufzählung ab, auf der dieses `CustomLineCap` basiert. |
| [setBaseCap(int value)](#setBaseCap-int-) | Legt die `LineCap`-Aufzählung fest, auf der dieses `CustomLineCap` basiert. |
| [getBaseInset()](#getBaseInset--) | Ruft den Abstand zwischen der Kappe und der Linie ab. |
| [setBaseInset(float value)](#setBaseInset-float-) | Legt den Abstand zwischen der Kappe und der Linie fest. |
| [getWidthScale()](#getWidthScale--) | Ruft den Betrag ab, um den dieses `CustomLineCap`-Klassenobjekt in Bezug auf die Breite des `System.Drawing.Pen`-Objekts skaliert wird. |
| [setWidthScale(float value)](#setWidthScale-float-) | Legt den Betrag fest, um den dieses `CustomLineCap`-Klassenobjekt in Bezug auf die Breite des `System.Drawing.Pen`-Objekts skaliert wird. |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | Legt die Kappen fest, die zum Starten und Beenden von Linien verwendet werden, aus denen diese benutzerdefinierte Kappe besteht. |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | Ruft die Kappen ab, die zum Starten und Beenden von Linien verwendet werden, aus denen diese benutzerdefinierte Kappe besteht. |
| [equals(Object o)](#equals-java.lang.Object-) | Überprüft, ob Objekte gleich sind. |
| [hashCode()](#hashCode--) | Gibt den Hashcode des aktuellen Objekts zurück. |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


Initialisiert eine neue Instanz der `CustomLineCap`-Klasse mit der angegebenen Kontur und Füllung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Ein `GraphicsPath`-Objekt, das die Füllung für die benutzerdefinierte Kappe definiert. |
| strokePath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Ein `GraphicsPath`-Objekt, das die Kontur der benutzerdefinierten Kappe definiert. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


Initialisiert eine neue Instanz der `CustomLineCap`-Klasse aus der angegebenen vorhandenen `LineCap`-Aufzählung mit der angegebenen Kontur und Füllung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Ein `GraphicsPath`-Objekt, das die Füllung für die benutzerdefinierte Kappe definiert. |
| strokePath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Ein `GraphicsPath`-Objekt, das die Kontur der benutzerdefinierten Kappe definiert. |
| baseCap | int | Die Linienkappe, aus der die benutzerdefinierte Kappe erstellt wird. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


Initialisiert eine neue Instanz der `CustomLineCap`-Klasse aus der angegebenen vorhandenen `LineCap`-Aufzählung mit der angegebenen Kontur, Füllung und Einrückung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Ein `GraphicsPath`-Objekt, das die Füllung für die benutzerdefinierte Kappe definiert. |
| strokePath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Ein `GraphicsPath`-Objekt, das die Kontur der benutzerdefinierten Kappe definiert. |
| baseCap | int | Die Linienkappe, aus der die benutzerdefinierte Kappe erstellt wird. |
| baseInset | float | Der Abstand zwischen der Kappe und der Linie. |

### getFillPath() {#getFillPath--}
```
public GraphicsPath getFillPath()
```


Ruft das Objekt ab, das die Füllung für die benutzerdefinierte Kappe definiert.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The object that defines the fill for the custom cap.
### setFillPath(GraphicsPath value) {#setFillPath-com.aspose.imaging.GraphicsPath-}
```
public void setFillPath(GraphicsPath value)
```


Legt das Objekt fest, das die Füllung für die benutzerdefinierte Kappe definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Das Objekt, das die Füllung für die benutzerdefinierte Kappe definiert. |

### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


Ruft das Objekt ab, das die Kontur der benutzerdefinierten Kappe definiert.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The object that defines the outline of the custom cap.
### setStrokePath(GraphicsPath value) {#setStrokePath-com.aspose.imaging.GraphicsPath-}
```
public void setStrokePath(GraphicsPath value)
```


Legt das Objekt fest, das die Kontur der benutzerdefinierten Kappe definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Das Objekt, das die Kontur der benutzerdefinierten Kappe definiert. |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


Ruft die `LineJoin`-Aufzählung ab, die bestimmt, wie Linien, die dieses `CustomLineCap`-Objekt bilden, verbunden werden.

**Returns:**
int - Die `LineJoin`-Aufzählung, die dieses `CustomLineCap`-Objekt zum Verbinden von Linien verwendet.
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


Legt die `LineJoin`-Aufzählung fest, die bestimmt, wie Linien, die dieses `CustomLineCap`-Objekt bilden, verbunden werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die `LineJoin`-Aufzählung, die dieses `CustomLineCap`-Objekt zum Verbinden von Linien verwendet. |

### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


Ruft die `LineCap`-Aufzählung ab, auf der dieses `CustomLineCap` basiert.

**Returns:**
int - Die `LineCap`-Aufzählung, auf der dieses `CustomLineCap` basiert.
### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


Legt die `LineCap`-Aufzählung fest, auf der dieses `CustomLineCap` basiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die `LineCap`-Aufzählung, auf der dieses `CustomLineCap` basiert. |

### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


Ruft den Abstand zwischen der Kappe und der Linie ab.

**Returns:**
float - Der Abstand zwischen dem Anfang des Caps und dem Ende der Linie.
### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


Legt den Abstand zwischen der Kappe und der Linie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Der Abstand zwischen dem Anfang des Caps und dem Ende der Linie. |

### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


Ruft den Betrag ab, um den dieses `CustomLineCap`-Klassenobjekt in Bezug auf die Breite des `System.Drawing.Pen`-Objekts skaliert wird.

**Returns:**
float - Der Betrag, um den das Cap skaliert wird.
### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


Legt den Betrag fest, um den dieses `CustomLineCap`-Klassenobjekt in Bezug auf die Breite des `System.Drawing.Pen`-Objekts skaliert wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Der Betrag, um den das Cap skaliert wird. |

### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public void setStrokeCaps(int startCap, int endCap)
```


Legt die Kappen fest, die zum Starten und Beenden von Linien verwendet werden, aus denen diese benutzerdefinierte Kappe besteht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startCap | int | Die `LineCap`-Aufzählung, die am Anfang einer Linie innerhalb dieses Caps verwendet wird. |
| endCap | int | Die `LineCap`-Aufzählung, die am Ende einer Linie innerhalb dieses Caps verwendet wird. |

### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public void getStrokeCaps(int[] startCap, int[] endCap)
```


Ruft die Kappen ab, die zum Starten und Beenden von Linien verwendet werden, aus denen diese benutzerdefinierte Kappe besteht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startCap | int[] | Die `LineCap`-Aufzählung, die am Anfang einer Linie innerhalb dieses Caps verwendet wird. |
| endCap | int[] | Die `LineCap`-Aufzählung, die am Ende einer Linie innerhalb dieses Caps verwendet wird. |

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
