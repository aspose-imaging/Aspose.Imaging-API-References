---
title: "Clase EmfGradientFill"
type: docs
weight: 560
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfgradientfill/
---

**Summary:** The EMR_GRADIENTFILL record specifies filling rectangles or triangles with gradients of color.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfGradientFill

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfGradientFill(source)](#EmfGradientFill_source_1) | Inicializa una nueva instancia de la clase [EmfGradientFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfgradientfill/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica un <br/>            rectángulo delimitador, en unidades del dispositivo inclusivas-inclusivas. |
| n_tri | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número de rectángulos o triángulos a rellenar. |
| n_ver | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número de vértices. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
| ul_mode | [EmfGradientFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgradientfill/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el modo de relleno degradado. El valor <br/>            DEBE estar en la enumeración GradientFill (sección 2.1.15). |
| vertex_data | [EmfVertexData](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfvertexdata/) | r/w | Obtiene o establece objetos que especifican los vértices de rectángulos o triángulos y <br/>            los colores que les corresponden. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfGradientFill(source) {#EmfGradientFill_source_1}


```
 EmfGradientFill(source) 
```

Inicializa una nueva instancia de la clase [EmfGradientFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfgradientfill/).

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


