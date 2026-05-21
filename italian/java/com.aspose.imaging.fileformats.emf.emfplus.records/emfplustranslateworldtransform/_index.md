---
title: "EmfPlusTranslateWorldTransform"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusTranslateWorldTransform esegue una traslazione sulla trasformazione dello spazio globale corrente."
type: docs
weight: 72
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusTranslateWorldTransform extends EmfPlusTerminalServerRecordType
```

Il record EmfPlusTranslateWorldTransform esegue una traslazione sulla trasformazione dello spazio globale corrente.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusTranslateWorldTransform(EmfPlusRecord source)](#EmfPlusTranslateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusTranslateWorldTransform`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | Ottiene un valore che indica se [matrice post moltiplicata]. |
| [getDx()](#getDx--) | Ottiene o imposta un valore a virgola mobile a 32 bit che definisce la distanza orizzontale. |
| [setDx(float value)](#setDx-float-) | Ottiene o imposta un valore a virgola mobile a 32 bit che definisce la distanza orizzontale. |
| [getDy()](#getDy--) | Ottiene o imposta un valore a virgola mobile a 32 bit che definisce il valore della distanza verticale. |
| [setDy(float value)](#setDy-float-) | Ottiene o imposta un valore a virgola mobile a 32 bit che definisce il valore della distanza verticale. |
### EmfPlusTranslateWorldTransform(EmfPlusRecord source) {#EmfPlusTranslateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusTranslateWorldTransform(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusTranslateWorldTransform`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getPostMultipliedMatrix() {#getPostMultipliedMatrix--}
```
public boolean getPostMultipliedMatrix()
```


Ottiene un valore che indica se [matrice post moltiplicata]. Se impostato, la matrice di trasformazione deve essere post-moltiplicata. Se non impostato, deve essere pre-moltiplicata.

Valore: `true` se [matrice post moltiplicata]; altrimenti, `false`.

**Returns:**
boolean
### getDx() {#getDx--}
```
public float getDx()
```


Ottiene o imposta un valore a virgola mobile a 32 bit che definisce la distanza orizzontale. La traduzione viene eseguita costruendo una nuova matrice di trasformazione del mondo dai campi dx e dy.

Valore: il dx.

**Returns:**
float
### setDx(float value) {#setDx-float-}
```
public void setDx(float value)
```


Ottiene o imposta un valore a virgola mobile a 32 bit che definisce la distanza orizzontale. La traduzione viene eseguita costruendo una nuova matrice di trasformazione del mondo dai campi dx e dy.

Valore: il dx.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getDy() {#getDy--}
```
public float getDy()
```


Ottiene o imposta un valore a virgola mobile a 32 bit che definisce il valore della distanza verticale.

Valore: il dy.

**Returns:**
float
### setDy(float value) {#setDy-float-}
```
public void setDy(float value)
```


Ottiene o imposta un valore a virgola mobile a 32 bit che definisce il valore della distanza verticale.

Valore: il dy.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

