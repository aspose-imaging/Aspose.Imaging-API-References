---
title: "Clase EmfExtFloodFill"
type: docs
weight: 450
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/
---

**Summary:** The EMR_EXTFLOODFILL record fills an area of the display surface with the current brush

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtFloodFill

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfExtFloodFill(source)](#EmfExtFloodFill_source_1) | Inicializa una nueva instancia de la clase [EmfExtFloodFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| argb_32_color | int | r/w | Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8), que se utiliza con el <br/>            FloodFillMode para determinar el área a rellenar. |
| flood_fill_mode | [EmfFloodFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emffloodfill/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica cómo usar el valor Color <br/>            para determinar el área de la operación de relleno. El valor DEBE estar en la enumeración FloodFill <br/>            (sección 2.1.13). |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Obtiene o establece un objeto WMF PointL ([MS-WMF] sección 2.2.2.15), que especifica las <br/>            coordenadas, en unidades lógicas, donde comienza el relleno. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfExtFloodFill(source) {#EmfExtFloodFill_source_1}


```
 EmfExtFloodFill(source) 
```

Inicializa una nueva instancia de la clase [EmfExtFloodFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/).

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


