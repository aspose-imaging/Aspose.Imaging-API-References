---
title: "TransformBrush"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Un Brush con capacità di trasformazione."
type: docs
weight: 19
url: /it/java/com.aspose.imaging.brushes/transformbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush)
```
public abstract class TransformBrush extends Brush
```

Un `Brush` con capacità di trasformazione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TransformBrush()](#TransformBrush--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getWrapMode()](#getWrapMode--) | Ottiene o imposta una enumerazione `Aspose.Imaging.WrapMode` che indica la modalità di avvolgimento per questo `TransformBrush`. |
| [setWrapMode(int value)](#setWrapMode-int-) | Ottiene o imposta una enumerazione `Aspose.Imaging.WrapMode` che indica la modalità di avvolgimento per questo `TransformBrush`. |
| [getTransform()](#getTransform--) | Ottiene o imposta una copia di `Aspose.Imaging.Matrix` che definisce una trasformazione geometrica locale per questo `TransformBrush`. |
| [setTransform(Matrix value)](#setTransform-com.aspose.imaging.Matrix-) | Ottiene o imposta una copia di `Aspose.Imaging.Matrix` che definisce una trasformazione geometrica locale per questo `TransformBrush`. |
| [isTransformChanged()](#isTransformChanged--) | Ottiene un valore che indica se le trasformazioni sono state modificate in qualche modo. |
| [resetTransform()](#resetTransform--) | Reimposta la proprietà `TransformBrush.Transform` all'identità. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | Moltiplica la `Aspose.Imaging.Matrix` che rappresenta la trasformazione geometrica locale di questo `LinearGradientBrush` per la `Aspose.Imaging.Matrix` specificata, anteponendo la `Aspose.Imaging.Matrix` specificata. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | Moltiplica la `Aspose.Imaging.Matrix` che rappresenta la trasformazione geometrica locale di questo `LinearGradientBrush` per la `Aspose.Imaging.Matrix` specificata nell'ordine specificato. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Trasla la trasformazione geometrica locale delle dimensioni specificate. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Scala la trasformazione geometrica locale delle quantità specificate. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Scala la trasformazione geometrica locale delle quantità specificate nell'ordine specificato. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Ruota la trasformazione geometrica locale della quantità specificata. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Ruota la trasformazione geometrica locale della quantità specificata nell'ordine specificato. |
### TransformBrush() {#TransformBrush--}
```
public TransformBrush()
```


### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Ottiene o imposta una enumerazione `Aspose.Imaging.WrapMode` che indica la modalità di avvolgimento per questo `TransformBrush`.

**Returns:**
int - Un `Aspose.Imaging.WrapMode` che specifica come vengono ripetuti i riempimenti disegnati con questo `TransformBrush`.
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Ottiene o imposta una enumerazione `Aspose.Imaging.WrapMode` che indica la modalità di avvolgimento per questo `TransformBrush`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Ottiene o imposta una copia di `Aspose.Imaging.Matrix` che definisce una trasformazione geometrica locale per questo `TransformBrush`.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - A copy of the `Aspose.Imaging.Matrix` that defines a geometric transform that applies only to fills drawn with this `TransformBrush`.
### setTransform(Matrix value) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix value)
```


Ottiene o imposta una copia di `Aspose.Imaging.Matrix` che definisce una trasformazione geometrica locale per questo `TransformBrush`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### isTransformChanged() {#isTransformChanged--}
```
public boolean isTransformChanged()
```


Restituisce un valore che indica se le trasformazioni sono state modificate in qualche modo. Ad esempio impostando la matrice di trasformazione o chiamando uno dei metodi che alterano la matrice di trasformazione. La proprietà è introdotta per compatibilità retroattiva con GDI+.

Valore: `True` se la trasformazione è stata modificata; altrimenti, `false`.

**Returns:**
boolean
### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Reimposta la proprietà `TransformBrush.Transform` all'identità.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.imaging.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Moltiplica la `Aspose.Imaging.Matrix` che rappresenta la trasformazione geometrica locale di questo `LinearGradientBrush` per la `Aspose.Imaging.Matrix` specificata, anteponendo la `Aspose.Imaging.Matrix` specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La `Aspose.Imaging.Matrix` con cui moltiplicare la trasformazione geometrica. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Moltiplica la `Aspose.Imaging.Matrix` che rappresenta la trasformazione geometrica locale di questo `LinearGradientBrush` per la `Aspose.Imaging.Matrix` specificata nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La `Aspose.Imaging.Matrix` con cui moltiplicare la trasformazione geometrica. |
| order | int | Un `Aspose.Imaging.MatrixOrder` che specifica in quale ordine moltiplicare le due matrici. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Trasla la trasformazione geometrica locale delle dimensioni specificate. Questo metodo antepone la traslazione alla trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dx | float | Il valore della traslazione in x. |
| dy | float | Il valore della traslazione in y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dx | float | Il valore della traslazione in x. |
| dy | float | Il valore della traslazione in y. |
| order | int | L'ordine (anteporre o aggiungere) con cui applicare la traslazione. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Scala la trasformazione geometrica locale delle quantità specificate. Questo metodo antepone la matrice di scala alla trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sx | float | La quantità di scala da applicare alla trasformazione nella direzione dell'asse x. |
| sy | float | La quantità di scala da applicare alla trasformazione nella direzione dell'asse y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Scala la trasformazione geometrica locale delle quantità specificate nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sx | float | La quantità di scala da applicare alla trasformazione nella direzione dell'asse x. |
| sy | float | La quantità di scala da applicare alla trasformazione nella direzione dell'asse y. |
| order | int | Un `Aspose.Imaging.MatrixOrder` che specifica se aggiungere o anteporre la matrice di scala. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Ruota la trasformazione geometrica locale della quantità specificata. Questo metodo antepone la rotazione alla trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | L'angolo di rotazione. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Ruota la trasformazione geometrica locale della quantità specificata nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | L'angolo di rotazione. |
| order | int | Un `Aspose.Imaging.MatrixOrder` che specifica se aggiungere o anteporre la matrice di rotazione. |

