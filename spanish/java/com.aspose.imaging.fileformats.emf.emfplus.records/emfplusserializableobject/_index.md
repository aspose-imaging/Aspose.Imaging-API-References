---
title: "EmfPlusSerializableObject"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusSerializableObject define un bloque de parámetros de efectos de imagen que ha sido serializado en un búfer de datos."
type: docs
weight: 53
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObjectRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusobjectrecordtype)
```
public final class EmfPlusSerializableObject extends EmfPlusObjectRecordType
```

El registro EmfPlusSerializableObject define un bloque de parámetros de efectos de imagen que ha sido serializado en un búfer de datos.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusSerializableObject(EmfPlusRecord source)](#EmfPlusSerializableObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusSerializableObject`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFlags()](#getFlags--) | Obtiene o establece un entero sin signo de 16 bits que no se utiliza. |
| [setFlags(short value)](#setFlags-short-) | Obtiene o establece un entero sin signo de 16 bits que no se utiliza. |
| [getObjectGuid()](#getObjectGuid--) | Obtiene o establece el valor de representación de paquete GUID ([MS-DTYP] sección 2.3.4.2) para el efecto de imagen. |
| [setObjectGuid(GuidPacketRepresentation value)](#setObjectGuid-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-) | Obtiene o establece el valor de representación de paquete GUID ([MS-DTYP] sección 2.3.4.2) para el efecto de imagen. |
| [getBufferSize()](#getBufferSize--) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño en bytes del campo Buffer alineado a 32 bits. |
| [setBufferSize(int value)](#setBufferSize-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño en bytes del campo Buffer alineado a 32 bits. |
| [getBuffer()](#getBuffer--) | Obtiene o establece una matriz de bytes de BufferSize que contiene el bloque de parámetros de efectos de imagen serializado que corresponde al GUID en el campo ObjectGUID. |
| [setBuffer(byte[] value)](#setBuffer-byte---) | Obtiene o establece una matriz de bytes de BufferSize que contiene el bloque de parámetros de efectos de imagen serializado que corresponde al GUID en el campo ObjectGUID. |
| [getImageEffect()](#getImageEffect--) | Obtiene o establece el efecto de imagen. |
| [setImageEffect(EmfPlusImageEffectsObjectType value)](#setImageEffect-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType-) | Obtiene o establece el efecto de imagen. |
### EmfPlusSerializableObject(EmfPlusRecord source) {#EmfPlusSerializableObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSerializableObject(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusSerializableObject`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### getFlags() {#getFlags--}
```
public short getFlags()
```


Obtiene o establece un entero sin signo de 16 bits que no se usa. Este campo DEBERÍA establecerse a cero y DEBE ser ignorado al recibirlo.

Valor: Los indicadores.

**Returns:**
short
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


Obtiene o establece un entero sin signo de 16 bits que no se usa. Este campo DEBERÍA establecerse a cero y DEBE ser ignorado al recibirlo.

Valor: Los indicadores.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getObjectGuid() {#getObjectGuid--}
```
public GuidPacketRepresentation getObjectGuid()
```


Obtiene o establece el valor de representación de paquete GUID ([MS-DTYP] sección 2.3.4.2) para el efecto de imagen. Esto DEBE corresponder a uno de los identificadores ImageEffects (sección 2.1.3.1).

**Returns:**
[GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation)
### setObjectGuid(GuidPacketRepresentation value) {#setObjectGuid-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-}
```
public void setObjectGuid(GuidPacketRepresentation value)
```


Obtiene o establece el valor de representación de paquete GUID ([MS-DTYP] sección 2.3.4.2) para el efecto de imagen. Esto DEBE corresponder a uno de los identificadores ImageEffects (sección 2.1.3.1).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |

### getBufferSize() {#getBufferSize--}
```
public int getBufferSize()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño en bytes del campo Buffer alineado a 32 bits.

**Returns:**
int
### setBufferSize(int value) {#setBufferSize-int-}
```
public void setBufferSize(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño en bytes del campo Buffer alineado a 32 bits.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getBuffer() {#getBuffer--}
```
public byte[] getBuffer()
```


Obtiene o establece una matriz de bytes de BufferSize que contiene el bloque de parámetros de efectos de imagen serializado que corresponde al GUID en el campo ObjectGUID. Esto DEBE ser uno de los objetos Image Effects (sección 2.2.3).

**Returns:**
byte[]
### setBuffer(byte[] value) {#setBuffer-byte---}
```
public void setBuffer(byte[] value)
```


Obtiene o establece una matriz de bytes de BufferSize que contiene el bloque de parámetros de efectos de imagen serializado que corresponde al GUID en el campo ObjectGUID. Esto DEBE ser uno de los objetos Image Effects (sección 2.2.3).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### getImageEffect() {#getImageEffect--}
```
public EmfPlusImageEffectsObjectType getImageEffect()
```


Obtiene o establece el efecto de imagen.

Valor: El efecto de imagen.

**Returns:**
[EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
### setImageEffect(EmfPlusImageEffectsObjectType value) {#setImageEffect-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType-}
```
public void setImageEffect(EmfPlusImageEffectsObjectType value)
```


Obtiene o establece el efecto de imagen.

Valor: El efecto de imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype) |  |

