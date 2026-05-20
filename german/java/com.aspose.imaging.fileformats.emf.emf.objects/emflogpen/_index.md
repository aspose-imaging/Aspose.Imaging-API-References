---
title: "EmfLogPen"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das LogPen‑Objekt definiert die Stilbreite und Farbe eines logischen Stifts."
type: docs
weight: 27
url: /de/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogpen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfBasePen](../../com.aspose.imaging.fileformats.emf.emf.objects/emfbasepen)
```
public final class EmfLogPen extends EmfBasePen
```

Das LogPen‑Objekt definiert Stil, Breite und Farbe eines logischen Pens.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfLogPen()](#EmfLogPen--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPenStyle()](#getPenStyle--) | Liefert oder legt eine 32‑Bit‑vorzeichenlose Ganzzahl fest, die den PenStyle angibt. |
| [setPenStyle(int value)](#setPenStyle-int-) | Liefert oder legt eine 32‑Bit‑vorzeichenlose Ganzzahl fest, die den PenStyle angibt. |
| [getWidth()](#getWidth--) | Liefert oder legt ein WMF‑PointL‑Objekt ([MS-WMF] Abschnitt 2.2.2.15) fest, das die Breite des Stifts anhand des Werts seines x‑Feldes angibt. |
| [setWidth(Point value)](#setWidth-com.aspose.imaging.Point-) | Liefert oder legt ein WMF‑PointL‑Objekt ([MS-WMF] Abschnitt 2.2.2.15) fest, das die Breite des Stifts anhand des Werts seines x‑Feldes angibt. |
| [getAffectWidth()](#getAffectWidth--) | Liefert oder legt die Breite des Effekts fest. |
| [setAffectWidth(int value)](#setAffectWidth-int-) | Liefert oder legt die Breite des Effekts fest. |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | Liefert oder legt ein WMF‑ColorRef‑Objekt ([MS-WMF] Abschnitt 2.2.2.8) fest, das den Stiftfarbwert angibt. |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | Liefert oder legt ein WMF‑ColorRef‑Objekt ([MS-WMF] Abschnitt 2.2.2.8) fest, das den Stiftfarbwert angibt. |
### EmfLogPen() {#EmfLogPen--}
```
public EmfLogPen()
```


### getPenStyle() {#getPenStyle--}
```
public int getPenStyle()
```


Liefert oder legt eine 32‑Bit‑vorzeichenlose Ganzzahl fest, die den PenStyle angibt. Der Wert MUSS aus der PenStyle‑Aufzählungstabelle stammen, die in Abschnitt 2.1.25 angegeben ist.

**Returns:**
int
### setPenStyle(int value) {#setPenStyle-int-}
```
public void setPenStyle(int value)
```


Liefert oder legt eine 32‑Bit‑vorzeichenlose Ganzzahl fest, die den PenStyle angibt. Der Wert MUSS aus der PenStyle‑Aufzählungstabelle stammen, die in Abschnitt 2.1.25 angegeben ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getWidth() {#getWidth--}
```
public Point getWidth()
```


Liefert oder legt ein WMF‑PointL‑Objekt ([MS-WMF] Abschnitt 2.2.2.15) fest, das die Breite des Stifts anhand des Werts seines x‑Feldes angibt. Der Wert seines y‑Feldes MUSS ignoriert werden.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setWidth(Point value) {#setWidth-com.aspose.imaging.Point-}
```
public void setWidth(Point value)
```


Liefert oder legt ein WMF‑PointL‑Objekt ([MS-WMF] Abschnitt 2.2.2.15) fest, das die Breite des Stifts anhand des Werts seines x‑Feldes angibt. Der Wert seines y‑Feldes MUSS ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getAffectWidth() {#getAffectWidth--}
```
public int getAffectWidth()
```


Liefert oder legt die Breite des Effekts fest.

Wert: Die Breite des Effekts.

**Returns:**
int
### setAffectWidth(int value) {#setAffectWidth-int-}
```
public void setAffectWidth(int value)
```


Liefert oder legt die Breite des Effekts fest.

Wert: Die Breite des Effekts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


Liefert oder legt ein WMF‑ColorRef‑Objekt ([MS-WMF] Abschnitt 2.2.2.8) fest, das den Stiftfarbwert angibt.

Wert: Die 32‑Bit‑ARGB‑Farbe

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


Liefert oder legt ein WMF‑ColorRef‑Objekt ([MS-WMF] Abschnitt 2.2.2.8) fest, das den Stiftfarbwert angibt.

Wert: Die 32‑Bit‑ARGB‑Farbe

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

