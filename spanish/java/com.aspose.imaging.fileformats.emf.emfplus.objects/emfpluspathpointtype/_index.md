---
title: "EmfPlusPathPointType"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusPathPointType especifica un valor de tipo asociado a un punto en un gráfico."
type: docs
weight: 61
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype)
```
public final class EmfPlusPathPointType extends EmfPlusBasePointType
```

El objeto EmfPlusPathPointType especifica un valor de tipo asociado a un punto en un gráfico.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusPathPointType()](#EmfPlusPathPointType--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getData()](#getData--) | Obtiene o establece los datos. |
| [setData(int value)](#setData-int-) | Obtiene o establece los datos. |
| [getType()](#getType--) | Obtiene o establece el tipo de punto de ruta, un entero sin signo de 4 bits. |
| [setType(int value)](#setType-int-) | Obtiene o establece el tipo de punto de ruta, un entero sin signo de 4 bits. |
| [getFlags()](#getFlags--) | Obtiene o establece un campo de bandera de 4 bits que especifica las propiedades del punto de ruta. |
| [setFlags(int value)](#setFlags-int-) | Obtiene o establece un campo de bandera de 4 bits que especifica las propiedades del punto de ruta. |
### EmfPlusPathPointType() {#EmfPlusPathPointType--}
```
public EmfPlusPathPointType()
```


### getData() {#getData--}
```
public int getData()
```


Obtiene o establece los datos.

Valor: Los datos.

**Returns:**
int
### setData(int value) {#setData-int-}
```
public void setData(int value)
```


Obtiene o establece los datos.

Valor: Los datos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getType() {#getType--}
```
public int getType()
```


Obtiene o establece el tipo de punto de ruta, un entero sin signo de 4 bits. Este valor DEBE estar definido en la enumeración PathPointType (sección 2.1.1.23).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Obtiene o establece el tipo de punto de ruta, un entero sin signo de 4 bits. Este valor DEBE estar definido en la enumeración PathPointType (sección 2.1.1.23).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getFlags() {#getFlags--}
```
public int getFlags()
```


Obtiene o establece un campo de bandera de 4 bits que especifica las propiedades del punto de ruta. Este valor DEBE ser una o más de las banderas PathPointType (sección 2.1.2.6).

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Obtiene o establece un campo de bandera de 4 bits que especifica las propiedades del punto de ruta. Este valor DEBE ser una o más de las banderas PathPointType (sección 2.1.2.6).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

