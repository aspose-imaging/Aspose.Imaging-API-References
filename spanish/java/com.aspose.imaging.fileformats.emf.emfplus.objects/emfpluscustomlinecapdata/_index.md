---
title: "EmfPlusCustomLineCapData"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusCustomLineCapData especifica datos predeterminados para una tapa de línea personalizada."
type: docs
weight: 36
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomBaseLineCap](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustombaselinecap)
```
public final class EmfPlusCustomLineCapData extends EmfPlusCustomBaseLineCap
```

El objeto EmfPlusCustomLineCapData especifica datos predeterminados para una tapa de línea personalizada.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusCustomLineCapData()](#EmfPlusCustomLineCapData--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCustomLineCapDataFlags()](#getCustomLineCapDataFlags--) | Obtiene o establece un entero sin signo de 32 bits que especifica los datos en el campo OptionalData |
| [setCustomLineCapDataFlags(int value)](#setCustomLineCapDataFlags-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica los datos en el campo OptionalData |
| [getBaseCap()](#getBaseCap--) | Obtiene o establece un entero sin signo de 32 bits que especifica el valor de la enumeración LineCap (sección 2.1.1.18) en la que se basa el cap de línea personalizado. |
| [setBaseCap(int value)](#setBaseCap-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el valor de la enumeración LineCap (sección 2.1.1.18) en la que se basa el cap de línea personalizado. |
| [getBaseInset()](#getBaseInset--) | Obtiene o establece un valor de punto flotante de 32 bits que especifica la distancia entre el inicio del cap de línea y el final de la línea. |
| [setBaseInset(float value)](#setBaseInset-float-) | Obtiene o establece un valor de punto flotante de 32 bits que especifica la distancia entre el inicio del cap de línea y el final de la línea. |
| [getStrokeStartCap()](#getStrokeStartCap--) | Obtiene o establece un entero sin signo de 32 bits que especifica el valor en la enumeración LineCap que indica el cap de línea utilizado al inicio de la línea a dibujar |
| [setStrokeStartCap(int value)](#setStrokeStartCap-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el valor en la enumeración LineCap que indica el cap de línea utilizado al inicio de la línea a dibujar |
| [getStrokeEndCap()](#getStrokeEndCap--) | Obtiene o establece un entero sin signo de 32 bits que especifica el valor en la enumeración LineCap que indica qué cap de línea se debe usar al final de la línea a dibujar. |
| [setStrokeEndCap(int value)](#setStrokeEndCap-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el valor en la enumeración LineCap que indica qué cap de línea se debe usar al final de la línea a dibujar. |
| [getStrokeJoin()](#getStrokeJoin--) | Obtiene o establece un entero sin signo de 32 bits que especifica el valor en la enumeración LineJoin (sección 2.1.1.19), que indica cómo unir dos líneas dibujadas con la misma pluma y cuyos extremos se encuentran. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el valor en la enumeración LineJoin (sección 2.1.1.19), que indica cómo unir dos líneas dibujadas con la misma pluma y cuyos extremos se encuentran. |
| [getStrokeMiterLimit()](#getStrokeMiterLimit--) | Obtiene o establece un valor de punto flotante de 32 bits que contiene el límite del grosor de la unión en una esquina en ángulo recto al establecer la relación máxima permitida entre la longitud del ángulo y el ancho de línea. |
| [setStrokeMiterLimit(float value)](#setStrokeMiterLimit-float-) | Obtiene o establece un valor de punto flotante de 32 bits que contiene el límite del grosor de la unión en una esquina en ángulo recto al establecer la relación máxima permitida entre la longitud del ángulo y el ancho de línea. |
| [getWidthScale()](#getWidthScale--) | Obtiene o establece un valor de punto flotante de 32 bits que especifica la cantidad por la cual escalar la tapa de línea personalizada con respecto al ancho del objeto EmfPlusPen (sección 2.2.1.7) que se utiliza para dibujar las líneas. |
| [setWidthScale(float value)](#setWidthScale-float-) | Obtiene o establece un valor de punto flotante de 32 bits que especifica la cantidad por la cual escalar la tapa de línea personalizada con respecto al ancho del objeto EmfPlusPen (sección 2.2.1.7) que se utiliza para dibujar las líneas. |
| [getFillHotSpot()](#getFillHotSpot--) | Obtiene o establece el objeto EmfPlusPointF que no se usa actualmente. |
| [setFillHotSpot(PointF value)](#setFillHotSpot-com.aspose.imaging.PointF-) | Obtiene o establece el objeto EmfPlusPointF que no se usa actualmente. |
| [getStrokeHotSpot()](#getStrokeHotSpot--) | Obtiene o establece el objeto EmfPlusPointF que no se usa actualmente. |
| [setStrokeHotSpot(PointF value)](#setStrokeHotSpot-com.aspose.imaging.PointF-) | Obtiene o establece el objeto EmfPlusPointF que no se usa actualmente. |
| [getOptionalData()](#getOptionalData--) | Obtiene o establece el objeto opcional EmfPlusCustomLineCapOptionalData (sección 2.2.2.14) que especifica datos adicionales para la tapa de línea gráfica personalizada. |
| [setOptionalData(EmfPlusCustomLineCapOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapOptionalData-) | Obtiene o establece el objeto opcional EmfPlusCustomLineCapOptionalData (sección 2.2.2.14) que especifica datos adicionales para la tapa de línea gráfica personalizada. |
### EmfPlusCustomLineCapData() {#EmfPlusCustomLineCapData--}
```
public EmfPlusCustomLineCapData()
```


### getCustomLineCapDataFlags() {#getCustomLineCapDataFlags--}
```
public int getCustomLineCapDataFlags()
```


Obtiene o establece un entero sin signo de 32 bits que especifica los datos en el campo OptionalData

**Returns:**
int
### setCustomLineCapDataFlags(int value) {#setCustomLineCapDataFlags-int-}
```
public void setCustomLineCapDataFlags(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica los datos en el campo OptionalData

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el valor de la enumeración LineCap (sección 2.1.1.18) en la que se basa el cap de línea personalizado.

**Returns:**
int
### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el valor de la enumeración LineCap (sección 2.1.1.18) en la que se basa el cap de línea personalizado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica la distancia entre el inicio del cap de línea y el final de la línea.

**Returns:**
float
### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica la distancia entre el inicio del cap de línea y el final de la línea.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getStrokeStartCap() {#getStrokeStartCap--}
```
public int getStrokeStartCap()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el valor en la enumeración LineCap que indica el cap de línea utilizado al inicio de la línea a dibujar

**Returns:**
int
### setStrokeStartCap(int value) {#setStrokeStartCap-int-}
```
public void setStrokeStartCap(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el valor en la enumeración LineCap que indica el cap de línea utilizado al inicio de la línea a dibujar

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getStrokeEndCap() {#getStrokeEndCap--}
```
public int getStrokeEndCap()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el valor en la enumeración LineCap que indica qué cap de línea se debe usar al final de la línea a dibujar.

**Returns:**
int
### setStrokeEndCap(int value) {#setStrokeEndCap-int-}
```
public void setStrokeEndCap(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el valor en la enumeración LineCap que indica qué cap de línea se debe usar al final de la línea a dibujar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el valor en la enumeración LineJoin (sección 2.1.1.19), la cual indica cómo unir dos líneas dibujadas con la misma pluma y cuyas extremidades se encuentran. En la intersección de los dos extremos de línea, una unión de línea hace que la conexión parezca más continua.

**Returns:**
int
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el valor en la enumeración LineJoin (sección 2.1.1.19), la cual indica cómo unir dos líneas dibujadas con la misma pluma y cuyas extremidades se encuentran. En la intersección de los dos extremos de línea, una unión de línea hace que la conexión parezca más continua.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getStrokeMiterLimit() {#getStrokeMiterLimit--}
```
public float getStrokeMiterLimit()
```


Obtiene o establece un valor de punto flotante de 32 bits que contiene el límite del grosor de la unión en una esquina en ángulo recto al establecer la relación máxima permitida entre la longitud del ángulo y el ancho de línea.

**Returns:**
float
### setStrokeMiterLimit(float value) {#setStrokeMiterLimit-float-}
```
public void setStrokeMiterLimit(float value)
```


Obtiene o establece un valor de punto flotante de 32 bits que contiene el límite del grosor de la unión en una esquina en ángulo recto al establecer la relación máxima permitida entre la longitud del ángulo y el ancho de línea.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica la cantidad por la cual escalar la tapa de línea personalizada con respecto al ancho del objeto EmfPlusPen (sección 2.2.1.7) que se utiliza para dibujar las líneas.

**Returns:**
float
### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica la cantidad por la cual escalar la tapa de línea personalizada con respecto al ancho del objeto EmfPlusPen (sección 2.2.1.7) que se utiliza para dibujar las líneas.

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

### getStrokeHotSpot() {#getStrokeHotSpot--}
```
public PointF getStrokeHotSpot()
```


Obtiene o establece el objeto EmfPlusPointF que no se usa actualmente. DEBE establecerse en \{0.0, 0.0\}.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setStrokeHotSpot(PointF value) {#setStrokeHotSpot-com.aspose.imaging.PointF-}
```
public void setStrokeHotSpot(PointF value)
```


Obtiene o establece el objeto EmfPlusPointF que no se usa actualmente. DEBE establecerse en \{0.0, 0.0\}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusCustomLineCapOptionalData getOptionalData()
```


Obtiene o establece el objeto opcional EmfPlusCustomLineCapOptionalData (sección 2.2.2.14) que especifica datos adicionales para la tapa de línea gráfica personalizada. El contenido específico de este campo se determina por el valor del campo CustomLineCapDataFlags.

**Returns:**
[EmfPlusCustomLineCapOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata)
### setOptionalData(EmfPlusCustomLineCapOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapOptionalData-}
```
public void setOptionalData(EmfPlusCustomLineCapOptionalData value)
```


Obtiene o establece el objeto opcional EmfPlusCustomLineCapOptionalData (sección 2.2.2.14) que especifica datos adicionales para la tapa de línea gráfica personalizada. El contenido específico de este campo se determina por el valor del campo CustomLineCapDataFlags.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusCustomLineCapOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata) |  |

