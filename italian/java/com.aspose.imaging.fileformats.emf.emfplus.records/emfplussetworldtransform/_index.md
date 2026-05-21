---
title: "EmfPlusSetWorldTransform"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusSetWorldTransform imposta la trasformazione globale in base ai valori di una matrice di trasformazione specificata."
type: docs
weight: 68
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetWorldTransform extends EmfPlusTerminalServerRecordType
```

Il record EmfPlusSetWorldTransform imposta la trasformazione globale in base ai valori di una matrice di trasformazione specificata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusSetWorldTransform(EmfPlusRecord source)](#EmfPlusSetWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusSetWorldTransform`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getMatrixData()](#getMatrixData--) | Ottiene o imposta un oggetto EmfPlusTransformMatrix (sezione 2.2.2.47) che definisce la nuova trasformazione mondiale corrente. |
| [setMatrixData(Matrix value)](#setMatrixData-com.aspose.imaging.Matrix-) | Ottiene o imposta un oggetto EmfPlusTransformMatrix (sezione 2.2.2.47) che definisce la nuova trasformazione mondiale corrente. |
### EmfPlusSetWorldTransform(EmfPlusRecord source) {#EmfPlusSetWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetWorldTransform(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusSetWorldTransform`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getMatrixData() {#getMatrixData--}
```
public Matrix getMatrixData()
```


Ottiene o imposta un oggetto EmfPlusTransformMatrix (sezione 2.2.2.47) che definisce la nuova trasformazione mondiale corrente.

Valore: i dati della matrice.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setMatrixData(Matrix value) {#setMatrixData-com.aspose.imaging.Matrix-}
```
public void setMatrixData(Matrix value)
```


Ottiene o imposta un oggetto EmfPlusTransformMatrix (sezione 2.2.2.47) che definisce la nuova trasformazione mondiale corrente.

Valore: i dati della matrice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

