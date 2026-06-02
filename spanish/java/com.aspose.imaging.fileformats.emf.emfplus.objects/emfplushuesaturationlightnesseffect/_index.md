---
title: "EmfPlusHueSaturationLightnessEffect"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto HueSaturationLightnessEffect especifica ajustes al tono, saturación y luminosidad de una imagen."
type: docs
weight: 46
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplushuesaturationlightnesseffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusHueSaturationLightnessEffect extends EmfPlusImageEffectsObjectType
```

El objeto HueSaturationLightnessEffect especifica ajustes al tono, la saturación y la luminosidad de una imagen.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusHueSaturationLightnessEffect()](#EmfPlusHueSaturationLightnessEffect--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getHueLevel()](#getHueLevel--) | Obtiene o establece el ajuste al tono. |
| [setHueLevel(int value)](#setHueLevel-int-) | Obtiene o establece el ajuste al tono. |
| [getSaturationLevel()](#getSaturationLevel--) | Obtiene o establece el ajuste a la saturación. |
| [setSaturationLevel(int value)](#setSaturationLevel-int-) | Obtiene o establece el ajuste a la saturación. |
| [getLightnessLevel()](#getLightnessLevel--) | Obtiene o establece el ajuste a la luminosidad. |
| [setLightnessLevel(int value)](#setLightnessLevel-int-) | Obtiene o establece el ajuste a la luminosidad. |
### EmfPlusHueSaturationLightnessEffect() {#EmfPlusHueSaturationLightnessEffect--}
```
public EmfPlusHueSaturationLightnessEffect()
```


### getHueLevel() {#getHueLevel--}
```
public int getHueLevel()
```


Obtiene o establece el ajuste al tono. -180 \\u2264 valor < 0 Los valores negativos especifican rotación en sentido horario en la rueda de color. 0 Un valor de 0 especifica que el tono NO DEBE cambiar. 0 < valor \\u2264 180 Los valores positivos especifican rotación en sentido antihorario en la rueda de color.

Valor: El nivel de tono.

**Returns:**
int
### setHueLevel(int value) {#setHueLevel-int-}
```
public void setHueLevel(int value)
```


Obtiene o establece el ajuste al tono. -180 \\u2264 valor < 0 Los valores negativos especifican rotación en sentido horario en la rueda de color. 0 Un valor de 0 especifica que el tono NO DEBE cambiar. 0 < valor \\u2264 180 Los valores positivos especifican rotación en sentido antihorario en la rueda de color.

Valor: El nivel de tono.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getSaturationLevel() {#getSaturationLevel--}
```
public int getSaturationLevel()
```


Obtiene o establece el ajuste a la saturación. -100 \\u2264 valor < 0 Los valores negativos especifican disminución de la saturación. 0 Un valor de 0 especifica que la saturación NO DEBE cambiar. 0 < valor \\u2264 100 Los valores positivos especifican aumento de la saturación.

Valor: El nivel de saturación.

**Returns:**
int
### setSaturationLevel(int value) {#setSaturationLevel-int-}
```
public void setSaturationLevel(int value)
```


Obtiene o establece el ajuste a la saturación. -100 \\u2264 valor < 0 Los valores negativos especifican disminución de la saturación. 0 Un valor de 0 especifica que la saturación NO DEBE cambiar. 0 < valor \\u2264 100 Los valores positivos especifican aumento de la saturación.

Valor: El nivel de saturación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getLightnessLevel() {#getLightnessLevel--}
```
public int getLightnessLevel()
```


Obtiene o establece el ajuste a la luminosidad. -100 \\u2264 valor < 0 Los valores negativos especifican disminución de la luminosidad. 0 Un valor de 0 especifica que la luminosidad NO DEBE cambiar. 0 < valor \\u2264 100 Los valores positivos especifican aumento de la luminosidad.

Valor: El nivel de luminosidad.

**Returns:**
int
### setLightnessLevel(int value) {#setLightnessLevel-int-}
```
public void setLightnessLevel(int value)
```


Obtiene o establece el ajuste a la luminosidad. -100 \\u2264 valor < 0 Los valores negativos especifican disminución de la luminosidad. 0 Un valor de 0 especifica que la luminosidad NO DEBE cambiar. 0 < valor \\u2264 100 Los valores positivos especifican aumento de la luminosidad.

Valor: El nivel de luminosidad.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

