---
title: "EmfCommentMultiFormats"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_COMMENT_MULTIFORMATS-Datensatz gibt ein Bild in mehreren Grafikformaten an."
type: docs
weight: 30
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype)
```
public final class EmfCommentMultiFormats extends EmfCommentPublicRecordType
```

Der EMR\_COMMENT\_MULTIFORMATS-Datensatz gibt ein Bild in mehreren Grafikformaten an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfCommentMultiFormats(EmfRecord source)](#EmfCommentMultiFormats-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der Klasse `EmfCommentMultiFormats`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getOutputRect()](#getOutputRect--) | Liest oder setzt ein WMF RectL-Objekt ([MS-WMF] Abschnitt 2.2.2.19), das das Ausgaberechteck in logischen Koordinaten festlegt. |
| [setOutputRect(Rectangle value)](#setOutputRect-com.aspose.imaging.Rectangle-) | Liest oder setzt ein WMF RectL-Objekt ([MS-WMF] Abschnitt 2.2.2.19), das das Ausgaberechteck in logischen Koordinaten festlegt. |
| [getAFormats()](#getAFormats--) | Liest oder setzt ein Array der Länge CountFormats mit Grafikformaten, angegeben durch EmrFormat-Objekte (Abschnitt 2.2.4), in Reihenfolge der Präferenz. |
| [setAFormats(EmfFormat[] value)](#setAFormats-com.aspose.imaging.fileformats.emf.emf.objects.EmfFormat---) | Liest oder setzt ein Array der Länge CountFormats mit Grafikformaten, angegeben durch EmrFormat-Objekte (Abschnitt 2.2.4), in Reihenfolge der Präferenz. |
| [getFormatData()](#getFormatData--) | Liest oder setzt ein variabel langes Byte-Array mit Bilddaten für alle im Datensatz enthaltenen Grafikformate. |
| [setFormatData(byte[][] value)](#setFormatData-byte-----) | Liest oder setzt ein variabel langes Byte-Array mit Bilddaten für alle im Datensatz enthaltenen Grafikformate. |
### EmfCommentMultiFormats(EmfRecord source) {#EmfCommentMultiFormats-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentMultiFormats(EmfRecord source)
```


Initialisiert eine neue Instanz der Klasse `EmfCommentMultiFormats`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getOutputRect() {#getOutputRect--}
```
public Rectangle getOutputRect()
```


Liest oder setzt ein WMF RectL-Objekt ([MS-WMF] Abschnitt 2.2.2.19), das das Ausgaberechteck in logischen Koordinaten festlegt.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setOutputRect(Rectangle value) {#setOutputRect-com.aspose.imaging.Rectangle-}
```
public void setOutputRect(Rectangle value)
```


Liest oder setzt ein WMF RectL-Objekt ([MS-WMF] Abschnitt 2.2.2.19), das das Ausgaberechteck in logischen Koordinaten festlegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAFormats() {#getAFormats--}
```
public EmfFormat[] getAFormats()
```


Liest oder setzt ein Array der Länge CountFormats mit Grafikformaten, angegeben durch EmrFormat-Objekte (Abschnitt 2.2.4), in Reihenfolge der Präferenz.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfFormat[]
### setAFormats(EmfFormat[] value) {#setAFormats-com.aspose.imaging.fileformats.emf.emf.objects.EmfFormat---}
```
public void setAFormats(EmfFormat[] value)
```


Liest oder setzt ein Array der Länge CountFormats mit Grafikformaten, angegeben durch EmrFormat-Objekte (Abschnitt 2.2.4), in Reihenfolge der Präferenz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfFormat\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfformat) |  |

### getFormatData() {#getFormatData--}
```
public byte[][] getFormatData()
```


Liest oder setzt ein variabel langes Byte-Array mit Bilddaten für alle im Datensatz enthaltenen Grafikformate. Die Größe der Daten für jedes Bild wird durch das Feld DataSize im entsprechenden EmrFormat-Objekt bereitgestellt. Somit ist die Gesamtlänge dieses Feldes die Summe der DataSize‑Werte aller EmrFormat‑Objekte. Das Grafikformat der Daten für jedes Bild wird durch das Feld Signature im entsprechenden EmrFormat‑Objekt angegeben.

**Returns:**
byte[][]
### setFormatData(byte[][] value) {#setFormatData-byte-----}
```
public void setFormatData(byte[][] value)
```


Liest oder setzt ein variabel langes Byte-Array mit Bilddaten für alle im Datensatz enthaltenen Grafikformate. Die Größe der Daten für jedes Bild wird durch das Feld DataSize im entsprechenden EmrFormat-Objekt bereitgestellt. Somit ist die Gesamtlänge dieses Feldes die Summe der DataSize‑Werte aller EmrFormat‑Objekte. Das Grafikformat der Daten für jedes Bild wird durch das Feld Signature im entsprechenden EmrFormat‑Objekt angegeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[][] |  |

