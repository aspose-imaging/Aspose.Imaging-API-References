---
title: "EmfModifyWorldTransform"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_MODIFYWORLDTRANSFORM modifica la transformación del espacio mundial actual al espacio de página en el contexto del dispositivo de reproducción."
type: docs
weight: 73
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfTransformRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emftransformrecordtype)
```
public final class EmfModifyWorldTransform extends EmfTransformRecordType
```

El registro EMR\_MODIFYWORLDTRANSFORM modifica la transformación del espacio mundial al espacio de página actual en el contexto del dispositivo de reproducción.

Para obtener más información sobre transformaciones y espacios de coordenadas, consulte [MSDN-WRLDPGSPC]. Consulte la sección 2.3.12 para la especificación de otros tipos de registros de transformación.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfModifyWorldTransform(EmfRecord source)](#EmfModifyWorldTransform-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfModifyWorldTransform`. |
| [EmfModifyWorldTransform()](#EmfModifyWorldTransform--) | Inicializa una nueva instancia de la clase `EmfModifyWorldTransform`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getModifyWorldTransformMode()](#getModifyWorldTransformMode--) | Obtiene o establece un entero sin signo de 32 bits que especifica cómo se utiliza la transformación especificada en Xform. |
| [setModifyWorldTransformMode(int value)](#setModifyWorldTransformMode-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica cómo se utiliza la transformación especificada en Xform. |
### EmfModifyWorldTransform(EmfRecord source) {#EmfModifyWorldTransform-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfModifyWorldTransform(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfModifyWorldTransform`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfModifyWorldTransform() {#EmfModifyWorldTransform--}
```
public EmfModifyWorldTransform()
```


Inicializa una nueva instancia de la clase `EmfModifyWorldTransform`.

### getModifyWorldTransformMode() {#getModifyWorldTransformMode--}
```
public int getModifyWorldTransformMode()
```


Obtiene o establece un entero sin signo de 32 bits que especifica cómo se utiliza la transformación especificada en Xform. Este valor MUST estar en la enumeración ModifyWorldTransformMode (sección 2.1.24).

**Returns:**
int
### setModifyWorldTransformMode(int value) {#setModifyWorldTransformMode-int-}
```
public void setModifyWorldTransformMode(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica cómo se utiliza la transformación especificada en Xform. Este valor MUST estar en la enumeración ModifyWorldTransformMode (sección 2.1.24).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

