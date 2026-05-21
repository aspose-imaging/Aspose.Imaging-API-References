---
title: "EmfPlusSave"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusSave‑Datensatz speichert den Grafikzustand, der durch einen angegebenen Index auf einem Stapel gespeicherter Grafikzustände identifiziert wird."
type: docs
weight: 51
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussave/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusSave extends EmfPlusStateRecordType
```

Der EmfPlusSave-Datensatz speichert den Grafikzustand, der durch einen angegebenen Index identifiziert wird, in einem Stapel gespeicherter Grafikzustände.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusSave(EmfPlusRecord source)](#EmfPlusSave-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusSave`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der ein Level angibt, das dem Grafikstatus zugeordnet wird. |
| [setStackIndex(int value)](#setStackIndex-int-) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der ein Level angibt, das dem Grafikstatus zugeordnet wird. |
### EmfPlusSave(EmfPlusRecord source) {#EmfPlusSave-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSave(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusSave`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der ein Level angibt, das dem Grafikstatus zugeordnet wird. Der Levelwert kann von einem nachfolgenden EmfPlusRestore‑Datensatz (Abschnitt 2.3.7.4) verwendet werden, um den Grafikstatus wiederherzustellen.

Wert: Der Index des Stacks.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der ein Level angibt, das dem Grafikstatus zugeordnet wird. Der Levelwert kann von einem nachfolgenden EmfPlusRestore‑Datensatz (Abschnitt 2.3.7.4) verwendet werden, um den Grafikstatus wiederherzustellen.

Wert: Der Index des Stacks.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

