---
title: "EmfPlusBeginContainer Class"
type: docs
weight: 10
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/
---

**Summary:** The EmfPlusBeginContainer record opens a new graphics state container and specifies a transform for it.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusBeginContainer

**Inheritance:** EmfPlusStateRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusBeginContainer(source)](#EmfPlusBeginContainer_source_1) | Inicializa una nueva instancia de la clase [EmfPlusBeginContainer](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| dest_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Obtiene o establece un objeto EmfPlusRectF (sección 2.2.2.39) que, junto con SrcRect, especifica<br/>            una transformación para el contenedor. Esta transformación produce SrcRect cuando se aplica a DestRect. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| page_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r | Obtiene la unidad de página. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Obtiene o establece un rectángulo EmfPlusRectF que, junto con DestRect, especifica una transformación<br/>            para el contenedor. Esta transformación produce SrcRect cuando se aplica a DestRect. |
| stack_index | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica un índice para asociarlo con el<br/>            contenedor de estado gráfico. El índice DEBE ser referenciado por un registro EmfPlusEndContainer subsecuente (sección 2.3.7.3) para cerrar el contenedor de estado gráfico. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusBeginContainer(source) {#EmfPlusBeginContainer_source_1}


```
 EmfPlusBeginContainer(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusBeginContainer](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

