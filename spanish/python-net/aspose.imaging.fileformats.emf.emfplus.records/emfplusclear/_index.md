---
title: "Clase EmfPlusClear"
type: docs
weight: 30
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusclear/
---

**Summary:** The EmfPlusClear record clears the output coordinate space and initializes it with a background color and transparency

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClear

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusClear(source)](#EmfPlusClear_source_1) | Inicializa una nueva instancia de la clase [EmfPlusClear](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusclear/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| argb_32_color | int | r/w | Obtiene o establece el color.<br/>            Un objeto EmfPlusARGB (sección 2.2.2.1) que define el color para pintar la pantalla. Todos los colores se especifican en [IEC-RGB], a menos que se indique lo contrario. |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusClear(source) {#EmfPlusClear_source_1}


```
 EmfPlusClear(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusClear](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusclear/) .

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

