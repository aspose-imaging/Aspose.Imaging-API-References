---
title: "EmfPlusComment"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusComment specifica dati privati arbitrari."
type: docs
weight: 14
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord)
```
public final class EmfPlusComment extends EmfPlusRecord
```

Il record EmfPlusComment specifica dati privati arbitrari.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusComment(EmfPlusRecord source)](#EmfPlusComment-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusComment`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPrivateData()](#getPrivateData--) | Ottiene o imposta un array di byte di lunghezza DataSize contenente dati privati. |
| [setPrivateData(byte[] value)](#setPrivateData-byte---) | Ottiene o imposta un array di byte di lunghezza DataSize contenente dati privati. |
| [getFlags()](#getFlags--) | Ottiene o imposta un intero senza segno a 16 bit che non è utilizzato. |
| [setFlags(short value)](#setFlags-short-) | Ottiene o imposta un intero senza segno a 16 bit che non è utilizzato. |
### EmfPlusComment(EmfPlusRecord source) {#EmfPlusComment-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusComment(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusComment`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getPrivateData() {#getPrivateData--}
```
public byte[] getPrivateData()
```


Ottiene o imposta un array di byte di lunghezza DataSize contenente dati privati. byte di dati specifici del record che seguono.

**Returns:**
byte[]
### setPrivateData(byte[] value) {#setPrivateData-byte---}
```
public void setPrivateData(byte[] value)
```


Ottiene o imposta un array di byte di lunghezza DataSize contenente dati privati. byte di dati specifici del record che seguono.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### getFlags() {#getFlags--}
```
public short getFlags()
```


Ottiene o imposta un intero senza segno a 16 bit che non è utilizzato. Questo campo DOVREBBE essere impostato a zero e DEVE essere ignorato al ricevimento.

**Returns:**
short
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


Ottiene o imposta un intero senza segno a 16 bit che non è utilizzato. Questo campo DOVREBBE essere impostato a zero e DEVE essere ignorato al ricevimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

