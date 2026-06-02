---
title: "EmfPlusRestore"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusRestore-Datensatz stellt den Grafikzustand wieder her, der durch einen angegebenen Index aus einem Stapel gespeicherter Grafikzustände identifiziert wird."
type: docs
weight: 49
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusRestore extends EmfPlusStateRecordType
```

Der EmfPlusRestore-Datensatz stellt den Grafikzustand, der durch einen angegebenen Index identifiziert wird, aus einem Stapel gespeicherter Grafikzustände wieder her.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusRestore(EmfPlusRecord source)](#EmfPlusRestore-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusRestore`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Liest oder schreibt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die mit einem Grafikzustand verbundene Ebene angibt. |
| [setStackIndex(int value)](#setStackIndex-int-) | Liest oder schreibt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die mit einem Grafikzustand verbundene Ebene angibt. |
### EmfPlusRestore(EmfPlusRecord source) {#EmfPlusRestore-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRestore(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusRestore`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Liest oder schreibt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die mit einem Grafikzustand verbundene Ebene angibt. Der Ebenenwert wurde dem Grafikzustand durch einen vorherigen EmfPlusSave‑Datensatz (Abschnitt 2.3.7.5) zugewiesen.

Wert: Der Index des Stacks.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Liest oder schreibt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die mit einem Grafikzustand verbundene Ebene angibt. Der Ebenenwert wurde dem Grafikzustand durch einen vorherigen EmfPlusSave‑Datensatz (Abschnitt 2.3.7.5) zugewiesen.

Wert: Der Index des Stacks.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

