---
title: "EmfPlusColorMatrixEffect"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto ColorMatrixEffect specifica una trasformazione affine da applicare a un'immagine."
type: docs
weight: 29
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolormatrixeffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusColorMatrixEffect extends EmfPlusImageEffectsObjectType
```

L'oggetto ColorMatrixEffect specifica una trasformazione affine da applicare a un'immagine.

Le immagini bitmap sono specificate da oggetti EmfPlusBitmap (sezione 2.2.2.2). Un effetto matrice di colore viene eseguito moltiplicando un vettore colore per un oggetto ColorMatrixEffect. Una matrice di colore 5x5 può eseguire una trasformazione lineare, inclusa riflessione, rotazione, shear o scala seguita da una traslazione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusColorMatrixEffect()](#EmfPlusColorMatrixEffect--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getMatrixN0()](#getMatrixN0--) | Ottiene o imposta il Matrix[N][0] della matrice di colore 5x5. |
| [setMatrixN0(int[] value)](#setMatrixN0-int---) | Ottiene o imposta il Matrix[N][0] della matrice di colore 5x5. |
| [getMatrixN1()](#getMatrixN1--) | Ottiene o imposta il Matrix[N][1] della matrice di colore 5x5. |
| [setMatrixN1(int[] value)](#setMatrixN1-int---) | Ottiene o imposta il Matrix[N][1] della matrice di colore 5x5. |
| [getMatrixN2()](#getMatrixN2--) | Ottiene o imposta il Matrix[N][2] della matrice di colore 5x5. |
| [setMatrixN2(int[] value)](#setMatrixN2-int---) | Ottiene o imposta il Matrix[N][2] della matrice di colore 5x5. |
| [getMatrixN3()](#getMatrixN3--) | Ottiene o imposta il Matrix[N][3] della matrice di colore 5x5. |
| [setMatrixN3(int[] value)](#setMatrixN3-int---) | Ottiene o imposta il Matrix[N][3] della matrice di colore 5x5. |
| [getMatrixN4()](#getMatrixN4--) | Ottiene o imposta il Matrix[N][4] della matrice di colore 5x5. |
| [setMatrixN4(int[] value)](#setMatrixN4-int---) | Ottiene o imposta il Matrix[N][4] della matrice di colore 5x5. |
| [getMatrix()](#getMatrix--) | Ottiene o imposta la matrice. |
| [setMatrix(int[][] value)](#setMatrix-int-----) | Ottiene o imposta la matrice. |
### EmfPlusColorMatrixEffect() {#EmfPlusColorMatrixEffect--}
```
public EmfPlusColorMatrixEffect()
```


### getMatrixN0() {#getMatrixN0--}
```
public int[] getMatrixN0()
```


Ottiene o imposta il Matrix[N][0] della matrice di colore 5x5. Questa riga è utilizzata per le trasformazioni.

Matrix\_0\_0 (4 byte): Matrix[0][0], che è il fattore per il colore rosso. Matrix\_1\_0 (4 byte): Matrix[1][0]. Matrix\_2\_0 (4 byte): Matrix[2][0]. Matrix\_3\_0 (4 byte): Matrix[3][0]. Matrix\_4\_0 (4 byte): Matrix[4][0]. Questo valore DEVE essere 0,0.

**Returns:**
int[]
### setMatrixN0(int[] value) {#setMatrixN0-int---}
```
public void setMatrixN0(int[] value)
```


Ottiene o imposta il Matrix[N][0] della matrice di colore 5x5. Questa riga è utilizzata per le trasformazioni.

Matrix\_0\_0 (4 byte): Matrix[0][0], che è il fattore per il colore rosso. Matrix\_1\_0 (4 byte): Matrix[1][0]. Matrix\_2\_0 (4 byte): Matrix[2][0]. Matrix\_3\_0 (4 byte): Matrix[3][0]. Matrix\_4\_0 (4 byte): Matrix[4][0]. Questo valore DEVE essere 0,0.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] |  |

### getMatrixN1() {#getMatrixN1--}
```
public int[] getMatrixN1()
```


Ottiene o imposta il Matrix[N][1] della matrice di colore 5x5. Questa riga è utilizzata per le trasformazioni.

Valore: La matrice n1.

Matrix\_0\_1 (4 byte): Matrix[0][1]. Matrix\_1\_1 (4 byte): Matrix[1][1], che è il fattore per il colore verde. Matrix\_2\_1 (4 byte): Matrix[2][1]. Matrix\_3\_1 (4 byte): Matrix[3][1]. Matrix\_4\_0 (4 byte): Matrix[4][0]. Questo valore DEVE essere 0,0.

**Returns:**
int[]
### setMatrixN1(int[] value) {#setMatrixN1-int---}
```
public void setMatrixN1(int[] value)
```


Ottiene o imposta il Matrix[N][1] della matrice di colore 5x5. Questa riga è utilizzata per le trasformazioni.

Valore: La matrice n1.

Matrix\_0\_1 (4 byte): Matrix[0][1]. Matrix\_1\_1 (4 byte): Matrix[1][1], che è il fattore per il colore verde. Matrix\_2\_1 (4 byte): Matrix[2][1]. Matrix\_3\_1 (4 byte): Matrix[3][1]. Matrix\_4\_0 (4 byte): Matrix[4][0]. Questo valore DEVE essere 0,0.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] |  |

### getMatrixN2() {#getMatrixN2--}
```
public int[] getMatrixN2()
```


Ottiene o imposta il Matrix[N][2] della matrice di colore 5x5. Questa riga è utilizzata per le trasformazioni.

Valore: La matrice n1.

Matrix\_0\_2 (4 byte): Matrix[0][2]. Matrix\_1\_2 (4 byte): Matrix[1][2]. Matrix\_2\_2 (4 byte): Matrix[2][2], che è il fattore per il colore blu. Matrix\_3\_1 (4 byte): Matrix[3][1]. Matrix\_4\_0 (4 byte): Matrix[4][0]. Questo valore DEVE essere 0,0.

**Returns:**
int[]
### setMatrixN2(int[] value) {#setMatrixN2-int---}
```
public void setMatrixN2(int[] value)
```


Ottiene o imposta il Matrix[N][2] della matrice di colore 5x5. Questa riga è utilizzata per le trasformazioni.

Valore: La matrice n1.

Matrix\_0\_2 (4 byte): Matrix[0][2]. Matrix\_1\_2 (4 byte): Matrix[1][2]. Matrix\_2\_2 (4 byte): Matrix[2][2], che è il fattore per il colore blu. Matrix\_3\_1 (4 byte): Matrix[3][1]. Matrix\_4\_0 (4 byte): Matrix[4][0]. Questo valore DEVE essere 0,0.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] |  |

### getMatrixN3() {#getMatrixN3--}
```
public int[] getMatrixN3()
```


Ottiene o imposta il Matrix[N][3] della matrice di colore 5x5. Questa riga è utilizzata per le trasformazioni.

Valore: La matrice n1.

Matrix\_0\_3 (4 byte): Matrix[0][3]. Matrix\_1\_3 (4 byte): Matrix[1][3]. Matrix\_2\_3 (4 byte): Matrix[2][3]. Matrix\_3\_3 (4 byte): Matrix[3][3], che è il fattore per l'alpha (trasparenza) Matrix\_4\_0 (4 byte): Matrix[4][0]. Questo valore DEVE essere 0,0.

**Returns:**
int[]
### setMatrixN3(int[] value) {#setMatrixN3-int---}
```
public void setMatrixN3(int[] value)
```


Ottiene o imposta il Matrix[N][3] della matrice di colore 5x5. Questa riga è utilizzata per le trasformazioni.

Valore: La matrice n1.

Matrix\_0\_3 (4 byte): Matrix[0][3]. Matrix\_1\_3 (4 byte): Matrix[1][3]. Matrix\_2\_3 (4 byte): Matrix[2][3]. Matrix\_3\_3 (4 byte): Matrix[3][3], che è il fattore per l'alpha (trasparenza) Matrix\_4\_0 (4 byte): Matrix[4][0]. Questo valore DEVE essere 0,0.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] |  |

### getMatrixN4() {#getMatrixN4--}
```
public int[] getMatrixN4()
```


Ottiene o imposta la Matrix[N][4] della matrice di colore 5x5. Questa riga è utilizzata per le traduzioni di colore.

Valore: La matrice n1.

Matrix\_0\_4 (4 byte): Matrix[0][4]. Matrix\_1\_4 (4 byte): Matrix[1][4]. Matrix\_2\_4 (4 byte): Matrix[2][4]. Matrix\_3\_4 (4 byte): Matrix[3][4]. Matrix\_4\_4 (4 byte): Matrix[4][4]. Questo valore DOVREBBE essere 1.0.

**Returns:**
int[]
### setMatrixN4(int[] value) {#setMatrixN4-int---}
```
public void setMatrixN4(int[] value)
```


Ottiene o imposta la Matrix[N][4] della matrice di colore 5x5. Questa riga è utilizzata per le traduzioni di colore.

Valore: La matrice n1.

Matrix\_0\_4 (4 byte): Matrix[0][4]. Matrix\_1\_4 (4 byte): Matrix[1][4]. Matrix\_2\_4 (4 byte): Matrix[2][4]. Matrix\_3\_4 (4 byte): Matrix[3][4]. Matrix\_4\_4 (4 byte): Matrix[4][4]. Questo valore DOVREBBE essere 1.0.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] |  |

### getMatrix() {#getMatrix--}
```
public int[][] getMatrix()
```


Ottiene o imposta la matrice.

Valore: La matrice.

**Returns:**
int[][]
### setMatrix(int[][] value) {#setMatrix-int-----}
```
public void setMatrix(int[][] value)
```


Ottiene o imposta la matrice.

Valore: La matrice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[][] |  |

