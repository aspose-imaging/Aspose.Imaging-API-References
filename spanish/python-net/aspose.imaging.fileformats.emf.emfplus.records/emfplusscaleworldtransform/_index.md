---
title: "Clase EmfPlusScaleWorldTransform"
type: docs
weight: 430
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/
---

**Summary:** The EmfPlusScaleWorldTransform record performs a scaling on the current world space transform.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusScaleWorldTransform

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusScaleWorldTransform(source)](#EmfPlusScaleWorldTransform_source_1) | Inicializa una nueva instancia de la clase [EmfPlusScaleWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| post_multiplied_matrix | bool | r | Obtiene un valor que indica si [post multiplied matrix].<br/>            Si está establecido, la matriz de transformación debe multiplicarse post-multiplicativamente. Si no está establecido, debe multiplicarse pre-multiplicativamente. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| sx | float | r/w | Obtiene o establece un valor de punto flotante de 32 bits que define el factor de escala horizontal. El escalado<br/>            se realiza construyendo una nueva matriz de transformación a partir de los valores de los campos Sx y Sy, como<br/>            se muestra en la tabla siguiente.<br/>            -----------------<br/> | Sx | 0 | 0 | <br/> | 0 | Sx | 0 | <br/>            -----------------<br/>            Figura 3: Matriz de Transformación de Escala |
| sy | float | r/w | Obtiene o establece un valor de punto flotante de 32 bits que define el factor de escala vertical. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusScaleWorldTransform(source) {#EmfPlusScaleWorldTransform_source_1}


```
 EmfPlusScaleWorldTransform(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusScaleWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/) .

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

