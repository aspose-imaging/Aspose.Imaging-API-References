---
title: "EmfDrawEscape"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_DRAWESCAPE trasmette informazioni arbitrarie a un driver di stampa."
type: docs
weight: 44
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfdrawescape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfEscapeRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype)
```
public final class EmfDrawEscape extends EmfEscapeRecordType
```

Il record EMR\_DRAWESCAPE passa informazioni arbitrarie a un driver di stampa. L'intento è che le informazioni provochino la realizzazione del disegno.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfDrawEscape(EmfRecord source)](#EmfDrawEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfDrawEscape`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCjIn()](#getCjIn--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di byte da passare al driver di stampa. |
| [setCjIn(int value)](#setCjIn-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di byte da passare al driver di stampa. |
| [getData()](#getData--) | Ottiene o imposta i dati da passare al driver di stampa. |
| [setData(byte[] value)](#setData-byte---) | Ottiene o imposta i dati da passare al driver di stampa. |
### EmfDrawEscape(EmfRecord source) {#EmfDrawEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfDrawEscape(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfDrawEscape`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getCjIn() {#getCjIn--}
```
public int getCjIn()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di byte da passare al driver di stampa.

**Returns:**
int
### setCjIn(int value) {#setCjIn-int-}
```
public void setCjIn(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di byte da passare al driver di stampa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Ottiene o imposta i dati da passare al driver di stampa. DEVONO esserci cjIn byte disponibili.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Ottiene o imposta i dati da passare al driver di stampa. DEVONO esserci cjIn byte disponibili.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

