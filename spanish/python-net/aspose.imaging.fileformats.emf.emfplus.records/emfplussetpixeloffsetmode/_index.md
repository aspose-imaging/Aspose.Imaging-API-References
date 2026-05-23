---
title: "Clase EmfPlusSetPixelOffsetMode"
type: docs
weight: 530
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpixeloffsetmode/
---

**Summary:** The EmfPlusSetPixelOffsetMode record specifies how pixels are centered with respect to the<br/>            coordinates of the drawing surface.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetPixelOffsetMode

**Inheritance:** EmfPlusPropertyRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusSetPixelOffsetMode(source)](#EmfPlusSetPixelOffsetMode_source_1) | Inicializa una nueva instancia de la clase [EmfPlusSetPixelOffsetMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpixeloffsetmode/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| pixel_offset_mode | [EmfPlusPixelOffsetMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/) | r/w | Obtiene o establece el valor del modo de desplazamiento de píxel, de la enumeración PixelOffsetMode<br/>            (sección 2.1.1.26). |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusSetPixelOffsetMode(source) {#EmfPlusSetPixelOffsetMode_source_1}


```
 EmfPlusSetPixelOffsetMode(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusSetPixelOffsetMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpixeloffsetmode/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

