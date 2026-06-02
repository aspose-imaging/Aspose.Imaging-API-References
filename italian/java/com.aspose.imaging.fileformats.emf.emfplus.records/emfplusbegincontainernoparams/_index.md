---
title: "EmfPlusBeginContainerNoParams"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusBeginContainerNoParams apre un nuovo contenitore di stato grafico."
type: docs
weight: 11
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusBeginContainerNoParams extends EmfPlusStateRecordType
```

Il record EmfPlusBeginContainerNoParams apre un nuovo contenitore di stato grafico.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusBeginContainerNoParams(EmfPlusRecord source)](#EmfPlusBeginContainerNoParams-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusBeginContainerNoParams`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Ottiene o imposta un intero senza segno a 32-bit che specifica un indice da associare al contenitore di stato grafico. |
| [setStackIndex(int value)](#setStackIndex-int-) | Ottiene o imposta un intero senza segno a 32-bit che specifica un indice da associare al contenitore di stato grafico. |
### EmfPlusBeginContainerNoParams(EmfPlusRecord source) {#EmfPlusBeginContainerNoParams-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusBeginContainerNoParams(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusBeginContainerNoParams`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Ottiene o imposta un intero senza segno a 32-bit che specifica un indice da associare al contenitore di stato grafico. L'indice DEVE essere referenziato da un successivo record EmfPlusEndContainer (sezione 2.3.7.3) per chiudere il contenitore di stato grafico.

Valore: L'indice dello stack.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Ottiene o imposta un intero senza segno a 32-bit che specifica un indice da associare al contenitore di stato grafico. L'indice DEVE essere referenziato da un successivo record EmfPlusEndContainer (sezione 2.3.7.3) per chiudere il contenitore di stato grafico.

Valore: L'indice dello stack.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

