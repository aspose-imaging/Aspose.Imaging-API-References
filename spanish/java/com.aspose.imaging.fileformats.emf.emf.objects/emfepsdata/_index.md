---
title: "EmfEpsData"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EpsData es un contenedor para datos EPS"
type: docs
weight: 14
url: /es/java/com.aspose.imaging.fileformats.emf.emf.objects/emfepsdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfEpsData extends EmfObject
```

El objeto EpsData es un contenedor para datos EPS
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfEpsData()](#EmfEpsData--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getSizeData()](#getSizeData--) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño total de este objeto, en bytes |
| [setSizeData(int value)](#setSizeData-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño total de este objeto, en bytes |
| [getVersion()](#getVersion--) | Obtiene o establece un entero sin signo de 32 bits que especifica el nivel del lenguaje PostScript. |
| [setVersion(int value)](#setVersion-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el nivel del lenguaje PostScript. |
| [getPoints()](#getPoints--) | Obtiene o establece una matriz de tres objetos Point28\_4 (sección 2.2.23) que define las coordenadas del paralelogramo de salida usando notación FIX de 28.4 bits |
| [setPoints(EmfPoint28To4[] value)](#setPoints-com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4---) | Obtiene o establece una matriz de tres objetos Point28\_4 (sección 2.2.23) que define las coordenadas del paralelogramo de salida usando notación FIX de 28.4 bits |
| [getPostScriptData()](#getPostScriptData--) | Obtiene o establece una matriz de bytes de datos PostScript. |
| [setPostScriptData(byte[] value)](#setPostScriptData-byte---) | Obtiene o establece una matriz de bytes de datos PostScript. |
### EmfEpsData() {#EmfEpsData--}
```
public EmfEpsData()
```


### getSizeData() {#getSizeData--}
```
public int getSizeData()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño total de este objeto, en bytes

**Returns:**
int
### setSizeData(int value) {#setSizeData-int-}
```
public void setSizeData(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño total de este objeto, en bytes

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el nivel del lenguaje PostScript. Este valor DEBE ser 0x00000001

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el nivel del lenguaje PostScript. Este valor DEBE ser 0x00000001

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getPoints() {#getPoints--}
```
public EmfPoint28To4[] getPoints()
```


Obtiene o establece una matriz de tres objetos Point28\_4 (sección 2.2.23) que define las coordenadas del paralelogramo de salida usando notación FIX de 28.4 bits

La esquina superior izquierda del paralelogramo es el primer punto de esta matriz, la esquina superior derecha es el segundo punto y la esquina inferior izquierda es el tercer punto. La esquina inferior derecha del paralelogramo se calcula a partir de los tres primeros puntos (A, B y C) tratándolos como vectores.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4[]
### setPoints(EmfPoint28To4[] value) {#setPoints-com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4---}
```
public void setPoints(EmfPoint28To4[] value)
```


Obtiene o establece una matriz de tres objetos Point28\_4 (sección 2.2.23) que define las coordenadas del paralelogramo de salida usando notación FIX de 28.4 bits

La esquina superior izquierda del paralelogramo es el primer punto de esta matriz, la esquina superior derecha es el segundo punto y la esquina inferior izquierda es el tercer punto. La esquina inferior derecha del paralelogramo se calcula a partir de los tres primeros puntos (A, B y C) tratándolos como vectores.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPoint28To4\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpoint28to4) |  |

### getPostScriptData() {#getPostScriptData--}
```
public byte[] getPostScriptData()
```


Obtiene o establece una matriz de bytes de datos PostScript. La longitud de esta matriz puede calcularse a partir del campo SizeData. Estos datos PUEDEN ser utilizados para renderizar una imagen.

**Returns:**
byte[]
### setPostScriptData(byte[] value) {#setPostScriptData-byte---}
```
public void setPostScriptData(byte[] value)
```


Obtiene o establece una matriz de bytes de datos PostScript. La longitud de esta matriz puede calcularse a partir del campo SizeData. Estos datos PUEDEN ser utilizados para renderizar una imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

