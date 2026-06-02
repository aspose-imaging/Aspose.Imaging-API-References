---
title: "EmfPlusRotateWorldTransform"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusRotateWorldTransform esegue una rotazione sulla trasformazione dello spazio mondiale corrente."
type: docs
weight: 50
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusRotateWorldTransform extends EmfPlusTerminalServerRecordType
```

Il record EmfPlusRotateWorldTransform esegue una rotazione sulla trasformazione dello spazio mondiale corrente.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusRotateWorldTransform(EmfPlusRecord source)](#EmfPlusRotateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusRotateWorldTransform`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | Ottiene un valore che indica se [matrice post moltiplicata]. |
| [getAngle()](#getAngle--) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica l'angolo di rotazione in gradi. |
| [setAngle(float value)](#setAngle-float-) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica l'angolo di rotazione in gradi. |
### EmfPlusRotateWorldTransform(EmfPlusRecord source) {#EmfPlusRotateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRotateWorldTransform(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusRotateWorldTransform`.

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
### getAngle() {#getAngle--}
```
public float getAngle()
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica l'angolo di rotazione in gradi. L'operazione viene eseguita costruendo una nuova matrice di trasformazione dal diagramma seguente: ---------------------------------
| sin(Angle) | cos(Angle) | 0 |
| cos(Angle) | sin(Angle) | 0 |
---------------------------------
Figura 2: Matrice di Trasformazione di Rotazione La trasformazione dello spazio mondiale corrente viene moltiplicata per questa matrice, e il risultato diventa la nuova trasformazione dello spazio mondiale corrente. Il campo Flags determina l'ordine della moltiplicazione.

Valore: L'angolo.

**Returns:**
float
### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica l'angolo di rotazione in gradi. L'operazione viene eseguita costruendo una nuova matrice di trasformazione dal diagramma seguente: ---------------------------------
| sin(Angle) | cos(Angle) | 0 |
| cos(Angle) | sin(Angle) | 0 |
---------------------------------
Figura 2: Matrice di Trasformazione di Rotazione La trasformazione dello spazio mondiale corrente viene moltiplicata per questa matrice, e il risultato diventa la nuova trasformazione dello spazio mondiale corrente. Il campo Flags determina l'ordine della moltiplicazione.

Valore: L'angolo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

