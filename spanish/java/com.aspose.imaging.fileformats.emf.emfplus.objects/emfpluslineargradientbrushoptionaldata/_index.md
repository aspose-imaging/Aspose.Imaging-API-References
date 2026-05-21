---
title: "EmfPlusLinearGradientBrushOptionalData"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusLinearGradientBrushOptionalData especifica datos opcionales para un pincel de degradado lineal."
type: docs
weight: 54
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusLinearGradientBrushOptionalData extends EmfPlusStructureObjectType
```

El objeto EmfPlusLinearGradientBrushOptionalData especifica datos opcionales para un pincel de degradado lineal.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusLinearGradientBrushOptionalData()](#EmfPlusLinearGradientBrushOptionalData--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Obtiene o establece un objeto opcional EmfPlusTransformMatrix (sección 2.2.2.47) que especifica una transformación de espacio mundial a espacio de dispositivo para el pincel de degradado lineal. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Obtiene o establece un objeto opcional EmfPlusTransformMatrix (sección 2.2.2.47) que especifica una transformación de espacio mundial a espacio de dispositivo para el pincel de degradado lineal. |
| [getBlendPattern()](#getBlendPattern--) | Obtiene o establece un patrón de mezcla opcional para el pincel de degradado lineal. |
| [setBlendPattern(EmfPlusBlendBase[] value)](#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase---) | Obtiene o establece un patrón de mezcla opcional para el pincel de degradado lineal. |
| [getBlendPatternAsPresetColors()](#getBlendPatternAsPresetColors--) | Obtiene el patrón de mezcla como colores predefinidos. |
| [getBlendPatternAsBlendFactorsH()](#getBlendPatternAsBlendFactorsH--) | Obtiene el patrón de mezcla como factores de mezcla h. |
| [getBlendPatternAsBlendFactorsV()](#getBlendPatternAsBlendFactorsV--) | Obtiene el patrón de mezcla como factores de mezcla v. |
### EmfPlusLinearGradientBrushOptionalData() {#EmfPlusLinearGradientBrushOptionalData--}
```
public EmfPlusLinearGradientBrushOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Obtiene o establece un objeto opcional EmfPlusTransformMatrix (sección 2.2.2.47) que especifica una transformación de espacio mundial a espacio de dispositivo para el pincel de degradado lineal. Este campo DEBE estar presente si la bandera BrushDataTransform está establecida en el campo BrushDataFlags del objeto EmfPlusLinearGradientBrushData.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Obtiene o establece un objeto opcional EmfPlusTransformMatrix (sección 2.2.2.47) que especifica una transformación de espacio mundial a espacio de dispositivo para el pincel de degradado lineal. Este campo DEBE estar presente si la bandera BrushDataTransform está establecida en el campo BrushDataFlags del objeto EmfPlusLinearGradientBrushData.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getBlendPattern() {#getBlendPattern--}
```
public EmfPlusBlendBase[] getBlendPattern()
```


Obtiene o establece un patrón de mezcla opcional para el pincel de degradado lineal. Si este campo está presente, DEBE contener ya sea un objeto EmfPlusBlendColors (sección 2.2.2.4), o uno o dos objetos EmfPlusBlendFactors (sección 2.2.2.5), pero NO DEBE contener ambos. La tabla a continuación muestra las combinaciones válidas de banderas BrushData del EmfPlusLinearGradientBrushData y los patrones de mezcla correspondientes: EmfPlusBlendFactors

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase[]
### setBlendPattern(EmfPlusBlendBase[] value) {#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase---}
```
public void setBlendPattern(EmfPlusBlendBase[] value)
```


Obtiene o establece un patrón de mezcla opcional para el pincel de degradado lineal. Si este campo está presente, DEBE contener ya sea un objeto EmfPlusBlendColors (sección 2.2.2.4), o uno o dos objetos EmfPlusBlendFactors (sección 2.2.2.5), pero NO DEBE contener ambos. La tabla a continuación muestra las combinaciones válidas de banderas BrushData del EmfPlusLinearGradientBrushData y los patrones de mezcla correspondientes: EmfPlusBlendFactors

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusBlendBase\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase) |  |

### getBlendPatternAsPresetColors() {#getBlendPatternAsPresetColors--}
```
public EmfPlusBlendColors getBlendPatternAsPresetColors()
```


Obtiene el patrón de mezcla como colores predefinidos.

Valor: El patrón de mezcla como colores predefinidos.

**Returns:**
[EmfPlusBlendColors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors)
### getBlendPatternAsBlendFactorsH() {#getBlendPatternAsBlendFactorsH--}
```
public EmfPlusBlendFactors getBlendPatternAsBlendFactorsH()
```


Obtiene el patrón de mezcla como factores de mezcla h.

Valor: El patrón de mezcla como factores de mezcla h.

**Returns:**
[EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors)
### getBlendPatternAsBlendFactorsV() {#getBlendPatternAsBlendFactorsV--}
```
public EmfPlusBlendFactors getBlendPatternAsBlendFactorsV()
```


Obtiene el patrón de mezcla como factores de mezcla v.

Valor: El patrón de mezcla como factores de mezcla v.

**Returns:**
[EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors)
