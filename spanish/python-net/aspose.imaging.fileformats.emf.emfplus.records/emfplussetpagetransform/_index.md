---
title: "EmfPlusSetPageTransform Class"
type: docs
weight: 520
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/
---

**Summary:** The EmfPlusSetPageTransform record specifies scaling factors and units for converting page space<br/>            coordinates to device space coordinates.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetPageTransform

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusSetPageTransform(source)](#EmfPlusSetPageTransform_source_1) | Inicializa una nueva instancia de la clase [EmfPlusSetPageTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| page_scale | float | r/w | Obtiene o establece un valor de punto flotante de 32 bits que especifica el factor de escala para convertir<br/>            coordenadas del espacio de página a coordenadas del espacio del dispositivo. |
| page_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r | Obtiene la unidad de medida para las coordenadas del espacio de página, de la enumeración UnitType<br/>            (sección 2.1.1.33). Este valor NO DEBE ser UnitTypeDisplay o UnitTypeWorld. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusSetPageTransform(source) {#EmfPlusSetPageTransform_source_1}


```
 EmfPlusSetPageTransform(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusSetPageTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

