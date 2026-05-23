---
title: "Clase EmfPlusRestore"
type: docs
weight: 400
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/
---

**Summary:** The EmfPlusRestore record restores the graphics state, identified by a specified index, from a stack of saved graphics states.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRestore

**Inheritance:** EmfPlusStateRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusRestore(source)](#EmfPlusRestore_source_1) | Inicializa una nueva instancia de la clase [EmfPlusRestore](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| stack_index | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el nivel asociado a un<br/> estado gráfico. El valor de nivel fue asignado al estado gráfico por un registro EmfPlusSave previo (sección 2.3.7.5). |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusRestore(source) {#EmfPlusRestore_source_1}


```
 EmfPlusRestore(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusRestore](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

