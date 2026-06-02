---
title: "EmfMetafileHeaderExtension1 Clase"
type: docs
weight: 620
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/
---

**Summary:** The EmfMetafileHeaderExtension1 record is the header record used in the first extension to EMF metafiles.<br/>            Following the EmfHeaderExtension1 field, the remaining fields are optional and can be present in any order.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension1

**Inheritance:** EmfMetafileHeader

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfMetafileHeaderExtension1(header)](#EmfMetafileHeaderExtension1_header_1) | Inicializa una nueva instancia de la clase [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/). |
| [EmfMetafileHeaderExtension1(header)](#EmfMetafileHeaderExtension1_header_2) | Inicializa una nueva instancia de la clase [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| emf_description | string | r/w | Obtiene o establece la descripción EMF<br/>            Una cadena Unicode UTF16-LE opcional, terminada en nulo, de longitud y contenido arbitrarios. <br/>            Su ubicación en el registro y el número de caracteres se especifican mediante los campos offDescription <br/>            y nDescription, respectivamente, en EmfHeader. Si el valor de cualquiera de los campos <br/>            es cero, no hay cadena de descripción presente. |
| emf_description_buffer | System.Byte | r/w | Obtiene o establece el búfer de descripción EMF<br/>            Una matriz de bytes opcional que contiene la cadena de descripción EMF, la cual <br/>            no necesita ser contigua con la porción fija del registro EmfMetafileHeader. En consecuencia, el campo en este búfer que está etiquetado como "UndefinedSpace" <br/>            es opcional y DEBE ser ignorado. |
| emf_header | [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) | r/w | Obtiene o establece un objeto Header (sección 2.2.9), que contiene información sobre el contenido<br/>            y la estructura del metafile |
| emf_header_extension1 | [EmfHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/) | r/w | Obtiene o establece un objeto HeaderExtension1, que especifica información adicional sobre la imagen en el metafile. |
| emf_header_record_buffer | System.Byte | r/w | Obtiene o establece una matriz de bytes opcional que contiene el resto del registro de encabezado EMF. <br/>            El tamaño de este campo DEBE ser múltiplo de 4 bytes |
| emf_pixel_format_buffer | System.Byte | r/w | Obtiene o establece una matriz de bytes opcional que contiene el descriptor de formato de píxel EMF, que no es necesario que sea contigua con la porción fija del registro EmfMetafileHeaderExtension1 o con la cadena de descripción EMF.<br/>            En consecuencia, el campo en este búfer que está etiquetado como "UndefinedSpace" es <br/>            opcional y DEBE ser ignorado |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_header(header)](#create_from_header_header_1) | Inicializa una nueva instancia de la clase [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/). |
| [create_from_header_extension1(header)](#create_from_header_extension1_header_2) | Inicializa una nueva instancia de la clase [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/). |
| [create_from_record(record)](#create_from_record_record_3) | Inicializa una nueva instancia de la clase [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/). |
| [create_from_type(type)](#create_from_type_type_4) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfMetafileHeaderExtension1(header) {#EmfMetafileHeaderExtension1_header_1}


```
 EmfMetafileHeaderExtension1(header) 
```

Inicializa una nueva instancia de la clase [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| header | [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) | El encabezado. |

### Constructor: EmfMetafileHeaderExtension1(header) {#EmfMetafileHeaderExtension1_header_2}


```
 EmfMetafileHeaderExtension1(header) 
```

Inicializa una nueva instancia de la clase [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| header | [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) | El encabezado. |

### Method: create_from_header(header)  [static] {#create_from_header_header_1}


```
 create_from_header(header) 
```

Inicializa una nueva instancia de la clase [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| header | [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) | El encabezado. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) |  |


### Method: create_from_header_extension1(header)  [static] {#create_from_header_extension1_header_2}


```
 create_from_header_extension1(header) 
```

Inicializa una nueva instancia de la clase [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| header | [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) | El encabezado. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) |  |


### Method: create_from_record(record)  [static] {#create_from_record_record_3}


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


### Method: create_from_type(type)  [static] {#create_from_type_type_4}


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


