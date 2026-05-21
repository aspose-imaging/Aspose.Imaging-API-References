---
title: "EmfPlusBlurEffect"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto BlurEffect especifica una disminución en la diferencia de intensidad entre píxeles en una imagen."
type: docs
weight: 19
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusBlurEffect extends EmfPlusImageEffectsObjectType
```

El objeto BlurEffect especifica una disminución en la diferencia de intensidad entre píxeles en una imagen.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusBlurEffect()](#EmfPlusBlurEffect--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Obtiene o establece un número de punto flotante de 32 bits que especifica el radio de desenfoque en píxeles, lo que determina la cantidad de píxeles involucrados en calcular el nuevo valor de un píxel dado. |
| [setBlurRadius(float value)](#setBlurRadius-float-) | Obtiene o establece un número de punto flotante de 32 bits que especifica el radio de desenfoque en píxeles, lo que determina la cantidad de píxeles involucrados en calcular el nuevo valor de un píxel dado. |
| [getExpandEdge()](#getExpandEdge--) | Obtiene o establece un valor Booleano de 32 bits que especifica si el mapa de bits se expande en una cantidad igual al valor de BlurRadius para producir bordes suaves. |
| [setExpandEdge(boolean value)](#setExpandEdge-boolean-) | Obtiene o establece un valor Booleano de 32 bits que especifica si el mapa de bits se expande en una cantidad igual al valor de BlurRadius para producir bordes suaves. |
### EmfPlusBlurEffect() {#EmfPlusBlurEffect--}
```
public EmfPlusBlurEffect()
```


### getBlurRadius() {#getBlurRadius--}
```
public float getBlurRadius()
```


Obtiene o establece un número de punto flotante de 32 bits que especifica el radio de desenfoque en píxeles, lo que determina la cantidad de píxeles involucrados en calcular el nuevo valor de un píxel dado. Este valor DEBE estar en el rango de 0.0 a 255.0.

**Returns:**
float
### setBlurRadius(float value) {#setBlurRadius-float-}
```
public void setBlurRadius(float value)
```


Obtiene o establece un número de punto flotante de 32 bits que especifica el radio de desenfoque en píxeles, lo que determina la cantidad de píxeles involucrados en calcular el nuevo valor de un píxel dado. Este valor DEBE estar en el rango de 0.0 a 255.0.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getExpandEdge() {#getExpandEdge--}
```
public boolean getExpandEdge()
```


Obtiene o establece un valor Booleano de 32 bits que especifica si el mapa de bits se expande en una cantidad igual al valor de BlurRadius para producir bordes suaves. Este valor DEBE ser uno de los siguientes: FALSE 0x00000000 El tamaño del mapa de bits NO DEBE cambiar, y sus bordes suaves DEBERÍAN recortarse al tamaño de BlurRadius. TRUE 0x00000001 El tamaño del mapa de bits DEBERÍA expandirse en una cantidad igual a BlurRadius para producir bordes suaves.

**Returns:**
boolean
### setExpandEdge(boolean value) {#setExpandEdge-boolean-}
```
public void setExpandEdge(boolean value)
```


Obtiene o establece un valor Booleano de 32 bits que especifica si el mapa de bits se expande en una cantidad igual al valor de BlurRadius para producir bordes suaves. Este valor DEBE ser uno de los siguientes: FALSE 0x00000000 El tamaño del mapa de bits NO DEBE cambiar, y sus bordes suaves DEBERÍAN recortarse al tamaño de BlurRadius. TRUE 0x00000001 El tamaño del mapa de bits DEBERÍA expandirse en una cantidad igual a BlurRadius para producir bordes suaves.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

