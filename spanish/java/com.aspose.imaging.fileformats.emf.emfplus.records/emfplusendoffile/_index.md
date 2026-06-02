---
title: "EmfPlusEndOfFile"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusEndOfFile especifica el final de los datos EMF en el metafichero."
type: docs
weight: 31
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusendoffile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusControlRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluscontrolrecordtype)
```
public final class EmfPlusEndOfFile extends EmfPlusControlRecordType
```

El registro EmfPlusEndOfFile especifica el final de los datos EMF+ en el metafichero.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusEndOfFile(EmfPlusRecord source)](#EmfPlusEndOfFile-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusEndOfFile`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFlags()](#getFlags--) | Obtiene o establece un entero sin signo de 16 bits que no se utiliza. |
| [setFlags(short value)](#setFlags-short-) | Obtiene o establece un entero sin signo de 16 bits que no se utiliza. |
### EmfPlusEndOfFile(EmfPlusRecord source) {#EmfPlusEndOfFile-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusEndOfFile(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusEndOfFile`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### getFlags() {#getFlags--}
```
public short getFlags()
```


Obtiene o establece un entero sin signo de 16 bits que no se utiliza. Este campo DEBERÍA establecerse en cero y DEBE ser ignorado al recibirlo.

**Returns:**
short
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


Obtiene o establece un entero sin signo de 16 bits que no se utiliza. Este campo DEBERÍA establecerse en cero y DEBE ser ignorado al recibirlo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

