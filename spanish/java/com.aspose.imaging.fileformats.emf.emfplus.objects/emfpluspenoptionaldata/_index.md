---
title: "EmfPlusPenOptionalData"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusPenOptionalData especifica datos opcionales para un lápiz gráfico."
type: docs
weight: 65
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPenOptionalData extends EmfPlusStructureObjectType
```

El objeto EmfPlusPenOptionalData especifica datos opcionales para un lápiz gráfico.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusPenOptionalData()](#EmfPlusPenOptionalData--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Obtiene o establece un objeto opcional EmfPlusTransformMatrix (sección 2.2.2.47) que especifica una transformación de espacio mundial a espacio de dispositivo para la pluma. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Obtiene o establece un objeto opcional EmfPlusTransformMatrix (sección 2.2.2.47) que especifica una transformación de espacio mundial a espacio de dispositivo para la pluma. |
| [getStartCap()](#getStartCap--) | Obtiene o establece un entero opcional con signo de 32 bits que especifica la forma del inicio de una línea en el campo CustomStartCapData. |
| [setStartCap(int value)](#setStartCap-int-) | Obtiene o establece un entero opcional con signo de 32 bits que especifica la forma del inicio de una línea en el campo CustomStartCapData. |
| [getEndCap()](#getEndCap--) | Obtiene o establece un entero opcional con signo de 32 bits que especifica la forma del final de una línea en el campo CustomEndCapData. |
| [setEndCap(int value)](#setEndCap-int-) | Obtiene o establece un entero opcional con signo de 32 bits que especifica la forma del final de una línea en el campo CustomEndCapData. |
| [getJoin()](#getJoin--) | Obtiene o establece un entero opcional con signo de 32 bits que especifica cómo unir dos líneas que son dibujadas por la misma pluma y cuyos extremos se encuentran. |
| [setJoin(int value)](#setJoin-int-) | Obtiene o establece un entero opcional con signo de 32 bits que especifica cómo unir dos líneas que son dibujadas por la misma pluma y cuyos extremos se encuentran. |
| [getMiterLimit()](#getMiterLimit--) | Obtiene o establece un valor opcional de punto flotante de 32 bits que especifica el límite de inglete, que es la relación máxima permitida entre la longitud del inglete y el ancho de la línea. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Obtiene o establece un valor opcional de punto flotante de 32 bits que especifica el límite de inglete, que es la relación máxima permitida entre la longitud del inglete y el ancho de la línea. |
| [getLineStyle()](#getLineStyle--) | Obtiene o establece un entero opcional con signo de 32 bits que especifica el estilo utilizado para las líneas dibujadas con este objeto pen. |
| [setLineStyle(int value)](#setLineStyle-int-) | Obtiene o establece un entero opcional con signo de 32 bits que especifica el estilo utilizado para las líneas dibujadas con este objeto pen. |
| [getDashedLineCapType()](#getDashedLineCapType--) | Obtiene o establece un entero opcional con signo de 32 bits que especifica la forma de ambos extremos de cada guión en una línea discontinua. |
| [setDashedLineCapType(int value)](#setDashedLineCapType-int-) | Obtiene o establece un entero opcional con signo de 32 bits que especifica la forma de ambos extremos de cada guión en una línea discontinua. |
| [getDashOffset()](#getDashOffset--) | Obtiene o establece un valor opcional de punto flotante de 32 bits que especifica la distancia desde el inicio de una línea hasta el inicio del primer espacio en un patrón de línea discontinua. |
| [setDashOffset(float value)](#setDashOffset-float-) | Obtiene o establece un valor opcional de punto flotante de 32 bits que especifica la distancia desde el inicio de una línea hasta el inicio del primer espacio en un patrón de línea discontinua. |
| [getDashedLineData()](#getDashedLineData--) | Obtiene o establece un objeto opcional EmfPlusDashedLineData (sección 2.2.2.16) que especifica las longitudes de los guiones y espacios en una línea discontinua personalizada. |
| [setDashedLineData(EmfPlusDashedLineData value)](#setDashedLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusDashedLineData-) | Obtiene o establece un objeto opcional EmfPlusDashedLineData (sección 2.2.2.16) que especifica las longitudes de los guiones y espacios en una línea discontinua personalizada. |
| [getPenAlignment()](#getPenAlignment--) | Obtiene o establece un entero opcional con signo de 32 bits que especifica la distribución del ancho de la pluma con respecto a las coordenadas de la línea que se está dibujando. |
| [setPenAlignment(int value)](#setPenAlignment-int-) | Obtiene o establece un entero opcional con signo de 32 bits que especifica la distribución del ancho de la pluma con respecto a las coordenadas de la línea que se está dibujando. |
| [getCompoundLineData()](#getCompoundLineData--) | Obtiene o establece un objeto opcional EmfPlusCompoundLineData (sección 2.2.2.9) que especifica una matriz de valores de punto flotante que definen la línea compuesta de una pluma, que está formada por líneas paralelas y espacios. |
| [setCompoundLineData(EmfPlusCompoundLineData value)](#setCompoundLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCompoundLineData-) | Obtiene o establece un objeto opcional EmfPlusCompoundLineData (sección 2.2.2.9) que especifica una matriz de valores de punto flotante que definen la línea compuesta de una pluma, que está formada por líneas paralelas y espacios. |
| [getCustomStartCapData()](#getCustomStartCapData--) | Obtiene o establece un objeto opcional EmfPlusCustomStartCapData (sección 2.2.2.15) que define la forma de la tapa inicial personalizada, que es la forma a usar al inicio de una línea dibujada con esta pluma. |
| [setCustomStartCapData(EmfPlusCustomStartCapData value)](#setCustomStartCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomStartCapData-) | Obtiene o establece un objeto opcional EmfPlusCustomStartCapData (sección 2.2.2.15) que define la forma de la tapa inicial personalizada, que es la forma a usar al inicio de una línea dibujada con esta pluma. |
| [getCustomEndCapData()](#getCustomEndCapData--) | Obtiene o establece un objeto opcional EmfPlusCustomEndCapData (sección 2.2.2.11) que define la forma de la tapa final personalizada, que es la forma a usar al final de una línea dibujada con esta pluma. |
| [setCustomEndCapData(EmfPlusCustomEndCapData value)](#setCustomEndCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomEndCapData-) | Obtiene o establece un objeto opcional EmfPlusCustomEndCapData (sección 2.2.2.11) que define la forma de la tapa final personalizada, que es la forma a usar al final de una línea dibujada con esta pluma. |
### EmfPlusPenOptionalData() {#EmfPlusPenOptionalData--}
```
public EmfPlusPenOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Obtiene o establece un objeto opcional EmfPlusTransformMatrix (sección 2.2.2.47) que especifica una transformación de espacio mundial a espacio de dispositivo para la pluma. Este campo DEBE estar presente si la bandera PenDataTransform está establecida en el campo PenDataFlags del objeto EmfPlusPenData.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Obtiene o establece un objeto opcional EmfPlusTransformMatrix (sección 2.2.2.47) que especifica una transformación de espacio mundial a espacio de dispositivo para la pluma. Este campo DEBE estar presente si la bandera PenDataTransform está establecida en el campo PenDataFlags del objeto EmfPlusPenData.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


