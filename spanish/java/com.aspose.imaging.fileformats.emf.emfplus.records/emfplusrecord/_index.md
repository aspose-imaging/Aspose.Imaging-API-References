---
title: "EmfPlusRecord"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El tipo de registro base Emf."
type: docs
weight: 46
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.emf.IRecord
```
public class EmfPlusRecord extends MetaObject implements IRecord
```

El tipo de registro base Emf+.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusRecord()](#EmfPlusRecord--) | Inicializa una nueva instancia de la clase `EmfPlusRecord`. |
| [EmfPlusRecord(EmfPlusRecord source)](#EmfPlusRecord-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusRecord`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getType()](#getType--) | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |
| [getFlags()](#getFlags--) | Obtiene un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo se debe realizar la operación y sobre la estructura del registro. |
| [setFlags(short value)](#setFlags-short-) | Establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo se debe realizar la operación y sobre la estructura del registro. |
| [getSize()](#getSize--) | Obtiene un entero sin signo de 32 bits que especifica el número de bytes alineado a 32 bits del registro completo, incluidos el encabezado de registro de 12 bytes y los datos específicos del registro. |
| [setSize(int value)](#setSize-int-) | Establece un entero sin signo de 32 bits que especifica el número de bytes alineado a 32 bits del registro completo, incluidos el encabezado de registro de 12 bytes y los datos específicos del registro. |
| [getDataSize()](#getDataSize--) | Obtiene un entero sin signo de 32 bits que DEBE definir el número de bytes de datos 32-bit\\u2013aligned en el campo RecordData que sigue. |
| [setDataSize(int value)](#setDataSize-int-) | Establece un entero sin signo de 32 bits que DEBE definir el número de bytes de datos 32-bit\\u2013aligned en el campo RecordData que sigue. |
### EmfPlusRecord() {#EmfPlusRecord--}
```
public EmfPlusRecord()
```


Inicializa una nueva instancia de la clase `EmfPlusRecord`.

### EmfPlusRecord(EmfPlusRecord source) {#EmfPlusRecord-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRecord(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusRecord`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### getType() {#getType--}
```
public short getType()
```


Obtiene un entero sin signo de 16 bits que identifica el tipo de registro.

**Returns:**
short
### getFlags() {#getFlags--}
```
public short getFlags()
```


Obtiene un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo se debe realizar la operación y sobre la estructura del registro.

**Returns:**
short - Las banderas.
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


Establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo se debe realizar la operación y sobre la estructura del registro.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short | Los indicadores. |

### getSize() {#getSize--}
```
public int getSize()
```


Obtiene un entero sin signo de 32 bits que especifica el número de bytes alineado a 32 bits del registro completo, incluidos el encabezado de registro de 12 bytes y los datos específicos del registro.

**Returns:**
int - El tamaño.
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Establece un entero sin signo de 32 bits que especifica el número de bytes alineado a 32 bits del registro completo, incluidos el encabezado de registro de 12 bytes y los datos específicos del registro.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El tamaño. |

### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Obtiene un entero sin signo de 32 bits que DEBE definir el número de bytes de datos 32-bit\u2013aligned en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes.

**Returns:**
int - El tamaño de los datos.
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


Establece un entero sin signo de 32 bits que DEBE definir el número de bytes de datos 32-bit\u2013aligned en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El tamaño de los datos. |

