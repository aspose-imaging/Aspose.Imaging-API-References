---
title: "EmfPlusPenData"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusPenData especifica propiedades de un lápiz gráfico."
type: docs
weight: 64
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPenData extends EmfPlusStructureObjectType
```

El objeto EmfPlusPenData especifica propiedades de un lápiz gráfico.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusPenData()](#EmfPlusPenData--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPenDataFlags()](#getPenDataFlags--) | Obtiene o establece un entero sin signo de 32 bits que especifica los datos en el campo OptionalData. |
| [setPenDataFlags(int value)](#setPenDataFlags-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica los datos en el campo OptionalData. |
| [getPenUnit()](#getPenUnit--) | Obtiene o establece un entero sin signo de 32 bits que especifica las unidades de medida para la pluma. |
| [setPenUnit(int value)](#setPenUnit-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica las unidades de medida para la pluma. |
| [getPenWidth()](#getPenWidth--) | Obtiene o establece un valor de punto flotante de 32 bits que especifica el ancho de la línea dibujada por la pluma en las unidades especificadas por el campo PenUnit. |
| [setPenWidth(float value)](#setPenWidth-float-) | Obtiene o establece un valor de punto flotante de 32 bits que especifica el ancho de la línea dibujada por la pluma en las unidades especificadas por el campo PenUnit. |
| [getOptionalData()](#getOptionalData--) | Obtiene o establece un objeto opcional EmfPlusPenOptionalData (sección 2.2.2.34) que especifica datos adicionales para el objeto pluma. |
| [setOptionalData(EmfPlusPenOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenOptionalData-) | Obtiene o establece un objeto opcional EmfPlusPenOptionalData (sección 2.2.2.34) que especifica datos adicionales para el objeto pluma. |
### EmfPlusPenData() {#EmfPlusPenData--}
```
public EmfPlusPenData()
```


### getPenDataFlags() {#getPenDataFlags--}
```
public int getPenDataFlags()
```


Obtiene o establece un entero sin signo de 32 bits que especifica los datos en el campo OptionalData. Este valor DEBE estar compuesto por indicadores PenData (sección 2.1.2.7).

**Returns:**
int
### setPenDataFlags(int value) {#setPenDataFlags-int-}
```
public void setPenDataFlags(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica los datos en el campo OptionalData. Este valor DEBE estar compuesto por indicadores PenData (sección 2.1.2.7).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getPenUnit() {#getPenUnit--}
```
public int getPenUnit()
```


Obtiene o establece un entero sin signo de 32 bits que especifica las unidades de medida para la pluma. El valor DEBE provenir de la enumeración UnitType (sección 2.1.1.33).

**Returns:**
int
### setPenUnit(int value) {#setPenUnit-int-}
```
public void setPenUnit(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica las unidades de medida para la pluma. El valor DEBE provenir de la enumeración UnitType (sección 2.1.1.33).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getPenWidth() {#getPenWidth--}
```
public float getPenWidth()
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica el ancho de la línea dibujada por la pluma en las unidades especificadas por el campo PenUnit. Si se especifica un ancho cero, se utiliza un valor mínimo, que se determina por las unidades.

**Returns:**
float
### setPenWidth(float value) {#setPenWidth-float-}
```
public void setPenWidth(float value)
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica el ancho de la línea dibujada por la pluma en las unidades especificadas por el campo PenUnit. Si se especifica un ancho cero, se utiliza un valor mínimo, que se determina por las unidades.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusPenOptionalData getOptionalData()
```


Obtiene o establece un objeto opcional EmfPlusPenOptionalData (sección 2.2.2.34) que especifica datos adicionales para el objeto pluma. El contenido específico de este campo se determina por el valor del campo PenDataFlags.

**Returns:**
[EmfPlusPenOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata)
### setOptionalData(EmfPlusPenOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenOptionalData-}
```
public void setOptionalData(EmfPlusPenOptionalData value)
```


Obtiene o establece un objeto opcional EmfPlusPenOptionalData (sección 2.2.2.34) que especifica datos adicionales para el objeto pluma. El contenido específico de este campo se determina por el valor del campo PenDataFlags.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusPenOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata) |  |

