---
title: "EmfPlusGetDc"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusGetDC especifica que los registros EMF subsecuentes encontrados en el metafichero DEBERÍAN ser procesados."
type: docs
weight: 39
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusgetdc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusControlRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluscontrolrecordtype)
```
public final class EmfPlusGetDc extends EmfPlusControlRecordType
```

El registro EmfPlusGetDC especifica que los registros EMF subsecuentes encontrados en el metafichero DEBERÍAN ser procesados.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusGetDc(EmfPlusRecord source)](#EmfPlusGetDc-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusGetDc`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFlags()](#getFlags--) | Obtiene o establece un entero sin signo de 16 bits que no se utiliza. |
| [setFlags(short value)](#setFlags-short-) | Obtiene o establece un entero sin signo de 16 bits que no se utiliza. |
### EmfPlusGetDc(EmfPlusRecord source) {#EmfPlusGetDc-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusGetDc(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusGetDc`.

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

