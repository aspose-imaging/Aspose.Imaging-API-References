---
title: "EmfPlusPathPointTypeRle"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EmfPlusPathPointTypeRle specifica valori di tipo associati a punti su un percorso grafico usando la compressione RLE."
type: docs
weight: 62
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype)
```
public final class EmfPlusPathPointTypeRle extends EmfPlusBasePointType
```

L'oggetto EmfPlusPathPointTypeRle specifica i valori di tipo associati ai punti di un percorso grafico usando la compressione RLE. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 B|1|RunCount | PointType | B (1 bit): Se impostato, i punti del percorso sono su una curva Bézier. Se non impostato, i punti del percorso sono su una linea grafica. RunCount (6 bit): Il conteggio di run, cioè il numero di punti del percorso da associare al tipo nel campo PointType. PointType (1 byte): Un oggetto EmfPlusPathPointType (sezione 2.2.2.31) che specifica il tipo da associare ai punti del percorso.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusPathPointTypeRle()](#EmfPlusPathPointTypeRle--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getData()](#getData--) | Ottiene o imposta i dati. |
| [setData(int value)](#setData-int-) | Ottiene o imposta i dati. |
| [getBezier()](#getBezier--) | Ottiene o imposta un valore che indica se questo `EmfPlusPathPointTypeRle` è Bézier. |
| [setBezier(boolean value)](#setBezier-boolean-) | Ottiene o imposta un valore che indica se questo `EmfPlusPathPointTypeRle` è Bézier. |
| [getRunCount()](#getRunCount--) | Ottiene o imposta il conteggio di run. |
| [setRunCount(byte value)](#setRunCount-byte-) | Ottiene o imposta il conteggio di run. |
| [getPointType()](#getPointType--) | Ottiene o imposta il tipo del punto. |
| [setPointType(EmfPlusPathPointType value)](#setPointType-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointType-) | Ottiene o imposta il tipo del punto. |
### EmfPlusPathPointTypeRle() {#EmfPlusPathPointTypeRle--}
```
public EmfPlusPathPointTypeRle()
```


### getData() {#getData--}
```
public int getData()
```


Ottiene o imposta i dati.

Valore: I dati.

**Returns:**
int
### setData(int value) {#setData-int-}
```
public void setData(int value)
```


Ottiene o imposta i dati.

Valore: I dati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getBezier() {#getBezier--}
```
public boolean getBezier()
```


Ottiene o imposta un valore che indica se questo `EmfPlusPathPointTypeRle` è Bézier. Se impostato, i punti del percorso sono su una curva Bézier. Se non impostato, i punti del percorso sono su una linea grafica.

Valore: `true` se Bézier; altrimenti, `false`.

**Returns:**
boolean
### setBezier(boolean value) {#setBezier-boolean-}
```
public void setBezier(boolean value)
```


Ottiene o imposta un valore che indica se questo `EmfPlusPathPointTypeRle` è Bézier. Se impostato, i punti del percorso sono su una curva Bézier. Se non impostato, i punti del percorso sono su una linea grafica.

Valore: `true` se Bézier; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getRunCount() {#getRunCount--}
```
public byte getRunCount()
```


Ottiene o imposta il conteggio di run. RunCount (6 bit): Il conteggio di run, cioè il numero di punti del percorso da associare al tipo nel campo PointType

Valore: Il conteggio di run.

**Returns:**
byte
### setRunCount(byte value) {#setRunCount-byte-}
```
public void setRunCount(byte value)
```


Ottiene o imposta il conteggio di run. RunCount (6 bit): Il conteggio di run, cioè il numero di punti del percorso da associare al tipo nel campo PointType

Valore: Il conteggio di run.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getPointType() {#getPointType--}
```
public EmfPlusPathPointType getPointType()
```


Ottiene o imposta il tipo del punto. PointType (1 byte): Un oggetto EmfPlusPathPointType (sezione 2.2.2.31) che specifica il tipo da associare ai punti del percorso.

Valore: Il tipo del punto.

**Returns:**
[EmfPlusPathPointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype)
### setPointType(EmfPlusPathPointType value) {#setPointType-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointType-}
```
public void setPointType(EmfPlusPathPointType value)
```


Ottiene o imposta il tipo del punto. PointType (1 byte): Un oggetto EmfPlusPathPointType (sezione 2.2.2.31) che specifica il tipo da associare ai punti del percorso.

Valore: Il tipo del punto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusPathPointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype) |  |

