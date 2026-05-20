---
title: "EmfInvertRgn"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_INVERTRGN-Datensatz invertiert die Farben im angegebenen Bereich."
type: docs
weight: 67
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfinvertrgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfInvertRgn extends EmfStateRecordType
```

Der EMR\_INVERTRGN-Datensatz invertiert die Farben in der angegebenen Region.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfInvertRgn(EmfRecord source)](#EmfInvertRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfInvertRgn`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBounds()](#getBounds--) | Liest oder setzt ein 128‑Bit‑WMF RectL-Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.19, das das Begrenzungsrechteck angibt. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Liest oder setzt ein 128‑Bit‑WMF RectL-Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.19, das das Begrenzungsrechteck angibt. |
| [getRgnDataSize()](#getRgnDataSize--) | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Größe der Regionsdaten in Bytes angibt. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Größe der Regionsdaten in Bytes angibt. |
| [getRgnData()](#getRgnData--) | Liest oder setzt ein Byte-Array der Länge RgnDataSize, das ein RegionData-Objekt in logischen Einheiten angibt. |
| [setRgnData(byte[] value)](#setRgnData-byte---) | Liest oder setzt ein Byte-Array der Länge RgnDataSize, das ein RegionData-Objekt in logischen Einheiten angibt. |
### EmfInvertRgn(EmfRecord source) {#EmfInvertRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfInvertRgn(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfInvertRgn`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

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

### getRgnData() {#getRgnData--}
```
public byte[] getRgnData()
```


Liest oder setzt ein Byte-Array der Länge RgnDataSize, das ein RegionData-Objekt in logischen Einheiten angibt.

**Returns:**
byte[]
### setRgnData(byte[] value) {#setRgnData-byte---}
```
public void setRgnData(byte[] value)
```


Liest oder setzt ein Byte-Array der Länge RgnDataSize, das ein RegionData-Objekt in logischen Einheiten angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

