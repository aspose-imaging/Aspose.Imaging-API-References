---
title: "EmfPlusCompoundLineData"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusCompoundLineData especifica datos de línea y espacio para una línea compuesta."
type: docs
weight: 30
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusCompoundLineData extends EmfPlusStructureObjectType
```

El objeto EmfPlusCompoundLineData especifica datos de línea y espacio para una línea compuesta.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusCompoundLineData()](#EmfPlusCompoundLineData--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCompoundLineData()](#getCompoundLineData--) | Obtiene o establece una matriz de valores de punto flotante CompoundLineDataSize que especifican la línea compuesta de un lápiz. |
| [setCompoundLineData(float[] value)](#setCompoundLineData-float---) | Obtiene o establece una matriz de valores de punto flotante CompoundLineDataSize que especifican la línea compuesta de un lápiz. |
### EmfPlusCompoundLineData() {#EmfPlusCompoundLineData--}
```
public EmfPlusCompoundLineData()
```


### getCompoundLineData() {#getCompoundLineData--}
```
public float[] getCompoundLineData()
```


Obtiene o establece una matriz de valores de punto flotante CompoundLineDataSize que especifican la línea compuesta de un lápiz. Los elementos DEBEN estar en orden creciente, y sus valores DEBEN estar entre 0.0 y 1.0, inclusive.

**Returns:**
float[]
### setCompoundLineData(float[] value) {#setCompoundLineData-float---}
```
public void setCompoundLineData(float[] value)
```


Obtiene o establece una matriz de valores de punto flotante CompoundLineDataSize que especifican la línea compuesta de un lápiz. Los elementos DEBEN estar en orden creciente, y sus valores DEBEN estar entre 0.0 y 1.0, inclusive.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float[] |  |

