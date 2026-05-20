---
title: "EmfSetColorSpace"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_SETCOLORSPACE‑Datensatz definiert das aktuelle logische Farbraum‑Objekt für Grafikoperationen."
type: docs
weight: 123
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetcolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfSetColorSpace extends EmfObjectManipulationRecordType
```

Der EMR\_SETCOLORSPACE-Datensatz definiert das aktuelle logische Farbraum‑Objekt für Grafikoperationen.

Das logische Farbraumobjekt, das durch diesen Datensatz definiert wird, MUSS in Zeichenoperationen verwendet werden, die durch nachfolgende EMF-Datensätze angegeben sind, bis entweder ein anderes logisches Farbraumobjekt durch einen anderen EMR\_SETCOLORSPACE-Datensatz angegeben wird oder das Objekt durch einen EMR\_DELETECOLORSPACE-Datensatz entfernt wird.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfSetColorSpace(EmfRecord source)](#EmfSetColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfSetColorSpace`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getIhCS()](#getIhCS--) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Index eines logischen Farbraumobjekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt. |
| [setIhCS(int value)](#setIhCS-int-) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Index eines logischen Farbraumobjekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt. |
### EmfSetColorSpace(EmfRecord source) {#EmfSetColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetColorSpace(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfSetColorSpace`-Klasse.

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

