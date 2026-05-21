---
title: "EmfPlusBlendFactors"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusBlendFactors especifica posiciones y factores para el patrón de mezcla de un pincel de degradado."
type: docs
weight: 18
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase)
```
public final class EmfPlusBlendFactors extends EmfPlusBlendBase
```

El objeto EmfPlusBlendFactors especifica posiciones y factores para el patrón de mezcla de un pincel de degradado.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusBlendFactors()](#EmfPlusBlendFactors--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBlendFactors()](#getBlendFactors--) | Obtiene o establece una matriz de PositionCount valores de punto flotante de 32 bits que especifican las proporciones de colores en las posiciones definidas en el campo BlendPositions. |
| [setBlendFactors(float[] value)](#setBlendFactors-float---) | Obtiene o establece una matriz de PositionCount valores de punto flotante de 32 bits que especifican las proporciones de colores en las posiciones definidas en el campo BlendPositions. |
### EmfPlusBlendFactors() {#EmfPlusBlendFactors--}
```
public EmfPlusBlendFactors()
```


### getBlendFactors() {#getBlendFactors--}
```
public float[] getBlendFactors()
```


Obtiene o establece una matriz de PositionCount valores de punto flotante de 32 bits que especifican las proporciones de colores en las posiciones definidas en el campo BlendPositions. Cada valor DEBE ser un número entre 0.0 y 1.0 inclusive.

**Returns:**
float[]
### setBlendFactors(float[] value) {#setBlendFactors-float---}
```
public void setBlendFactors(float[] value)
```


Obtiene o establece una matriz de PositionCount valores de punto flotante de 32 bits que especifican las proporciones de colores en las posiciones definidas en el campo BlendPositions. Cada valor DEBE ser un número entre 0.0 y 1.0 inclusive.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float[] |  |

