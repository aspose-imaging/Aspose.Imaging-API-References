---
title: "EmfPlusBlendBase"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Objeto base para objetos de mezcla"
type: docs
weight: 16
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public abstract class EmfPlusBlendBase extends EmfPlusStructureObjectType
```

Objeto base para objetos de mezcla
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusBlendBase()](#EmfPlusBlendBase--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBlendPositions()](#getBlendPositions--) | Obtiene o establece posiciones de mezcla, una matriz de valores de punto flotante de 32 bits PositionCount que especifican proporciones de distancia a lo largo de la línea de degradado. |
| [setBlendPositions(float[] value)](#setBlendPositions-float---) | Obtiene o establece posiciones de mezcla, una matriz de valores de punto flotante de 32 bits PositionCount que especifican proporciones de distancia a lo largo de la línea de degradado. |
### EmfPlusBlendBase() {#EmfPlusBlendBase--}
```
public EmfPlusBlendBase()
```


### getBlendPositions() {#getBlendPositions--}
```
public float[] getBlendPositions()
```


Obtiene o establece posiciones de mezcla, una matriz de valores de punto flotante de 32 bits PositionCount que especifican proporciones de distancia a lo largo de la línea de degradado. Cada elemento DEBE ser un número entre 0.0 y 1.0 inclusive. Para un pincel de degradado lineal, 0.0 representa el punto de inicio y 1.0 representa el punto final. Para un pincel de degradado de ruta, 0.0 representa el punto medio y 1.0 representa un punto final.

**Returns:**
float[]
### setBlendPositions(float[] value) {#setBlendPositions-float---}
```
public void setBlendPositions(float[] value)
```


Obtiene o establece posiciones de mezcla, una matriz de valores de punto flotante de 32 bits PositionCount que especifican proporciones de distancia a lo largo de la línea de degradado. Cada elemento DEBE ser un número entre 0.0 y 1.0 inclusive. Para un pincel de degradado lineal, 0.0 representa el punto de inicio y 1.0 representa el punto final. Para un pincel de degradado de ruta, 0.0 representa el punto medio y 1.0 representa un punto final.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float[] |  |

