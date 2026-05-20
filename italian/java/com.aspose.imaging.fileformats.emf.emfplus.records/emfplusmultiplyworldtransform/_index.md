---
title: "EmfPlusMultiplyWorldTransform"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusMultiplyWorldTransform moltiplica la trasformazione dello spazio mondiale corrente per una matrice di trasformazione specificata."
type: docs
weight: 41
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusMultiplyWorldTransform extends EmfPlusTerminalServerRecordType
```

Il record EmfPlusMultiplyWorldTransform moltiplica la trasformazione dello spazio mondiale corrente per una matrice di trasformazione specificata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusMultiplyWorldTransform(EmfPlusRecord source)](#EmfPlusMultiplyWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusMultiplyWorldTransform`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | Ottiene un valore che indica se [matrice post moltiplicata]. |
| [getMatrixData()](#getMatrixData--) | Ottiene o imposta un oggetto EmfPlusTransformMatrix (sezione 2.2.2.47) che definisce la matrice di moltiplicazione. |
| [setMatrixData(Matrix value)](#setMatrixData-com.aspose.imaging.Matrix-) | Ottiene o imposta un oggetto EmfPlusTransformMatrix (sezione 2.2.2.47) che definisce la matrice di moltiplicazione. |
### EmfPlusMultiplyWorldTransform(EmfPlusRecord source) {#EmfPlusMultiplyWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusMultiplyWorldTransform(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusMultiplyWorldTransform`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getPostMultipliedMatrix() {#getPostMultipliedMatrix--}
```
public boolean getPostMultipliedMatrix()
```


Ottiene un valore che indica se [post multiplied matrix]. Se impostato, la matrice di trasformazione deve essere post-moltiplicata. Se non impostato, deve essere pre-moltiplicata.

Valore: `true` se [matrice post moltiplicata]; altrimenti, `false`.

**Returns:**
boolean
### getMatrixData() {#getMatrixData--}
```
public Matrix getMatrixData()
```


Ottiene o imposta un oggetto EmfPlusTransformMatrix (sezione 2.2.2.47) che definisce la matrice di moltiplicazione.

Valore: i dati della matrice.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setMatrixData(Matrix value) {#setMatrixData-com.aspose.imaging.Matrix-}
```
public void setMatrixData(Matrix value)
```


Ottiene o imposta un oggetto EmfPlusTransformMatrix (sezione 2.2.2.47) che definisce la matrice di moltiplicazione.

Valore: i dati della matrice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

