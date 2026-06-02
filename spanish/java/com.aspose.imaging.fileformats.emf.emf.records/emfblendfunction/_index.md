---
title: "EmfBlendFunction"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Una estructura que especifica las operaciones de mezcla para los mapas de bits fuente y destino."
type: docs
weight: 18
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class EmfBlendFunction extends Struct<EmfBlendFunction>
```

Una estructura que especifica las operaciones de mezcla para los mapas de bits fuente y destino.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfBlendFunction()](#EmfBlendFunction--) |  |
| [EmfBlendFunction(int dwordData)](#EmfBlendFunction-int-) | Inicializa una nueva instancia de la clase `EmfBlendFunction`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBlendOperation()](#getBlendOperation--) | Obtiene el código de operación de mezcla. |
| [getBlendFlags()](#getBlendFlags--) | Obtiene los indicadores de mezcla. |
| [getSrcConstantAlpha()](#getSrcConstantAlpha--) | Obtiene un entero sin signo de 8 bits que especifica la transparencia alfa, la cual determina la mezcla de los mapas de bits de origen y destino. |
| [getAlphaFormat()](#getAlphaFormat--) | Obtiene una estructura que especifica cómo se interpretan los píxeles de origen y destino con respecto a la transparencia alfa. |
| [toInt()](#toInt--) | Convierte la representación en cadena de un número a un entero. |
| [CloneTo(EmfBlendFunction that)](#CloneTo-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-) |  |
| [Clone()](#Clone--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
| [isEquals(EmfBlendFunction obj1, EmfBlendFunction obj2)](#isEquals-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-) |  |
### EmfBlendFunction() {#EmfBlendFunction--}
```
public EmfBlendFunction()
```


### EmfBlendFunction(int dwordData) {#EmfBlendFunction-int-}
```
public EmfBlendFunction(int dwordData)
```


Inicializa una nueva instancia de la clase `EmfBlendFunction`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dwordData | int | Los datos dword. |

### getBlendOperation() {#getBlendOperation--}
```
public byte getBlendOperation()
```


Obtiene el código de operación de mezcla. La única operación de mezcla de origen y destino que se ha definido es 0x00, la cual especifica que el mapa de bits de origen DEBE combinarse con el mapa de bits de destino basándose en los valores de transparencia alfa de los píxeles de origen. Consulte las siguientes ecuaciones para obtener detalles.

**Returns:**
byte
### getBlendFlags() {#getBlendFlags--}
```
public byte getBlendFlags()
```


Obtiene los indicadores de mezcla. Este valor DEBE ser 0x00 y DEBE ser ignorado.

**Returns:**
byte
### getSrcConstantAlpha() {#getSrcConstantAlpha--}
```
public byte getSrcConstantAlpha()
```


Obtiene un entero sin signo de 8 bits que especifica la transparencia alfa, la cual determina la mezcla de los mapas de bits de origen y destino. Este valor DEBE usarse en todo el mapa de bits de origen. El valor mínimo de transparencia alfa, cero, corresponde a completamente transparente; el valor máximo, 0xFF, corresponde a completamente opaco. En efecto, un valor de 0xFF especifica que los valores alfa por píxel determinan la mezcla de los mapas de bits de origen y destino. Consulte las ecuaciones más adelante en esta sección para obtener detalles.

**Returns:**
byte
### getAlphaFormat() {#getAlphaFormat--}
```
public byte getAlphaFormat()
```


Obtiene una estructura que especifica cómo se interpretan los píxeles de origen y destino con respecto a la transparencia alfa.

**Returns:**
byte
### toInt() {#toInt--}
```
public int toInt()
```


Convierte la representación en cadena de un número a un entero.

**Returns:**
int - El valor DWORD de la estructura.
### CloneTo(EmfBlendFunction that) {#CloneTo-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-}
```
public void CloneTo(EmfBlendFunction that)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| that | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |

### Clone() {#Clone--}
```
public EmfBlendFunction Clone()
```




**Returns:**
[EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isEquals(EmfBlendFunction obj1, EmfBlendFunction obj2) {#isEquals-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-}
```
public static boolean isEquals(EmfBlendFunction obj1, EmfBlendFunction obj2)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj1 | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |
| obj2 | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |

**Returns:**
boolean
