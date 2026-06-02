---
title: "EmfPlusEndContainer"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusEndContainer-Datensatz schließt einen Grafikzustandscontainer, der zuvor durch eine Begin-Container-Operation geöffnet wurde."
type: docs
weight: 30
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusEndContainer extends EmfPlusStateRecordType
```

Der EmfPlusEndContainer-Datensatz schließt einen Grafikzustandscontainer, der zuvor durch eine Begin-Container-Operation geöffnet wurde.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusEndContainer(EmfPlusRecord source)](#EmfPlusEndContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusEndContainer`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index eines Grafikzustands‑Containers angibt. |
| [setStackIndex(int value)](#setStackIndex-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index eines Grafikzustands‑Containers angibt. |
### EmfPlusEndContainer(EmfPlusRecord source) {#EmfPlusEndContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusEndContainer(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusEndContainer`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index eines Grafikzustands‑Containers angibt. Der Index MUST must match den Wert, der einem Grafikzustands‑Container zugeordnet ist, der durch einen vorherigen EmfPlusBeginContainer (Abschnitt 2.3.7.1) oder EmfPlusBeginContainerNoParams‑Datensatz (Abschnitt 2.3.7.2) geöffnet wurde.

Wert: Der Index des Stacks.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index eines Grafikzustands‑Containers angibt. Der Index MUST must match den Wert, der einem Grafikzustands‑Container zugeordnet ist, der durch einen vorherigen EmfPlusBeginContainer (Abschnitt 2.3.7.1) oder EmfPlusBeginContainerNoParams‑Datensatz (Abschnitt 2.3.7.2) geöffnet wurde.

Wert: Der Index des Stacks.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

