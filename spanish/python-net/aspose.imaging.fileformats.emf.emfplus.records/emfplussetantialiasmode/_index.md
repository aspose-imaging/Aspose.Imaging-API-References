---
title: "Clase EmfPlusSetAntiAliasMode"
type: docs
weight: 450
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/
---

**Summary:** The EmfPlusSetAntiAliasMode record specifies the anti-aliasing mode for text output.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetAntiAliasMode

**Inheritance:** EmfPlusPropertyRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusSetAntiAliasMode(source)](#EmfPlusSetAntiAliasMode_source_1) | Inicializa una nueva instancia de la clase [EmfPlusSetAntiAliasMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| anti_aliasing | bool | r/w | Obtiene o establece un valor que indica si [anti aliasing].<br/>            Si está establecido, se DEBE realizar anti-aliasing.<br/>            Si está despejado, NO SE DEBE realizar anti-aliasing. |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| smoothing_mode | [EmfPlusSmoothingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplussmoothingmode/) | r/w | Obtiene o establece el modo de suavizado.<br/>            (7 bits): El valor del modo de suavizado, de la enumeración SmoothingMode (sección 2.1.1.28) |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusSetAntiAliasMode(source) {#EmfPlusSetAntiAliasMode_source_1}


```
 EmfPlusSetAntiAliasMode(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusSetAntiAliasMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

