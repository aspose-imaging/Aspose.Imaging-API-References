---
title: "GuidPacketRepresentation"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La versión del paquete se usa dentro de los protocolos de bloque."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class GuidPacketRepresentation extends Struct<GuidPacketRepresentation>
```

La versión del paquete se utiliza dentro de los protocolos de bloque. El siguiente diagrama representa un GUID como una secuencia opaca de bytes. Un GUID, también conocido como UUID, es una estructura de 16 bytes, destinada a servir como identificador único de un objeto. Existen tres representaciones de un GUID, como se describe en las siguientes secciones.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [GuidPacketRepresentation()](#GuidPacketRepresentation--) |  |
| [GuidPacketRepresentation(int data1, short data2, short data3, long data4)](#GuidPacketRepresentation-int-short-short-long-) | Inicializa una nueva instancia de la estructura `GuidPacketRepresentation`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getData1()](#getData1--) | Obtiene o establece el valor del miembro Data1 (sección 2.3.4), en orden de bytes little-endian. |
| [setData1(int value)](#setData1-int-) | Obtiene o establece el valor del miembro Data1 (sección 2.3.4), en orden de bytes little-endian. |
| [getData2()](#getData2--) | Obtiene o establece el valor del miembro Data2 (sección 2.3.4), en orden de bytes little-endian. |
| [setData2(short value)](#setData2-short-) | Obtiene o establece el valor del miembro Data2 (sección 2.3.4), en orden de bytes little-endian. |
| [getData3()](#getData3--) | Obtiene o establece el valor del miembro Data3 (sección 2.3.4), en orden de bytes little-endian. |
| [setData3(short value)](#setData3-short-) | Obtiene o establece el valor del miembro Data3 (sección 2.3.4), en orden de bytes little-endian. |
| [getData4()](#getData4--) | Obtiene o establece el valor del miembro Data4 (sección 2.3.4), en orden de bytes little-endian. |
| [setData4(long value)](#setData4-long-) | Obtiene o establece el valor del miembro Data4 (sección 2.3.4), en orden de bytes little-endian. |
| [toString()](#toString--) | Devuelve una `System.String` que representa esta instancia. |
| [CloneTo(GuidPacketRepresentation that)](#CloneTo-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-) |  |
| [Clone()](#Clone--) |  |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isEquals(GuidPacketRepresentation obj1, GuidPacketRepresentation obj2)](#isEquals-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-) |  |
### GuidPacketRepresentation() {#GuidPacketRepresentation--}
```
public GuidPacketRepresentation()
```


### GuidPacketRepresentation(int data1, short data2, short data3, long data4) {#GuidPacketRepresentation-int-short-short-long-}
```
public GuidPacketRepresentation(int data1, short data2, short data3, long data4)
```


Inicializa una nueva instancia de la estructura `GuidPacketRepresentation`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data1 | int | El data1. |
| data2 | short | El data2. |
| data3 | short | El data3. |
| data4 | long | El data4. |

### getData1() {#getData1--}
```
public int getData1()
```


Obtiene o establece el valor del miembro Data1 (sección 2.3.4), en orden de bytes little-endian.

Valor: El data1.

**Returns:**
int
### setData1(int value) {#setData1-int-}
```
public void setData1(int value)
```


Obtiene o establece el valor del miembro Data1 (sección 2.3.4), en orden de bytes little-endian.

Valor: El data1.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getData2() {#getData2--}
```
public short getData2()
```


Obtiene o establece el valor del miembro Data2 (sección 2.3.4), en orden de bytes little-endian.

Valor: Los datos2.

**Returns:**
short
### setData2(short value) {#setData2-short-}
```
public void setData2(short value)
```


Obtiene o establece el valor del miembro Data2 (sección 2.3.4), en orden de bytes little-endian.

Valor: Los datos2.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getData3() {#getData3--}
```
public short getData3()
```


Obtiene o establece el valor del miembro Data3 (sección 2.3.4), en orden de bytes little-endian.

Valor: Los datos3.

**Returns:**
short
### setData3(short value) {#setData3-short-}
```
public void setData3(short value)
```


Obtiene o establece el valor del miembro Data3 (sección 2.3.4), en orden de bytes little-endian.

Valor: Los datos3.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getData4() {#getData4--}
```
public long getData4()
```


Obtiene o establece el valor del miembro Data4 (sección 2.3.4), en orden de bytes little-endian.

Valor: Los datos4.

**Returns:**
long
### setData4(long value) {#setData4-long-}
```
public void setData4(long value)
```


Obtiene o establece el valor del miembro Data4 (sección 2.3.4), en orden de bytes little-endian.

Valor: Los datos4.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### toString() {#toString--}
```
public String toString()
```


Devuelve una `System.String` que representa esta instancia.

**Returns:**
java.lang.String - Un `System.String` que representa esta instancia.
### CloneTo(GuidPacketRepresentation that) {#CloneTo-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-}
```
public void CloneTo(GuidPacketRepresentation that)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| that | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |

### Clone() {#Clone--}
```
public GuidPacketRepresentation Clone()
```




**Returns:**
[GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation)
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
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
### isEquals(GuidPacketRepresentation obj1, GuidPacketRepresentation obj2) {#isEquals-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-}
```
public static boolean isEquals(GuidPacketRepresentation obj1, GuidPacketRepresentation obj2)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj1 | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |
| obj2 | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |

**Returns:**
boolean
