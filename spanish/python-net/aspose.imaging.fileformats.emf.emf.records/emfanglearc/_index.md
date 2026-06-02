---
title: "Clase EmfAngleArc"
type: docs
weight: 30
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfanglearc/
---

**Summary:** The EMR_ANGLEARC record specifies a line segment of an arc. The line segment is drawn from the <br/>            current position to the beginning of the arc. The arc is drawn along the perimeter of a circle with the <br/>            given radius and center. The length of the arc is defined by the given start and sweep angles

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfAngleArc

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfAngleArc()](#EmfAngleArc__1) | Inicializa una nueva instancia de la clase [EmfAngleArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfanglearc/). |
| [EmfAngleArc(source)](#EmfAngleArc_source_2) | Inicializa una nueva instancia de la clase [EmfAngleArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfanglearc/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| center | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Obtiene o establece un objeto WMF PointL de 64 bits, especificado en [MS-WMF] sección 2.2.2.15, que <br/>            especifica las coordenadas lógicas del centro del círculo. |
| radio | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el radio del círculo, en unidades lógicas. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| start_angle | float | r/w | Obtiene o establece un flotante de 32 bits que especifica el ángulo inicial del arco, en grados. |
| sweep_angle | float | r/w | Obtiene o establece un flotante de 32 bits que especifica el ángulo de barrido del arco, en grados. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfAngleArc() {#EmfAngleArc__1}


```
 EmfAngleArc() 
```

Inicializa una nueva instancia de la clase [EmfAngleArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfanglearc/).

### Constructor: EmfAngleArc(source) {#EmfAngleArc_source_2}


```
 EmfAngleArc(source) 
```

Inicializa una nueva instancia de la clase [EmfAngleArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfanglearc/).

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


