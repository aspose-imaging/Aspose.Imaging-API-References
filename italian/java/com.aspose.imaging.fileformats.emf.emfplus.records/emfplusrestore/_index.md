---
title: "EmfPlusRestore"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusRestore ripristina lo stato grafico identificato da un indice specificato da una pila di stati grafici salvati."
type: docs
weight: 49
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusRestore extends EmfPlusStateRecordType
```

Il record EmfPlusRestore ripristina lo stato grafico, identificato da un indice specificato, da una pila di stati grafici salvati.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusRestore(EmfPlusRecord source)](#EmfPlusRestore-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusRestore`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il livello associato a uno stato grafico. |
| [setStackIndex(int value)](#setStackIndex-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il livello associato a uno stato grafico. |
### EmfPlusRestore(EmfPlusRecord source) {#EmfPlusRestore-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRestore(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusRestore`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il livello associato a uno stato grafico. Il valore del livello è stato assegnato allo stato grafico da un record EmfPlusSave precedente (sezione 2.3.7.5).

Valore: L'indice dello stack.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il livello associato a uno stato grafico. Il valore del livello è stato assegnato allo stato grafico da un record EmfPlusSave precedente (sezione 2.3.7.5).

Valore: L'indice dello stack.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

