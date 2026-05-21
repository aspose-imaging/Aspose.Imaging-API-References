---
title: "Matrix"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Sostituisce la GDI Matrix."
type: docs
weight: 72
url: /it/java/com.aspose.imaging/matrix/
---
**Inheritance:**
java.lang.Object
```
public class Matrix
```

Sostituisce la matrice GDI+.

--------------------

La maggior parte degli algoritmi è presa da AffineTransform.java di Sun. Nomi Java per gli elementi della matrice usati internamente. Mappa dei nomi Java a quelli .net con descrizione: m00 M11 Scala X m10 M12 Scostamento Y m01 M21 Scostamento X m11 M22 Scala Y m02 M31 Traslazione X m12 M32 Traslazione Y
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Matrix()](#Matrix--) | Inizializza una nuova istanza della classe Matrix come matrice identità. |
| [Matrix(float m11, float m12, float m21, float m22, float m31, float m32)](#Matrix-float-float-float-float-float-float-) | Inizializza una nuova istanza della classe [Matrix](../../com.aspose.imaging/matrix). |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.imaging.RectangleF-com.aspose.imaging.PointF---) | Inizializza una nuova istanza della classe [Matrix](../../com.aspose.imaging/matrix) alla trasformazione geometrica definita dal rettangolo specificato e dall'array di punti. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.imaging.Rectangle-com.aspose.imaging.Point---) | Inizializza una nuova istanza della classe [Matrix](../../com.aspose.imaging/matrix) alla trasformazione geometrica definita dal rettangolo specificato e dall'array di punti. |
| [Matrix(Matrix origin)](#Matrix-com.aspose.imaging.Matrix-) | Crea una copia della classe [Matrix](../../com.aspose.imaging/matrix). |
## Campi

| Campo | Descrizione |
| --- | --- |
| [TYPE_IDENTITY](#TYPE-IDENTITY) | Una trasformazione identità è quella in cui le coordinate di output sono sempre le stesse delle coordinate di input. |
| [TYPE_TRANSLATION](#TYPE-TRANSLATION) | Una traslazione sposta le coordinate di una quantità costante in x e y senza modificare la lunghezza o l'angolo dei vettori. |
| [TYPE_UNIFORM_SCALE](#TYPE-UNIFORM-SCALE) | Una scala uniforme moltiplica la lunghezza dei vettori della stessa quantità sia nella direzione x che nella y senza cambiare l'angolo tra i vettori. |
| [TYPE_GENERAL_SCALE](#TYPE-GENERAL-SCALE) | Una scala generale moltiplica la lunghezza dei vettori di quantità diverse nelle direzioni x e y senza modificare l'angolo tra vettori perpendicolari. |
| [TYPE_MASK_SCALE](#TYPE-MASK-SCALE) | Questa costante è una maschera di bit per uno qualsiasi dei bit di flag di scala. |
| [TYPE_FLIP](#TYPE-FLIP) | Questo bit di flag indica che la trasformazione definita da questo oggetto esegue un ribaltamento speculare attorno a qualche asse, che trasforma il normale sistema di coordinate destro in un sistema sinistro, oltre alle conversioni indicate dagli altri bit di flag. |
| [TYPE_QUADRANT_ROTATION](#TYPE-QUADRANT-ROTATION) | Questo bit di flag indica che la trasformazione definita da questo oggetto esegue una rotazione di quadrante di un multiplo di 90 gradi, oltre alle conversioni indicate dagli altri bit di flag. |
| [TYPE_GENERAL_ROTATION](#TYPE-GENERAL-ROTATION) | Questo bit di flag indica che la trasformazione definita da questo oggetto esegue una rotazione di un angolo arbitrario, oltre alle conversioni indicate dagli altri bit di flag. |
| [TYPE_MASK_ROTATION](#TYPE-MASK-ROTATION) | Questa costante è una maschera di bit per uno qualsiasi dei bit di flag di rotazione. |
| [TYPE_GENERAL_TRANSFORM](#TYPE-GENERAL-TRANSFORM) | Questa costante indica che la trasformazione definita da questo oggetto esegue una conversione arbitraria delle coordinate di input. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isEquals(Matrix a, Matrix b)](#isEquals-com.aspose.imaging.Matrix-com.aspose.imaging.Matrix-) | Determina se due matrici sono uguali. |
| [getM11()](#getM11--) | Restituisce l'elemento della matrice nella prima riga, prima colonna. |
| [getM12()](#getM12--) | Restituisce l'elemento della matrice nella prima riga, seconda colonna. |
| [getM21()](#getM21--) | Restituisce l'elemento della matrice nella seconda riga, prima colonna. |
| [getM22()](#getM22--) | Restituisce l'elemento della matrice nella seconda riga, seconda colonna. |
| [getM31()](#getM31--) | Restituisce l'elemento della matrice nella terza riga, prima colonna. |
| [getM32()](#getM32--) | Restituisce l'elemento della matrice nella terza riga, prima colonna. |
| [toString()](#toString--) | Restituisce una String che rappresenta questa istanza. |
| [getElements()](#getElements--) | Restituisce una copia degli elementi della matrice. |
| [transformPoints(PointF[] points)](#transformPoints-com.aspose.imaging.PointF---) | Applica la trasformazione geometrica rappresentata da questa [Matrix](../../com.aspose.imaging/matrix) a un array specificato di punti. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | Applica il vettore di scala specificato (scaleX e scaleY) a questa [Matrix](../../com.aspose.imaging/matrix) usando l'ordine specificato. |
| [scale(float sx, float sy)](#scale-float-float-) | Applica il vettore di scala specificato (scaleX e scaleY) a questa Matrix usando l'ordine (predefinito) Prepend. |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | Applica il vettore di traslazione specificato a questa Matrix nell'ordine specificato. |
| [translate(float tx, float ty)](#translate-float-float-) | Applica il vettore di traslazione specificato a questa [Matrix](../../com.aspose.imaging/matrix) usando l'ordine (predefinito) Prepend. |
| [multiply(Matrix tTx, int order)](#multiply-com.aspose.imaging.Matrix-int-) | Moltiplica questa Matrix per la matrice specificata nel parametro matrix e nell'ordine specificato nel parametro order. |
| [multiply(Matrix tTx)](#multiply-com.aspose.imaging.Matrix-) | Moltiplica questa Matrix per la matrice specificata nel parametro matrix usando l'ordine (predefinito) Prepend. |
| [rotate(float angle, int order)](#rotate-float-int-) | Applica una rotazione in senso orario di un valore specificato nel parametro angle, attorno all'origine (coordinate x e y zero) per questa Matrix nell'ordine specificato. |
| [rotate(float angle)](#rotate-float-) | Applica una rotazione in senso orario di un valore specificato nel parametro angle, attorno all'origine (coordinate x e y zero) per questa Matrix nell'ordine predefinito (Prepend). |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.imaging.PointF-int-) | Applica una rotazione in senso orario attorno al punto specificato a questa Matrix nell'ordine specificato. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.imaging.PointF-) | Applica una rotazione in senso orario attorno al punto specificato a questa Matrix nell'ordine predefinito (Prepend). |
| [reset()](#reset--) | Reimposta questa Matrice in modo che contenga gli elementi della matrice identità. |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questa istanza. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se l'`Object` specificato è uguale a questa istanza. |
| [isIdentity()](#isIdentity--) | Restituisce `true` se questo `AffineTransform` è una trasformazione identità. |
### Matrix() {#Matrix--}
```
public Matrix()
```


Inizializza una nuova istanza della classe Matrix come matrice identità.

### Matrix(float m11, float m12, float m21, float m22, float m31, float m32) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```


Inizializza una nuova istanza della classe [Matrix](../../com.aspose.imaging/matrix).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| m11 | float | m00 M11 Scala X |
| m12 | float | m10 M12 Taglio Y |
| m21 | float | m01 M21 Taglio X |
| m22 | float | m11 M22 Scala Y |
| m31 | float | m02 M31 Traslazione X |
| m32 | float | m12 M32 Traslazione Y |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.imaging.RectangleF-com.aspose.imaging.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


Inizializza una nuova istanza della classe [Matrix](../../com.aspose.imaging/matrix) alla trasformazione geometrica definita dal rettangolo specificato e dall'array di punti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Una struttura [RectangleF](../../com.aspose.imaging/rectanglef) che rappresenta il rettangolo da trasformare. |
| plgpts | [PointF\[\]](../../com.aspose.imaging/pointf) | Un array di tre strutture [PointF](../../com.aspose.imaging/pointf) che rappresentano i punti di un parallelogramma verso il quale verranno trasformati gli angoli superiore sinistro, superiore destro e inferiore sinistro del rettangolo. L'angolo inferiore destro del parallelogramma è implicito nei primi tre angoli. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.imaging.Rectangle-com.aspose.imaging.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


Inizializza una nuova istanza della classe [Matrix](../../com.aspose.imaging/matrix) alla trasformazione geometrica definita dal rettangolo specificato e dall'array di punti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Una struttura [Rectangle](../../com.aspose.imaging/rectangle) che rappresenta il rettangolo da trasformare. |
| plgpts | [Point\[\]](../../com.aspose.imaging/point) | Un array di tre strutture [Point](../../com.aspose.imaging/point) che rappresentano i punti di un parallelogramma verso il quale verranno trasformati gli angoli superiore sinistro, superiore destro e inferiore sinistro del rettangolo. L'angolo inferiore destro del parallelogramma è implicito nei primi tre angoli. |

### Matrix(Matrix origin) {#Matrix-com.aspose.imaging.Matrix-}
```
public Matrix(Matrix origin)
```


Crea una copia della classe [Matrix](../../com.aspose.imaging/matrix).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| origin | [Matrix](../../com.aspose.imaging/matrix) | Una matrice di base per l'adattamento. |

### TYPE_IDENTITY {#TYPE-IDENTITY}
```
public static final int TYPE_IDENTITY
```


Una trasformazione identità è quella in cui le coordinate di output sono sempre le stesse delle coordinate di input. Se questa trasformazione è diversa dalla trasformazione identità, il tipo sarà o la costante GENERAL\_TRANSFORM o una combinazione dei flag appropriati per le varie conversioni di coordinate che questa trasformazione esegue.

### TYPE_TRANSLATION {#TYPE-TRANSLATION}
```
public static final int TYPE_TRANSLATION
```


Una traslazione sposta le coordinate di una quantità costante in x e y senza modificare la lunghezza o l'angolo dei vettori.

### TYPE_UNIFORM_SCALE {#TYPE-UNIFORM-SCALE}
```
public static final int TYPE_UNIFORM_SCALE
```


Una scala uniforme moltiplica la lunghezza dei vettori della stessa quantità sia nella direzione x che nella direzione y senza modificare l'angolo tra i vettori. Questo bit di flag è mutuamente esclusivo dal flag TypeGeneralScale.

### TYPE_GENERAL_SCALE {#TYPE-GENERAL-SCALE}
```
public static final int TYPE_GENERAL_SCALE
```


Una scala generale moltiplica la lunghezza dei vettori di quantità diverse nelle direzioni x e y senza modificare l'angolo tra vettori perpendicolari. Questo bit di flag è mutuamente esclusivo dal flag TypeUniformScale.

### TYPE_MASK_SCALE {#TYPE-MASK-SCALE}
```
public static final int TYPE_MASK_SCALE
```


Questa costante è una maschera di bit per uno qualsiasi dei bit di flag di scala.

### TYPE_FLIP {#TYPE-FLIP}
```
public static final int TYPE_FLIP
```


Questo bit di flag indica che la trasformazione definita da questo oggetto esegue un ribaltamento a specchio attorno a qualche asse, il quale trasforma il normale sistema di coordinate destro in un sistema sinistro, oltre alle conversioni indicate dagli altri bit di flag. Un sistema di coordinate destro è quello in cui l'asse X positivo ruota in senso antiorario per sovrapporsi all'asse Y positivo, simile alla direzione in cui le dita della mano destra si avvolgono quando si guarda il pollice di profilo. Un sistema di coordinate sinistro è quello in cui l'asse X positivo ruota in senso orario per sovrapporsi all'asse Y positivo, simile alla direzione in cui le dita della mano sinistra si avvolgono. Non esiste un metodo matematico per determinare l'angolo della trasformazione di ribaltamento o specchiatura originale, poiché tutti gli angoli di ribaltamento sono identici dato un'adeguata rotazione di aggiustamento. NOTA: TypeFlip è stato aggiunto dopo che GENERAL\_TRANSFORM era già in circolazione pubblica e i bit di flag non potevano più essere rinumerati comodamente senza introdurre incompatibilità binarie nel codice esterno.

### TYPE_QUADRANT_ROTATION {#TYPE-QUADRANT-ROTATION}
```
public static final int TYPE_QUADRANT_ROTATION
```


Questo bit di flag indica che la trasformazione definita da questo oggetto esegue una rotazione di quadrante di un multiplo di 90 gradi, oltre alle conversioni indicate dagli altri bit di flag. Una rotazione modifica gli angoli dei vettori della stessa quantità indipendentemente dalla direzione originale del vettore e senza alterare la lunghezza del vettore. Questo bit di flag è mutuamente esclusivo dal flag TypeGeneralRotation.

### TYPE_GENERAL_ROTATION {#TYPE-GENERAL-ROTATION}
```
public static final int TYPE_GENERAL_ROTATION
```


Questo bit di flag indica che la trasformazione definita da questo oggetto esegue una rotazione di un angolo arbitrario oltre alle conversioni indicate da altri bit di flag. Una rotazione cambia gli angoli dei vettori della stessa quantità indipendentemente dalla direzione originale del vettore e senza modificare la lunghezza del vettore. Questo bit di flag è mutuamente esclusivo con il

### TYPE_MASK_ROTATION {#TYPE-MASK-ROTATION}
```
public static final int TYPE_MASK_ROTATION
```


Questa costante è una maschera di bit per uno qualsiasi dei bit di flag di rotazione.

### TYPE_GENERAL_TRANSFORM {#TYPE-GENERAL-TRANSFORM}
```
public static final int TYPE_GENERAL_TRANSFORM
```


Questa costante indica che la trasformazione definita da questo oggetto esegue una conversione arbitraria delle coordinate di input. Se questa trasformazione può essere classificata da una delle costanti sopra, il tipo sarà oppure la costante TypeIdentity oppure una combinazione dei bit di flag appropriati per le varie conversioni di coordinate che questa trasformazione esegue.

### isEquals(Matrix a, Matrix b) {#isEquals-com.aspose.imaging.Matrix-com.aspose.imaging.Matrix-}
```
public static boolean isEquals(Matrix a, Matrix b)
```


Determina se due matrici sono uguali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Matrix](../../com.aspose.imaging/matrix) | La prima matrice da confrontare. |
| b | [Matrix](../../com.aspose.imaging/matrix) | La seconda matrice da confrontare. |

**Returns:**
boolean - True se le matrici sono uguali.
### getM11() {#getM11--}
```
public final float getM11()
```


Restituisce l'elemento della matrice alla prima riga prima colonna. Rappresenta la scala lungo l'asse X.

**Returns:**
float - l'elemento della matrice alla prima riga prima colonna.
### getM12() {#getM12--}
```
public final float getM12()
```


Restituisce l'elemento della matrice alla prima riga seconda colonna. Rappresenta lo shear lungo l'asse Y.

**Returns:**
float - l'elemento della matrice alla prima riga seconda colonna.
### getM21() {#getM21--}
```
public final float getM21()
```


Restituisce l'elemento della matrice alla seconda riga prima colonna. Rappresenta lo shear lungo l'asse X.

**Returns:**
float - l'elemento della matrice alla seconda riga prima colonna.
### getM22() {#getM22--}
```
public final float getM22()
```


Restituisce l'elemento della matrice alla seconda riga seconda colonna. Rappresenta la scala lungo l'asse Y.

**Returns:**
float - l'elemento della matrice alla seconda riga seconda colonna.
### getM31() {#getM31--}
```
public final float getM31()
```


Restituisce l'elemento della matrice alla terza riga prima colonna. Rappresenta la traslazione lungo l'asse X.

**Returns:**
float - l'elemento della matrice alla terza riga prima colonna.
### getM32() {#getM32--}
```
public final float getM32()
```


Restituisce l'elemento della matrice alla terza riga prima colonna. Rappresenta la traslazione lungo l'asse Y.

**Returns:**
float - l'elemento della matrice alla terza riga prima colonna.
### toString() {#toString--}
```
public String toString()
```


Restituisce una String che rappresenta questa istanza.

**Returns:**
java.lang.String - Una stringa che rappresenta questa istanza.
### getElements() {#getElements--}
```
public final float[] getElements()
```


Restituisce una copia degli elementi della matrice.

**Returns:**
float[] - Una copia degli elementi della matrice.
### transformPoints(PointF[] points) {#transformPoints-com.aspose.imaging.PointF---}
```
public final void transformPoints(PointF[] points)
```


Applica la trasformazione geometrica rappresentata da questa [Matrix](../../com.aspose.imaging/matrix) a un array specificato di punti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | I punti. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public final void scale(float scaleX, float scaleY, int order)
```


Applica il vettore di scala specificato (scaleX e scaleY) a questa [Matrix](../../com.aspose.imaging/matrix) usando l'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scaleX | float | La scala X. |
| scaleY | float | La scala Y. |
| order | int | L'ordine. |

### scale(float sx, float sy) {#scale-float-float-}
```
public final void scale(float sx, float sy)
```


Applica il vettore di scala specificato (scaleX e scaleY) a questa Matrix usando l'ordine (predefinito) Prepend.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sx | float | Il sx. Il sx. Il sx. |
| sy | float | Il sy. Il sy. Il sy. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public final void translate(float offsetX, float offsetY, int order)
```


Applica il vettore di traslazione specificato a questa Matrix nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| offsetX | float | L'offset X. |
| offsetY | float | L'offset Y. |
| order | int | L'ordine. |

### translate(float tx, float ty) {#translate-float-float-}
```
public final void translate(float tx, float ty)
```


Applica il vettore di traslazione specificato a questa [Matrix](../../com.aspose.imaging/matrix) usando l'ordine (predefinito) Prepend.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tx | float | Il tx. Il tx. Il tx. |
| ty | float | Il ty. Il ty. Il ty. |

### multiply(Matrix tTx, int order) {#multiply-com.aspose.imaging.Matrix-int-}
```
public final void multiply(Matrix tTx, int order)
```


Moltiplica questa Matrix per la matrice specificata nel parametro matrix e nell'ordine specificato nel parametro order.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tTx | [Matrix](../../com.aspose.imaging/matrix) | Il tx. Il tx. Il tx. |
| order | int | L'ordine. L'ordine. L'ordine. |

### multiply(Matrix tTx) {#multiply-com.aspose.imaging.Matrix-}
```
public final void multiply(Matrix tTx)
```


Moltiplica questa Matrix per la matrice specificata nel parametro matrix usando l'ordine (predefinito) Prepend.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tTx | [Matrix](../../com.aspose.imaging/matrix) | La matrice con cui moltiplicare. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public final void rotate(float angle, int order)
```


Applica una rotazione in senso orario di un valore specificato nel parametro angle, attorno all'origine (coordinate x e y zero) per questa Matrix nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | L'angolo di rotazione. |
| order | int | L'ordine della matrice. |

### rotate(float angle) {#rotate-float-}
```
public final void rotate(float angle)
```


Applica una rotazione in senso orario di un valore specificato nel parametro angle, attorno all'origine (coordinate x e y zero) per questa Matrix nell'ordine predefinito (Prepend).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | L'angolo di rotazione. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.imaging.PointF-int-}
```
public final void rotateAt(float angle, PointF point, int order)
```


Applica una rotazione in senso orario attorno al punto specificato a questa Matrix nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | L'angolo. |
| point | [PointF](../../com.aspose.imaging/pointf) | Il punto. |
| order | int | L'ordine. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.imaging.PointF-}
```
public final void rotateAt(float angle, PointF point)
```


Applica una rotazione in senso orario attorno al punto specificato a questa Matrix nell'ordine predefinito (Prepend).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | L'angolo. |
| point | [PointF](../../com.aspose.imaging/pointf) | Il punto. |

### reset() {#reset--}
```
public final void reset()
```


Reimposta questa Matrice in modo che contenga gli elementi della matrice identità.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash per questa istanza.

**Returns:**
int - Un codice hash per questa istanza, adatto per l'uso in algoritmi di hashing e strutture dati come una tabella hash.
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
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


Restituisce `true` se questo `AffineTransform` è una trasformazione identità.

**Returns:**
boolean - `true` se questo `AffineTransform` è una trasformazione identità; `false` altrimenti.
