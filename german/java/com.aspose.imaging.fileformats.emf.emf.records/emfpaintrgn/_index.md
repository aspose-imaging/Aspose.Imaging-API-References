---
title: "EmfPaintRgn"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_PAINTRGN‑Datensatz malt den angegebenen Bereich, indem er den aktuell im Wiedergabegeräte‑Kontext ausgewählten Pinsel verwendet."
type: docs
weight: 80
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPaintRgn extends EmfDrawingRecordType
```

Der EMR\\_PAINTRGN-Datensatz malt die angegebene Region, indem er den aktuell im Wiedergabegeräte-Kontext ausgewählten Pinsel verwendet.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPaintRgn(EmfRecord source)](#EmfPaintRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfPaintRgn`‑Klasse. |
| [EmfPaintRgn()](#EmfPaintRgn--) | Initialisiert eine neue Instanz der `EmfPaintRgn`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBounds()](#getBounds--) | Liest ein 128‑Bit‑WMF‑RectL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.19, das das Begrenzungsrechteck angibt. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Schreibt ein 128‑Bit‑WMF‑RectL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.19, das das Begrenzungsrechteck angibt. |
| [getRgnDataSize()](#getRgnDataSize--) | Liest eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe der Regionsdaten in Bytes angibt. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Schreibt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe der Regionsdaten in Bytes angibt. |
| [getRgnData()](#getRgnData--) | Liest ein Byte‑Array der Länge RgnDataSize, das ein RegionData‑Objekt (Abschnitt 2.2.24) in logischen Einheiten angibt. |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Schreibt ein Byte‑Array der Länge RgnDataSize, das ein RegionData‑Objekt (Abschnitt 2.2.24) in logischen Einheiten angibt. |
### EmfPaintRgn(EmfRecord source) {#EmfPaintRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPaintRgn(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfPaintRgn`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfPaintRgn() {#EmfPaintRgn--}
```
public EmfPaintRgn()
```


Initialisiert eine neue Instanz der `EmfPaintRgn`‑Klasse.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Liest ein 128‑Bit‑WMF‑RectL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.19, das das Begrenzungsrechteck angibt.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Schreibt ein 128‑Bit‑WMF‑RectL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.19, das das Begrenzungsrechteck angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


Liest eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe der Regionsdaten in Bytes angibt.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


Schreibt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe der Regionsdaten in Bytes angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Liest ein Byte‑Array der Länge RgnDataSize, das ein RegionData‑Objekt (Abschnitt 2.2.24) in logischen Einheiten angibt.

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Schreibt ein Byte‑Array der Länge RgnDataSize, das ein RegionData‑Objekt (Abschnitt 2.2.24) in logischen Einheiten angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

