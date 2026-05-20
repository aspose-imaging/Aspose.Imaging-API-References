---
title: "EmfPlusBeginContainer"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusBeginContainer apre un nuovo contenitore di stato grafico e specifica una trasformazione per esso."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusBeginContainer extends EmfPlusStateRecordType
```

Il record EmfPlusBeginContainer apre un nuovo contenitore di stato grafico e specifica una trasformazione per esso.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusBeginContainer(EmfPlusRecord source)](#EmfPlusBeginContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusBeginContainer`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPageUnit()](#getPageUnit--) | Ottiene l'unità di pagina. |
| [getDestRect()](#getDestRect--) | Ottiene o imposta un oggetto EmfPlusRectF (sezione 2.2.2.39) che, insieme a SrcRect, specifica una trasformazione per il contenitore. |
| [setDestRect(RectangleF value)](#setDestRect-com.aspose.imaging.RectangleF-) | Ottiene o imposta un oggetto EmfPlusRectF (sezione 2.2.2.39) che, insieme a SrcRect, specifica una trasformazione per il contenitore. |
| [getSrcRect()](#getSrcRect--) | Ottiene o imposta un rettangolo EmfPlusRectF che, insieme a DestRect, specifica una trasformazione per il contenitore. |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | Ottiene o imposta un rettangolo EmfPlusRectF che, insieme a DestRect, specifica una trasformazione per il contenitore. |
| [getStackIndex()](#getStackIndex--) | Ottiene o imposta un intero senza segno a 32-bit che specifica un indice da associare al contenitore di stato grafico. |
| [setStackIndex(int value)](#setStackIndex-int-) | Ottiene o imposta un intero senza segno a 32-bit che specifica un indice da associare al contenitore di stato grafico. |
### EmfPlusBeginContainer(EmfPlusRecord source) {#EmfPlusBeginContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusBeginContainer(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusBeginContainer`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


Ottiene l'unità di pagina.

Valore: L'unità di pagina.

**Returns:**
int
### getDestRect() {#getDestRect--}
```
public RectangleF getDestRect()
```


Ottiene o imposta un oggetto EmfPlusRectF (sezione 2.2.2.39) che, insieme a SrcRect, specifica una trasformazione per il contenitore. Questa trasformazione produce SrcRect quando applicata a DestRect.

Valore: Il rettangolo di destinazione.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setDestRect(RectangleF value) {#setDestRect-com.aspose.imaging.RectangleF-}
```
public void setDestRect(RectangleF value)
```


Ottiene o imposta un oggetto EmfPlusRectF (sezione 2.2.2.39) che, insieme a SrcRect, specifica una trasformazione per il contenitore. Questa trasformazione produce SrcRect quando applicata a DestRect.

Valore: Il rettangolo di destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


Ottiene o imposta un rettangolo EmfPlusRectF che, insieme a DestRect, specifica una trasformazione per il contenitore. Questa trasformazione produce SrcRect quando applicata a DestRect.

Valore: il rettangolo di origine.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


Ottiene o imposta un rettangolo EmfPlusRectF che, insieme a DestRect, specifica una trasformazione per il contenitore. Questa trasformazione produce SrcRect quando applicata a DestRect.

Valore: il rettangolo di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

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

