---
title: "EmfSelectClipPath"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_SELECTCLIPPATH-Datensatz legt den aktuellen Pfad als Clipping‑Region für einen Wiedergabegeräte‑Kontext fest, wobei die neue Region mit vorhandenen Clipping‑Regionen unter Verwendung des angegebenen Modus kombiniert wird."
type: docs
weight: 115
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfselectclippath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfSelectClipPath extends EmfClippingRecordType
```

Der EMR\_SELECTCLIPPATH-Datensatz legt den aktuellen Pfad als Clipping‑Region für einen Wiedergabe-Gerätekontext fest und kombiniert die neue Region mit einer vorhandenen Clipping‑Region unter Verwendung des angegebenen Modus.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfSelectClipPath(EmfRecord source)](#EmfSelectClipPath-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfSelectClipPath`‑Klasse. |
| [EmfSelectClipPath()](#EmfSelectClipPath--) | Initialisiert eine neue Instanz der `EmfSelectClipPath`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRegionMode()](#getRegionMode--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Art der Pfadverwendung angibt. |
| [setRegionMode(int value)](#setRegionMode-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Art der Pfadverwendung angibt. |
### EmfSelectClipPath(EmfRecord source) {#EmfSelectClipPath-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSelectClipPath(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfSelectClipPath`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfSelectClipPath() {#EmfSelectClipPath--}
```
public EmfSelectClipPath()
```


Initialisiert eine neue Instanz der `EmfSelectClipPath`‑Klasse.

### getRegionMode() {#getRegionMode--}
```
public int getRegionMode()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Art der Pfadverwendung angibt. Der Wert MUSS in der Aufzählung RegionMode (Abschnitt 2.1.29) enthalten sein.

**Returns:**
int
### setRegionMode(int value) {#setRegionMode-int-}
```
public void setRegionMode(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Art der Pfadverwendung angibt. Der Wert MUSS in der Aufzählung RegionMode (Abschnitt 2.1.29) enthalten sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

