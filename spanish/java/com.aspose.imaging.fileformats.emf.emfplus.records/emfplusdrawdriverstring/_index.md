---
title: "EmfPlusDrawDriverString"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusDrawDriverString especifica la salida de texto con posiciones de caracteres."
type: docs
weight: 20
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawDriverString extends EmfPlusDrawingRecordType
```

El registro EmfPlusDrawDriverString especifica la salida de texto con posiciones de caracteres.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusDrawDriverString(EmfPlusRecord source)](#EmfPlusDrawDriverString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusDrawDriverString`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getObjectId()](#getObjectId--) | Obtiene el identificador del objeto. |
| [setObjectId(byte value)](#setObjectId-byte-) | Establece el identificador del objeto. |
| [getBrushId()](#getBrushId--) | Obtiene el identificador del pincel Un entero sin signo de 32 bits que especifica ya sea el color de primer plano del texto o un pincel gráfico, dependiendo del valor del indicador S en Flags. |
| [setBrushId(int value)](#setBrushId-int-) | Establece el identificador del pincel Un entero sin signo de 32 bits que especifica ya sea el color de primer plano del texto o un pincel gráfico, dependiendo del valor de la bandera S en los Flags |
| [getDriverStringOptionsFlags()](#getDriverStringOptionsFlags--) | Obtiene las banderas de opciones de cadena del controlador Un entero sin signo de 32 bits que especifica el espaciado, la orientación y la calidad de renderizado de la cadena. |
| [setDriverStringOptionsFlags(int value)](#setDriverStringOptionsFlags-int-) | Establece las banderas de opciones de cadena del controlador Un entero sin signo de 32 bits que especifica el espaciado, la orientación y la calidad de renderizado de la cadena. |
| [getGlyphCount()](#getGlyphCount--) | Obtiene el recuento de glifos Un entero sin signo de 32 bits que especifica el número de glifos en la cadena |
| [setGlyphCount(int value)](#setGlyphCount-int-) | Establece el recuento de glifos Un entero sin signo de 32 bits que especifica el número de glifos en la cadena |
| [getGlyphPos()](#getGlyphPos--) | Obtiene la matriz de posiciones de glifos Una matriz de objetos EmfPlusPointF (sección 2.2.2.36) que especifican la posición de salida de cada glifo de carácter. |
| [setGlyphPos(PointF[] value)](#setGlyphPos-com.aspose.imaging.PointF---) | Establece la matriz de posiciones de glifos Una matriz de objetos EmfPlusPointF (sección 2.2.2.36) que especifican la posición de salida de cada glifo de carácter. |
| [getGlyphs()](#getGlyphs--) | Obtiene la matriz de glifos Una matriz de valores de 16 bits que definen la cadena de texto a dibujar. |
| [setGlyphs(short[] value)](#setGlyphs-short---) | Establece la matriz de glifos Una matriz de valores de 16 bits que definen la cadena de texto a dibujar. |
| [isColor()](#isColor--) | Obtiene o establece un valor que indica si esta instancia es de color. |
| [setColor(boolean value)](#setColor-boolean-) | Establece un valor que indica si esta instancia es de color. |
| [getMatrixPresent()](#getMatrixPresent--) | Obtiene si la bandera de matriz presente Un entero sin signo de 32 bits que especifica si una matriz de transformación está presente en el campo TransformMatrix 0 - no hay matriz presente. |
| [setMatrixPresent(int value)](#setMatrixPresent-int-) | Establece si la bandera de matriz presente Un entero sin signo de 32 bits que especifica si una matriz de transformación está presente en el campo TransformMatrix 0 - no hay matriz presente. |
| [getTransformMatrix()](#getTransformMatrix--) | Obtiene la matriz de transformación Un objeto opcional EmfPlusTransformMatrix (sección 2.2.2.47) que especifica la transformación a aplicar a cada valor en la matriz de texto. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Establece la matriz de transformación Un objeto opcional EmfPlusTransformMatrix (sección 2.2.2.47) que especifica la transformación a aplicar a cada valor en la matriz de texto. |
### EmfPlusDrawDriverString(EmfPlusRecord source) {#EmfPlusDrawDriverString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawDriverString(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusDrawDriverString`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Obtiene el identificador del objeto. El índice de la tabla de objetos EMF+ de un objeto `` (sección 2.2.1.3) para renderizar el texto. El valor DEBE ser de 0 a 63, inclusive.

**Returns:**
byte - El identificador del objeto.
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Establece el identificador del objeto. El índice de la tabla de objetos EMF+ de un objeto `` (sección 2.2.1.3) para renderizar el texto. El valor DEBE ser de 0 a 63, inclusive.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte | El identificador del objeto. |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Obtiene el identificador del pincel Un entero sin signo de 32 bits que especifica ya sea el color de primer plano del texto o un pincel gráfico, dependiendo del valor del indicador S en Flags.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Establece el identificador del pincel Un entero sin signo de 32 bits que especifica ya sea el color de primer plano del texto o un pincel gráfico, dependiendo del valor de la bandera S en los Flags

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getDriverStringOptionsFlags() {#getDriverStringOptionsFlags--}
```
public int getDriverStringOptionsFlags()
```


Obtiene las banderas de opciones de cadena del controlador Un entero sin signo de 32 bits que especifica el espaciado, la orientación y la calidad de renderizado de la cadena.

**Returns:**
int
### setDriverStringOptionsFlags(int value) {#setDriverStringOptionsFlags-int-}
```
public void setDriverStringOptionsFlags(int value)
```


Establece las banderas de opciones de cadena del controlador Un entero sin signo de 32 bits que especifica el espaciado, la orientación y la calidad de renderizado de la cadena.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getGlyphCount() {#getGlyphCount--}
```
public int getGlyphCount()
```


Obtiene el recuento de glifos Un entero sin signo de 32 bits que especifica el número de glifos en la cadena

**Returns:**
int
### setGlyphCount(int value) {#setGlyphCount-int-}
```
public void setGlyphCount(int value)
```


Establece el recuento de glifos Un entero sin signo de 32 bits que especifica el número de glifos en la cadena

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getGlyphPos() {#getGlyphPos--}
```
public PointF[] getGlyphPos()
```


Obtiene la matriz de posiciones de glifos Una matriz de objetos EmfPlusPointF (sección 2.2.2.36) que especifican la posición de salida de cada glifo de carácter. DEBE haber elementos GlyphCount, que tienen una correspondencia uno a uno con los elementos de la matriz Glyphs. Las posiciones de los glifos se calculan a partir de la posición del primer glifo si la bandera DriverStringOptionsRealizedAdvance en las banderas DriverStringOptions está activada. En este caso, GlyphPos especifica solo la posición del primer glifo.

**Returns:**
com.aspose.imaging.PointF[]
### setGlyphPos(PointF[] value) {#setGlyphPos-com.aspose.imaging.PointF---}
```
public void setGlyphPos(PointF[] value)
```


Establece la matriz de posiciones de glifos Una matriz de objetos EmfPlusPointF (sección 2.2.2.36) que especifican la posición de salida de cada glifo de carácter. DEBE haber elementos GlyphCount, que tienen una correspondencia uno a uno con los elementos de la matriz Glyphs. Las posiciones de los glifos se calculan a partir de la posición del primer glifo si la bandera DriverStringOptionsRealizedAdvance en las banderas DriverStringOptions está activada. En este caso, GlyphPos especifica solo la posición del primer glifo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### getGlyphs() {#getGlyphs--}
```
public short[] getGlyphs()
```


Obtiene la matriz de glifos Una matriz de valores de 16 bits que definen la cadena de texto a dibujar. Si la bandera DriverStringOptionsCmapLookup en el campo DriverStringOptionsFlags está activada, cada valor en esta matriz especifica un carácter Unicode. De lo contrario, cada valor especifica un índice a un glifo de carácter en el objeto EmfPlusFont especificado por el valor ObjectId en el campo Flags.

**Returns:**
short[]
### setGlyphs(short[] value) {#setGlyphs-short---}
```
public void setGlyphs(short[] value)
```


Establece la matriz de glifos Una matriz de valores de 16 bits que definen la cadena de texto a dibujar. Si la bandera DriverStringOptionsCmapLookup en el campo DriverStringOptionsFlags está activada, cada valor en esta matriz especifica un carácter Unicode. De lo contrario, cada valor especifica un índice a un glifo de carácter en el objeto EmfPlusFont especificado por el valor ObjectId en el campo Flags.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short[] |  |

### isColor() {#isColor--}
```
public boolean isColor()
```


Obtiene o establece un valor que indica si esta instancia es de color. Este bit indica el tipo de datos en el campo BrushId. Si está activado, BrushId especifica el valor de color en un objeto EmfPlusARGB (sección 2.2.2.1). Si está desactivado, BrushId contiene el índice de la tabla de objetos EMF+ de un objeto EmfPlusBrush (sección 2.2.1.1).

**Returns:**
boolean - `true` si esta instancia es de color; de lo contrario, `false`.
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Establece un valor que indica si esta instancia es de color. Este bit indica el tipo de datos en el campo BrushId. Si está activado, BrushId especifica el valor de color en un objeto EmfPlusARGB (sección 2.2.2.1). Si está desactivado, BrushId contiene el índice de la tabla de objetos EMF+ de un objeto EmfPlusBrush (sección 2.2.1.1).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | `true` si esta instancia es de color; de lo contrario, `false`. |

### getMatrixPresent() {#getMatrixPresent--}
```
public int getMatrixPresent()
```


Obtiene el indicador de matriz presente, un entero sin signo de 32 bits que especifica si una matriz de transformación está presente en el campo TransformMatrix: 0 - no hay matriz presente. 1 - la matriz de transformación está en el campo TransformMatrix.

**Returns:**
int
### setMatrixPresent(int value) {#setMatrixPresent-int-}
```
public void setMatrixPresent(int value)
```


Establece el indicador de matriz presente, un entero sin signo de 32 bits que especifica si una matriz de transformación está presente en el campo TransformMatrix: 0 - no hay matriz presente. 1 - la matriz de transformación está en el campo TransformMatrix.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Obtiene la matriz de transformación, un objeto opcional EmfPlusTransformMatrix (sección 2.2.2.47) que especifica la transformación a aplicar a cada valor en la matriz de texto. La presencia de estos datos se determina a partir del campo MatrixPresent.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Establece la matriz de transformación, un objeto opcional EmfPlusTransformMatrix (sección 2.2.2.47) que especifica la transformación a aplicar a cada valor en la matriz de texto. La presencia de estos datos se determina a partir del campo MatrixPresent.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

