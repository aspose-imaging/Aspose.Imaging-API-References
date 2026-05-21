---
title: "EmfSelectObject"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_SELECTOBJECT-posten lägger till ett grafikobjekt i den aktuella metafilens uppspelningsenhetskontext."
type: docs
weight: 116
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfselectobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public final class EmfSelectObject extends EmfRecord
```

EMR\_SELECTOBJECT-posten lägger till ett grafikobjekt i den aktuella metafilens uppspelningsenhetskontext. Objektet specificeras antingen av dess index i EMF‑objektabellen (avsnitt 3.1.1.1) eller av dess värde från uppräkningen StockObject (avsnitt 2.1.31).
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfSelectObject(EmfRecord record)](#EmfSelectObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfSelectObject`. |
| [EmfSelectObject()](#EmfSelectObject--) | Initierar en ny instans av klassen `EmfSelectObject`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getObjectHandle()](#getObjectHandle--) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar antingen indexet för ett grafikobjekt i EMF‑objektabellen eller indexet för ett standardobjekt från uppräkningen `Consts.EmfStockObject`. |
| [setObjectHandle(int value)](#setObjectHandle-int-) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar antingen indexet för ett grafikobjekt i EMF‑objektabellen eller indexet för ett standardobjekt från uppräkningen `Consts.EmfStockObject`. |
### EmfSelectObject(EmfRecord record) {#EmfSelectObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSelectObject(EmfRecord record)
```


Initierar en ny instans av klassen `EmfSelectObject`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Posten. |

### EmfSelectObject() {#EmfSelectObject--}
```
public EmfSelectObject()
```


Initierar en ny instans av klassen `EmfSelectObject`.

### getObjectHandle() {#getObjectHandle--}
```
public int getObjectHandle()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar antingen indexet för ett grafikobjekt i EMF‑objektabellen eller indexet för ett standardobjekt från uppräkningen `Consts.EmfStockObject`.

**Returns:**
int
### setObjectHandle(int value) {#setObjectHandle-int-}
```
public void setObjectHandle(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar antingen indexet för ett grafikobjekt i EMF‑objektabellen eller indexet för ett standardobjekt från uppräkningen `Consts.EmfStockObject`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

