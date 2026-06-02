---
title: "EmfPlusPathGradientBrushOptionalData"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusPathGradientBrushOptionalData especifica datos opcionales para un pincel de gradiente de ruta."
type: docs
weight: 60
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPathGradientBrushOptionalData extends EmfPlusStructureObjectType
```

El objeto EmfPlusPathGradientBrushOptionalData especifica datos opcionales para un pincel de gradiente de ruta.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusPathGradientBrushOptionalData()](#EmfPlusPathGradientBrushOptionalData--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Obtiene o establece un objeto EmfPlusTransformMatrix opcional (sección 2.2.2.47) que especifica una transformación de espacio mundial a espacio de dispositivo para el pincel de degradado de trayectoria. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Obtiene o establece un objeto EmfPlusTransformMatrix opcional (sección 2.2.2.47) que especifica una transformación de espacio mundial a espacio de dispositivo para el pincel de degradado de trayectoria. |
| [getBlendPattern()](#getBlendPattern--) | Obtiene o establece un patrón de mezcla opcional para el pincel de degradado de trayectoria. |
| [setBlendPattern(EmfPlusBlendBase value)](#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase-) | Obtiene o establece un patrón de mezcla opcional para el pincel de degradado de trayectoria. |
| [getFocusScaleData()](#getFocusScaleData--) | Obtiene o establece un objeto opcional EmfPlusFocusScaleData (sección 2.2.2.18) que especifica las escalas de foco para el pincel de degradado de trayectoria. |
| [setFocusScaleData(EmfPlusFocusScaleData value)](#setFocusScaleData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFocusScaleData-) | Obtiene o establece un objeto opcional EmfPlusFocusScaleData (sección 2.2.2.18) que especifica las escalas de foco para el pincel de degradado de trayectoria. |
### EmfPlusPathGradientBrushOptionalData() {#EmfPlusPathGradientBrushOptionalData--}
```
public EmfPlusPathGradientBrushOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Obtiene o establece un objeto opcional EmfPlusTransformMatrix (sección 2.2.2.47) que especifica una transformación del espacio mundial al espacio del dispositivo para el pincel de degradado de trayectoria. Este campo DEBE estar presente si la bandera BrushDataTransform está establecida en el campo BrushDataFlags del objeto EmfPlusPathGradientBrushData.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Obtiene o establece un objeto opcional EmfPlusTransformMatrix (sección 2.2.2.47) que especifica una transformación del espacio mundial al espacio del dispositivo para el pincel de degradado de trayectoria. Este campo DEBE estar presente si la bandera BrushDataTransform está establecida en el campo BrushDataFlags del objeto EmfPlusPathGradientBrushData.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getBlendPattern() {#getBlendPattern--}
```
public EmfPlusBlendBase getBlendPattern()
```


Obtiene o establece un patrón de mezcla opcional para el pincel de degradado de trayectoria. Si este campo está presente, DEBE contener ya sea un objeto EmfPlusBlendColors (sección 2.2.2.4) o un objeto EmfPlusBlendFactors (sección 2.2.2.5), pero NO DEBE contener ambos. La tabla a continuación muestra las combinaciones válidas de banderas BrushData de EmfPlusPathGradientBrushData y los patrones de mezcla correspondientes:

**Returns:**
[EmfPlusBlendBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase)
### setBlendPattern(EmfPlusBlendBase value) {#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase-}
```
public void setBlendPattern(EmfPlusBlendBase value)
```


Obtiene o establece un patrón de mezcla opcional para el pincel de degradado de trayectoria. Si este campo está presente, DEBE contener ya sea un objeto EmfPlusBlendColors (sección 2.2.2.4) o un objeto EmfPlusBlendFactors (sección 2.2.2.5), pero NO DEBE contener ambos. La tabla a continuación muestra las combinaciones válidas de banderas BrushData de EmfPlusPathGradientBrushData y los patrones de mezcla correspondientes:

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusBlendBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase) |  |

### getFocusScaleData() {#getFocusScaleData--}
```
public EmfPlusFocusScaleData getFocusScaleData()
```


Obtiene o establece un objeto opcional EmfPlusFocusScaleData (sección 2.2.2.18) que especifica las escalas de foco para el pincel de degradado de trayectoria. Este campo DEBE estar presente si la bandera BrushDataFocusScales está establecida en el campo BrushDataFlags del objeto EmfPlusPathGradientBrushData.

**Returns:**
[EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata)
### setFocusScaleData(EmfPlusFocusScaleData value) {#setFocusScaleData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFocusScaleData-}
```
public void setFocusScaleData(EmfPlusFocusScaleData value)
```


Obtiene o establece un objeto opcional EmfPlusFocusScaleData (sección 2.2.2.18) que especifica las escalas de foco para el pincel de degradado de trayectoria. Este campo DEBE estar presente si la bandera BrushDataFocusScales está establecida en el campo BrushDataFlags del objeto EmfPlusPathGradientBrushData.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata) |  |

