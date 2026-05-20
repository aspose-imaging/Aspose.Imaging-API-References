---
title: "EmfLogBrushEx"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das LogBrushEx-Objekt definiert die Stilfarbe und das Muster eines geräteunabhängigen Pinsels."
type: docs
weight: 21
url: /de/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfLogBrushEx extends EmfObject
```

Das LogBrushEx‑Objekt definiert Stil, Farbe und Muster eines geräteunabhängigen Pinsels.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfLogBrushEx()](#EmfLogBrushEx--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBrushStyle()](#getBrushStyle--) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Pinselstil angibt. |
| [setBrushStyle(int value)](#setBrushStyle-int-) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Pinselstil angibt. |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | Ruft ein 32‑Bit‑WMF‑ColorRef‑Objekt ([MS-WMF] Abschnitt 2.2.2.8) ab oder legt es fest, das eine Farbe angibt. |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | Ruft ein 32‑Bit‑WMF‑ColorRef‑Objekt ([MS-WMF] Abschnitt 2.2.2.8) ab oder legt es fest, das eine Farbe angibt. |
| [getBrushHatch()](#getBrushHatch--) | Ruft ein 32‑Bit‑vorzeichenloses Feld ab oder legt es fest, das die Pinsel‑Schraffurdaten enthält. |
| [setBrushHatch(int value)](#setBrushHatch-int-) | Ruft ein 32‑Bit‑vorzeichenloses Feld ab oder legt es fest, das die Pinsel‑Schraffurdaten enthält. |
### EmfLogBrushEx() {#EmfLogBrushEx--}
```
public EmfLogBrushEx()
```


### getBrushStyle() {#getBrushStyle--}
```
public int getBrushStyle()
```


Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Pinselstil angibt. Der Wert MUSS eine Aufzählung aus der WMF‑BrushStyle‑Aufzählung ([MS-WMF] Abschnitt 2.1.1.4) sein. Die Stilwerte, die in dieser Struktur unterstützt werden, sind später in diesem Abschnitt aufgeführt. Der BS\_NULL‑Stil SOLLTE verwendet werden, um einen Pinsel zu spezifizieren, der keine Wirkung hat.

**Returns:**
int
### setBrushStyle(int value) {#setBrushStyle-int-}
```
public void setBrushStyle(int value)
```


Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Pinselstil angibt. Der Wert MUSS eine Aufzählung aus der WMF‑BrushStyle‑Aufzählung ([MS-WMF] Abschnitt 2.1.1.4) sein. Die Stilwerte, die in dieser Struktur unterstützt werden, sind später in diesem Abschnitt aufgeführt. Der BS\_NULL‑Stil SOLLTE verwendet werden, um einen Pinsel zu spezifizieren, der keine Wirkung hat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


Ruft ein 32‑Bit‑WMF‑ColorRef‑Objekt ([MS-WMF] Abschnitt 2.2.2.8) ab oder legt es fest, das eine Farbe angibt. Die Interpretation dieses Feldes hängt vom Wert von BrushStyle ab, wie in der folgenden Tabelle erläutert.

Wert: Die 32‑Bit‑ARGB‑Farbe

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


Ruft ein 32‑Bit‑WMF‑ColorRef‑Objekt ([MS-WMF] Abschnitt 2.2.2.8) ab oder legt es fest, das eine Farbe angibt. Die Interpretation dieses Feldes hängt vom Wert von BrushStyle ab, wie in der folgenden Tabelle erläutert.

Wert: Die 32‑Bit‑ARGB‑Farbe

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getBrushHatch() {#getBrushHatch--}
```
public int getBrushHatch()
```


Ruft ein 32‑Bit‑vorzeichenloses Feld ab oder legt es fest, das die Pinsel‑Schraffurdaten enthält. Seine Interpretation hängt vom Wert von BrushStyle ab,

**Returns:**
int
### setBrushHatch(int value) {#setBrushHatch-int-}
```
public void setBrushHatch(int value)
```


Ruft ein 32‑Bit‑vorzeichenloses Feld ab oder legt es fest, das die Pinsel‑Schraffurdaten enthält. Seine Interpretation hängt vom Wert von BrushStyle ab,

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

