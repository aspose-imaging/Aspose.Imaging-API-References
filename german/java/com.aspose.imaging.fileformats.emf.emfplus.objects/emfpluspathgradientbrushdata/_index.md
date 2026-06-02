---
title: "EmfPlusPathGradientBrushData"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmfPlusPathGradientBrushData-Objekt gibt einen Pfadverlauf für einen Grafik-Pinsel an."
type: docs
weight: 59
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusPathGradientBrushData extends EmfPlusBaseBrushData
```

Das EmfPlusPathGradientBrushData-Objekt gibt einen Pfadverlauf für einen Grafik-Pinsel an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusPathGradientBrushData()](#EmfPlusPathGradientBrushData--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBrushDataFlags()](#getBrushDataFlags--) | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der die Daten im Feld OptionalData angibt. |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der die Daten im Feld OptionalData angibt. |
| [getWrapMode()](#getWrapMode--) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer aus der Aufzählung WrapMode (Abschnitt 2.1.1.34), der angibt, ob der Bereich außerhalb der Pinselgrenze gemalt werden soll. |
| [setWrapMode(int value)](#setWrapMode-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer aus der Aufzählung WrapMode (Abschnitt 2.1.1.34), der angibt, ob der Bereich außerhalb der Pinselgrenze gemalt werden soll. |
| [getCenterArgb32Color()](#getCenterArgb32Color--) | Liest oder legt fest EmfPlusARGB-Objekt (Abschnitt 2.2.2.1), das die Mittelwertfarbe des Pfadverlaufspinsels angibt, also die Farbe, die am Mittelpunkt des Pinsels erscheint. |
| [setCenterArgb32Color(int value)](#setCenterArgb32Color-int-) | Liest oder legt fest EmfPlusARGB-Objekt (Abschnitt 2.2.2.1), das die Mittelwertfarbe des Pfadverlaufspinsels angibt, also die Farbe, die am Mittelpunkt des Pinsels erscheint. |
| [getCenterPointF()](#getCenterPointF--) | Liest oder legt fest EmfPlusARGB-Objekt (Abschnitt 2.2.2.1), das die Mittelwertfarbe des Pfadverlaufspinsels angibt, also die Farbe, die am Mittelpunkt des Pinsels erscheint. |
| [setCenterPointF(PointF value)](#setCenterPointF-com.aspose.imaging.PointF-) | Liest oder legt fest EmfPlusARGB-Objekt (Abschnitt 2.2.2.1), das die Mittelwertfarbe des Pfadverlaufspinsels angibt, also die Farbe, die am Mittelpunkt des Pinsels erscheint. |
| [getSurroundingArgb32Colors()](#getSurroundingArgb32Colors--) | Liest oder legt fest ein Array von SurroundingColorCount EmfPlusARGB-Objekten, die die Farben für diskrete Punkte auf der Begrenzung des Pinsels angeben. |
| [setSurroundingArgb32Colors(int[] value)](#setSurroundingArgb32Colors-int---) | Liest oder legt fest ein Array von SurroundingColorCount EmfPlusARGB-Objekten, die die Farben für diskrete Punkte auf der Begrenzung des Pinsels angeben. |
| [getBoundaryData()](#getBoundaryData--) | Liest oder legt fest die Begrenzung des Pfadverlaufspinsels, die entweder durch einen Pfad oder eine geschlossene kardinale Spline angegeben wird. |
| [setBoundaryData(EmfPlusBoundaryBase value)](#setBoundaryData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBoundaryBase-) | Liest oder legt fest die Begrenzung des Pfadverlaufspinsels, die entweder durch einen Pfad oder eine geschlossene kardinale Spline angegeben wird. |
| [getOptionalData()](#getOptionalData--) | Liest oder legt fest ein optionales EmfPlusPathGradientBrushOptionalData-Objekt (Abschnitt 2.2.2.30), das zusätzliche Daten für den Pfadverlaufspinsel angibt. |
| [setOptionalData(EmfPlusPathGradientBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData-) | Liest oder legt fest ein optionales EmfPlusPathGradientBrushOptionalData-Objekt (Abschnitt 2.2.2.30), das zusätzliche Daten für den Pfadverlaufspinsel angibt. |
### EmfPlusPathGradientBrushData() {#EmfPlusPathGradientBrushData--}
```
public EmfPlusPathGradientBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


Liest oder legt fest 32‑Bit‑vorzeichenlose Ganzzahl, die die Daten im OptionalData‑Feld angibt. Dieser Wert MUSS aus BrushData‑Flags (Abschnitt 2.1.2.1) bestehen. Die folgenden Flags sind für einen Pfadverlaufspinsel relevant:

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


