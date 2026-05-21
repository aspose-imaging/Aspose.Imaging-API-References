---
title: "EmfPlusEndContainer"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusEndContainer chiude un contenitore di stato grafico che era stato precedentemente aperto da un'operazione di avvio del contenitore."
type: docs
weight: 30
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusEndContainer extends EmfPlusStateRecordType
```

Il record EmfPlusEndContainer chiude un contenitore di stato grafico che era stato precedentemente aperto da un'operazione di avvio del contenitore.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusEndContainer(EmfPlusRecord source)](#EmfPlusEndContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusEndContainer`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice di un contenitore di stato grafico. |
| [setStackIndex(int value)](#setStackIndex-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice di un contenitore di stato grafico. |
### EmfPlusEndContainer(EmfPlusRecord source) {#EmfPlusEndContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusEndContainer(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusEndContainer`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice di un contenitore di stato grafico. L'indice DEVE corrispondere al valore associato a un contenitore di stato grafico aperto da un precedente record EmfPlusBeginContainer (sezione 2.3.7.1) o EmfPlusBeginContainerNoParams (sezione 2.3.7.2).

Valore: L'indice dello stack.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice di un contenitore di stato grafico. L'indice DEVE corrispondere al valore associato a un contenitore di stato grafico aperto da un precedente record EmfPlusBeginContainer (sezione 2.3.7.1) o EmfPlusBeginContainerNoParams (sezione 2.3.7.2).

Valore: L'indice dello stack.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

