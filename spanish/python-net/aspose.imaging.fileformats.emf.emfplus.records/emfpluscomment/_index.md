---
title: "Clase EmfPlusComment"
type: docs
weight: 50
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/
---

**Summary:** The EmfPlusComment record specifies arbitrary private data.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusComment

**Inheritance:** EmfPlusRecord

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusComment(source)](#EmfPlusComment_source_1) | Inicializa una nueva instancia de la clase [EmfPlusComment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que no se usa. Este campo DEBERÍA establecerse en cero<br/>            y DEBE ser ignorado al recibirlo. |
| private_data | System.Byte | r/w | Obtiene o establece una matriz de bytes de longitud DataSize de datos privados.<br/>            bytes de datos específicos del registro que siguen. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusComment(source) {#EmfPlusComment_source_1}


```
 EmfPlusComment(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusComment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

