---
title: "EmfPlusPathGradientBrushData"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusPathGradientBrushData especifica un gradiente de ruta para un pincel gráfico."
type: docs
weight: 59
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusPathGradientBrushData extends EmfPlusBaseBrushData
```

El objeto EmfPlusPathGradientBrushData especifica un gradiente de ruta para un pincel gráfico.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusPathGradientBrushData()](#EmfPlusPathGradientBrushData--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBrushDataFlags()](#getBrushDataFlags--) | Obtiene o establece un entero sin signo de 32 bits que especifica los datos en el campo OptionalData. |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica los datos en el campo OptionalData. |
| [getWrapMode()](#getWrapMode--) | Obtiene o establece un entero con signo de 32 bits de la enumeración WrapMode (sección 2.1.1.34) que especifica si se debe pintar el área fuera del límite del pincel. |
| [setWrapMode(int value)](#setWrapMode-int-) | Obtiene o establece un entero con signo de 32 bits de la enumeración WrapMode (sección 2.1.1.34) que especifica si se debe pintar el área fuera del límite del pincel. |
| [getCenterArgb32Color()](#getCenterArgb32Color--) | Obtiene o establece el objeto EmfPlusARGB (sección 2.2.2.1) que especifica el color central del pincel de degradado de ruta, que es el color que aparece en el punto central del pincel. |
| [setCenterArgb32Color(int value)](#setCenterArgb32Color-int-) | Obtiene o establece el objeto EmfPlusARGB (sección 2.2.2.1) que especifica el color central del pincel de degradado de ruta, que es el color que aparece en el punto central del pincel. |
| [getCenterPointF()](#getCenterPointF--) | Obtiene o establece el objeto EmfPlusARGB (sección 2.2.2.1) que especifica el color central del pincel de degradado de ruta, que es el color que aparece en el punto central del pincel. |
| [setCenterPointF(PointF value)](#setCenterPointF-com.aspose.imaging.PointF-) | Obtiene o establece el objeto EmfPlusARGB (sección 2.2.2.1) que especifica el color central del pincel de degradado de ruta, que es el color que aparece en el punto central del pincel. |
| [getSurroundingArgb32Colors()](#getSurroundingArgb32Colors--) | Obtiene o establece una matriz de objetos EmfPlusARGB SurroundingColorCount que especifican los colores para puntos discretos en el contorno del pincel. |
| [setSurroundingArgb32Colors(int[] value)](#setSurroundingArgb32Colors-int---) | Obtiene o establece una matriz de objetos EmfPlusARGB SurroundingColorCount que especifican los colores para puntos discretos en el contorno del pincel. |
| [getBoundaryData()](#getBoundaryData--) | Obtiene o establece el contorno del pincel de degradado de ruta, que se especifica mediante una ruta o una spline cardinal cerrada. |
| [setBoundaryData(EmfPlusBoundaryBase value)](#setBoundaryData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBoundaryBase-) | Obtiene o establece el contorno del pincel de degradado de ruta, que se especifica mediante una ruta o una spline cardinal cerrada. |
| [getOptionalData()](#getOptionalData--) | Obtiene o establece un objeto opcional EmfPlusPathGradientBrushOptionalData (sección 2.2.2.30) que especifica datos adicionales para el pincel de degradado de ruta. |
| [setOptionalData(EmfPlusPathGradientBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData-) | Obtiene o establece un objeto opcional EmfPlusPathGradientBrushOptionalData (sección 2.2.2.30) que especifica datos adicionales para el pincel de degradado de ruta. |
### EmfPlusPathGradientBrushData() {#EmfPlusPathGradientBrushData--}
```
public EmfPlusPathGradientBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


