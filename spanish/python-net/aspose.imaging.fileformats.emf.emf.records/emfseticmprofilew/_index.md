---
title: "Clase EmfSetIcmProfileW"
type: docs
weight: 1180
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/
---

**Summary:** The EMR_SETICMPROFILEW record specifies a color profile in a file with a name consisting of<br/>            Unicode characters, for graphics output.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetIcmProfileW

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfSetIcmProfileW(source)](#EmfSetIcmProfileW_source_1) | Inicializa una nueva instancia de la clase [EmfSetIcmProfileW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| cb_data | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de los datos del perfil de color, si está adjunto. |
| cb_name | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número de bytes en el nombre Unicode<br/>            UTF16-LE del perfil de color deseado. |
| datos | System.Byte | r/w | Obtiene o establece una matriz de tamaño (cbName + cbData) en bytes, que especifica el nombre UTF16-LE<br/>            y los datos sin procesar del perfil de color deseado. |
| dw_flags | int | r/w | Obtiene o establece un entero sin signo de 32 bits que contiene los indicadores del perfil de color. |
| nombre | string | r | Obtiene el nombre |
| raw_data | System.Byte | r | Obtiene los datos sin procesar |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetIcmProfileW(source) {#EmfSetIcmProfileW_source_1}


```
 EmfSetIcmProfileW(source) 
```

Inicializa una nueva instancia de la clase [EmfSetIcmProfileW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/).

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


