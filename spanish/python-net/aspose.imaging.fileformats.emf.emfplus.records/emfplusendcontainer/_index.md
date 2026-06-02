---
title: "Clase EmfPlusEndContainer"
type: docs
weight: 210
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/
---

**Summary:** The EmfPlusEndContainer record closes a graphics state container that was previously opened by a begin container operation.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusEndContainer

**Inheritance:** EmfPlusStateRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusEndContainer(source)](#EmfPlusEndContainer_source_1) | Inicializa una nueva instancia de la clase [EmfPlusEndContainer](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| stack_index | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el índice de un contenedor de estado gráfico<br/>            . El índice DEBE coincidir con el valor asociado a un contenedor de estado gráfico<br/>            abierto por un registro EmfPlusBeginContainer previo (sección 2.3.7.1) o<br/>            por el registro EmfPlusBeginContainerNoParams (sección 2.3.7.2). |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusEndContainer(source) {#EmfPlusEndContainer_source_1}


```
 EmfPlusEndContainer(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusEndContainer](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

