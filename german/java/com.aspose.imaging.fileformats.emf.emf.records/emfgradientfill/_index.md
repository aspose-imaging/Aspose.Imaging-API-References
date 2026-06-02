---
title: "EmfGradientFill"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_GRADIENTFILL-Datensatz definiert das Füllen von Rechtecken oder Dreiecken mit Farbverläufen."
type: docs
weight: 65
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfgradientfill/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfGradientFill extends EmfDrawingRecordType
```

Der EMR\_GRADIENTFILL-Datensatz gibt das Füllen von Rechtecken oder Dreiecken mit Farbverläufen an.

Ein EMR_GRADIENTFILL-Datensatz, der festlegt, dass die drei Scheitelpunkte eines Dreiecks die Figur mit sanften Farbverläufen füllen SOLLTEN.[85] Ein EMR_GRADIENTFILL-Datensatz, der festlegt, dass die oberen linken und unteren rechten Scheitelpunkte eines Rechtecks die Figur mit sanften Farbverläufen füllen SOLLTEN. Es gibt zwei Farbverlauf‑Füllmodi in der GradientFill‑Aufzählung, die beim Zeichnen eines Rechtecks verwendet werden können. Im Modus GRADIENT_FILL_RECT_H wird das Rechteck von links nach rechts gefüllt. Im Modus GRADIENT_FILL_RECT_V wird das Rechteck von oben nach unten gefüllt. Hinweis: Ein EMR_GRADIENTFILL-Datensatz MUSS die Alpha‑Felder in den TriVertex‑Objekten ignorieren. Ein EMR_ALPHABLEND-Datensatz (Abschnitt 2.3.1.1), der unmittelbar auf den EMR_GRADIENTFILL-Datensatz folgt, kann verwendet werden, um einen Alpha‑Transparenz‑Verlauf auf den gefüllten Bereich anzuwenden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfGradientFill(EmfRecord source)](#EmfGradientFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfGradientFill`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBounds()](#getBounds--) | Liest oder setzt ein WMF RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19), das ein Begrenzungsrechteck in inklusiven Geräteeinheiten angibt. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Liest oder setzt ein WMF RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19), das ein Begrenzungsrechteck in inklusiven Geräteeinheiten angibt. |
| [getNVer()](#getNVer--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Anzahl der Scheitelpunkte angibt. |
| [setNVer(int value)](#setNVer-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Anzahl der Scheitelpunkte angibt. |
| [getNTri()](#getNTri--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Anzahl der zu füllenden Rechtecke oder Dreiecke angibt. |
| [setNTri(int value)](#setNTri-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Anzahl der zu füllenden Rechtecke oder Dreiecke angibt. |
| [getUlMode()](#getUlMode--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Farbverlauf‑Füllmodus angibt. |
| [setUlMode(int value)](#setUlMode-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Farbverlauf‑Füllmodus angibt. |
| [getVertexData()](#getVertexData--) | Ruft Objekte ab oder legt sie fest, die die Scheitelpunkte von Rechtecken oder Dreiecken angeben und die zugehörigen Farben. |
| [setVertexData(EmfVertexData value)](#setVertexData-com.aspose.imaging.fileformats.emf.emf.records.EmfVertexData-) | Ruft Objekte ab oder legt sie fest, die die Scheitelpunkte von Rechtecken oder Dreiecken angeben und die zugehörigen Farben. |
### EmfGradientFill(EmfRecord source) {#EmfGradientFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfGradientFill(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfGradientFill`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Liest oder setzt ein WMF RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19), das ein Begrenzungsrechteck in inklusiven Geräteeinheiten angibt.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Liest oder setzt ein WMF RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19), das ein Begrenzungsrechteck in inklusiven Geräteeinheiten angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getNVer() {#getNVer--}
```
public int getNVer()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Anzahl der Scheitelpunkte angibt.

**Returns:**
int
### setNVer(int value) {#setNVer-int-}
```
public void setNVer(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Anzahl der Scheitelpunkte angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getNTri() {#getNTri--}
```
public int getNTri()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Anzahl der zu füllenden Rechtecke oder Dreiecke angibt.

**Returns:**
int
### setNTri(int value) {#setNTri-int-}
```
public void setNTri(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Anzahl der zu füllenden Rechtecke oder Dreiecke angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getUlMode() {#getUlMode--}
```
public int getUlMode()
```


Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Gradient‑Füllmodus angibt. Der Wert MUSS in der GradientFill‑Aufzählung (Abschnitt 2.1.15) liegen.

**Returns:**
int
### setUlMode(int value) {#setUlMode-int-}
```
public void setUlMode(int value)
```


Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Gradient‑Füllmodus angibt. Der Wert MUSS in der GradientFill‑Aufzählung (Abschnitt 2.1.15) liegen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getVertexData() {#getVertexData--}
```
public EmfVertexData getVertexData()
```


Ruft Objekte ab oder legt sie fest, die die Scheitelpunkte von Rechtecken oder Dreiecken angeben und die zugehörigen Farben.

**Returns:**
[EmfVertexData](../../com.aspose.imaging.fileformats.emf.emf.records/emfvertexdata)
### setVertexData(EmfVertexData value) {#setVertexData-com.aspose.imaging.fileformats.emf.emf.records.EmfVertexData-}
```
public void setVertexData(EmfVertexData value)
```


Ruft Objekte ab oder legt sie fest, die die Scheitelpunkte von Rechtecken oder Dreiecken angeben und die zugehörigen Farben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfVertexData](../../com.aspose.imaging.fileformats.emf.emf.records/emfvertexdata) |  |

