---
title: "Clase EmfPlusSetClipPath"
type: docs
weight: 460
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/
---

**Summary:** The EmfPlusSetClipPath record combines the current clipping region with a graphics path.<br/>            The new current clipping region is set to the result of the CombineMode operation.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetClipPath

**Inheritance:** EmfPlusClippingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusSetClipPath(source)](#EmfPlusSetClipPath_source_1) | Inicializa una nueva instancia de la clase [EmfPlusSetClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| cm | [EmfPlusCombineMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscombinemode/) | r/w | Obtiene o establece el CM (4 bits): Especifica la operación lógica para combinar dos regiones. Consulte la<br/>            enumeración CombineMode (sección 2.1.1.4) para conocer el significado de los valores. |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| object_id | System.Byte | r/w | Obtiene o establece el índice de un objeto EmfPlusPath (sección 2.2.1.6) en la EMF+<br/>            Tabla de objetos. El valor DEBE ser de 0 a 63, inclusive. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusSetClipPath(source) {#EmfPlusSetClipPath_source_1}


```
 EmfPlusSetClipPath(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusSetClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/) .

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

