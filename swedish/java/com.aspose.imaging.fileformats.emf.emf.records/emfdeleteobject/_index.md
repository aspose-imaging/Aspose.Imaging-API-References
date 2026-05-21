---
title: "EmfDeleteObject"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_DELETEOBJECT-posten tar bort ett grafikobjekt som specificeras av dess index i EMF Object Table avsnitt 3.1.1.1."
type: docs
weight: 43
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public final class EmfDeleteObject extends EmfRecord
```

Den EMR\_DELETEOBJECT-posten tar bort ett grafikobjekt, som specificeras av dess index i EMF-objektabellen (avsnitt 3.1.1.1).
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfDeleteObject(EmfRecord record)](#EmfDeleteObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfDeleteObject`. |
| [EmfDeleteObject()](#EmfDeleteObject--) | Initierar en ny instans av klassen `EmfDeleteObject`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getObjectHandle()](#getObjectHandle--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antingen indexet för ett grafikobjekt i EMF Object Table eller indexet för ett standardobjekt från StockObject‑enumerationen. |
| [setObjectHandle(int value)](#setObjectHandle-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antingen indexet för ett grafikobjekt i EMF Object Table eller indexet för ett standardobjekt från StockObject‑enumerationen. |
### EmfDeleteObject(EmfRecord record) {#EmfDeleteObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfDeleteObject(EmfRecord record)
```


Initierar en ny instans av klassen `EmfDeleteObject`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Posten. |

### EmfDeleteObject() {#EmfDeleteObject--}
```
public EmfDeleteObject()
```


Initierar en ny instans av klassen `EmfDeleteObject`.

### getObjectHandle() {#getObjectHandle--}
```
public int getObjectHandle()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antingen indexet för ett grafikobjekt i EMF Object Table eller indexet för ett standardobjekt från StockObject‑enumerationen.

**Returns:**
int
### setObjectHandle(int value) {#setObjectHandle-int-}
```
public void setObjectHandle(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antingen indexet för ett grafikobjekt i EMF Object Table eller indexet för ett standardobjekt från StockObject‑enumerationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

