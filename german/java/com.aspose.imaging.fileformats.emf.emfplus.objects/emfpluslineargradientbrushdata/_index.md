---
title: "EmfPlusLinearGradientBrushData"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmfPlusLinearGradientBrushData-Objekt gibt einen linearen Farbverlauf für einen Grafik-Pinsel an."
type: docs
weight: 53
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusLinearGradientBrushData extends EmfPlusBaseBrushData
```

Das EmfPlusLinearGradientBrushData-Objekt gibt einen linearen Farbverlauf für einen Grafik-Pinsel an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusLinearGradientBrushData()](#EmfPlusLinearGradientBrushData--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBrushDataFlags()](#getBrushDataFlags--) | Liest oder setzt die BrushData‑Flags. |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | Liest oder setzt die BrushData‑Flags. |
| [getEndArgb32Color()](#getEndArgb32Color--) | Liest oder setzt die Endfarbe. |
| [setEndArgb32Color(int value)](#setEndArgb32Color-int-) | Liest oder setzt die Endfarbe. |
| [getOptionalData()](#getOptionalData--) | Liest oder setzt die optionalen Daten. |
| [setOptionalData(EmfPlusLinearGradientBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData-) | Liest oder setzt die optionalen Daten. |
| [getRectF()](#getRectF--) | Liest oder setzt das RectF. |
| [setRectF(RectangleF value)](#setRectF-com.aspose.imaging.RectangleF-) | Liest oder setzt das RectF. |
| [getStartArgb32Color()](#getStartArgb32Color--) | Liest oder setzt die Startfarbe. |
| [setStartArgb32Color(int value)](#setStartArgb32Color-int-) | Liest oder setzt die Startfarbe. |
| [getWrapMode()](#getWrapMode--) | Liest oder setzt den Wrap-Modus. |
| [setWrapMode(int value)](#setWrapMode-int-) | Liest oder setzt den Wrap-Modus. |
### EmfPlusLinearGradientBrushData() {#EmfPlusLinearGradientBrushData--}
```
public EmfPlusLinearGradientBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


Liest oder setzt die BrushData‑Flags.

Wert: BrushDataFlags (4 Bytes): Ein 32‑Bit‑vorzeichenloser Integer, der die Daten im Feld OptionalData angibt. Dieser Wert MUSS aus `EmfPlusBrushDataFlags` (Abschnitt 2.1.2.1) zusammengesetzt sein.

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


Liest oder setzt die BrushData‑Flags.

Wert: BrushDataFlags (4 Bytes): Ein 32‑Bit‑vorzeichenloser Integer, der die Daten im Feld OptionalData angibt. Dieser Wert MUSS aus `EmfPlusBrushDataFlags` (Abschnitt 2.1.2.1) zusammengesetzt sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getEndArgb32Color() {#getEndArgb32Color--}
```
public int getEndArgb32Color()
```


Liest oder setzt die Endfarbe.

Wert: Ein EmfPlusARGB‑Objekt, das die Farbe am Endgrenzpunkt des linearen Verlaufs‑Pinsels angibt.

**Returns:**
int
### setEndArgb32Color(int value) {#setEndArgb32Color-int-}
```
public void setEndArgb32Color(int value)
```


Liest oder setzt die Endfarbe.

Wert: Ein EmfPlusARGB‑Objekt, das die Farbe am Endgrenzpunkt des linearen Verlaufs‑Pinsels angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusLinearGradientBrushOptionalData getOptionalData()
```


Liest oder setzt die optionalen Daten.

Wert: Ein optionales `EmfPlusLinearGradientBrushOptionalData`‑Objekt (Abschnitt 2.2.2.25), das zusätzliche Daten für den linearen Verlaufs‑Pinsel angibt. Der genaue Inhalt dieses Feldes wird durch den Wert des Feldes BrushDataFlags bestimmt.

**Returns:**
[EmfPlusLinearGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata)
### setOptionalData(EmfPlusLinearGradientBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData-}
```
public void setOptionalData(EmfPlusLinearGradientBrushOptionalData value)
```


Liest oder setzt die optionalen Daten.

Wert: Ein optionales `EmfPlusLinearGradientBrushOptionalData`‑Objekt (Abschnitt 2.2.2.25), das zusätzliche Daten für den linearen Verlaufs‑Pinsel angibt. Der genaue Inhalt dieses Feldes wird durch den Wert des Feldes BrushDataFlags bestimmt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusLinearGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata) |  |

### getRectF() {#getRectF--}
```
public RectangleF getRectF()
```


Liest oder setzt das RectF.

Wert: Ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39), das die Start‑ und Endpunkte der Verlaufs­linie angibt. Die obere linke Ecke des Rechtecks ist der Startpunkt. Die untere rechte Ecke ist der Endpunkt.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectF(RectangleF value) {#setRectF-com.aspose.imaging.RectangleF-}
```
public void setRectF(RectangleF value)
```


Liest oder setzt das RectF.

Wert: Ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39), das die Start‑ und Endpunkte der Verlaufs­linie angibt. Die obere linke Ecke des Rechtecks ist der Startpunkt. Die untere rechte Ecke ist der Endpunkt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getStartArgb32Color() {#getStartArgb32Color--}
```
public int getStartArgb32Color()
```


Liest oder setzt die Startfarbe.

Wert: Ein EmfPlusARGB‑Objekt (Abschnitt 2.2.2.1), das die Farbe am Startgrenzpunkt des linearen Verlaufs‑Pinsels angibt.

**Returns:**
int
### setStartArgb32Color(int value) {#setStartArgb32Color-int-}
```
public void setStartArgb32Color(int value)
```


Liest oder setzt die Startfarbe.

Wert: Ein EmfPlusARGB‑Objekt (Abschnitt 2.2.2.1), das die Farbe am Startgrenzpunkt des linearen Verlaufs‑Pinsels angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Liest oder setzt den Wrap-Modus.

Wert: Ein 32‑Bit‑vorzeichenbehafteter Integer aus der Aufzählung WrapMode (Abschnitt 2.1.1.34), der angibt, ob der Bereich außerhalb der Pinselgrenze gemalt werden soll. Beim Malen außerhalb der Grenze gibt der Wrap‑Modus an, wie der Farbverlauf wiederholt wird.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Liest oder setzt den Wrap-Modus.

Wert: Ein 32‑Bit‑vorzeichenbehafteter Integer aus der Aufzählung WrapMode (Abschnitt 2.1.1.34), der angibt, ob der Bereich außerhalb der Pinselgrenze gemalt werden soll. Beim Malen außerhalb der Grenze gibt der Wrap‑Modus an, wie der Farbverlauf wiederholt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

