---
title: "EmfFormat"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EmrFormat contiene informazioni che identificano il formato dei dati immagine in un record EMR_COMMENT_MULTIFORMATS sezione 2.3.3.4.3."
type: docs
weight: 15
url: /it/java/com.aspose.imaging.fileformats.emf.emf.objects/emfformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfFormat extends EmfObject
```

L'oggetto EmrFormat contiene informazioni che identificano il formato dei dati immagine in un record EMR\_COMMENT\_MULTIFORMATS (sezione 2.3.3.4.3).
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfFormat()](#EmfFormat--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSignature()](#getSignature--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il formato dei dati immagine. |
| [setSignature(int value)](#setSignature-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il formato dei dati immagine. |
| [getVersion()](#getVersion--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di versione del formato. |
| [setVersion(int value)](#setVersion-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di versione del formato. |
| [getSizeData()](#getSizeData--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dei dati in byte |
| [setSizeData(int value)](#setSizeData-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dei dati in byte |
| [getOffData()](#getOffData--) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'offset dei dati dall'inizio del campo identificatore in un record EMR\_COMMENT\_PUBLIC (sezione 2.3.3.4). |
| [setOffData(int value)](#setOffData-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'offset dei dati dall'inizio del campo identificatore in un record EMR\_COMMENT\_PUBLIC (sezione 2.3.3.4). |
### EmfFormat() {#EmfFormat--}
```
public EmfFormat()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il formato dei dati immagine. Questo valore DEVE appartenere all'enumerazione FormatSignature (sezione 2.1.14).

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il formato dei dati immagine. Questo valore DEVE appartenere all'enumerazione FormatSignature (sezione 2.1.14).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di versione del formato. Se il campo Signature specifica Encapsulated PostScript (EPS), questo valore DEVE essere 0x00000001; altrimenti, questo valore DEVE essere ignorato.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di versione del formato. Se il campo Signature specifica Encapsulated PostScript (EPS), questo valore DEVE essere 0x00000001; altrimenti, questo valore DEVE essere ignorato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getSizeData() {#getSizeData--}
```
public int getSizeData()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dei dati in byte

**Returns:**
int
### setSizeData(int value) {#setSizeData-int-}
```
public void setSizeData(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dei dati in byte

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getOffData() {#getOffData--}
```
public int getOffData()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'offset dei dati dall'inizio del campo identificatore in un record EMR\_COMMENT\_PUBLIC (sezione 2.3.3.4). L'offset DEVE essere allineato a 32 bit.

**Returns:**
int
### setOffData(int value) {#setOffData-int-}
```
public void setOffData(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'offset dei dati dall'inizio del campo identificatore in un record EMR\_COMMENT\_PUBLIC (sezione 2.3.3.4). L'offset DEVE essere allineato a 32 bit.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

