---
title: "EmfDeleteColorSpace"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_DELETECOLORSPACE‑Datensatz löscht ein logisches Farbraumobjekt."
type: docs
weight: 42
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfdeletecolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfDeleteColorSpace extends EmfObjectManipulationRecordType
```

Der EMR\_DELETECOLORSPACE-Datensatz löscht ein logisches Farbraumobjekt.

Ein EMR\_DELETEOBJECT‑Datensatz SOLLTE anstelle von EMR\_DELETECOLORSPACE verwendet werden, um ein logisches Farbraumobjekt zu löschen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfDeleteColorSpace(EmfRecord source)](#EmfDeleteColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfDeleteColorSpace`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getIhCS()](#getIhCS--) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Index eines logischen Farbraumobjekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt. |
| [setIhCS(int value)](#setIhCS-int-) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Index eines logischen Farbraumobjekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt. |
### EmfDeleteColorSpace(EmfRecord source) {#EmfDeleteColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfDeleteColorSpace(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfDeleteColorSpace`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getIhCS() {#getIhCS--}
```
public int getIhCS()
```


Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Index eines logischen Farbraumobjekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt.

Dieses Objekt ist entweder ein WMF‑LogColorSpace‑ oder ein LogColorSpaceW‑Objekt ([MS-WMF] Abschnitte 2.2.2.11 bzw. 2.2.2.12).

**Returns:**
int
### setIhCS(int value) {#setIhCS-int-}
```
public void setIhCS(int value)
```


Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Index eines logischen Farbraumobjekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt.

Dieses Objekt ist entweder ein WMF‑LogColorSpace‑ oder ein LogColorSpaceW‑Objekt ([MS-WMF] Abschnitte 2.2.2.11 bzw. 2.2.2.12).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

