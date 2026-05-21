---
title: "EmfColorAdjustment"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto ColorAdjustment define valores para ajustar los colores en los mapas de bits de origen en transferencias de bloques de bits."
type: docs
weight: 12
url: /es/java/com.aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfColorAdjustment extends EmfObject
```

El objeto ColorAdjustment define valores para ajustar los colores en los mapas de bits de origen en transferencias de bloques de bits.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfColorAdjustment()](#EmfColorAdjustment--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getSize()](#getSize--) | Obtiene o establece un entero sin signo de 16 bits que especifica el tamaño en bytes de este objeto. |
| [setSize(short value)](#setSize-short-) | Obtiene o establece un entero sin signo de 16 bits que especifica el tamaño en bytes de este objeto. |
| [getValues()](#getValues--) | Obtiene o establece un entero sin signo de 16 bits que especifica cómo preparar la imagen de salida. |
| [setValues(int value)](#setValues-int-) | Obtiene o establece un entero sin signo de 16 bits que especifica cómo preparar la imagen de salida. |
| [getIlluminantIndex()](#getIlluminantIndex--) | Obtiene o establece un entero sin signo de 16 bits que especifica el tipo de fuente de luz estándar bajo la cual se visualiza la imagen, a partir de la enumeración Illuminant (sección 2.1.19). |
| [setIlluminantIndex(int value)](#setIlluminantIndex-int-) | Obtiene o establece un entero sin signo de 16 bits que especifica el tipo de fuente de luz estándar bajo la cual se visualiza la imagen, a partir de la enumeración Illuminant (sección 2.1.19). |
| [getRedGamma()](#getRedGamma--) | Obtiene o establece un entero sin signo de 16 bits que especifica el valor de corrección gamma de n-ésima potencia para la primaria roja de los colores de origen. |
| [setRedGamma(short value)](#setRedGamma-short-) | Obtiene o establece un entero sin signo de 16 bits que especifica el valor de corrección gamma de n-ésima potencia para la primaria roja de los colores de origen. |
| [getGreenGamma()](#getGreenGamma--) | Obtiene o establece un entero sin signo de 16 bits que especifica el valor de corrección gamma de n-ésima potencia para la primaria verde de los colores de origen. |
| [setGreenGamma(short value)](#setGreenGamma-short-) | Obtiene o establece un entero sin signo de 16 bits que especifica el valor de corrección gamma de n-ésima potencia para la primaria verde de los colores de origen. |
| [getBlueGamma()](#getBlueGamma--) | Obtiene o establece un entero sin signo de 16 bits que especifica el valor de corrección gamma de n-ésima potencia para la primaria azul de los colores de origen. |
| [setBlueGamma(short value)](#setBlueGamma-short-) | Obtiene o establece un entero sin signo de 16 bits que especifica el valor de corrección gamma de n-ésima potencia para la primaria azul de los colores de origen. |
| [getReferenceBlack()](#getReferenceBlack--) | Obtiene o establece un entero sin signo de 16 bits que especifica la referencia negra para los colores de origen. |
| [setReferenceBlack(short value)](#setReferenceBlack-short-) | Obtiene o establece un entero sin signo de 16 bits que especifica la referencia negra para los colores de origen. |
| [getReferenceWhite()](#getReferenceWhite--) | Obtiene o establece un entero sin signo de 16 bits que especifica la referencia blanca para los colores de origen. |
| [setReferenceWhite(short value)](#setReferenceWhite-short-) | Obtiene o establece un entero sin signo de 16 bits que especifica la referencia blanca para los colores de origen. |
| [getContrast()](#getContrast--) | Obtiene o establece un entero con signo de 16 bits que especifica la cantidad de contraste que se aplicará al objeto de origen. |
| [setContrast(short value)](#setContrast-short-) | Obtiene o establece un entero con signo de 16 bits que especifica la cantidad de contraste que se aplicará al objeto de origen. |
| [getBrightness()](#getBrightness--) | Obtiene o establece un entero con signo de 16 bits que especifica la cantidad de brillo que se aplicará al objeto de origen. |
| [setBrightness(short value)](#setBrightness-short-) | Obtiene o establece un entero con signo de 16 bits que especifica la cantidad de brillo que se aplicará al objeto de origen. |
| [getColorfullness()](#getColorfullness--) | Obtiene o establece un entero con signo de 16 bits que especifica la cantidad de color que se aplicará al objeto de origen. |
| [setColorfullness(short value)](#setColorfullness-short-) | Obtiene o establece un entero con signo de 16 bits que especifica la cantidad de color que se aplicará al objeto de origen. |
| [getRedGreenTint()](#getRedGreenTint--) | Obtiene o establece un entero con signo de 16 bits que especifica la cantidad de ajuste de tono rojo o verde que se aplicará al objeto de origen. |
| [setRedGreenTint(short value)](#setRedGreenTint-short-) | Obtiene o establece un entero con signo de 16 bits que especifica la cantidad de ajuste de tono rojo o verde que se aplicará al objeto de origen. |
### EmfColorAdjustment() {#EmfColorAdjustment--}
```
public EmfColorAdjustment()
```


### getSize() {#getSize--}
```
public short getSize()
```


Obtiene o establece un entero sin signo de 16 bits que especifica el tamaño en bytes de este objeto. Este DEBE ser 0x0018.

**Returns:**
short
### setSize(short value) {#setSize-short-}
```
public void setSize(short value)
```


Obtiene o establece un entero sin signo de 16 bits que especifica el tamaño en bytes de este objeto. Este DEBE ser 0x0018.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getValues() {#getValues--}
```
public int getValues()
```


Obtiene o establece un entero sin signo de 16 bits que especifica cómo preparar la imagen de salida. Este campo puede establecerse en NULL o en cualquier combinación de valores de la enumeración ColorAdjustment (sección 2.1.5).

**Returns:**
int
### setValues(int value) {#setValues-int-}
```
public void setValues(int value)
```


Obtiene o establece un entero sin signo de 16 bits que especifica cómo preparar la imagen de salida. Este campo puede establecerse en NULL o en cualquier combinación de valores de la enumeración ColorAdjustment (sección 2.1.5).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getIlluminantIndex() {#getIlluminantIndex--}
```
public int getIlluminantIndex()
```


Obtiene o establece un entero sin signo de 16 bits que especifica el tipo de fuente de luz estándar bajo la cual se visualiza la imagen, a partir de la enumeración Illuminant (sección 2.1.19).

**Returns:**
int
### setIlluminantIndex(int value) {#setIlluminantIndex-int-}
```
public void setIlluminantIndex(int value)
```


Obtiene o establece un entero sin signo de 16 bits que especifica el tipo de fuente de luz estándar bajo la cual se visualiza la imagen, a partir de la enumeración Illuminant (sección 2.1.19).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getRedGamma() {#getRedGamma--}
```
public short getRedGamma()
```


Obtiene o establece un entero sin signo de 16 bits que especifica el valor de corrección gamma de n-ésima potencia para la primaria roja de los colores de origen. Este valor DEBERÍA estar en el rango de 2,500 a 65,000. Un valor de 10,000 significa que NO SE DEBE realizar la corrección gamma.

**Returns:**
short
### setRedGamma(short value) {#setRedGamma-short-}
```
public void setRedGamma(short value)
```


Obtiene o establece un entero sin signo de 16 bits que especifica el valor de corrección gamma de n-ésima potencia para la primaria roja de los colores de origen. Este valor DEBERÍA estar en el rango de 2,500 a 65,000. Un valor de 10,000 significa que NO SE DEBE realizar la corrección gamma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getGreenGamma() {#getGreenGamma--}
```
public short getGreenGamma()
```


Obtiene o establece un entero sin signo de 16 bits que especifica el valor de corrección gamma de n-ésima potencia para la primaria verde de los colores de origen. Este valor DEBERÍA estar en el rango de 2,500 a 65,000. Un valor de 10,000 significa que NO SE DEBE realizar la corrección gamma.

**Returns:**
short
### setGreenGamma(short value) {#setGreenGamma-short-}
```
public void setGreenGamma(short value)
```


Obtiene o establece un entero sin signo de 16 bits que especifica el valor de corrección gamma de n-ésima potencia para la primaria verde de los colores de origen. Este valor DEBERÍA estar en el rango de 2,500 a 65,000. Un valor de 10,000 significa que NO SE DEBE realizar la corrección gamma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getBlueGamma() {#getBlueGamma--}
```
public short getBlueGamma()
```


Obtiene o establece un entero sin signo de 16 bits que especifica el valor de corrección gamma de n-ésima potencia para la primaria azul de los colores de origen. Este valor DEBERÍA estar en el rango de 2,500 a 65,000. Un valor de 10,000 significa que NO SE DEBE realizar la corrección gamma.

**Returns:**
short
### setBlueGamma(short value) {#setBlueGamma-short-}
```
public void setBlueGamma(short value)
```


Obtiene o establece un entero sin signo de 16 bits que especifica el valor de corrección gamma de n-ésima potencia para la primaria azul de los colores de origen. Este valor DEBERÍA estar en el rango de 2,500 a 65,000. Un valor de 10,000 significa que NO SE DEBE realizar la corrección gamma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getReferenceBlack() {#getReferenceBlack--}
```
public short getReferenceBlack()
```


Obtiene o establece un entero sin signo de 16 bits que especifica la referencia de negro para los colores de origen. Cualquier color más oscuro que esto se trata como negro. Este valor DEBERÍA estar en el rango de cero a 4,000.

**Returns:**
short
### setReferenceBlack(short value) {#setReferenceBlack-short-}
```
public void setReferenceBlack(short value)
```


Obtiene o establece un entero sin signo de 16 bits que especifica la referencia de negro para los colores de origen. Cualquier color más oscuro que esto se trata como negro. Este valor DEBERÍA estar en el rango de cero a 4,000.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getReferenceWhite() {#getReferenceWhite--}
```
public short getReferenceWhite()
```


Obtiene o establece un entero sin signo de 16 bits que especifica la referencia de blanco para los colores de origen. Cualquier color más claro que esto se trata como blanco. Este valor DEBERÍA estar en el rango de 6,000 a 10,000.

**Returns:**
short
### setReferenceWhite(short value) {#setReferenceWhite-short-}
```
public void setReferenceWhite(short value)
```


Obtiene o establece un entero sin signo de 16 bits que especifica la referencia de blanco para los colores de origen. Cualquier color más claro que esto se trata como blanco. Este valor DEBERÍA estar en el rango de 6,000 a 10,000.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getContrast() {#getContrast--}
```
public short getContrast()
```


Obtiene o establece un entero con signo de 16 bits que especifica la cantidad de contraste que se aplicará al objeto de origen. Este valor DEBERÍA estar en el rango de \\u2013100 a 100. Un valor de cero significa que NO SE DEBE realizar el ajuste de contraste.

**Returns:**
short
### setContrast(short value) {#setContrast-short-}
```
public void setContrast(short value)
```


Obtiene o establece un entero con signo de 16 bits que especifica la cantidad de contraste que se aplicará al objeto de origen. Este valor DEBERÍA estar en el rango de \\u2013100 a 100. Un valor de cero significa que NO SE DEBE realizar el ajuste de contraste.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getBrightness() {#getBrightness--}
```
public short getBrightness()
```


Obtiene o establece un entero con signo de 16 bits que especifica la cantidad de brillo que se aplicará al objeto de origen. Este valor DEBERÍA estar en el rango de \\u2013100 a 100. Un valor de cero significa que NO SE DEBE realizar el ajuste de brillo.

**Returns:**
short
### setBrightness(short value) {#setBrightness-short-}
```
public void setBrightness(short value)
```


Obtiene o establece un entero con signo de 16 bits que especifica la cantidad de brillo que se aplicará al objeto de origen. Este valor DEBERÍA estar en el rango de \\u2013100 a 100. Un valor de cero significa que NO SE DEBE realizar el ajuste de brillo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getColorfullness() {#getColorfullness--}
```
public short getColorfullness()
```


Obtiene o establece un entero con signo de 16 bits que especifica la cantidad de color que se aplicará al objeto de origen. Este valor DEBERÍA estar en el rango de \\u2013100 a 100. Un valor de cero significa que NO SE DEBE realizar el ajuste de color.

**Returns:**
short
### setColorfullness(short value) {#setColorfullness-short-}
```
public void setColorfullness(short value)
```


Obtiene o establece un entero con signo de 16 bits que especifica la cantidad de color que se aplicará al objeto de origen. Este valor DEBERÍA estar en el rango de \\u2013100 a 100. Un valor de cero significa que NO SE DEBE realizar el ajuste de color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getRedGreenTint() {#getRedGreenTint--}
```
public short getRedGreenTint()
```


Obtiene o establece un entero con signo de 16 bits que especifica la cantidad de ajuste de tono rojo o verde que se aplicará al objeto de origen. Este valor DEBERÍA estar en el rango de \\u2013100 a 100. Los números positivos ajustan hacia el rojo y los números negativos ajustan hacia el verde. Un valor de cero significa que NO SE DEBE realizar el ajuste de tono.

**Returns:**
short
### setRedGreenTint(short value) {#setRedGreenTint-short-}
```
public void setRedGreenTint(short value)
```


Obtiene o establece un entero con signo de 16 bits que especifica la cantidad de ajuste de tono rojo o verde que se aplicará al objeto de origen. Este valor DEBERÍA estar en el rango de \\u2013100 a 100. Los números positivos ajustan hacia el rojo y los números negativos ajustan hacia el verde. Un valor de cero significa que NO SE DEBE realizar el ajuste de tono.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