Liest oder legt fest 32‑Bit‑vorzeichenlose Ganzzahl, die die Daten im OptionalData‑Feld angibt. Dieser Wert MUSS aus BrushData‑Flags (Abschnitt 2.1.2.1) bestehen. Die folgenden Flags sind für einen Pfadverlaufspinsel relevant:

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Liest oder legt fest 32‑Bit‑vorzeichenbehaftete Ganzzahl aus der WrapMode‑Aufzählung (Abschnitt 2.1.1.34), die angibt, ob der Bereich außerhalb der Begrenzung des Pinsels gemalt werden soll. Beim Malen außerhalb der Begrenzung gibt der Wrap‑Modus an, wie der Farbverlauf wiederholt wird.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Liest oder legt fest 32‑Bit‑vorzeichenbehaftete Ganzzahl aus der WrapMode‑Aufzählung (Abschnitt 2.1.1.34), die angibt, ob der Bereich außerhalb der Begrenzung des Pinsels gemalt werden soll. Beim Malen außerhalb der Begrenzung gibt der Wrap‑Modus an, wie der Farbverlauf wiederholt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCenterArgb32Color() {#getCenterArgb32Color--}
```
public int getCenterArgb32Color()
```


Liest oder legt fest EmfPlusARGB-Objekt (Abschnitt 2.2.2.1), das die Mittelwertfarbe des Pfadverlaufspinsels angibt, also die Farbe, die am Mittelpunkt des Pinsels erscheint. Die Farbe des Pinsels ändert sich allmählich von der Randfarbe zur Mittelwertfarbe, wenn sie vom Rand zum Mittelpunkt verläuft.

**Returns:**
int
### setCenterArgb32Color(int value) {#setCenterArgb32Color-int-}
```
public void setCenterArgb32Color(int value)
```


Liest oder legt fest EmfPlusARGB-Objekt (Abschnitt 2.2.2.1), das die Mittelwertfarbe des Pfadverlaufspinsels angibt, also die Farbe, die am Mittelpunkt des Pinsels erscheint. Die Farbe des Pinsels ändert sich allmählich von der Randfarbe zur Mittelwertfarbe, wenn sie vom Rand zum Mittelpunkt verläuft.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCenterPointF() {#getCenterPointF--}
```
public PointF getCenterPointF()
```


Liest oder legt fest EmfPlusARGB-Objekt (Abschnitt 2.2.2.1), das die Mittelwertfarbe des Pfadverlaufspinsels angibt, also die Farbe, die am Mittelpunkt des Pinsels erscheint. Die Farbe des Pinsels ändert sich allmählich von der Randfarbe zur Mittelwertfarbe, wenn sie vom Rand zum Mittelpunkt verläuft.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setCenterPointF(PointF value) {#setCenterPointF-com.aspose.imaging.PointF-}
```
public void setCenterPointF(PointF value)
```


Liest oder legt fest EmfPlusARGB-Objekt (Abschnitt 2.2.2.1), das die Mittelwertfarbe des Pfadverlaufspinsels angibt, also die Farbe, die am Mittelpunkt des Pinsels erscheint. Die Farbe des Pinsels ändert sich allmählich von der Randfarbe zur Mittelwertfarbe, wenn sie vom Rand zum Mittelpunkt verläuft.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getSurroundingArgb32Colors() {#getSurroundingArgb32Colors--}
```
public int[] getSurroundingArgb32Colors()
```


Liest oder legt fest ein Array von SurroundingColorCount EmfPlusARGB-Objekten, die die Farben für diskrete Punkte auf der Begrenzung des Pinsels angeben.

**Returns:**
int[]
### setSurroundingArgb32Colors(int[] value) {#setSurroundingArgb32Colors-int---}
```
public void setSurroundingArgb32Colors(int[] value)
```


Liest oder legt fest ein Array von SurroundingColorCount EmfPlusARGB-Objekten, die die Farben für diskrete Punkte auf der Begrenzung des Pinsels angeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] |  |

### getBoundaryData() {#getBoundaryData--}
```
public EmfPlusBoundaryBase getBoundaryData()
```


Liest oder legt fest die Begrenzung des Pfadverlaufspinsels, die entweder durch einen Pfad oder eine geschlossene kardinale Spline angegeben wird. Ist das BrushDataPath‑Flag im Feld BrushDataFlags gesetzt, MUSS dieses Feld ein EmfPlusBoundaryPathData‑Objekt (Abschnitt 2.2.2.6) enthalten; andernfalls MUSS dieses Feld ein EmfPlusBoundaryPointData‑Objekt (Abschnitt 2.2.2.7) enthalten.

**Returns:**
[EmfPlusBoundaryBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase)
### setBoundaryData(EmfPlusBoundaryBase value) {#setBoundaryData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBoundaryBase-}
```
public void setBoundaryData(EmfPlusBoundaryBase value)
```


Liest oder legt fest die Begrenzung des Pfadverlaufspinsels, die entweder durch einen Pfad oder eine geschlossene kardinale Spline angegeben wird. Ist das BrushDataPath‑Flag im Feld BrushDataFlags gesetzt, MUSS dieses Feld ein EmfPlusBoundaryPathData‑Objekt (Abschnitt 2.2.2.6) enthalten; andernfalls MUSS dieses Feld ein EmfPlusBoundaryPointData‑Objekt (Abschnitt 2.2.2.7) enthalten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusBoundaryBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase) |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusPathGradientBrushOptionalData getOptionalData()
```


Liest oder legt fest ein optionales EmfPlusPathGradientBrushOptionalData‑Objekt (Abschnitt 2.2.2.30), das zusätzliche Daten für den Pfadverlaufspinsel angibt. Der genaue Inhalt dieses Feldes wird durch den Wert des Feldes BrushDataFlags bestimmt.

**Returns:**
[EmfPlusPathGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata)
### setOptionalData(EmfPlusPathGradientBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData-}
```
public void setOptionalData(EmfPlusPathGradientBrushOptionalData value)
```


Liest oder legt fest ein optionales EmfPlusPathGradientBrushOptionalData‑Objekt (Abschnitt 2.2.2.30), das zusätzliche Daten für den Pfadverlaufspinsel angibt. Der genaue Inhalt dieses Feldes wird durch den Wert des Feldes BrushDataFlags bestimmt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusPathGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata) |  |

