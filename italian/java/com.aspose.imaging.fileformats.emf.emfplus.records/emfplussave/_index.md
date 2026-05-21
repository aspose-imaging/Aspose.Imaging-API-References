---
title: "EmfPlusSave"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusSave salva lo stato grafico identificato da un indice specificato su una pila di stati grafici salvati."
type: docs
weight: 51
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussave/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusSave extends EmfPlusStateRecordType
```

Il record EmfPlusSave salva lo stato grafico, identificato da un indice specificato, su una pila di stati grafici salvati.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusSave(EmfPlusRecord source)](#EmfPlusSave-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusSave`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Ottiene o imposta un intero senza segno a 32 bit che specifica un livello da associare allo stato grafico. |
| [setStackIndex(int value)](#setStackIndex-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica un livello da associare allo stato grafico. |
### EmfPlusSave(EmfPlusRecord source) {#EmfPlusSave-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSave(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusSave`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica un livello da associare allo stato grafico. Il valore del livello può essere usato da una successiva operazione di record EmfPlusRestore (sezione 2.3.7.4) per recuperare lo stato grafico.

Valore: L'indice dello stack.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica un livello da associare allo stato grafico. Il valore del livello può essere usato da una successiva operazione di record EmfPlusRestore (sezione 2.3.7.4) per recuperare lo stato grafico.

Valore: L'indice dello stack.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

