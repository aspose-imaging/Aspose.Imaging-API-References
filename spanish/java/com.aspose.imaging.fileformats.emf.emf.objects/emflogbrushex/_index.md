---
title: "EmfLogBrushEx"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto LogBrushEx define el estilo, color y patrón de un pincel independiente del dispositivo."
type: docs
weight: 21
url: /es/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfLogBrushEx extends EmfObject
```

El objeto LogBrushEx define el estilo, color y patrón de un pincel independiente del dispositivo.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfLogBrushEx()](#EmfLogBrushEx--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBrushStyle()](#getBrushStyle--) | Obtiene o establece un entero sin signo de 32 bits que especifica el estilo del pincel. |
| [setBrushStyle(int value)](#setBrushStyle-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el estilo del pincel. |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | Obtiene o establece un objeto WMF ColorRef de 32 bits ([MS-WMF] sección 2.2.2.8) que especifica un color. |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | Obtiene o establece un objeto WMF ColorRef de 32 bits ([MS-WMF] sección 2.2.2.8) que especifica un color. |
| [getBrushHatch()](#getBrushHatch--) | Obtiene o establece un campo sin signo de 32 bits que contiene los datos de trama del pincel. |
| [setBrushHatch(int value)](#setBrushHatch-int-) | Obtiene o establece un campo sin signo de 32 bits que contiene los datos de trama del pincel. |
### EmfLogBrushEx() {#EmfLogBrushEx--}
```
public EmfLogBrushEx()
```


### getBrushStyle() {#getBrushStyle--}
```
public int getBrushStyle()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el estilo del pincel. El valor DEBE ser una enumeración de la enumeración WMF BrushStyle ([MS-WMF] sección 2.1.1.4). Los valores de estilo que se admiten en esta estructura se enumeran más adelante en esta sección. El estilo BS\_NULL DEBERÍA usarse para especificar un pincel que no tiene efecto.

**Returns:**
int
### setBrushStyle(int value) {#setBrushStyle-int-}
```
public void setBrushStyle(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el estilo del pincel. El valor DEBE ser una enumeración de la enumeración WMF BrushStyle ([MS-WMF] sección 2.1.1.4). Los valores de estilo que se admiten en esta estructura se enumeran más adelante en esta sección. El estilo BS\_NULL DEBERÍA usarse para especificar un pincel que no tiene efecto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


Obtiene o establece un objeto WMF ColorRef de 32 bits ([MS-WMF] sección 2.2.2.8) que especifica un color. La interpretación de este campo depende del valor de BrushStyle, como se explica en la tabla siguiente.

Valor: El color ARGB de 32 bits

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


Obtiene o establece un objeto WMF ColorRef de 32 bits ([MS-WMF] sección 2.2.2.8) que especifica un color. La interpretación de este campo depende del valor de BrushStyle, como se explica en la tabla siguiente.

Valor: El color ARGB de 32 bits

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getBrushHatch() {#getBrushHatch--}
```
public int getBrushHatch()
```


Obtiene o establece un campo sin signo de 32 bits que contiene los datos de trama del pincel. Su interpretación depende del valor de BrushStyle,

**Returns:**
int
### setBrushHatch(int value) {#setBrushHatch-int-}
```
public void setBrushHatch(int value)
```


Obtiene o establece un campo sin signo de 32 bits que contiene los datos de trama del pincel. Su interpretación depende del valor de BrushStyle,

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

