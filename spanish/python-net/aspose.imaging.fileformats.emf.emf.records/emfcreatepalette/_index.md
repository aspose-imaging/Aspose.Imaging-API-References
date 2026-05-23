---
title: "Clase EmfCreatePalette"
type: docs
weight: 310
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/
---

**Summary:** The EMR_CREATEPALETTE record defines a logical palette for graphics operations.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreatePalette

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfCreatePalette(source)](#EmfCreatePalette_source_1) | Inicializa una nueva instancia de la clase [EmfCreatePalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| ih_pal | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto de paleta lógica<br/>            en la tabla de objetos EMF (sección 3.1.1.1). Este índice DEBE guardarse para que este objeto pueda ser<br/>            reutilizado o modificado. |
| log_palette | [EmfLogPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogpalette/) | r/w | Obtiene o establece un objeto LogPalette (sección 2.2.17). El campo Version de este objeto<br/>            DEBE establecerse en 0x0300. Si el valor NumberOfEntries en este objeto es cero, el procesamiento de<br/>            este registro DEBE fallar. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCreatePalette(source) {#EmfCreatePalette_source_1}


```
 EmfCreatePalette(source) 
```

Inicializa una nueva instancia de la clase [EmfCreatePalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | La fuente. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | La fuente. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | El tipo de registro. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


