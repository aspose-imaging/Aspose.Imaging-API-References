---
title: "Clase EmfPlusRotateWorldTransform"
type: docs
weight: 410
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/
---

**Summary:** The EmfPlusRotateWorldTransform record performs a rotation on the current world space transform.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRotateWorldTransform

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusRotateWorldTransform(source)](#EmfPlusRotateWorldTransform_source_1) | Inicializa una nueva instancia de la clase [EmfPlusRotateWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| angle | float | r/w | Obtiene o establece un valor de punto flotante de 32 bits que especifica el ángulo de rotación en grados.<br/>            La operación se realiza construyendo una nueva matriz de transformación a partir del siguiente<br/>            diagrama:<br/>            ---------------------------------<br/> | sin(Angle) | cos(Angle) | 0 | <br/> | cos(Angle) | sin(Angle) | 0 | <br/>            ---------------------------------<br/>            Figura 2: Matriz de Transformación de Rotación<br/>            La transformación del espacio mundial actual se multiplica por esta matriz, y el resultado se convierte en la<br/>            nueva transformación del espacio mundial actual. El campo Flags determina el orden de multiplicación. |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| post_multiplied_matrix | bool | r | Obtiene un valor que indica si [post multiplied matrix].<br/>            Si está establecido, la matriz de transformación debe ser post-multiplicada. Si está despejado, debe ser pre-multiplicada. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusRotateWorldTransform(source) {#EmfPlusRotateWorldTransform_source_1}


```
 EmfPlusRotateWorldTransform(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusRotateWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

