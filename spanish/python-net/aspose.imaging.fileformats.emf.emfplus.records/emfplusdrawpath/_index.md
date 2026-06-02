---
title: "Clase EmfPlusDrawPath"
type: docs
weight: 160
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/
---

**Summary:** The EmfPlusDrawPath record specifies drawing a graphics path.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawPath

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusDrawPath(source)](#EmfPlusDrawPath_source_1) | Inicializa una nueva instancia de la clase [EmfPlusDrawPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| object_id | System.Byte | r/w | Obtiene o establece el identificador del objeto.<br/>            El índice del objeto EmfPlusPath (sección 2.2.1.6) a dibujar, en la<br/>            tabla de objetos EMF+. El valor DEBE ser de 0 a 63, inclusive. |
| pen_id | int | r/w | Obtiene o establece el identificador del bolígrafo<br/>            Un entero sin signo de 32 bits que especifica un índice en la tabla de objetos EMF+<br/>            para un objeto EmfPlusPen (sección 2.2.1.7) que se usará para dibujar el EmfPlusPath.<br/>            El valor DEBE ser de 0 a 63, inclusive |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusDrawPath(source) {#EmfPlusDrawPath_source_1}


```
 EmfPlusDrawPath(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusDrawPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

