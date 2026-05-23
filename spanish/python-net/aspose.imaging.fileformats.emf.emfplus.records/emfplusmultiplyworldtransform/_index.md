---
title: "Clase EmfPlusMultiplyWorldTransform"
type: docs
weight: 320
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/
---

**Summary:** The EmfPlusMultiplyWorldTransform record multiplies the current world space transform by a<br/>            specified transform matrix.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusMultiplyWorldTransform

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusMultiplyWorldTransform(source)](#EmfPlusMultiplyWorldTransform_source_1) | Inicializa una nueva instancia de la clase [EmfPlusMultiplyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| matrix_data | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtiene o establece un objeto EmfPlusTransformMatrix (sección 2.2.2.47) que define la matriz de multiplicación. |
| post_multiplied_matrix | bool | r | Obtiene un valor que indica si [post multiplied matrix].<br/>            Si está establecido, la matriz de transformación debe multiplicarse post-multiplicativamente. Si no está establecido, debe multiplicarse pre-multiplicativamente. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusMultiplyWorldTransform(source) {#EmfPlusMultiplyWorldTransform_source_1}


```
 EmfPlusMultiplyWorldTransform(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusMultiplyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

