---
title: "EmfGlsBoundedRecord Clase"
type: docs
weight: 540
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/
---

**Summary:** The EMR_GLSBOUNDEDRECORD record specifies an OpenGL function with a bounding rectangle for output.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfGlsBoundedRecord

**Inheritance:** EmfOpenGlRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfGlsBoundedRecord(source)](#EmfGlsBoundedRecord_source_1) | Inicializa una nueva instancia de la [EmfGlsBoundedRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/) clase. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que define un rectángulo delimitador<br/>            en unidades del dispositivo, para la salida producida al ejecutar la función OpenGL. |
| cb_data | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño, en bytes, del campo Data.<br/>            Si este valor es cero, no se adjuntan datos a este registro. |
| datos | System.Byte | r/w | Obtiene o establece una matriz opcional de bytes de longitud cbData que especifica los datos para la función OpenGL. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfGlsBoundedRecord(source) {#EmfGlsBoundedRecord_source_1}


```
 EmfGlsBoundedRecord(source) 
```

Inicializa una nueva instancia de la [EmfGlsBoundedRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/) clase.

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


