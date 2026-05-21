---
title: "Pen"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Define un objeto utilizado para dibujar líneas, curvas y figuras."
type: docs
weight: 81
url: /es/java/com.aspose.imaging/pen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.TransparencySupporter](../../com.aspose.imaging/transparencysupporter)
```
public class Pen extends TransparencySupporter
```

Define un objeto usado para dibujar líneas, curvas y figuras.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.imaging.Color-) | Inicializa una nueva instancia de la clase `Pen` con el color especificado. |
| [Pen(Color color, float width)](#Pen-com.aspose.imaging.Color-float-) | Inicializa una nueva instancia de la clase `Pen` con las propiedades `Color` y `Pen.Width` especificadas. |
| [Pen(Brush brush)](#Pen-com.aspose.imaging.Brush-) | Inicializa una nueva instancia de la clase `Pen` con el `Brush` especificado. |
| [Pen(Brush brush, float width)](#Pen-com.aspose.imaging.Brush-float-) | Inicializa una nueva instancia de la clase `Pen` con el `Brush` y `Pen.Width` especificados. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getWidth()](#getWidth--) | Obtiene el ancho de este `Pen`, en unidades del objeto Graphics utilizado para dibujar. |
| [setWidth(float value)](#setWidth-float-) | Establece el ancho de este `Pen`, en unidades del objeto Graphics utilizado para dibujar. |
| [getStartCap()](#getStartCap--) | Obtiene el estilo de extremo usado al inicio de las líneas dibujadas con este `Pen`. |
| [setStartCap(int value)](#setStartCap-int-) | Establece el estilo de extremo usado al inicio de las líneas dibujadas con este `Pen`. |
| [getEndCap()](#getEndCap--) | Obtiene el estilo de extremo usado al final de las líneas dibujadas con este `Pen`. |
| [setEndCap(int value)](#setEndCap-int-) | Establece el estilo de extremo usado al final de las líneas dibujadas con este `Pen`. |
| [getDashCap()](#getDashCap--) | Obtiene el estilo de extremo usado al final de los guiones que forman líneas discontinuas dibujadas con este `Pen`. |
| [setDashCap(int value)](#setDashCap-int-) | Establece el estilo de extremo usado al final de los guiones que forman líneas discontinuas dibujadas con este `Pen`. |
| [getLineJoin()](#getLineJoin--) | Obtiene el estilo de unión para los extremos de dos líneas consecutivas dibujadas con este `Pen`. |
| [setLineJoin(int value)](#setLineJoin-int-) | Establece el estilo de unión para los extremos de dos líneas consecutivas dibujadas con este `Pen`. |
| [getCustomStartCap()](#getCustomStartCap--) | Obtiene un extremo personalizado para usar al inicio de las líneas dibujadas con este `Pen`. |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.imaging.CustomLineCap-) | Establece un extremo personalizado para usar al inicio de las líneas dibujadas con este `Pen`. |
| [getCustomEndCap()](#getCustomEndCap--) | Obtiene un extremo personalizado para usar al final de las líneas dibujadas con este `Pen`. |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.imaging.CustomLineCap-) | Establece un extremo personalizado para usar al final de las líneas dibujadas con este `Pen`. |
| [getMiterLimit()](#getMiterLimit--) | Obtiene el límite del grosor de la unión en una esquina biselada. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Establece el límite del grosor de la unión en una esquina biselada. |
| [getAlignment()](#getAlignment--) | Obtiene la alineación de este `Pen`. |
| [setAlignment(int value)](#setAlignment-int-) | Establece la alineación de este `Pen`. |
| [getTransform()](#getTransform--) | Obtiene una copia de la transformación geométrica de este `Pen`. |
| [setTransform(Matrix value)](#setTransform-com.aspose.imaging.Matrix-) | Establece una copia de la transformación geométrica de este `Pen`. |
| [getPenType()](#getPenType--) | Obtiene el estilo de líneas dibujadas con este `Pen`. |
| [getColor()](#getColor--) | Obtiene el color de este `Pen`. |
| [setColor(Color value)](#setColor-com.aspose.imaging.Color-) | Establece el color de este `Pen`. |
| [getBrush()](#getBrush--) | Obtiene el `Brush` que determina los atributos de este `Pen`. |
| [setBrush(Brush value)](#setBrush-com.aspose.imaging.Brush-) | Establece el `Brush` que determina los atributos de este `Pen`. |
| [getDashStyle()](#getDashStyle--) | Obtiene el estilo usado para líneas discontinuas dibujadas con este `Pen`. |
| [setDashStyle(int value)](#setDashStyle-int-) | Establece el estilo usado para líneas discontinuas dibujadas con este `Pen`. |
| [getDashOffset()](#getDashOffset--) | Obtiene la distancia desde el inicio de una línea hasta el comienzo de un patrón de guiones. |
| [setDashOffset(float value)](#setDashOffset-float-) | Establece la distancia desde el inicio de una línea hasta el comienzo de un patrón de guiones. |
| [getDashPattern()](#getDashPattern--) | Obtiene una matriz de guiones y espacios personalizados. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | Establece una matriz de guiones y espacios personalizados. |
| [getCompoundArray()](#getCompoundArray--) | Obtiene una matriz de valores que especifica una pluma compuesta. |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | Establece una matriz de valores que especifica una pluma compuesta. |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | Establece los valores que determinan el estilo del extremo usado para terminar líneas dibujadas por este `Pen`. |
| [resetTransform()](#resetTransform--) | Restablece la matriz de transformación geométrica de este `Pen` a la identidad. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | Multiplica la matriz de transformación de este `Pen` por la `Matrix` especificada. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | Multiplica la matriz de transformación de este `Pen` por la `Matrix` especificada en el orden especificado. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Traslada la transformación geométrica local por las dimensiones especificadas. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Traslada la transformación geométrica local por las dimensiones especificadas en el orden especificado. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Escala la transformación geométrica local por los factores especificados. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Escala la transformación geométrica local por los factores especificados en el orden especificado. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Rota la transformación geométrica local por el ángulo especificado. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Rota la transformación geométrica local por el ángulo especificado en el orden especificado. |
| [equals(Object o)](#equals-java.lang.Object-) | Comprueba si los objetos son iguales. |
| [hashCode()](#hashCode--) |  |

## Example: This example shows the creation and usage Pen objects.
Este ejemplo muestra la creación y uso de objetos Pen. El ejemplo crea una nueva Image y dibuja Rectángulos en la superficie de Image.
``` java

// Crea una instancia de BmpOptions y establece sus diversas propiedades
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Crea una instancia de FileCreateSource y asígnala como Source para la instancia de BmpOptions
// El segundo parámetro Boolean determina si el archivo a crear es IsTemporal o no
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Crea una instancia de Image en la ruta especificada
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Crea una instancia de Graphics e inicialízala con el objeto Image
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // Limpia la superficie de Graphics con Color blanco.
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // Crea una instancia de Pen con el color Rojo y ancho 5
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // Crea una instancia de HatchBrush y establece sus propiedades
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // Crea una instancia de Pen e inicialízala con el objeto HatchBrush y ancho
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // Dibuja Rectángulos especificando el objeto Pen
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // Dibuja Rectángulos especificando el objeto Pen
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // Guardar todos los cambios.
    image.save();
} finally {
    image.dispose();
}
```

### Pen(Color color) {#Pen-com.aspose.imaging.Color-}
```
public Pen(Color color)
```


Inicializa una nueva instancia de la clase `Pen` con el color especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | Una estructura `Color` que indica el color de este `Pen`. |

### Pen(Color color, float width) {#Pen-com.aspose.imaging.Color-float-}
```
public Pen(Color color, float width)
```


Inicializa una nueva instancia de la clase `Pen` con las propiedades `Color` y `Pen.Width` especificadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | Una estructura `Color` que indica el color de este `Pen`. |
| width | float | Un valor que indica el ancho de este `Pen`. |

### Pen(Brush brush) {#Pen-com.aspose.imaging.Brush-}
```
public Pen(Brush brush)
```


Inicializa una nueva instancia de la clase `Pen` con el `Brush` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Un `Brush` que determina las propiedades de relleno de este `Pen`. |

### Pen(Brush brush, float width) {#Pen-com.aspose.imaging.Brush-float-}
```
public Pen(Brush brush, float width)
```


Inicializa una nueva instancia de la clase `Pen` con el `Brush` y `Pen.Width` especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Un `Brush` que determina las características de este `Pen`. |
| width | float | El ancho del nuevo `Pen`. |

### getWidth() {#getWidth--}
```
public float getWidth()
```


Obtiene el ancho de este `Pen`, en unidades del objeto Graphics utilizado para dibujar.

**Returns:**
float - El ancho de este `Pen`.
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Establece el ancho de este `Pen`, en unidades del objeto Graphics utilizado para dibujar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El ancho de este `Pen`. |

### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


Obtiene el estilo de extremo usado al inicio de las líneas dibujadas con este `Pen`.

**Returns:**
int - Uno de los valores `LineCap` que representa el estilo de tapa usado al inicio de las líneas dibujadas con este `Pen`.
### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


Establece el estilo de extremo usado al inicio de las líneas dibujadas con este `Pen`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Uno de los valores `LineCap` que representa el estilo de tapa usado al inicio de las líneas dibujadas con este `Pen`. |

### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


Obtiene el estilo de extremo usado al final de las líneas dibujadas con este `Pen`.

**Returns:**
int - Uno de los valores `LineCap` que representa el estilo de tapa usado al final de las líneas dibujadas con este `Pen`.
### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


Establece el estilo de extremo usado al final de las líneas dibujadas con este `Pen`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Uno de los valores `LineCap` que representa el estilo de tapa usado al final de las líneas dibujadas con este `Pen`. |

### getDashCap() {#getDashCap--}
```
public int getDashCap()
```


Obtiene el estilo de extremo usado al final de los guiones que forman líneas discontinuas dibujadas con este `Pen`.

**Returns:**
int - Uno de los valores `DashCap` que representa el estilo de tapa usado al inicio y al final de los guiones que forman líneas punteadas dibujadas con este `Pen`.
### setDashCap(int value) {#setDashCap-int-}
```
public void setDashCap(int value)
```


Establece el estilo de extremo usado al final de los guiones que forman líneas discontinuas dibujadas con este `Pen`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Uno de los valores `DashCap` que representa el estilo de tapa usado al inicio y al final de los guiones que forman líneas punteadas dibujadas con este `Pen`. |

### getLineJoin() {#getLineJoin--}
```
public int getLineJoin()
```


Obtiene el estilo de unión para los extremos de dos líneas consecutivas dibujadas con este `Pen`.

**Returns:**
int - Un `LineJoin` que representa el estilo de unión para los extremos de dos líneas consecutivas dibujadas con este `Pen`.
### setLineJoin(int value) {#setLineJoin-int-}
```
public void setLineJoin(int value)
```


Establece el estilo de unión para los extremos de dos líneas consecutivas dibujadas con este `Pen`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Un `LineJoin` que representa el estilo de unión para los extremos de dos líneas consecutivas dibujadas con este `Pen`. |

### getCustomStartCap() {#getCustomStartCap--}
```
public CustomLineCap getCustomStartCap()
```


Obtiene un extremo personalizado para usar al inicio de las líneas dibujadas con este `Pen`.

**Returns:**
[CustomLineCap](../../com.aspose.imaging/customlinecap) - A `CustomLineCap` that represents the cap used at the beginning of lines drawn with this `Pen`.
### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.imaging.CustomLineCap-}
```
public void setCustomStartCap(CustomLineCap value)
```


Establece un extremo personalizado para usar al inicio de las líneas dibujadas con este `Pen`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.imaging/customlinecap) | Un `CustomLineCap` que representa la tapa utilizada al inicio de las líneas dibujadas con este `Pen`. |

### getCustomEndCap() {#getCustomEndCap--}
```
public CustomLineCap getCustomEndCap()
```


Obtiene un extremo personalizado para usar al final de las líneas dibujadas con este `Pen`.

**Returns:**
[CustomLineCap](../../com.aspose.imaging/customlinecap) - A `CustomLineCap` that represents the cap used at the end of lines drawn with this `Pen`.
### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.imaging.CustomLineCap-}
```
public void setCustomEndCap(CustomLineCap value)
```


Establece un extremo personalizado para usar al final de las líneas dibujadas con este `Pen`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.imaging/customlinecap) | Un `CustomLineCap` que representa la tapa utilizada al final de las líneas dibujadas con este `Pen`. |

### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


Obtiene el límite del grosor de la unión en una esquina biselada.

**Returns:**
float - El límite del grosor de la unión en una esquina biselada.
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


Establece el límite del grosor de la unión en una esquina biselada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El límite del grosor de la unión en una esquina biselada. |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Obtiene la alineación de este `Pen`.

**Returns:**
int - Un `PenAlignment` que representa la alineación de este `Pen`.
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Establece la alineación de este `Pen`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Un `PenAlignment` que representa la alineación de este `Pen`. |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Obtiene una copia de la transformación geométrica de este `Pen`.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - A copy of the `Matrix` that represents the geometric transformation for this `Pen`.
### setTransform(Matrix value) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix value)
```


Establece una copia de la transformación geométrica de este `Pen`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) | Una copia de la `Matrix` que representa la transformación geométrica de este `Pen`. |

### getPenType() {#getPenType--}
```
public int getPenType()
```


Obtiene el estilo de líneas dibujadas con este `Pen`.

**Returns:**
int - Una enumeración `PenType` que especifica el estilo de las líneas dibujadas con este `Pen`.
### getColor() {#getColor--}
```
public Color getColor()
```


Obtiene el color de este `Pen`.

**Returns:**
[Color](../../com.aspose.imaging/color) - A `Color` structure that represents the color of this `Pen`.
### setColor(Color value) {#setColor-com.aspose.imaging.Color-}
```
public void setColor(Color value)
```


Establece el color de este `Pen`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Una estructura `Color` que representa el color de este `Pen`. |

### getBrush() {#getBrush--}
```
public Brush getBrush()
```


Obtiene el `Brush` que determina los atributos de este `Pen`.

**Returns:**
[Brush](../../com.aspose.imaging/brush) - A `Brush` that determines attributes of this `Pen`.
### setBrush(Brush value) {#setBrush-com.aspose.imaging.Brush-}
```
public void setBrush(Brush value)
```


Establece el `Brush` que determina los atributos de este `Pen`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Brush](../../com.aspose.imaging/brush) | Un `Brush` que determina los atributos de este `Pen`. |

### getDashStyle() {#getDashStyle--}
```
public int getDashStyle()
```


Obtiene el estilo usado para líneas discontinuas dibujadas con este `Pen`.

**Returns:**
int - Un `DashStyle` que representa el estilo usado para líneas discontinuas dibujadas con este `Pen`.
### setDashStyle(int value) {#setDashStyle-int-}
```
public void setDashStyle(int value)
```


Establece el estilo usado para líneas discontinuas dibujadas con este `Pen`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Un `DashStyle` que representa el estilo usado para líneas discontinuas dibujadas con este `Pen`. |

### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


Obtiene la distancia desde el inicio de una línea hasta el comienzo de un patrón de guiones.

**Returns:**
float - La distancia desde el inicio de una línea hasta el comienzo de un patrón de guiones.
### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


Establece la distancia desde el inicio de una línea hasta el comienzo de un patrón de guiones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | La distancia desde el inicio de una línea hasta el comienzo de un patrón de guiones. |

### getDashPattern() {#getDashPattern--}
```
public float[] getDashPattern()
```


Obtiene una matriz de guiones y espacios personalizados.

**Returns:**
float[] - Una matriz de números reales que especifica las longitudes de guiones y espacios alternados en líneas discontinuas.
### setDashPattern(float[] value) {#setDashPattern-float---}
```
public void setDashPattern(float[] value)
```


Establece una matriz de guiones y espacios personalizados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float[] | Una matriz de números reales que especifica las longitudes de guiones y espacios alternados en líneas discontinuas. |

### getCompoundArray() {#getCompoundArray--}
```
public float[] getCompoundArray()
```


Obtiene una matriz de valores que especifica un bolígrafo compuesto. Un bolígrafo compuesto dibuja una línea compuesta formada por líneas paralelas y espacios.

**Returns:**
float[] - Una matriz de números reales que especifica la matriz compuesta. Los elementos de la matriz deben estar en orden ascendente, no ser menores que 0 y no ser mayores que 1.
### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public void setCompoundArray(float[] value)
```


Establece una matriz de valores que especifica un bolígrafo compuesto. Un bolígrafo compuesto dibuja una línea compuesta formada por líneas paralelas y espacios.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float[] | Una matriz de números reales que especifica la matriz compuesta. Los elementos de la matriz deben estar en orden ascendente, no ser menores que 0 y no ser mayores que 1. |

### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public void setLineCap(int startCap, int endCap, int dashCap)
```


Establece los valores que determinan el estilo del extremo usado para terminar líneas dibujadas por este `Pen`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startCap | int | Un `LineCap` que representa el estilo de tapa a usar al inicio de las líneas dibujadas con este `Pen`. |
| endCap | int | Un `LineCap` que representa el estilo de tapa a usar al final de las líneas dibujadas con este `Pen`. |
| dashCap | int | Un `LineCap` que representa el estilo de tapa a usar al inicio o al final de líneas discontinuas dibujadas con este `Pen`. |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Restablece la matriz de transformación geométrica de este `Pen` a la identidad.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.imaging.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multiplica la matriz de transformación de este `Pen` por la `Matrix` especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | El objeto `Matrix` por el cual multiplicar la matriz de transformación. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplica la matriz de transformación de este `Pen` por la `Matrix` especificada en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | El `Matrix` por el cual multiplicar la matriz de transformación. |
| order | int | El orden en el que realizar la operación de multiplicación. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Traslada la transformación geométrica local por las dimensiones especificadas. Este método antepone la traslación a la transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dx | float | El valor de la traslación en x. |
| dy | float | El valor de la traslación en y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Traslada la transformación geométrica local por las dimensiones especificadas en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dx | float | El valor de la traslación en x. |
| dy | float | El valor de la traslación en y. |
| order | int | El orden (anteponer o anexar) en el que aplicar la traslación. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Escala la transformación geométrica local por los factores especificados. Este método antepone la matriz de escala a la transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sx | float | El factor por el cual escalar la transformación en la dirección del eje x. |
| sy | float | El factor por el cual escalar la transformación en la dirección del eje y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Escala la transformación geométrica local por los factores especificados en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sx | float | El factor por el cual escalar la transformación en la dirección del eje x. |
| sy | float | El factor por el cual escalar la transformación en la dirección del eje y. |
| order | int | Un `MatrixOrder` que especifica si anexar o anteponer la matriz de escala. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Rota la transformación geométrica local por el ángulo especificado. Este método antepone la rotación a la transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | El ángulo de rotación. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Rota la transformación geométrica local por el ángulo especificado en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | El ángulo de rotación. |
| order | int | Un `MatrixOrder` que especifica si anexar o anteponer la matriz de rotación. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Comprueba si los objetos son iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| o | java.lang.Object | El otro objeto. |

**Returns:**
boolean - El resultado de la comparación de igualdad.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtiene el código hash del objeto actual.

**Returns:**
int
