---
title: "EmfSetPixelV Clase"
type: docs
weight: 1260
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/
---

**Summary:** The EMR_SETPIXELV record defines the color of the pixel at the specified logical coordinates.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetPixelV

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfSetPixelV()](#EmfSetPixelV__1) | Inicializa una nueva instancia de la clase [EmfSetPixelV](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/). |
| [EmfSetPixelV(source)](#EmfSetPixelV_source_2) | Inicializa una nueva instancia de la clase [EmfSetPixelV](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| argb_32_color | int | r/w | Obtiene o establece un objeto ColorRef WMF de 32 bits ([MS-WMF] sección 2.2.2.8) que especifica el color del píxel. |
| pixel | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Obtiene o establece un objeto PointL WMF de 64 bits ([MS-WMF] sección 2.2.2.15) que especifica las<br/>            coordenadas lógicas del píxel. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetPixelV() {#EmfSetPixelV__1}


```
 EmfSetPixelV() 
```

Inicializa una nueva instancia de la clase [EmfSetPixelV](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/).

### Constructor: EmfSetPixelV(source) {#EmfSetPixelV_source_2}


```
 EmfSetPixelV(source) 
```

Inicializa una nueva instancia de la clase [EmfSetPixelV](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/).

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


