---
title: "EmfPlusSharpenEffect"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto SharpenEffect especifica un aumento en la diferencia de intensidad entre píxeles en una imagen."
type: docs
weight: 72
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplussharpeneffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusSharpenEffect extends EmfPlusImageEffectsObjectType
```

El objeto SharpenEffect especifica un aumento en la diferencia de intensidad entre píxeles en una imagen.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusSharpenEffect()](#EmfPlusSharpenEffect--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getRadius()](#getRadius--) | Obtiene o establece un número de punto flotante de 32 bits que especifica el radio de nitidez en píxeles, lo que determina la cantidad de píxeles involucrados en el cálculo del nuevo valor de un píxel dado. |
| [setRadius(float value)](#setRadius-float-) | Obtiene o establece un número de punto flotante de 32 bits que especifica el radio de nitidez en píxeles, lo que determina la cantidad de píxeles involucrados en el cálculo del nuevo valor de un píxel dado. |
| [getAmount()](#getAmount--) | Obtiene o establece un número de punto flotante de 32 bits que especifica la diferencia de intensidad entre un píxel dado y los píxeles circundantes. |
| [setAmount(float value)](#setAmount-float-) | Obtiene o establece un número de punto flotante de 32 bits que especifica la diferencia de intensidad entre un píxel dado y los píxeles circundantes. |
### EmfPlusSharpenEffect() {#EmfPlusSharpenEffect--}
```
public EmfPlusSharpenEffect()
```


### getRadius() {#getRadius--}
```
public float getRadius()
```


Obtiene o establece un número de punto flotante de 32 bits que especifica el radio de nitidez en píxeles, lo que determina la cantidad de píxeles involucrados en el cálculo del nuevo valor de un píxel dado. A medida que este valor aumenta, la cantidad de píxeles involucrados en el cálculo aumenta, y el bitmap resultante DEBERÍA volverse más nítido.

Valor: El radio.

**Returns:**
float
### setRadius(float value) {#setRadius-float-}
```
public void setRadius(float value)
```


Obtiene o establece un número de punto flotante de 32 bits que especifica el radio de nitidez en píxeles, lo que determina la cantidad de píxeles involucrados en el cálculo del nuevo valor de un píxel dado. A medida que este valor aumenta, la cantidad de píxeles involucrados en el cálculo aumenta, y el bitmap resultante DEBERÍA volverse más nítido.

Valor: El radio.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getAmount() {#getAmount--}
```
public float getAmount()
```


Obtiene o establece un número de punto flotante de 32 bits que especifica la diferencia de intensidad entre un píxel dado y los píxeles circundantes. 0 indica que no DEBE realizarse la nitidez. 0 < valor \\u2264 100 A medida que este valor aumenta, la diferencia de intensidad entre píxeles DEBERÍA aumentar.

Valor: La cantidad.

**Returns:**
float
### setAmount(float value) {#setAmount-float-}
```
public void setAmount(float value)
```


Obtiene o establece un número de punto flotante de 32 bits que especifica la diferencia de intensidad entre un píxel dado y los píxeles circundantes. 0 indica que no DEBE realizarse la nitidez. 0 < valor \\u2264 100 A medida que este valor aumenta, la diferencia de intensidad entre píxeles DEBERÍA aumentar.

Valor: La cantidad.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

