---
title: "EmfPlusRecord"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il tipo di record base Emf."
type: docs
weight: 46
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.emf.IRecord
```
public class EmfPlusRecord extends MetaObject implements IRecord
```

Il tipo di record base Emf+.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusRecord()](#EmfPlusRecord--) | Inizializza una nuova istanza della classe `EmfPlusRecord`. |
| [EmfPlusRecord(EmfPlusRecord source)](#EmfPlusRecord-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusRecord`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getType()](#getType--) | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |
| [getFlags()](#getFlags--) | Ottiene un intero senza segno a 16 bit che contiene informazioni per alcuni record su come l'operazione deve essere eseguita e sulla struttura del record. |
| [setFlags(short value)](#setFlags-short-) | Imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come l'operazione deve essere eseguita e sulla struttura del record. |
| [getSize()](#getSize--) | Ottiene un intero senza segno a 32 bit che specifica il numero di byte allineati a 32 bit dell'intero record, includendo l'intestazione del record di 12 byte e i dati specifici del record. |
| [setSize(int value)](#setSize-int-) | Imposta un intero senza segno a 32 bit che specifica il numero di byte allineati a 32 bit dell'intero record, includendo l'intestazione del record di 12 byte e i dati specifici del record. |
| [getDataSize()](#getDataSize--) | Ottiene un intero senza segno a 32 bit che DEVE definire il numero di byte di dati 32-bit\u2013aligned nel campo RecordData che segue. |
| [setDataSize(int value)](#setDataSize-int-) | Imposta un intero senza segno a 32 bit che DEVE definire il numero di byte di dati 32-bit\u2013aligned nel campo RecordData che segue. |
### EmfPlusRecord() {#EmfPlusRecord--}
```
public EmfPlusRecord()
```


Inizializza una nuova istanza della classe `EmfPlusRecord`.

### EmfPlusRecord(EmfPlusRecord source) {#EmfPlusRecord-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRecord(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusRecord`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getType() {#getType--}
```
public short getType()
```


Ottiene un intero senza segno a 16 bit che identifica il tipo di record.

**Returns:**
short
### getFlags() {#getFlags--}
```
public short getFlags()
```


Ottiene un intero senza segno a 16 bit che contiene informazioni per alcuni record su come l'operazione deve essere eseguita e sulla struttura del record.

**Returns:**
short - I flag.
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


Imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come l'operazione deve essere eseguita e sulla struttura del record.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short | I flag. |

### getSize() {#getSize--}
```
public int getSize()
```


Ottiene un intero senza segno a 32 bit che specifica il numero di byte allineati a 32 bit dell'intero record, includendo l'intestazione del record di 12 byte e i dati specifici del record.

**Returns:**
int - La dimensione.
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Imposta un intero senza segno a 32 bit che specifica il numero di byte allineati a 32 bit dell'intero record, includendo l'intestazione del record di 12 byte e i dati specifici del record.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La dimensione. |

### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Restituisce un intero senza segno a 32-bit che DEVE definire il numero di byte di dati 32-bit\u2013allineato nel campo RecordData che segue. Questo numero non include l'intestazione del record di 12 byte.

**Returns:**
int - La dimensione dei dati.
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


Imposta un intero senza segno a 32-bit che DEVE definire il numero di byte di dati 32-bit\u2013allineato nel campo RecordData che segue. Questo numero non include l'intestazione del record di 12 byte.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La dimensione dei dati. |

