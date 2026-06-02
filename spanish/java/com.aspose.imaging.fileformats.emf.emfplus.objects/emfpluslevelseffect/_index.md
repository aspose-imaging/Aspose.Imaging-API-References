---
title: "EmfPlusLevelsEffect"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto LevelsEffect especifica ajustes a los reflejos, tonos medios y sombras de una imagen."
type: docs
weight: 51
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusLevelsEffect extends EmfPlusImageEffectsObjectType
```

El objeto LevelsEffect especifica ajustes a los resaltados, tonos medios y sombras de una imagen.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusLevelsEffect()](#EmfPlusLevelsEffect--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getHighlight()](#getHighlight--) | Obtiene o establece la cantidad de aclarado de los reflejos de una imagen. |
| [setHighlight(int value)](#setHighlight-int-) | Obtiene o establece la cantidad de aclarado de los reflejos de una imagen. |
| [getMidTone()](#getMidTone--) | Obtiene o establece la cantidad de aclarado o oscurecimiento de los tonos medios de una imagen. |
| [setMidTone(int value)](#setMidTone-int-) | Obtiene o establece la cantidad de aclarado o oscurecimiento de los tonos medios de una imagen. |
| [getShadow()](#getShadow--) | Obtiene o establece la cantidad de oscurecimiento de las sombras de una imagen. |
| [setShadow(int value)](#setShadow-int-) | Obtiene o establece la cantidad de oscurecimiento de las sombras de una imagen. |
### EmfPlusLevelsEffect() {#EmfPlusLevelsEffect--}
```
public EmfPlusLevelsEffect()
```


### getHighlight() {#getHighlight--}
```
public int getHighlight()
```


Obtiene o establece la cantidad de aclarado de los reflejos de una imagen. Los valores del canal de color en el extremo alto del rango de intensidad se alteran más que los valores cercanos al medio o al extremo bajo, lo que significa que una imagen puede aclararse sin perder el contraste entre las partes más oscuras de la imagen. 0 \\u2264 value < Especifica que los reflejos con un porcentaje de intensidad por encima de este umbral DEBERÁN aumentarse. 100 Especifica que los reflejos NO DEBEN cambiar.

Valor: El reflejo.

**Returns:**
int
### setHighlight(int value) {#setHighlight-int-}
```
public void setHighlight(int value)
```


Obtiene o establece la cantidad de aclarado de los reflejos de una imagen. Los valores del canal de color en el extremo alto del rango de intensidad se alteran más que los valores cercanos al medio o al extremo bajo, lo que significa que una imagen puede aclararse sin perder el contraste entre las partes más oscuras de la imagen. 0 \\u2264 value < Especifica que los reflejos con un porcentaje de intensidad por encima de este umbral DEBERÁN aumentarse. 100 Especifica que los reflejos NO DEBEN cambiar.

Valor: El reflejo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getMidTone() {#getMidTone--}
```
public int getMidTone()
```


Obtiene o establece la cantidad de aclarado o oscurecimiento de los tonos medios de una imagen. Los valores del canal de color en el medio del rango de intensidad se alteran más que los valores cercanos a los extremos alto o bajo, lo que significa que una imagen puede aclararse u oscurecerse sin perder el contraste entre las partes más oscuras y más claras de la imagen. -100 \\u2264 value < 0 Especifica que los tonos medios se oscurecen. 0 Especifica que los tonos medios NO DEBEN cambiar. 0 < value \\u2264 100 Especifica que los tonos medios se aclaran.

Valor: El tono medio.

**Returns:**
int
### setMidTone(int value) {#setMidTone-int-}
```
public void setMidTone(int value)
```


Obtiene o establece la cantidad de aclarado o oscurecimiento de los tonos medios de una imagen. Los valores del canal de color en el medio del rango de intensidad se alteran más que los valores cercanos a los extremos alto o bajo, lo que significa que una imagen puede aclararse u oscurecerse sin perder el contraste entre las partes más oscuras y más claras de la imagen. -100 \\u2264 value < 0 Especifica que los tonos medios se oscurecen. 0 Especifica que los tonos medios NO DEBEN cambiar. 0 < value \\u2264 100 Especifica que los tonos medios se aclaran.

Valor: El tono medio.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getShadow() {#getShadow--}
```
public int getShadow()
```


Obtiene o establece la cantidad de oscurecimiento de las sombras de una imagen. Los valores del canal de color en el extremo bajo del rango de intensidad se alteran más que los valores cercanos al medio o al extremo alto, lo que significa que una imagen puede oscurecerse sin perder el contraste entre las partes más claras de la imagen. 0 Especifica que las sombras NO DEBEN cambiar. 0 < value \\u2264 100 Especifica que las sombras con un porcentaje de intensidad por debajo de este umbral se oscurecen.

Valor: La sombra.

**Returns:**
int
### setShadow(int value) {#setShadow-int-}
```
public void setShadow(int value)
```


Obtiene o establece la cantidad de oscurecimiento de las sombras de una imagen. Los valores del canal de color en el extremo bajo del rango de intensidad se alteran más que los valores cercanos al medio o al extremo alto, lo que significa que una imagen puede oscurecerse sin perder el contraste entre las partes más claras de la imagen. 0 Especifica que las sombras NO DEBEN cambiar. 0 < value \\u2264 100 Especifica que las sombras con un porcentaje de intensidad por debajo de este umbral se oscurecen.

Valor: La sombra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

