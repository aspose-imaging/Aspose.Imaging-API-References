---
title: "Clase EmfPlusTranslateWorldTransform"
type: docs
weight: 630
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/
---

**Summary:** The EmfPlusTranslateWorldTransform record performs a translation on the current world space transform.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTranslateWorldTransform

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusTranslateWorldTransform(source)](#EmfPlusTranslateWorldTransform_source_1) | Inicializa una nueva instancia de la clase [EmfPlusTranslateWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| dx | float | r/w | Obtiene o establece un valor de punto flotante de 32 bits que define la distancia horizontal. La traducción<br/>            se realiza construyendo una nueva matriz de transformación mundial a partir de los campos dx y dy. |
| dy | float | r/w | Obtiene o establece un valor de punto flotante de 32 bits que define el valor de la distancia vertical. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| post_multiplied_matrix | bool | r | Obtiene un valor que indica si [post multiplied matrix].<br/>            Si está establecido, la matriz de transformación debe ser post-multiplicada. Si está despejado, debe ser pre-multiplicada. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusTranslateWorldTransform(source) {#EmfPlusTranslateWorldTransform_source_1}


```
 EmfPlusTranslateWorldTransform(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusTranslateWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

