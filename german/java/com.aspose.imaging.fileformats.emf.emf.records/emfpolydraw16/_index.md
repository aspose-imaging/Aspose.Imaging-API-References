---
title: "EmfPolyDraw16"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_POLYDRAW16‑Record gibt eine Menge von Liniensegmenten und Bézier‑Kurven an."
type: docs
weight: 90
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw16/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyDraw16 extends EmfPolyShape
```

Der EMR\\_POLYDRAW16-Datensatz spezifiziert einen Satz von Liniensegmenten und Bézier-Kurven.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPolyDraw16(EmfRecord source)](#EmfPolyDraw16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfPolyDraw16`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAbTypes()](#getAbTypes--) | Liest oder setzt ein Array der Länge Count mit Bytes, das die Punktetypen angibt. |
| [setAbTypes(byte[] value)](#setAbTypes-byte---) | Legt ein Count-Längen-Array von Bytes fest, das die Punktetypen angibt. |
### EmfPolyDraw16(EmfRecord source) {#EmfPolyDraw16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyDraw16(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfPolyDraw16`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getAbTypes() {#getAbTypes--}
```
public byte[] getAbTypes()
```


Liest oder legt ein Count-Längen-Array von Bytes fest, das die Punktetypen angibt. Dieser Wert MUSS in der Point‑Aufzählung (Abschnitt 2.1.26) enthalten sein.

**Returns:**
byte[]
### setAbTypes(byte[] value) {#setAbTypes-byte---}
```
public void setAbTypes(byte[] value)
```


Legt ein Count-Längen-Array von Bytes fest, das die Punktetypen angibt. Dieser Wert MUSS in der Point‑Aufzählung (Abschnitt 2.1.26) enthalten sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] | ein Count-Längen-Array von Bytes, das die Punktetypen angibt. |

