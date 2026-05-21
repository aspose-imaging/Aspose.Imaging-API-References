---
title: "Matrix"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Reemplaza la matriz GDI."
type: docs
weight: 72
url: /es/java/com.aspose.imaging/matrix/
---
**Inheritance:**
java.lang.Object
```
public class Matrix
```

Reemplaza la matriz GDI+.

--------------------

La mayoría de los algoritmos se tomaron de AffineTransform.java de Sun. Nombres de Java para los elementos de la matriz usados internamente. Mapa de nombres de Java a los de .net con descripción: m00 M11 Escala X m10 M12 Cizalladura Y m01 M21 Cizalladura X m11 M22 Escala Y m02 M31 Traslación X m12 M32 Traslación Y
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Matrix()](#Matrix--) | Inicializa una nueva instancia de la clase Matrix como la matriz identidad. |
| [Matrix(float m11, float m12, float m21, float m22, float m31, float m32)](#Matrix-float-float-float-float-float-float-) | Inicializa una nueva instancia de la clase [Matrix](../../com.aspose.imaging/matrix). |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.imaging.RectangleF-com.aspose.imaging.PointF---) | Inicializa una nueva instancia de la clase [Matrix](../../com.aspose.imaging/matrix) con la transformación geométrica definida por el rectángulo especificado y la matriz de puntos. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.imaging.Rectangle-com.aspose.imaging.Point---) | Inicializa una nueva instancia de la clase [Matrix](../../com.aspose.imaging/matrix) con la transformación geométrica definida por el rectángulo especificado y la matriz de puntos. |
| [Matrix(Matrix origin)](#Matrix-com.aspose.imaging.Matrix-) | Crea una copia de la clase [Matrix](../../com.aspose.imaging/matrix). |
## Campos

| Campo | Descripción |
| --- | --- |
| [TYPE_IDENTITY](#TYPE-IDENTITY) | Una transformación identidad es aquella en la que las coordenadas de salida son siempre las mismas que las coordenadas de entrada. |
| [TYPE_TRANSLATION](#TYPE-TRANSLATION) | Una traslación mueve las coordenadas una cantidad constante en x e y sin cambiar la longitud o el ángulo de los vectores. |
| [TYPE_UNIFORM_SCALE](#TYPE-UNIFORM-SCALE) | Una escala uniforme multiplica la longitud de los vectores por la misma cantidad en las direcciones x e y sin cambiar el ángulo entre los vectores. |
| [TYPE_GENERAL_SCALE](#TYPE-GENERAL-SCALE) | Una escala general multiplica la longitud de los vectores por diferentes cantidades en las direcciones x e y sin cambiar el ángulo entre vectores perpendiculares. |
| [TYPE_MASK_SCALE](#TYPE-MASK-SCALE) | Esta constante es una máscara de bits para cualquiera de los bits de bandera de escala. |
| [TYPE_FLIP](#TYPE-FLIP) | Este bit de bandera indica que la transformación definida por este objeto realiza una inversión de imagen espejo alrededor de algún eje, lo que cambia el sistema de coordenadas normalmente derecho a uno izquierdo, además de las conversiones indicadas por otros bits de bandera. |
| [TYPE_QUADRANT_ROTATION](#TYPE-QUADRANT-ROTATION) | Este bit de bandera indica que la transformación definida por este objeto realiza una rotación de cuadrante por un múltiplo de 90 grados, además de las conversiones indicadas por otros bits de bandera. |
| [TYPE_GENERAL_ROTATION](#TYPE-GENERAL-ROTATION) | Este bit de bandera indica que la transformación definida por este objeto realiza una rotación por un ángulo arbitrario, además de las conversiones indicadas por otros bits de bandera. |
| [TYPE_MASK_ROTATION](#TYPE-MASK-ROTATION) | Esta constante es una máscara de bits para cualquiera de los bits de bandera de rotación. |
| [TYPE_GENERAL_TRANSFORM](#TYPE-GENERAL-TRANSFORM) | Esta constante indica que la transformación definida por este objeto realiza una conversión arbitraria de las coordenadas de entrada. |
## Métodos

| Método | Descripción |
| --- | --- |
| [isEquals(Matrix a, Matrix b)](#isEquals-com.aspose.imaging.Matrix-com.aspose.imaging.Matrix-) | Determina si dos matrices son iguales. |
| [getM11()](#getM11--) | Obtiene el elemento de la matriz en la primera fila, primera columna. |
| [getM12()](#getM12--) | Obtiene el elemento de la matriz en la primera fila, segunda columna. |
| [getM21()](#getM21--) | Obtiene el elemento de la matriz en la segunda fila, primera columna. |
| [getM22()](#getM22--) | Obtiene el elemento de la matriz en la segunda fila, segunda columna. |
| [getM31()](#getM31--) | Obtiene el elemento de la matriz en la tercera fila, primera columna. |
| [getM32()](#getM32--) | Obtiene el elemento de la matriz en la tercera fila, primera columna. |
| [toString()](#toString--) | Devuelve una cadena que representa esta instancia. |
| [getElements()](#getElements--) | Obtiene una copia de los elementos de la matriz. |
| [transformPoints(PointF[] points)](#transformPoints-com.aspose.imaging.PointF---) | Aplica la transformación geométrica representada por este [Matrix](../../com.aspose.imaging/matrix) a una matriz especificada de puntos. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | Aplica el vector de escala especificado (scaleX y scaleY) a este [Matrix](../../com.aspose.imaging/matrix) usando el orden especificado. |
| [scale(float sx, float sy)](#scale-float-float-) | Aplica el vector de escala especificado (scaleX y scaleY) a este Matrix usando el orden (predeterminado) Prepend. |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | Aplica el vector de traslación especificado a este Matrix en el orden especificado. |
| [translate(float tx, float ty)](#translate-float-float-) | Aplica el vector de traslación especificado a este [Matrix](../../com.aspose.imaging/matrix) usando el orden (predeterminado) Prepend. |
| [multiply(Matrix tTx, int order)](#multiply-com.aspose.imaging.Matrix-int-) | Multiplica este Matrix por la matriz especificada en el parámetro matrix, y en el orden especificado en el parámetro order. |
| [multiply(Matrix tTx)](#multiply-com.aspose.imaging.Matrix-) | Multiplica este Matrix por la matriz especificada en el parámetro matrix usando el orden (predeterminado) Prepend. |
| [rotate(float angle, int order)](#rotate-float-int-) | Aplica una rotación en sentido horario de una cantidad especificada en el parámetro angle, alrededor del origen (coordenadas x e y cero) para este Matrix en el orden especificado. |
| [rotate(float angle)](#rotate-float-) | Aplica una rotación en sentido horario de una cantidad especificada en el parámetro angle, alrededor del origen (coordenadas x e y cero) para este Matrix en el orden predeterminado (Prepend). |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.imaging.PointF-int-) | Aplica una rotación en sentido horario alrededor del punto especificado a este Matrix en el orden especificado. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.imaging.PointF-) | Aplica una rotación en sentido horario alrededor del punto especificado a este Matrix en el orden predeterminado (Prepend). |
| [reset()](#reset--) | Restablece esta Matriz para que tenga los elementos de la matriz identidad. |
| [hashCode()](#hashCode--) | Devuelve un código hash para esta instancia. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el `Object` especificado es igual a esta instancia. |
| [isIdentity()](#isIdentity--) | Devuelve `true` si este `AffineTransform` es una transformación de identidad. |
### Matrix() {#Matrix--}
```
public Matrix()
```


Inicializa una nueva instancia de la clase Matrix como la matriz identidad.

### Matrix(float m11, float m12, float m21, float m22, float m31, float m32) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```


Inicializa una nueva instancia de la clase [Matrix](../../com.aspose.imaging/matrix).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| m11 | float | m00 M11 Escala X |
| m12 | float | m10 M12 Cizalla Y |
| m21 | float | m01 M21 Cizalla X |
| m22 | float | m11 M22 Escala Y |
| m31 | float | m02 M31 Trasladar X |
| m32 | float | m12 M32 Trasladar Y |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.imaging.RectangleF-com.aspose.imaging.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


Inicializa una nueva instancia de la clase [Matrix](../../com.aspose.imaging/matrix) con la transformación geométrica definida por el rectángulo especificado y la matriz de puntos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Una estructura [RectangleF](../../com.aspose.imaging/rectanglef) que representa el rectángulo a transformar. |
| plgpts | [PointF\[\]](../../com.aspose.imaging/pointf) | Una matriz de tres estructuras [PointF](../../com.aspose.imaging/pointf) que representa los puntos de un paralelogramo al que se transformarán las esquinas superior izquierda, superior derecha e inferior izquierda del rectángulo. La esquina inferior derecha del paralelogramo se deduce de las tres primeras esquinas. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.imaging.Rectangle-com.aspose.imaging.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


Inicializa una nueva instancia de la clase [Matrix](../../com.aspose.imaging/matrix) con la transformación geométrica definida por el rectángulo especificado y la matriz de puntos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Una estructura [Rectangle](../../com.aspose.imaging/rectangle) que representa el rectángulo a transformar. |
| plgpts | [Point\[\]](../../com.aspose.imaging/point) | Una matriz de tres estructuras [Point](../../com.aspose.imaging/point) que representa los puntos de un paralelogramo al que se transformarán las esquinas superior izquierda, superior derecha e inferior izquierda del rectángulo. La esquina inferior derecha del paralelogramo se deduce de las tres primeras esquinas. |

### Matrix(Matrix origin) {#Matrix-com.aspose.imaging.Matrix-}
```
public Matrix(Matrix origin)
```


Crea una copia de la clase [Matrix](../../com.aspose.imaging/matrix).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| origin | [Matrix](../../com.aspose.imaging/matrix) | Una matriz base para coping |

### TYPE_IDENTITY {#TYPE-IDENTITY}
```
public static final int TYPE_IDENTITY
```


Una transformación de identidad es aquella en la que las coordenadas de salida son siempre las mismas que las coordenadas de entrada. Si esta transformación es distinta de la transformación de identidad, el tipo será la constante GENERAL\_TRANSFORM o una combinación de los bits de bandera apropiados para las diversas conversiones de coordenadas que realiza esta transformación.

### TYPE_TRANSLATION {#TYPE-TRANSLATION}
```
public static final int TYPE_TRANSLATION
```


Una traslación mueve las coordenadas una cantidad constante en x e y sin cambiar la longitud o el ángulo de los vectores.

### TYPE_UNIFORM_SCALE {#TYPE-UNIFORM-SCALE}
```
public static final int TYPE_UNIFORM_SCALE
```


Una escala uniforme multiplica la longitud de los vectores por la misma cantidad en las direcciones x e y sin cambiar el ángulo entre los vectores. Este bit de bandera es mutuamente excluyente con la bandera TypeGeneralScale.

### TYPE_GENERAL_SCALE {#TYPE-GENERAL-SCALE}
```
public static final int TYPE_GENERAL_SCALE
```


Una escala general multiplica la longitud de los vectores por diferentes cantidades en las direcciones x e y sin cambiar el ángulo entre vectores perpendiculares. Este bit de bandera es mutuamente excluyente con la bandera TypeUniformScale.

### TYPE_MASK_SCALE {#TYPE-MASK-SCALE}
```
public static final int TYPE_MASK_SCALE
```


Esta constante es una máscara de bits para cualquiera de los bits de bandera de escala.

### TYPE_FLIP {#TYPE-FLIP}
```
public static final int TYPE_FLIP
```


Este bit de bandera indica que la transformación definida por este objeto realiza una inversión de imagen espejo alrededor de algún eje, lo que cambia el sistema de coordenadas normalmente derecho a uno izquierdo, además de las conversiones indicadas por otros bits de bandera. Un sistema de coordenadas derecho es aquel en el que el eje X positivo gira en sentido antihorario para superponerse al eje Y positivo, similar a la dirección en que se curvan los dedos de la mano derecha cuando se mira de frente el pulgar. Un sistema de coordenadas izquierdo es aquel en el que el eje X positivo gira en sentido horario para superponerse al eje Y positivo, similar a la dirección en que se curvan los dedos de la mano izquierda. No existe una forma matemática de determinar el ángulo de la inversión o espejo original, ya que todos los ángulos de inversión son idénticos dado una rotación de ajuste apropiada. NOTA: TypeFlip se añadió después de que GENERAL\_TRANSFORM estuviera en circulación pública y los bits de bandera ya no pudieron renumerarse convenientemente sin introducir incompatibilidad binaria en código externo.

### TYPE_QUADRANT_ROTATION {#TYPE-QUADRANT-ROTATION}
```
public static final int TYPE_QUADRANT_ROTATION
```


Este bit de bandera indica que la transformación definida por este objeto realiza una rotación de cuadrante en múltiplos de 90 grados, además de las conversiones indicadas por otros bits de bandera. Una rotación cambia los ángulos de los vectores en la misma cantidad sin importar la dirección original del vector y sin cambiar la longitud del vector. Este bit de bandera es mutuamente excluyente con la bandera TypeGeneralRotation.

### TYPE_GENERAL_ROTATION {#TYPE-GENERAL-ROTATION}
```
public static final int TYPE_GENERAL_ROTATION
```


Este bit de bandera indica que la transformación definida por este objeto realiza una rotación por un ángulo arbitrario además de las conversiones indicadas por otros bits de bandera. Una rotación cambia los ángulos de los vectores en la misma cantidad sin importar la dirección original del vector y sin cambiar la longitud del vector. Este bit de bandera es mutuamente exclusivo con el

### TYPE_MASK_ROTATION {#TYPE-MASK-ROTATION}
```
public static final int TYPE_MASK_ROTATION
```


Esta constante es una máscara de bits para cualquiera de los bits de bandera de rotación.

### TYPE_GENERAL_TRANSFORM {#TYPE-GENERAL-TRANSFORM}
```
public static final int TYPE_GENERAL_TRANSFORM
```


Esta constante indica que la transformación definida por este objeto realiza una conversión arbitraria de las coordenadas de entrada. Si esta transformación puede clasificarse por cualquiera de las constantes anteriores, el tipo será la constante TypeIdentity o una combinación de los bits de bandera apropiados para las diversas conversiones de coordenadas que realiza esta transformación.

### isEquals(Matrix a, Matrix b) {#isEquals-com.aspose.imaging.Matrix-com.aspose.imaging.Matrix-}
```
public static boolean isEquals(Matrix a, Matrix b)
```


Determina si dos matrices son iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Matrix](../../com.aspose.imaging/matrix) | La primera matriz a comparar. |
| b | [Matrix](../../com.aspose.imaging/matrix) | La segunda matriz a comparar. |

**Returns:**
boolean - Verdadero si las matrices son iguales.
### getM11() {#getM11--}
```
public final float getM11()
```


Obtiene el elemento de la matriz en la primera fila primera columna. Representa la escala a lo largo del eje X.

**Returns:**
float - el elemento de la matriz en la primera fila primera columna.
### getM12() {#getM12--}
```
public final float getM12()
```


Obtiene el elemento de la matriz en la primera fila segunda columna. Representa la cizalladura a lo largo del eje Y.

**Returns:**
float - el elemento de la matriz en la primera fila segunda columna.
### getM21() {#getM21--}
```
public final float getM21()
```


Obtiene el elemento de la matriz en la segunda fila primera columna. Representa la cizalladura a lo largo del eje X.

**Returns:**
float - el elemento de la matriz en la segunda fila primera columna.
### getM22() {#getM22--}
```
public final float getM22()
```


Obtiene el elemento de la matriz en la segunda fila segunda columna. Representa la escala a lo largo del eje Y.

**Returns:**
float - el elemento de la matriz en la segunda fila segunda columna.
### getM31() {#getM31--}
```
public final float getM31()
```


Obtiene el elemento de la matriz en la tercera fila primera columna. Representa la traslación a lo largo del eje X.

**Returns:**
float - el elemento de la matriz en la tercera fila primera columna.
### getM32() {#getM32--}
```
public final float getM32()
```


Obtiene el elemento de la matriz en la tercera fila primera columna. Representa la traslación a lo largo del eje Y.

**Returns:**
float - el elemento de la matriz en la tercera fila primera columna.
### toString() {#toString--}
```
public String toString()
```


Devuelve una cadena que representa esta instancia.

**Returns:**
java.lang.String - Una cadena que representa esta instancia.
### getElements() {#getElements--}
```
public final float[] getElements()
```


Obtiene una copia de los elementos de la matriz.

**Returns:**
float[] - Una copia de los elementos de la matriz.
### transformPoints(PointF[] points) {#transformPoints-com.aspose.imaging.PointF---}
```
public final void transformPoints(PointF[] points)
```


Aplica la transformación geométrica representada por este [Matrix](../../com.aspose.imaging/matrix) a una matriz especificada de puntos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Los puntos. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public final void scale(float scaleX, float scaleY, int order)
```


Aplica el vector de escala especificado (scaleX y scaleY) a este [Matrix](../../com.aspose.imaging/matrix) usando el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scaleX | float | La escala X. |
| scaleY | float | La escala Y. |
| order | int | El orden. |

### scale(float sx, float sy) {#scale-float-float-}
```
public final void scale(float sx, float sy)
```


Aplica el vector de escala especificado (scaleX y scaleY) a este Matrix usando el orden (predeterminado) Prepend.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sx | float | The sx. The sx. The sx. |
| sy | float | The sy. The sy. The sy. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public final void translate(float offsetX, float offsetY, int order)
```


Aplica el vector de traslación especificado a este Matrix en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| offsetX | float | El desplazamiento X. |
| offsetY | float | El desplazamiento Y. |
| order | int | El orden. |

### translate(float tx, float ty) {#translate-float-float-}
```
public final void translate(float tx, float ty)
```


Aplica el vector de traslación especificado a este [Matrix](../../com.aspose.imaging/matrix) usando el orden (predeterminado) Prepend.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tx | float | El tx. El tx. El tx. |
| ty | float | El ty. El ty. El ty. |

### multiply(Matrix tTx, int order) {#multiply-com.aspose.imaging.Matrix-int-}
```
public final void multiply(Matrix tTx, int order)
```


Multiplica este Matrix por la matriz especificada en el parámetro matrix, y en el orden especificado en el parámetro order.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tTx | [Matrix](../../com.aspose.imaging/matrix) | El tx. El tx. El tx. |
| order | int | El orden. El orden. El orden. |

### multiply(Matrix tTx) {#multiply-com.aspose.imaging.Matrix-}
```
public final void multiply(Matrix tTx)
```


Multiplica este Matrix por la matriz especificada en el parámetro matrix usando el orden (predeterminado) Prepend.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tTx | [Matrix](../../com.aspose.imaging/matrix) | La matriz con la que multiplicar. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public final void rotate(float angle, int order)
```


Aplica una rotación en sentido horario de una cantidad especificada en el parámetro angle, alrededor del origen (coordenadas x e y cero) para este Matrix en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | El ángulo de rotación. |
| order | int | El orden de la matriz. |

### rotate(float angle) {#rotate-float-}
```
public final void rotate(float angle)
```


Aplica una rotación en sentido horario de una cantidad especificada en el parámetro angle, alrededor del origen (coordenadas x e y cero) para este Matrix en el orden predeterminado (Prepend).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | El ángulo de rotación. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.imaging.PointF-int-}
```
public final void rotateAt(float angle, PointF point, int order)
```


Aplica una rotación en sentido horario alrededor del punto especificado a este Matrix en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | El ángulo. |
| point | [PointF](../../com.aspose.imaging/pointf) | El punto. |
| order | int | El orden. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.imaging.PointF-}
```
public final void rotateAt(float angle, PointF point)
```


Aplica una rotación en sentido horario alrededor del punto especificado a este Matrix en el orden predeterminado (Prepend).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | El ángulo. |
| point | [PointF](../../com.aspose.imaging/pointf) | El punto. |

### reset() {#reset--}
```
public final void reset()
```


Restablece esta Matriz para que tenga los elementos de la matriz identidad.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para esta instancia.

**Returns:**
int - Un código hash para esta instancia, adecuado para su uso en algoritmos de hash y estructuras de datos como una tabla hash.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si el `Object` especificado es igual a esta instancia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El `Object` para comparar con esta instancia. |

**Returns:**
boolean - `true` si el `Object` especificado es igual a esta instancia; de lo contrario, `false`.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


Devuelve `true` si este `AffineTransform` es una transformación de identidad.

**Returns:**
boolean - `true` si este `AffineTransform` es una transformación identidad; `false` de lo contrario.