Obtiene o establece un entero opcional con signo de 32 bits que especifica la forma del inicio de una línea en el campo CustomStartCapData. Este campo DEBE estar presente si la bandera PenDataStartCap está establecida en el campo PenDataFlags del objeto EmfPlusPenData, y el valor DEBE estar definido en la enumeración LineCapType (sección 2.1.1.18).

**Returns:**
int
### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


Obtiene o establece un entero opcional con signo de 32 bits que especifica la forma del inicio de una línea en el campo CustomStartCapData. Este campo DEBE estar presente si la bandera PenDataStartCap está establecida en el campo PenDataFlags del objeto EmfPlusPenData, y el valor DEBE estar definido en la enumeración LineCapType (sección 2.1.1.18).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


Obtiene o establece un entero opcional con signo de 32 bits que especifica la forma del final de una línea en el campo CustomEndCapData. Este campo DEBE estar presente si la bandera PenDataEndCap está establecida en el campo PenDataFlags del objeto EmfPlusPenData, y el valor DEBE estar definido en la enumeración LineCapType.

**Returns:**
int
### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


Obtiene o establece un entero opcional con signo de 32 bits que especifica la forma del final de una línea en el campo CustomEndCapData. Este campo DEBE estar presente si la bandera PenDataEndCap está establecida en el campo PenDataFlags del objeto EmfPlusPenData, y el valor DEBE estar definido en la enumeración LineCapType.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getJoin() {#getJoin--}
```
public int getJoin()
```


Obtiene o establece un entero con signo de 32 bits opcional que especifica cómo unir dos líneas que son dibujadas por la misma pluma y cuyos extremos se encuentran. Este campo DEBE estar presente si la bandera PenDataJoin está establecida en el campo PenDataFlags del objeto EmfPlusPenData, y el valor DEBE estar definido en la enumeración LineJoinType (sección 2.1.1.19).

**Returns:**
int
### setJoin(int value) {#setJoin-int-}
```
public void setJoin(int value)
```


Obtiene o establece un entero con signo de 32 bits opcional que especifica cómo unir dos líneas que son dibujadas por la misma pluma y cuyos extremos se encuentran. Este campo DEBE estar presente si la bandera PenDataJoin está establecida en el campo PenDataFlags del objeto EmfPlusPenData, y el valor DEBE estar definido en la enumeración LineJoinType (sección 2.1.1.19).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


Obtiene o establece un valor de punto flotante de 32 bits opcional que especifica el límite de inglete, que es la relación máxima permitida entre la longitud del inglete y el ancho de la línea. La longitud del inglete es la distancia desde la intersección de las paredes de la línea en el interior de la unión hasta la intersección de las paredes de la línea fuera de la unión. La longitud del inglete puede ser grande cuando el ángulo entre dos líneas es pequeño. Este campo DEBE estar presente si la bandera PenDataMiterLimit está establecida en el campo PenDataFlags del objeto EmfPlusPenData.

**Returns:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


Obtiene o establece un valor de punto flotante de 32 bits opcional que especifica el límite de inglete, que es la relación máxima permitida entre la longitud del inglete y el ancho de la línea. La longitud del inglete es la distancia desde la intersección de las paredes de la línea en el interior de la unión hasta la intersección de las paredes de la línea fuera de la unión. La longitud del inglete puede ser grande cuando el ángulo entre dos líneas es pequeño. Este campo DEBE estar presente si la bandera PenDataMiterLimit está establecida en el campo PenDataFlags del objeto EmfPlusPenData.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getLineStyle() {#getLineStyle--}
```
public int getLineStyle()
```


Obtiene o establece un entero con signo de 32 bits opcional que especifica el estilo usado para las líneas dibujadas con este objeto de pluma. Este campo DEBE estar presente si la bandera PenDataLineStyle está establecida en el campo PenDataFlags del objeto EmfPlusPenData, y el valor DEBE estar definido en la enumeración LineStyle (sección 2.1.1.20).

**Returns:**
int
### setLineStyle(int value) {#setLineStyle-int-}
```
public void setLineStyle(int value)
```


Obtiene o establece un entero con signo de 32 bits opcional que especifica el estilo usado para las líneas dibujadas con este objeto de pluma. Este campo DEBE estar presente si la bandera PenDataLineStyle está establecida en el campo PenDataFlags del objeto EmfPlusPenData, y el valor DEBE estar definido en la enumeración LineStyle (sección 2.1.1.20).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getDashedLineCapType() {#getDashedLineCapType--}
```
public int getDashedLineCapType()
```


Obtiene o establece un entero con signo de 32 bits opcional que especifica la forma de ambos extremos de cada guión en una línea discontinua. Este campo DEBE estar presente si la bandera PenDataDashedLineCap está establecida en el campo PenDataFlags del objeto EmfPlusPenData, y el valor DEBE estar definido en la enumeración DashedLineCapType (sección 2.1.1.10).

**Returns:**
int
### setDashedLineCapType(int value) {#setDashedLineCapType-int-}
```
public void setDashedLineCapType(int value)
```


Obtiene o establece un entero con signo de 32 bits opcional que especifica la forma de ambos extremos de cada guión en una línea discontinua. Este campo DEBE estar presente si la bandera PenDataDashedLineCap está establecida en el campo PenDataFlags del objeto EmfPlusPenData, y el valor DEBE estar definido en la enumeración DashedLineCapType (sección 2.1.1.10).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


Obtiene o establece un valor de punto flotante de 32 bits opcional que especifica la distancia desde el inicio de una línea hasta el inicio del primer espacio en un patrón de línea discontinua. Este campo DEBE estar presente si la bandera PenDataDashedLineOffset está establecida en el campo PenDataFlags del objeto EmfPlusPenData.

**Returns:**
float
### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


Obtiene o establece un valor de punto flotante de 32 bits opcional que especifica la distancia desde el inicio de una línea hasta el inicio del primer espacio en un patrón de línea discontinua. Este campo DEBE estar presente si la bandera PenDataDashedLineOffset está establecida en el campo PenDataFlags del objeto EmfPlusPenData.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getDashedLineData() {#getDashedLineData--}
```
public EmfPlusDashedLineData getDashedLineData()
```


Obtiene o establece el objeto opcional EmfPlusDashedLineData (sección 2.2.2.16) que especifica las longitudes de los guiones y espacios en una línea discontinua personalizada. Este campo DEBE estar presente si la bandera PenDataDashedLine está establecida en el campo PenDataFlags del objeto EmfPlusPenData.

**Returns:**
[EmfPlusDashedLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata)
### setDashedLineData(EmfPlusDashedLineData value) {#setDashedLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusDashedLineData-}
```
public void setDashedLineData(EmfPlusDashedLineData value)
```


Obtiene o establece el objeto opcional EmfPlusDashedLineData (sección 2.2.2.16) que especifica las longitudes de los guiones y espacios en una línea discontinua personalizada. Este campo DEBE estar presente si la bandera PenDataDashedLine está establecida en el campo PenDataFlags del objeto EmfPlusPenData.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusDashedLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata) |  |

### getPenAlignment() {#getPenAlignment--}
```
public int getPenAlignment()
```


Obtiene o establece un entero con signo de 32 bits opcional que especifica la distribución del ancho de la pluma con respecto a las coordenadas de la línea que se está dibujando. Este campo DEBE estar presente si la bandera PenDataNonCenter está establecida en el campo PenDataFlags del objeto EmfPlusPenData, y el valor DEBE estar definido en la enumeración PenAlignment (sección 2.1.1.24).

**Returns:**
int
### setPenAlignment(int value) {#setPenAlignment-int-}
```
public void setPenAlignment(int value)
```


Obtiene o establece un entero con signo de 32 bits opcional que especifica la distribución del ancho de la pluma con respecto a las coordenadas de la línea que se está dibujando. Este campo DEBE estar presente si la bandera PenDataNonCenter está establecida en el campo PenDataFlags del objeto EmfPlusPenData, y el valor DEBE estar definido en la enumeración PenAlignment (sección 2.1.1.24).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCompoundLineData() {#getCompoundLineData--}
```
public EmfPlusCompoundLineData getCompoundLineData()
```


Obtiene o establece el objeto opcional EmfPlusCompoundLineData (sección 2.2.2.9) que especifica una matriz de valores de punto flotante que definen la línea compuesta de una pluma, la cual está formada por líneas paralelas y espacios. Este campo DEBE estar presente si la bandera PenDataCompoundLine está establecida en el campo PenDataFlags del objeto EmfPlusPenData

**Returns:**
[EmfPlusCompoundLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata)
### setCompoundLineData(EmfPlusCompoundLineData value) {#setCompoundLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCompoundLineData-}
```
public void setCompoundLineData(EmfPlusCompoundLineData value)
```


Obtiene o establece el objeto opcional EmfPlusCompoundLineData (sección 2.2.2.9) que especifica una matriz de valores de punto flotante que definen la línea compuesta de una pluma, la cual está formada por líneas paralelas y espacios. Este campo DEBE estar presente si la bandera PenDataCompoundLine está establecida en el campo PenDataFlags del objeto EmfPlusPenData

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusCompoundLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata) |  |

### getCustomStartCapData() {#getCustomStartCapData--}
```
public EmfPlusCustomStartCapData getCustomStartCapData()
```


Obtiene o establece el objeto opcional EmfPlusCustomStartCapData (sección 2.2.2.15) que define la forma de capucha inicial personalizada, que es la forma a usar al inicio de una línea dibujada con esta pluma. Puede ser cualquiera de varias formas, como un cuadrado, círculo o diamante. Este campo DEBE estar presente si la bandera PenDataCustomStartCap está establecida en el campo PenDataFlags del objeto EmfPlusPenData

**Returns:**
[EmfPlusCustomStartCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata)
### setCustomStartCapData(EmfPlusCustomStartCapData value) {#setCustomStartCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomStartCapData-}
```
public void setCustomStartCapData(EmfPlusCustomStartCapData value)
```


Obtiene o establece el objeto opcional EmfPlusCustomStartCapData (sección 2.2.2.15) que define la forma de capucha inicial personalizada, que es la forma a usar al inicio de una línea dibujada con esta pluma. Puede ser cualquiera de varias formas, como un cuadrado, círculo o diamante. Este campo DEBE estar presente si la bandera PenDataCustomStartCap está establecida en el campo PenDataFlags del objeto EmfPlusPenData

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusCustomStartCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata) |  |

### getCustomEndCapData() {#getCustomEndCapData--}
```
public EmfPlusCustomEndCapData getCustomEndCapData()
```


Obtiene o establece el objeto opcional EmfPlusCustomEndCapData (sección 2.2.2.11) que define la forma de capucha final personalizada, que es la forma a usar al final de una línea dibujada con esta pluma. Puede ser cualquiera de varias formas, como un cuadrado, círculo o diamante. Este campo DEBE estar presente si la bandera PenDataCustomEndCap está establecida en el campo PenDataFlags del objeto EmfPlusPenData

**Returns:**
[EmfPlusCustomEndCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata)
### setCustomEndCapData(EmfPlusCustomEndCapData value) {#setCustomEndCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomEndCapData-}
```
public void setCustomEndCapData(EmfPlusCustomEndCapData value)
```


Obtiene o establece el objeto opcional EmfPlusCustomEndCapData (sección 2.2.2.11) que define la forma de capucha final personalizada, que es la forma a usar al final de una línea dibujada con esta pluma. Puede ser cualquiera de varias formas, como un cuadrado, círculo o diamante. Este campo DEBE estar presente si la bandera PenDataCustomEndCap está establecida en el campo PenDataFlags del objeto EmfPlusPenData

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusCustomEndCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata) |  |

