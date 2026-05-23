---
title: "Clase EmfPlusOffsetClip"
type: docs
weight: 350
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusoffsetclip/
---

**Summary:** The EmfPlusOffsetClip record applies a translation transform on the current clipping region for the world space.<br/>            The new current clipping region is set to the result of the translation transform.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusOffsetClip

**Inheritance:** EmfPlusClippingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusOffsetClip(source)](#EmfPlusOffsetClip_source_1) | Inicializa una nueva instancia de la clase [EmfPlusOffsetClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusoffsetclip/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| dx | float | r/w | Obtiene o establece un valor de punto flotante de 32 bits que especifica el desplazamiento horizontal para la traducción. |
| dy | float | r/w | Obtiene o establece un valor de punto flotante de 32 bits que especifica el desplazamiento vertical para la traducción. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusOffsetClip(source) {#EmfPlusOffsetClip_source_1}


```
 EmfPlusOffsetClip(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusOffsetClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusoffsetclip/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

