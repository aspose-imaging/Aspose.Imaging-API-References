---
title: "RectangleProjectedShape"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta una forma proiettata su un rettangolo ruotato in una determinata orientazione."
type: docs
weight: 16
url: /it/java/com.aspose.imaging.shapes/rectangleprojectedshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape)
```
public abstract class RectangleProjectedShape extends Shape
```

Rappresenta una forma che viene proiettata su un rettangolo ruotato in una particolare orientazione. Specificata da quattro punti che possono essere ruotati nello spazio mantenendo la stessa lunghezza dei lati e 90 gradi tra i lati adiacenti.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLeftTop()](#getLeftTop--) | Ottiene il punto in alto a sinistra del rettangolo. |
| [getRightTop()](#getRightTop--) | Ottiene il punto in alto a destra del rettangolo. |
| [getLeftBottom()](#getLeftBottom--) | Ottiene il punto in basso a sinistra del rettangolo. |
| [getRightBottom()](#getRightBottom--) | Ottiene il punto in basso a destra del rettangolo. |
| [getCenter()](#getCenter--) | Ottiene il centro della forma. |
| [getBounds()](#getBounds--) | Ottiene i limiti dell'oggetto. |
| [getRectangleWidth()](#getRectangleWidth--) | Ottiene la larghezza del rettangolo. |
| [getRectangleHeight()](#getRectangleHeight--) | Ottiene l'altezza del rettangolo. |
| [hasSegments()](#hasSegments--) | Ottiene un valore che indica se la forma ha segmenti. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Ottiene i limiti dell'oggetto. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Ottiene i limiti dell'oggetto. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Applica la trasformazione specificata alla forma. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se l'`Object` specificato è uguale a questa istanza. |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questa istanza. |
### getLeftTop() {#getLeftTop--}
```
public PointF getLeftTop()
```


Ottiene il punto in alto a sinistra del rettangolo.

Valore: Il punto in alto a sinistra del rettangolo.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getRightTop() {#getRightTop--}
```
public PointF getRightTop()
```


Ottiene il punto in alto a destra del rettangolo.

Valore: Il punto in alto a destra del rettangolo.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getLeftBottom() {#getLeftBottom--}
```
public PointF getLeftBottom()
```


Ottiene il punto in basso a sinistra del rettangolo.

Valore: Il punto in basso a sinistra del rettangolo.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getRightBottom() {#getRightBottom--}
```
public PointF getRightBottom()
```


Ottiene il punto in basso a destra del rettangolo.

Valore: Il punto in basso a destra del rettangolo.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Ottiene il centro della forma.

Valore: Il centro della forma.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Ottiene i limiti dell'oggetto.

Valore: I limiti dell'oggetto.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getRectangleWidth() {#getRectangleWidth--}
```
public double getRectangleWidth()
```


Ottiene la larghezza del rettangolo.

Valore: La larghezza del rettangolo.

**Returns:**
double
### getRectangleHeight() {#getRectangleHeight--}
```
public double getRectangleHeight()
```


Ottiene l'altezza del rettangolo.

Valore: L'altezza del rettangolo.

**Returns:**
double
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Ottiene un valore che indica se la forma ha segmenti.

Valore: `True` se la forma ha segmenti; altrimenti, `false`.

**Returns:**
boolean
### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Ottiene i limiti dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La matrice da applicare prima che i limiti vengano calcolati. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Ottiene i limiti dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La matrice da applicare prima che i limiti vengano calcolati. |
| pen | [Pen](../../com.aspose.imaging/pen) | La penna da usare per l'oggetto. Questo può influenzare le dimensioni dei limiti dell'oggetto. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


Applica la trasformazione specificata alla forma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | La trasformazione da applicare. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se l'`Object` specificato è uguale a questa istanza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'`Object` da confrontare con questa istanza. |

**Returns:**
boolean - `true` se l'`Object` specificato è uguale a questa istanza; altrimenti, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash per questa istanza.

**Returns:**
int - Un codice hash per questa istanza, adatto per l'uso in algoritmi di hashing e strutture dati come una tabella hash.
