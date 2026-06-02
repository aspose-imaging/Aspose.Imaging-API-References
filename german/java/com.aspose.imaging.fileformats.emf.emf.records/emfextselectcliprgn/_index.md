---
title: "EmfExtSelectClipRgn"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_EXTSELECTCLIPRGN-Datensatz kombiniert die angegebene Region mit der aktuellen Clip-Region unter Verwendung des angegebenen Modus."
type: docs
weight: 55
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfExtSelectClipRgn extends EmfClippingRecordType
```

Der EMR\_EXTSELECTCLIPRGN-Datensatz kombiniert die angegebene Region mit der aktuellen Clip-Region unter Verwendung des angegebenen Modus. Hinweis: Felder, die in diesem Abschnitt nicht beschrieben werden, sind in Abschnitt 2.3.2 angegeben.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfExtSelectClipRgn(EmfRecord source)](#EmfExtSelectClipRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfExtSelectClipRgn`-Klasse. |
| [EmfExtSelectClipRgn()](#EmfExtSelectClipRgn--) | Initialisiert eine neue Instanz der `EmfExtSelectClipRgn`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRgnDataSize()](#getRgnDataSize--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe der Regionsdaten in Bytes angibt. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe der Regionsdaten in Bytes angibt. |
| [getRegionMode()](#getRegionMode--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Art der Verwendung der Region angibt. |
| [setRegionMode(int value)](#setRegionMode-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Art der Verwendung der Region angibt. |
| [getRgnData()](#getRgnData--) | Liest oder setzt ein Byte‑Array der Länge RgnDataSize, das ein RegionData‑Objekt in logischen Einheiten angibt. |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Liest oder setzt ein Byte‑Array der Länge RgnDataSize, das ein RegionData‑Objekt in logischen Einheiten angibt. |
### EmfExtSelectClipRgn(EmfRecord source) {#EmfExtSelectClipRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtSelectClipRgn(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfExtSelectClipRgn`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfExtSelectClipRgn() {#EmfExtSelectClipRgn--}
```
public EmfExtSelectClipRgn()
```


Initialisiert eine neue Instanz der `EmfExtSelectClipRgn`-Klasse.

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe der Regionsdaten in Bytes angibt.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe der Regionsdaten in Bytes angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getRegionMode() {#getRegionMode--}
```
public int getRegionMode()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Art der Verwendung der Region angibt. Der Wert MUSS in der RegionMode‑Aufzählung (Abschnitt 2.1.29) enthalten sein.

**Returns:**
int
### setRegionMode(int value) {#setRegionMode-int-}
```
public void setRegionMode(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Art der Verwendung der Region angibt. Der Wert MUSS in der RegionMode‑Aufzählung (Abschnitt 2.1.29) enthalten sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Liest oder setzt ein Byte‑Array der Länge RgnDataSize, das ein RegionData‑Objekt in logischen Einheiten angibt. Wenn RegionMode RGN\_COPY ist, können diese Daten weggelassen werden und die Clip-Region SOLLTE auf die Standard‑(NULL‑)Clip-Region gesetzt werden.

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Liest oder setzt ein Byte‑Array der Länge RgnDataSize, das ein RegionData‑Objekt in logischen Einheiten angibt. Wenn RegionMode RGN\_COPY ist, können diese Daten weggelassen werden und die Clip-Region SOLLTE auf die Standard‑(NULL‑)Clip-Region gesetzt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

