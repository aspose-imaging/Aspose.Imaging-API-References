---
title: "EmfPlusBrightnessContrastEffect"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto BrightnessContrastEffect especifica una expansión o contracción de las áreas más claras y más oscuras de una imagen."
type: docs
weight: 23
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrightnesscontrasteffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusBrightnessContrastEffect extends EmfPlusImageEffectsObjectType
```

El objeto BrightnessContrastEffect especifica una expansión o contracción de las áreas más claras y más oscuras de una imagen.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusBrightnessContrastEffect()](#EmfPlusBrightnessContrastEffect--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBrightnessLevel()](#getBrightnessLevel--) | Obtiene o establece un entero con signo de 32 bits que especifica el nivel de brillo. |
| [setBrightnessLevel(int value)](#setBrightnessLevel-int-) | Obtiene o establece un entero con signo de 32 bits que especifica el nivel de brillo. |
| [getContrastLevel()](#getContrastLevel--) | Obtiene o establece un entero con signo de 32 bits que especifica el nivel de contraste. |
| [setContrastLevel(int value)](#setContrastLevel-int-) | Obtiene o establece un entero con signo de 32 bits que especifica el nivel de contraste. |
### EmfPlusBrightnessContrastEffect() {#EmfPlusBrightnessContrastEffect--}
```
public EmfPlusBrightnessContrastEffect()
```


### getBrightnessLevel() {#getBrightnessLevel--}
```
public int getBrightnessLevel()
```


Obtiene o establece un entero con signo de 32 bits que especifica el nivel de brillo. Este valor DEBE estar en el rango -255 a 255, con los siguientes efectos: -255 \\u2264 valor < 0 A medida que el valor disminuye, el brillo de la imagen DEBERÍA disminuir. 0 Un valor de 0 especifica que el brillo NO DEBE cambiar. 0 < valor \\u2264 255 A medida que el valor aumenta, el brillo de la imagen DEBERÍA aumentar.

**Returns:**
int
### setBrightnessLevel(int value) {#setBrightnessLevel-int-}
```
public void setBrightnessLevel(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica el nivel de brillo. Este valor DEBE estar en el rango -255 a 255, con los siguientes efectos: -255 \\u2264 valor < 0 A medida que el valor disminuye, el brillo de la imagen DEBERÍA disminuir. 0 Un valor de 0 especifica que el brillo NO DEBE cambiar. 0 < valor \\u2264 255 A medida que el valor aumenta, el brillo de la imagen DEBERÍA aumentar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getContrastLevel() {#getContrastLevel--}
```
public int getContrastLevel()
```


Obtiene o establece un entero con signo de 32 bits que especifica el nivel de contraste. Este valor DEBE estar en el rango -100 a 100, con los siguientes efectos: -100 \\u2264 valor < 0 A medida que el valor disminuye, el contraste de la imagen DEBERÍA disminuir. 0 Un valor de 0 especifica que el contraste NO DEBE cambiar. 0 < valor \\u2264 100 A medida que el valor aumenta, el contraste de la imagen DEBERÍA aumentar.

**Returns:**
int
### setContrastLevel(int value) {#setContrastLevel-int-}
```
public void setContrastLevel(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica el nivel de contraste. Este valor DEBE estar en el rango -100 a 100, con los siguientes efectos: -100 \\u2264 valor < 0 A medida que el valor disminuye, el contraste de la imagen DEBERÍA disminuir. 0 Un valor de 0 especifica que el contraste NO DEBE cambiar. 0 < valor \\u2264 100 A medida que el valor aumenta, el contraste de la imagen DEBERÍA aumentar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

