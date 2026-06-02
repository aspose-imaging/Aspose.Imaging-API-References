---
title: "EmfSelectObject"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_SELECTOBJECT‑Datensatz fügt dem aktuellen Metadatei‑Wiedergabegeräte‑Kontext ein Grafikobjekt hinzu."
type: docs
weight: 116
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfselectobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public final class EmfSelectObject extends EmfRecord
```

Der EMR\_SELECTOBJECT‑Datensatz fügt dem aktuellen Metadatei‑Wiedergabegeräte‑Kontext ein Grafikobjekt hinzu. Das Objekt wird entweder durch seinen Index in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) oder durch seinen Wert aus der StockObject‑Aufzählung (Abschnitt 2.1.31) angegeben.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfSelectObject(EmfRecord record)](#EmfSelectObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfSelectObject`‑Klasse. |
| [EmfSelectObject()](#EmfSelectObject--) | Initialisiert eine neue Instanz der `EmfSelectObject`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getObjectHandle()](#getObjectHandle--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die entweder den Index eines Grafikobjekts in der EMF‑Objekttabelle oder den Index eines Stock‑Objekts aus der `Consts.EmfStockObject`‑Aufzählung angibt. |
| [setObjectHandle(int value)](#setObjectHandle-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die entweder den Index eines Grafikobjekts in der EMF‑Objekttabelle oder den Index eines Stock‑Objekts aus der `Consts.EmfStockObject`‑Aufzählung angibt. |
### EmfSelectObject(EmfRecord record) {#EmfSelectObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSelectObject(EmfRecord record)
```


Initialisiert eine neue Instanz der `EmfSelectObject`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Der Datensatz. |

### EmfSelectObject() {#EmfSelectObject--}
```
public EmfSelectObject()
```


Initialisiert eine neue Instanz der `EmfSelectObject`‑Klasse.

### getObjectHandle() {#getObjectHandle--}
```
public int getObjectHandle()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die entweder den Index eines Grafikobjekts in der EMF‑Objekttabelle oder den Index eines Stock‑Objekts aus der `Consts.EmfStockObject`‑Aufzählung angibt.

**Returns:**
int
### setObjectHandle(int value) {#setObjectHandle-int-}
```
public void setObjectHandle(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die entweder den Index eines Grafikobjekts in der EMF‑Objekttabelle oder den Index eines Stock‑Objekts aus der `Consts.EmfStockObject`‑Aufzählung angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

