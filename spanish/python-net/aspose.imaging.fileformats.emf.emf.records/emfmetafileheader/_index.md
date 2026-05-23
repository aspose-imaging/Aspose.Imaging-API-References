---
title: "Clase EmfMetafileHeader"
type: docs
weight: 610
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/
---

**Summary:** The EMR_HEADER record types define the starting points of EMF metafiles<br/>            and specify properties of the device on which the image in the metafile<br/>            was created. The information in the header record makes it possible for<br/>            EMF metafiles to be independent of any specific output device.<br/>            The value of the Size field can be used to distinguish between the different<br/>            EMR_HEADER record types listed earlier in this section.<br/>            There are three possible headers:<br/>            The base header, which is the EmfMetafileHeader record.<br/>            The fixed-size part of this header is 88 bytes, and it contains a Header object.<br/>            The first extension header, which is the EmfMetafileHeaderExtension1 record.<br/>            The fixed-size part of this header is 100 bytes, and it contains a Header object<br/>            and a HeaderExtension1 object (section 2.2.10).<br/>            The second extension header, which is the EmfMetafileHeaderExtension2 record.<br/>            The fixed-size part of this header is 108 bytes, and it contains a Header object,<br/>            a HeaderExtension1 object, and a HeaderExtension2 object (section 2.2.11).

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader

**Inheritance:** EmfRecord

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfMetafileHeader()](#EmfMetafileHeader__1) | Inicializa una nueva instancia de la clase [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/). |
| [EmfMetafileHeader(header)](#EmfMetafileHeader_header_2) | Inicializa una nueva instancia de la clase [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/). |
| [EmfMetafileHeader(record)](#EmfMetafileHeader_record_3) | Inicializa una nueva instancia de la clase [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| emf_description | string | r/w | Obtiene o establece la descripción EMF<br/>            Una cadena Unicode UTF16-LE opcional, terminada en nulo, de longitud y contenido arbitrarios. <br/>            Su ubicación en el registro y el número de caracteres se especifican mediante los campos offDescription <br/>            y nDescription, respectivamente, en EmfHeader. Si el valor de cualquiera de los campos <br/>            es cero, no hay cadena de descripción presente. |
| emf_description_buffer | System.Byte | r/w | Obtiene o establece el búfer de descripción EMF<br/>            Una matriz de bytes opcional que contiene la cadena de descripción EMF, la cual <br/>            no necesita ser contigua con la porción fija del registro EmfMetafileHeader. En consecuencia, el campo en este búfer que está etiquetado como "UndefinedSpace" <br/>            es opcional y DEBE ser ignorado. |
| emf_header | [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) | r/w | Obtiene o establece un objeto Header (sección 2.2.9), que contiene información sobre el contenido<br/>            y la estructura del metafile |
| emf_header_record_buffer | System.Byte | r/w | Obtiene o establece una matriz de bytes opcional que contiene el resto del registro de encabezado EMF. <br/>            El tamaño de este campo DEBE ser múltiplo de 4 bytes |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_header(header)](#create_from_header_header_1) | Inicializa una nueva instancia de la clase [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/). |
| [create_from_record(record)](#create_from_record_record_2) | Inicializa una nueva instancia de la clase [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/). |
| [create_from_type(type)](#create_from_type_type_3) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfMetafileHeader() {#EmfMetafileHeader__1}


```
 EmfMetafileHeader() 
```

Inicializa una nueva instancia de la clase [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/).

### Constructor: EmfMetafileHeader(header) {#EmfMetafileHeader_header_2}


```
 EmfMetafileHeader(header) 
```

Inicializa una nueva instancia de la clase [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| header | [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) | El encabezado. |

### Constructor: EmfMetafileHeader(record) {#EmfMetafileHeader_record_3}


```
 EmfMetafileHeader(record) 
```

Inicializa una nueva instancia de la clase [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | El registro. |

### Method: create_from_header(header)  [static] {#create_from_header_header_1}


```
 create_from_header(header) 
```

Inicializa una nueva instancia de la clase [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| header | [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) | El encabezado. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) |  |


### Method: create_from_record(record)  [static] {#create_from_record_record_2}


```
 create_from_record(record) 
```

Inicializa una nueva instancia de la clase [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | El registro. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_3}


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


