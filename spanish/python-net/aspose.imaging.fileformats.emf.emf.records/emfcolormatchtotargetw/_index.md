---
title: "Clase EmfColorMatchToTargetW"
type: docs
weight: 150
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/
---

**Summary:** The EMR_COLORMATCHTOTargetW record specifies whether to perform color matching with a color<br/>            profile that is specified in a file with a name consisting of Unicode characters.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfColorMatchToTargetW

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfColorMatchToTargetW(source)](#EmfColorMatchToTargetW_source_1) | Inicializa una nueva instancia de la clase [EmfColorMatchToTargetW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| cb_data | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de los datos sin procesar del perfil de color objetivo<br/>            si está contenido en el campo Data. |
| cb_name | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número de bytes en el nombre Unicode<br/>            UTF16-LE del perfil de color deseado. |
| datos | System.Byte | r/w | Obtiene o establece una matriz de tamaño (cbName + cbData) en bytes, que especifica el nombre UTF16-LE<br/>            y los datos sin procesar del perfil de color deseado. |
| dw_action | [EmfColorSpace](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfcolorspace/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica un valor de la enumeración ColorSpace<br/>            (sección 2.1.7). |
| dw_flags | [EmfColorMatchToTarget](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfcolormatchtotarget/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica un valor de la<br/>            enumeración ColorMatchToTarget (sección 2.1.6). |
| nombre | string | r | Obtiene el nombre |
| raw_data | System.Byte | r | Obtiene los datos sin procesar |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfColorMatchToTargetW(source) {#EmfColorMatchToTargetW_source_1}


```
 EmfColorMatchToTargetW(source) 
```

Inicializa una nueva instancia de la clase [EmfColorMatchToTargetW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/).

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


