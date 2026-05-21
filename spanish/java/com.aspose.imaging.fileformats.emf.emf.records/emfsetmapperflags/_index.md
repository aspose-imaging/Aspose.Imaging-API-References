---
title: "EmfSetMapperFlags"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_SETMAPPERFLAGS especifica los parámetros del proceso de emparejamiento de fuentes lógicas con fuentes físicas que realiza el asignador de fuentes."
type: docs
weight: 131
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetmapperflags/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetMapperFlags extends EmfStateRecordType
```

El registro EMR\_SETMAPPERFLAGS especifica los parámetros del proceso de emparejamiento de fuentes lógicas con fuentes físicas, que es realizado por el asignador de fuentes.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfSetMapperFlags(EmfRecord source)](#EmfSetMapperFlags-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfSetMapperFlags`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFlags()](#getFlags--) | Obtiene o establece un entero sin signo de 32 bits que especifica los parámetros del proceso de emparejamiento de fuentes. |
| [setFlags(int value)](#setFlags-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica los parámetros del proceso de emparejamiento de fuentes. |
### EmfSetMapperFlags(EmfRecord source) {#EmfSetMapperFlags-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetMapperFlags(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfSetMapperFlags`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### getFlags() {#getFlags--}
```
public int getFlags()
```


Obtiene o establece un entero sin signo de 32 bits que especifica los parámetros del proceso de emparejamiento de fuentes.

0x00000001 El asignador de fuentes DEBERÍA seleccionar solo fuentes que coincidan con la relación de aspecto del dispositivo de salida, tal como está definido actualmente en el contexto del dispositivo de reproducción.

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica los parámetros del proceso de emparejamiento de fuentes.

0x00000001 El asignador de fuentes DEBERÍA seleccionar solo fuentes que coincidan con la relación de aspecto del dispositivo de salida, tal como está definido actualmente en el contexto del dispositivo de reproducción.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

