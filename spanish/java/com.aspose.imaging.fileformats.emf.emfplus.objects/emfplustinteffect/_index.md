---
title: "EmfPlusTintEffect"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto TintEffect especifica una adición de negro o blanco a un tono especificado en una imagen."
type: docs
weight: 79
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustinteffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusTintEffect extends EmfPlusImageEffectsObjectType
```

El objeto TintEffect especifica una adición de negro o blanco a un tono especificado en una imagen.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusTintEffect()](#EmfPlusTintEffect--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getHue()](#getHue--) | Obtiene o establece un entero con signo de 32 bits que especifica el matiz al que se aplica el efecto de tono. |
| [setHue(int value)](#setHue-int-) | Obtiene o establece un entero con signo de 32 bits que especifica el matiz al que se aplica el efecto de tono. |
| [getAmount()](#getAmount--) | Obtiene o establece un entero con signo de 32 bits que especifica cuánto se refuerza o debilita el matiz. |
| [setAmount(int value)](#setAmount-int-) | Obtiene o establece un entero con signo de 32 bits que especifica cuánto se refuerza o debilita el matiz. |
### EmfPlusTintEffect() {#EmfPlusTintEffect--}
```
public EmfPlusTintEffect()
```


### getHue() {#getHue--}
```
public int getHue()
```


Obtiene o establece un entero con signo de 32 bits que especifica el matiz al que se aplica el efecto de tono. -180 \\u2264 valor < 0 El color en una rotación antihoraria especificada de la rueda de colores, comenzando desde el azul. 0 Un valor de 0 especifica el color azul en la rueda de colores. 0 < valor \\u2264 180 El color en una rotación horaria especificada de la rueda de colores, comenzando desde el azul.

**Returns:**
int
### setHue(int value) {#setHue-int-}
```
public void setHue(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica el matiz al que se aplica el efecto de tono. -180 \\u2264 valor < 0 El color en una rotación antihoraria especificada de la rueda de colores, comenzando desde el azul. 0 Un valor de 0 especifica el color azul en la rueda de colores. 0 < valor \\u2264 180 El color en una rotación horaria especificada de la rueda de colores, comenzando desde el azul.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getAmount() {#getAmount--}
```
public int getAmount()
```


Obtiene o establece un entero con signo de 32 bits que especifica cuánto se refuerza o debilita el matiz. -100 \\u2264 valor < 0 Los valores negativos especifican cuánto se debilita el matiz, lo que equivale a la adición de negro. 0 Un valor de 0 especifica que el tono NO DEBE cambiar. 0 < valor \\u2264 100 Los valores positivos especifican cuánto se refuerza el matiz, lo que equivale a la adición de blanco.

Valor: La cantidad.

**Returns:**
int
### setAmount(int value) {#setAmount-int-}
```
public void setAmount(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica cuánto se refuerza o debilita el matiz. -100 \\u2264 valor < 0 Los valores negativos especifican cuánto se debilita el matiz, lo que equivale a la adición de negro. 0 Un valor de 0 especifica que el tono NO DEBE cambiar. 0 < valor \\u2264 100 Los valores positivos especifican cuánto se refuerza el matiz, lo que equivale a la adición de blanco.

Valor: La cantidad.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