Obtiene o establece un entero sin signo de 32 bits que especifica los datos en el campo OptionalData. Este valor DEBE estar compuesto por banderas BrushData (sección 2.1.2.1). Las siguientes banderas son relevantes para un pincel de degradado de ruta:

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica los datos en el campo OptionalData. Este valor DEBE estar compuesto por banderas BrushData (sección 2.1.2.1). Las siguientes banderas son relevantes para un pincel de degradado de ruta:

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Obtiene o establece un entero con signo de 32 bits de la enumeración WrapMode (sección 2.1.1.34) que especifica si se pinta el área fuera del contorno del pincel. Al pintar fuera del contorno, el modo WrapMode especifica cómo se repite el degradado de color.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Obtiene o establece un entero con signo de 32 bits de la enumeración WrapMode (sección 2.1.1.34) que especifica si se pinta el área fuera del contorno del pincel. Al pintar fuera del contorno, el modo WrapMode especifica cómo se repite el degradado de color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCenterArgb32Color() {#getCenterArgb32Color--}
```
public int getCenterArgb32Color()
```


Obtiene o establece el objeto EmfPlusARGB (sección 2.2.2.1) que especifica el color central del pincel de degradado de ruta, que es el color que aparece en el punto central del pincel. El color del pincel cambia gradualmente desde el color del contorno hasta el color central a medida que se desplaza del contorno al punto central.

**Returns:**
int
### setCenterArgb32Color(int value) {#setCenterArgb32Color-int-}
```
public void setCenterArgb32Color(int value)
```


Obtiene o establece el objeto EmfPlusARGB (sección 2.2.2.1) que especifica el color central del pincel de degradado de ruta, que es el color que aparece en el punto central del pincel. El color del pincel cambia gradualmente desde el color del contorno hasta el color central a medida que se desplaza del contorno al punto central.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCenterPointF() {#getCenterPointF--}
```
public PointF getCenterPointF()
```


Obtiene o establece el objeto EmfPlusARGB (sección 2.2.2.1) que especifica el color central del pincel de degradado de ruta, que es el color que aparece en el punto central del pincel. El color del pincel cambia gradualmente desde el color del contorno hasta el color central a medida que se desplaza del contorno al punto central.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setCenterPointF(PointF value) {#setCenterPointF-com.aspose.imaging.PointF-}
```
public void setCenterPointF(PointF value)
```


Obtiene o establece el objeto EmfPlusARGB (sección 2.2.2.1) que especifica el color central del pincel de degradado de ruta, que es el color que aparece en el punto central del pincel. El color del pincel cambia gradualmente desde el color del contorno hasta el color central a medida que se desplaza del contorno al punto central.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getSurroundingArgb32Colors() {#getSurroundingArgb32Colors--}
```
public int[] getSurroundingArgb32Colors()
```


Obtiene o establece una matriz de objetos EmfPlusARGB SurroundingColorCount que especifican los colores para puntos discretos en el contorno del pincel.

**Returns:**
int[]
### setSurroundingArgb32Colors(int[] value) {#setSurroundingArgb32Colors-int---}
```
public void setSurroundingArgb32Colors(int[] value)
```


Obtiene o establece una matriz de objetos EmfPlusARGB SurroundingColorCount que especifican los colores para puntos discretos en el contorno del pincel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] |  |

### getBoundaryData() {#getBoundaryData--}
```
public EmfPlusBoundaryBase getBoundaryData()
```


Obtiene o establece el contorno del pincel de degradado de ruta, que se especifica mediante una ruta o una spline cardinal cerrada. Si la bandera BrushDataPath está establecida en el campo BrushDataFlags, este campo DEBE contener un objeto EmfPlusBoundaryPathData (sección 2.2.2.6); de lo contrario, este campo DEBE contener un objeto EmfPlusBoundaryPointData (sección 2.2.2.7).

**Returns:**
[EmfPlusBoundaryBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase)
### setBoundaryData(EmfPlusBoundaryBase value) {#setBoundaryData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBoundaryBase-}
```
public void setBoundaryData(EmfPlusBoundaryBase value)
```


Obtiene o establece el contorno del pincel de degradado de ruta, que se especifica mediante una ruta o una spline cardinal cerrada. Si la bandera BrushDataPath está establecida en el campo BrushDataFlags, este campo DEBE contener un objeto EmfPlusBoundaryPathData (sección 2.2.2.6); de lo contrario, este campo DEBE contener un objeto EmfPlusBoundaryPointData (sección 2.2.2.7).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusBoundaryBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase) |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusPathGradientBrushOptionalData getOptionalData()
```


Obtiene o establece un objeto opcional EmfPlusPathGradientBrushOptionalData (sección 2.2.2.30) que especifica datos adicionales para el pincel de degradado de ruta. El contenido específico de este campo se determina por el valor del campo BrushDataFlags.

**Returns:**
[EmfPlusPathGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata)
### setOptionalData(EmfPlusPathGradientBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData-}
```
public void setOptionalData(EmfPlusPathGradientBrushOptionalData value)
```


Obtiene o establece un objeto opcional EmfPlusPathGradientBrushOptionalData (sección 2.2.2.30) que especifica datos adicionales para el pincel de degradado de ruta. El contenido específico de este campo se determina por el valor del campo BrushDataFlags.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusPathGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata) |  |

