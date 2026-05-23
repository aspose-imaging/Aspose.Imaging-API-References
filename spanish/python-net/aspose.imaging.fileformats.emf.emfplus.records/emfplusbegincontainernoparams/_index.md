---
title: "Clase EmfPlusBeginContainerNoParams"
type: docs
weight: 20
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/
---

**Summary:** The EmfPlusBeginContainerNoParams record opens a new graphics state container.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusBeginContainerNoParams

**Inheritance:** EmfPlusStateRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusBeginContainerNoParams(source)](#EmfPlusBeginContainerNoParams_source_1) | Inicializa una nueva instancia de la [EmfPlusBeginContainerNoParams](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/) clase. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| stack_index | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica un índice para asociarlo con el<br/>            contenedor de estado gráfico. El índice DEBE ser referenciado por un registro EmfPlusEndContainer subsecuente (sección 2.3.7.3) para cerrar el contenedor de estado gráfico. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusBeginContainerNoParams(source) {#EmfPlusBeginContainerNoParams_source_1}


```
 EmfPlusBeginContainerNoParams(source) 
```

Inicializa una nueva instancia de la [EmfPlusBeginContainerNoParams](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/) clase.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

