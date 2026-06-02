---
title: "EmfPlusLinearGradientBrushData"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusLinearGradientBrushData especifica un degradado lineal para un pincel gráfico."
type: docs
weight: 53
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusLinearGradientBrushData extends EmfPlusBaseBrushData
```

El objeto EmfPlusLinearGradientBrushData especifica un degradado lineal para un pincel gráfico.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusLinearGradientBrushData()](#EmfPlusLinearGradientBrushData--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBrushDataFlags()](#getBrushDataFlags--) | Obtiene o establece las banderas de datos del pincel. |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | Obtiene o establece las banderas de datos del pincel. |
| [getEndArgb32Color()](#getEndArgb32Color--) | Obtiene o establece el color final. |
| [setEndArgb32Color(int value)](#setEndArgb32Color-int-) | Obtiene o establece el color final. |
| [getOptionalData()](#getOptionalData--) | Obtiene o establece los datos opcionales. |
| [setOptionalData(EmfPlusLinearGradientBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData-) | Obtiene o establece los datos opcionales. |
| [getRectF()](#getRectF--) | Obtiene o establece el rect f. |
| [setRectF(RectangleF value)](#setRectF-com.aspose.imaging.RectangleF-) | Obtiene o establece el rect f. |
| [getStartArgb32Color()](#getStartArgb32Color--) | Obtiene o establece el color inicial. |
| [setStartArgb32Color(int value)](#setStartArgb32Color-int-) | Obtiene o establece el color inicial. |
| [getWrapMode()](#getWrapMode--) | Obtiene o establece el modo de ajuste. |
| [setWrapMode(int value)](#setWrapMode-int-) | Obtiene o establece el modo de ajuste. |
### EmfPlusLinearGradientBrushData() {#EmfPlusLinearGradientBrushData--}
```
public EmfPlusLinearGradientBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


Obtiene o establece las banderas de datos del pincel.

Valor: BrushDataFlags (4 bytes): Un entero sin signo de 32 bits que especifica los datos en el campo OptionalData. Este valor DEBE estar compuesto por `EmfPlusBrushDataFlags` (sección 2.1.2.1).

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


Obtiene o establece las banderas de datos del pincel.

Valor: BrushDataFlags (4 bytes): Un entero sin signo de 32 bits que especifica los datos en el campo OptionalData. Este valor DEBE estar compuesto por `EmfPlusBrushDataFlags` (sección 2.1.2.1).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getEndArgb32Color() {#getEndArgb32Color--}
```
public int getEndArgb32Color()
```


Obtiene o establece el color final.

Valor: Un objeto EmfPlusARGB que especifica el color en el punto de límite final del pincel de degradado lineal.

**Returns:**
int
### setEndArgb32Color(int value) {#setEndArgb32Color-int-}
```
public void setEndArgb32Color(int value)
```


Obtiene o establece el color final.

Valor: Un objeto EmfPlusARGB que especifica el color en el punto de límite final del pincel de degradado lineal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusLinearGradientBrushOptionalData getOptionalData()
```


Obtiene o establece los datos opcionales.

Valor: Un objeto opcional `EmfPlusLinearGradientBrushOptionalData` (sección 2.2.2.25) que especifica datos adicionales para el pincel de degradado lineal. El contenido específico de este campo se determina por el valor del campo BrushDataFlags.

**Returns:**
[EmfPlusLinearGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata)
### setOptionalData(EmfPlusLinearGradientBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData-}
```
public void setOptionalData(EmfPlusLinearGradientBrushOptionalData value)
```


Obtiene o establece los datos opcionales.

Valor: Un objeto opcional `EmfPlusLinearGradientBrushOptionalData` (sección 2.2.2.25) que especifica datos adicionales para el pincel de degradado lineal. El contenido específico de este campo se determina por el valor del campo BrushDataFlags.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusLinearGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata) |  |

### getRectF() {#getRectF--}
```
public RectangleF getRectF()
```


Obtiene o establece el rect f.

Valor: Un objeto EmfPlusRectF (sección 2.2.2.39) que especifica los puntos de inicio y fin de la línea de degradado. La esquina superior izquierda del rectángulo es el punto de inicio. La esquina inferior derecha es el punto de fin.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectF(RectangleF value) {#setRectF-com.aspose.imaging.RectangleF-}
```
public void setRectF(RectangleF value)
```


Obtiene o establece el rect f.

Valor: Un objeto EmfPlusRectF (sección 2.2.2.39) que especifica los puntos de inicio y fin de la línea de degradado. La esquina superior izquierda del rectángulo es el punto de inicio. La esquina inferior derecha es el punto de fin.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getStartArgb32Color() {#getStartArgb32Color--}
```
public int getStartArgb32Color()
```


Obtiene o establece el color inicial.

Valor: Un objeto EmfPlusARGB (sección 2.2.2.1) que especifica el color en el punto de límite inicial del pincel de degradado lineal.

**Returns:**
int
### setStartArgb32Color(int value) {#setStartArgb32Color-int-}
```
public void setStartArgb32Color(int value)
```


Obtiene o establece el color inicial.

Valor: Un objeto EmfPlusARGB (sección 2.2.2.1) que especifica el color en el punto de límite inicial del pincel de degradado lineal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Obtiene o establece el modo de ajuste.

Valor: Un entero con signo de 32 bits de la enumeración WrapMode (sección 2.1.1.34) que especifica si se debe pintar el área fuera del límite del pincel. Al pintar fuera del límite, el modo de ajuste especifica cómo se repite el degradado de color.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Obtiene o establece el modo de ajuste.

Valor: Un entero con signo de 32 bits de la enumeración WrapMode (sección 2.1.1.34) que especifica si se debe pintar el área fuera del límite del pincel. Al pintar fuera del límite, el modo de ajuste especifica cómo se repite el degradado de color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

