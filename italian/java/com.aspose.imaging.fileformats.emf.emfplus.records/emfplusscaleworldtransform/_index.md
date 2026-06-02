---
title: "EmfPlusScaleWorldTransform"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusScaleWorldTransform esegue una scalatura sulla trasformazione dello spazio mondiale corrente."
type: docs
weight: 52
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusScaleWorldTransform extends EmfPlusTerminalServerRecordType
```

Il record EmfPlusScaleWorldTransform esegue una scalatura sulla trasformazione dello spazio mondiale corrente.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusScaleWorldTransform(EmfPlusRecord source)](#EmfPlusScaleWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusScaleWorldTransform`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | Ottiene un valore che indica se [matrice post moltiplicata]. |
| [getSx()](#getSx--) | Ottiene o imposta un valore a virgola mobile a 32 bit che definisce il fattore di scala orizzontale. |
| [setSx(float value)](#setSx-float-) | Ottiene o imposta un valore a virgola mobile a 32 bit che definisce il fattore di scala orizzontale. |
| [getSy()](#getSy--) | Ottiene o imposta un valore a virgola mobile a 32 bit che definisce il fattore di scala verticale. |
| [setSy(float value)](#setSy-float-) | Ottiene o imposta un valore a virgola mobile a 32 bit che definisce il fattore di scala verticale. |
### EmfPlusScaleWorldTransform(EmfPlusRecord source) {#EmfPlusScaleWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusScaleWorldTransform(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusScaleWorldTransform`.

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
### getSx() {#getSx--}
```
public float getSx()
```


Ottiene o imposta un valore a virgola mobile a 32 bit che definisce il fattore di scala orizzontale. La scalatura viene eseguita costruendo una nuova matrice di trasformazione dai valori dei campi Sx e Sy, come mostrato nella tabella seguente. ----------------- | Sx | 0 | 0 | | 0 | Sx | 0 | ----------------- Figura 3: Matrice di trasformazione della scala

**Returns:**
float
### setSx(float value) {#setSx-float-}
```
public void setSx(float value)
```


Ottiene o imposta un valore a virgola mobile a 32 bit che definisce il fattore di scala orizzontale. La scalatura viene eseguita costruendo una nuova matrice di trasformazione dai valori dei campi Sx e Sy, come mostrato nella tabella seguente. ----------------- | Sx | 0 | 0 | | 0 | Sx | 0 | ----------------- Figura 3: Matrice di trasformazione della scala

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getSy() {#getSy--}
```
public float getSy()
```


Ottiene o imposta un valore a virgola mobile a 32 bit che definisce il fattore di scala verticale.

**Returns:**
float
### setSy(float value) {#setSy-float-}
```
public void setSy(float value)
```


Ottiene o imposta un valore a virgola mobile a 32 bit che definisce il fattore di scala verticale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

