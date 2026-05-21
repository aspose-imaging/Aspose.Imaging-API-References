---
title: "EmfPlusCustomLineCapArrowData"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusCustomLineCapArrowData especifica datos de flecha ajustables para una tapa de línea personalizada."
type: docs
weight: 35
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecaparrowdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomBaseLineCap](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustombaselinecap)
```
public final class EmfPlusCustomLineCapArrowData extends EmfPlusCustomBaseLineCap
```

El objeto EmfPlusCustomLineCapArrowData especifica datos de flecha ajustables para una tapa de línea personalizada.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusCustomLineCapArrowData()](#EmfPlusCustomLineCapArrowData--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getWidth()](#getWidth--) | Obtiene o establece un valor de punto flotante de 32 bits que especifica el ancho de la tapa de flecha |
| [setWidth(float value)](#setWidth-float-) | Obtiene o establece un valor de punto flotante de 32 bits que especifica el ancho de la tapa de flecha |
| [getHeight()](#getHeight--) | Obtiene o establece un valor de punto flotante de 32 bits que especifica la altura de la tapa de flecha. |
| [setHeight(float value)](#setHeight-float-) | Obtiene o establece un valor de punto flotante de 32 bits que especifica la altura de la tapa de flecha. |
| [getMiddleInset()](#getMiddleInset--) | Obtiene o establece un valor de punto flotante de 32 bits que especifica el número de píxeles entre el contorno de la tapa de flecha y el relleno de la tapa de flecha. |
| [setMiddleInset(float value)](#setMiddleInset-float-) | Obtiene o establece un valor de punto flotante de 32 bits que especifica el número de píxeles entre el contorno de la tapa de flecha y el relleno de la tapa de flecha. |
| [getFillState()](#getFillState--) | Obtiene o establece un valor booleano de 32 bits que indica si la tapa de flecha está rellena. |
| [setFillState(boolean value)](#setFillState-boolean-) | Obtiene o establece un valor booleano de 32 bits que indica si la tapa de flecha está rellena. |
| [getLineStartCap()](#getLineStartCap--) | Obtiene o establece un entero sin signo de 32 bits que especifica el valor en la enumeración LineCap que indica la forma de extremo de línea que se debe usar al inicio de la línea a dibujar |
| [setLineStartCap(int value)](#setLineStartCap-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el valor en la enumeración LineCap que indica la forma de extremo de línea que se debe usar al inicio de la línea a dibujar |
| [getLineEndCap()](#getLineEndCap--) | Obtiene o establece un entero sin signo de 32 bits que especifica el valor en la enumeración LineCap que indica la forma de extremo de línea que se debe usar al final de la línea a dibujar |
| [setLineEndCap(int value)](#setLineEndCap-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el valor en la enumeración LineCap que indica la forma de extremo de línea que se debe usar al final de la línea a dibujar |
| [getLineJoin()](#getLineJoin--) | Obtiene o establece un entero sin signo de 32 bits que especifica el valor en la enumeración LineJoin que indica cómo unir dos líneas dibujadas con la misma pluma y cuyos extremos se encuentran. |
| [setLineJoin(int value)](#setLineJoin-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el valor en la enumeración LineJoin que indica cómo unir dos líneas dibujadas con la misma pluma y cuyos extremos se encuentran. |
| [getLineMiterLimit()](#getLineMiterLimit--) | Obtiene o establece un valor de punto flotante de 32 bits que especifica el límite del grosor de la unión en una esquina en inglete estableciendo la relación máxima permitida entre la longitud del inglete y el ancho de la línea. |
| [setLineMiterLimit(float value)](#setLineMiterLimit-float-) | Obtiene o establece un valor de punto flotante de 32 bits que especifica el límite del grosor de la unión en una esquina en inglete estableciendo la relación máxima permitida entre la longitud del inglete y el ancho de la línea. |
| [getWidthScale()](#getWidthScale--) | Obtiene o establece un valor de punto flotante de 32 bits que especifica la cantidad por la cual escalar un objeto EmfPlusCustomLineCap con respecto al ancho de la pluma gráfica utilizada para dibujar las líneas |
| [setWidthScale(float value)](#setWidthScale-float-) | Obtiene o establece un valor de punto flotante de 32 bits que especifica la cantidad por la cual escalar un objeto EmfPlusCustomLineCap con respecto al ancho de la pluma gráfica utilizada para dibujar las líneas |
| [getFillHotSpot()](#getFillHotSpot--) | Obtiene o establece el objeto EmfPlusPointF que no se usa actualmente. |
| [setFillHotSpot(PointF value)](#setFillHotSpot-com.aspose.imaging.PointF-) | Obtiene o establece el objeto EmfPlusPointF que no se usa actualmente. |
| [getLineHotSpot()](#getLineHotSpot--) | Obtiene o establece un objeto EmfPlusPointF que no se utiliza actualmente. |
| [setLineHotSpot(PointF value)](#setLineHotSpot-com.aspose.imaging.PointF-) | Obtiene o establece un objeto EmfPlusPointF que no se utiliza actualmente. |
### EmfPlusCustomLineCapArrowData() {#EmfPlusCustomLineCapArrowData--}
```
public EmfPlusCustomLineCapArrowData()
```


### getWidth() {#getWidth--}
```
public float getWidth()
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica el ancho de la tapa de flecha

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica el ancho de la tapa de flecha

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getHeight() {#getHeight--}
```
public float getHeight()
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica la altura de la tapa de flecha.

**Returns:**
float
### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica la altura de la tapa de flecha.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getMiddleInset() {#getMiddleInset--}
```
public float getMiddleInset()
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica el número de píxeles entre el contorno de la tapa de flecha y el relleno de la tapa de flecha.

**Returns:**
float
### setMiddleInset(float value) {#setMiddleInset-float-}
```
public void setMiddleInset(float value)
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica el número de píxeles entre el contorno de la tapa de flecha y el relleno de la tapa de flecha.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getFillState() {#getFillState--}
```
public boolean getFillState()
```


Obtiene o establece un valor booleano de 32 bits que indica si la tapa de flecha está rellena. Si la tapa de flecha no está rellena, solo se dibuja el contorno.

**Returns:**
boolean
### setFillState(boolean value) {#setFillState-boolean-}
```
public void setFillState(boolean value)
```


Obtiene o establece un valor booleano de 32 bits que indica si la tapa de flecha está rellena. Si la tapa de flecha no está rellena, solo se dibuja el contorno.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getLineStartCap() {#getLineStartCap--}
```
public int getLineStartCap()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el valor en la enumeración LineCap que indica la forma de extremo de línea que se debe usar al inicio de la línea a dibujar

**Returns:**
int
### setLineStartCap(int value) {#setLineStartCap-int-}
```
public void setLineStartCap(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el valor en la enumeración LineCap que indica la forma de extremo de línea que se debe usar al inicio de la línea a dibujar

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getLineEndCap() {#getLineEndCap--}
```
public int getLineEndCap()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el valor en la enumeración LineCap que indica la forma de extremo de línea que se debe usar al final de la línea a dibujar

**Returns:**
int
### setLineEndCap(int value) {#setLineEndCap-int-}
```
public void setLineEndCap(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el valor en la enumeración LineCap que indica la forma de extremo de línea que se debe usar al final de la línea a dibujar

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getLineJoin() {#getLineJoin--}
```
public int getLineJoin()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el valor en la enumeración LineJoin que indica cómo unir dos líneas dibujadas con la misma pluma y cuyos extremos se encuentran. En la intersección de los dos extremos de línea, una unión de línea hace que la conexión parezca más continua.

**Returns:**
int
### setLineJoin(int value) {#setLineJoin-int-}
```
public void setLineJoin(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el valor en la enumeración LineJoin que indica cómo unir dos líneas dibujadas con la misma pluma y cuyos extremos se encuentran. En la intersección de los dos extremos de línea, una unión de línea hace que la conexión parezca más continua.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getLineMiterLimit() {#getLineMiterLimit--}
```
public float getLineMiterLimit()
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica el límite del grosor de la unión en una esquina en inglete estableciendo la relación máxima permitida entre la longitud del inglete y el ancho de la línea.

**Returns:**
float
### setLineMiterLimit(float value) {#setLineMiterLimit-float-}
```
public void setLineMiterLimit(float value)
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica el límite del grosor de la unión en una esquina en inglete estableciendo la relación máxima permitida entre la longitud del inglete y el ancho de la línea.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica la cantidad por la cual escalar un objeto EmfPlusCustomLineCap con respecto al ancho de la pluma gráfica utilizada para dibujar las líneas

**Returns:**
float
### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica la cantidad por la cual escalar un objeto EmfPlusCustomLineCap con respecto al ancho de la pluma gráfica utilizada para dibujar las líneas

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getFillHotSpot() {#getFillHotSpot--}
```
public PointF getFillHotSpot()
```


Obtiene o establece el objeto EmfPlusPointF que no se usa actualmente. DEBE establecerse en \{0.0, 0.0\}.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setFillHotSpot(PointF value) {#setFillHotSpot-com.aspose.imaging.PointF-}
```
public void setFillHotSpot(PointF value)
```


Obtiene o establece el objeto EmfPlusPointF que no se usa actualmente. DEBE establecerse en \{0.0, 0.0\}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getLineHotSpot() {#getLineHotSpot--}
```
public PointF getLineHotSpot()
```


Obtiene o establece un objeto EmfPlusPointF que no se utiliza actualmente. DEBE establecerse en \{0.0, 0.0\}.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setLineHotSpot(PointF value) {#setLineHotSpot-com.aspose.imaging.PointF-}
```
public void setLineHotSpot(PointF value)
```


Obtiene o establece un objeto EmfPlusPointF que no se utiliza actualmente. DEBE establecerse en \{0.0, 0.0\}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

