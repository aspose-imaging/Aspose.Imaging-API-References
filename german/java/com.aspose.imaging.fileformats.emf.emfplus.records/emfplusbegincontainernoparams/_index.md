---
title: "EmfPlusBeginContainerNoParams"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusBeginContainerNoParams-Datensatz öffnet einen neuen Grafikzustandscontainer."
type: docs
weight: 11
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusBeginContainerNoParams extends EmfPlusStateRecordType
```

Der EmfPlusBeginContainerNoParams-Datensatz öffnet einen neuen Grafikzustandscontainer.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusBeginContainerNoParams(EmfPlusRecord source)](#EmfPlusBeginContainerNoParams-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusBeginContainerNoParams`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Liefert oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der einen Index angibt, der dem Grafik‑Zustandscontainer zugeordnet wird. |
| [setStackIndex(int value)](#setStackIndex-int-) | Liefert oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der einen Index angibt, der dem Grafik‑Zustandscontainer zugeordnet wird. |
### EmfPlusBeginContainerNoParams(EmfPlusRecord source) {#EmfPlusBeginContainerNoParams-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusBeginContainerNoParams(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusBeginContainerNoParams`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Liefert oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der einen Index angibt, der dem Grafik‑Zustandscontainer zugeordnet wird. Der Index MUSS von einem nachfolgenden EmfPlusEndContainer‑Datensatz (Abschnitt 2.3.7.3) referenziert werden, um den Grafik‑Zustandscontainer zu schließen.

Wert: Der Index des Stacks.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Liefert oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der einen Index angibt, der dem Grafik‑Zustandscontainer zugeordnet wird. Der Index MUSS von einem nachfolgenden EmfPlusEndContainer‑Datensatz (Abschnitt 2.3.7.3) referenziert werden, um den Grafik‑Zustandscontainer zu schließen.

Wert: Der Index des Stacks.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

