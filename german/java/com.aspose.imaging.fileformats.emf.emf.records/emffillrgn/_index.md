---
title: "EmfFillRgn"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_FILLRGN‑Datensatz füllt die angegebene Region mithilfe des angegebenen Pinsels."
type: docs
weight: 59
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emffillrgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfFillRgn extends EmfDrawingRecordType
```

Der EMR\_FILLRGN-Datensatz füllt die angegebene Region mithilfe des angegebenen Pinsels.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfFillRgn(EmfRecord source)](#EmfFillRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der Klasse `EmfFillRgn`. |
| [EmfFillRgn()](#EmfFillRgn--) | Initialisiert eine neue Instanz der Klasse `EmfFillRgn`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBounds()](#getBounds--) | Liest oder setzt ein 128‑Bit‑WMF RectL-Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.19, das das Begrenzungsrechteck angibt. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Liest oder setzt ein 128‑Bit‑WMF RectL-Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.19, das das Begrenzungsrechteck angibt. |
| [getRgnDataSize()](#getRgnDataSize--) | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Größe der Regionsdaten in Bytes angibt. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Größe der Regionsdaten in Bytes angibt. |
| [getIhBrush()](#getIhBrush--) | Liest oder legt eine 32‑Bit‑vorzeichenlose Ganzzahl fest, die den EMF‑Objekttabellen‑Index des Pinsels zum Füllen der Region angibt. |
| [setIhBrush(int value)](#setIhBrush-int-) | Liest oder legt eine 32‑Bit‑vorzeichenlose Ganzzahl fest, die den EMF‑Objekttabellen‑Index des Pinsels zum Füllen der Region angibt. |
| [getRgnData()](#getRgnData--) | Liest oder legt ein RgnDataSize‑Längen-Array von Bytes fest, das ein RegionData‑Objekt (Abschnitt 2.2.24) enthält. |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Liest oder legt ein RgnDataSize‑Längen-Array von Bytes fest, das ein RegionData‑Objekt (Abschnitt 2.2.24) enthält. |
### EmfFillRgn(EmfRecord source) {#EmfFillRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfFillRgn(EmfRecord source)
```


Initialisiert eine neue Instanz der Klasse `EmfFillRgn`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfFillRgn() {#EmfFillRgn--}
```
public EmfFillRgn()
```


Initialisiert eine neue Instanz der Klasse `EmfFillRgn`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Liest oder setzt ein 128‑Bit‑WMF RectL-Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.19, das das Begrenzungsrechteck angibt.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Liest oder setzt ein 128‑Bit‑WMF RectL-Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.19, das das Begrenzungsrechteck angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Größe der Regionsdaten in Bytes angibt.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Größe der Regionsdaten in Bytes angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Liest oder legt eine 32‑Bit‑vorzeichenlose Ganzzahl fest, die den EMF‑Objekttabellen‑Index des Pinsels zum Füllen der Region angibt.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Liest oder legt eine 32‑Bit‑vorzeichenlose Ganzzahl fest, die den EMF‑Objekttabellen‑Index des Pinsels zum Füllen der Region angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Liest oder legt ein RgnDataSize‑Längen-Array von Bytes fest, das ein RegionData‑Objekt (Abschnitt 2.2.24) enthält.

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Liest oder legt ein RgnDataSize‑Längen-Array von Bytes fest, das ein RegionData‑Objekt (Abschnitt 2.2.24) enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

