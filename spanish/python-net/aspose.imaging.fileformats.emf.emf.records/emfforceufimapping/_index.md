---
title: "Clase EmfForceUfiMapping"
type: docs
weight: 520
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfforceufimapping/
---

**Summary:** The EMR_FORCEUFIMAPPING record forces the font mapper to match fonts based on their<br/>            UniversalFontId in preference to their LogFont (section 2.2.13) information.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfForceUfiMapping

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfForceUfiMapping(source)](#EmfForceUfiMapping_source_1) | Inicializa una nueva instancia de la clase [EmfForceUfiMapping](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfforceufimapping/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
| ufi | [EmfUniversalFontId](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/) | r/w | Obtiene o establece el id de fuente a usar, especificado como UniversalFontId (sección 2.2.27). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfForceUfiMapping(source) {#EmfForceUfiMapping_source_1}


```
 EmfForceUfiMapping(source) 
```

Inicializa una nueva instancia de la clase [EmfForceUfiMapping](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfforceufimapping/).

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


