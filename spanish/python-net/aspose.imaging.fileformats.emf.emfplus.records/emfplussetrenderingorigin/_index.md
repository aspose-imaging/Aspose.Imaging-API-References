---
title: "Clase EmfPlusSetRenderingOrigin"
type: docs
weight: 540
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetrenderingorigin/
---

**Summary:** The EmfPlusSetRenderingOrigin record specifies the rendering origin for graphics output.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetRenderingOrigin

**Inheritance:** EmfPlusPropertyRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusSetRenderingOrigin(source)](#EmfPlusSetRenderingOrigin_source_1) | Inicializa una nueva instancia de la clase [EmfPlusSetRenderingOrigin](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetrenderingorigin/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |
| x | int | r/w | Obtiene o establece un entero sin signo de 32 bits que define el valor de la coordenada horizontal del origen de renderizado. |
| y | int | r/w | Obtiene o establece un entero sin signo de 32 bits que define el valor de la coordenada vertical del origen de renderizado. |


### Constructor: EmfPlusSetRenderingOrigin(source) {#EmfPlusSetRenderingOrigin_source_1}


```
 EmfPlusSetRenderingOrigin(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusSetRenderingOrigin](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetrenderingorigin/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

