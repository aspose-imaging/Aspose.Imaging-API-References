---
title: "EmfSetColorAdjustment"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_SETCOLORADJUSTMENT especifica las propiedades de ajuste de color en el contexto del dispositivo de reproducción."
type: docs
weight: 122
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetcoloradjustment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetColorAdjustment extends EmfStateRecordType
```

El registro EMR\_SETCOLORADJUSTMENT especifica las propiedades de ajuste de color en el contexto de dispositivo de reproducción.

Los valores de ajuste de color se utilizan para ajustar el color de entrada del mapa de bits de origen para operaciones gráficas realizadas por los registros EMR\_STRETCHBLT y EMR\_STRETCHDIBITS cuando el modo STRETCH\_HALFTONE está establecido a partir de la enumeración StretchMode (sección 2.1.32). El objeto ColorAdjustment especificado por este registro DEBE ser utilizado en operaciones gráficas que requieran un objeto ColorAdjustment, hasta que otro registro EMR\_SETCOLORADJUSTMENT especifique un objeto ColorAdjustment diferente, o hasta que el objeto sea eliminado por un registro EMR\_DELETEOBJECT.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfSetColorAdjustment(EmfRecord source)](#EmfSetColorAdjustment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfSetColorAdjustment`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getColorAdjustment()](#getColorAdjustment--) | Obtiene o establece un objeto ColorAdjustment (sección 2.2.2) que especifica los valores de ajuste de color. |
| [setColorAdjustment(EmfColorAdjustment value)](#setColorAdjustment-com.aspose.imaging.fileformats.emf.emf.objects.EmfColorAdjustment-) | Obtiene o establece un objeto ColorAdjustment (sección 2.2.2) que especifica los valores de ajuste de color. |
### EmfSetColorAdjustment(EmfRecord source) {#EmfSetColorAdjustment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetColorAdjustment(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfSetColorAdjustment`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### getColorAdjustment() {#getColorAdjustment--}
```
public EmfColorAdjustment getColorAdjustment()
```


Obtiene o establece un objeto ColorAdjustment (sección 2.2.2) que especifica los valores de ajuste de color.

**Returns:**
[EmfColorAdjustment](../../com.aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment)
### setColorAdjustment(EmfColorAdjustment value) {#setColorAdjustment-com.aspose.imaging.fileformats.emf.emf.objects.EmfColorAdjustment-}
```
public void setColorAdjustment(EmfColorAdjustment value)
```


Obtiene o establece un objeto ColorAdjustment (sección 2.2.2) que especifica los valores de ajuste de color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfColorAdjustment](../../com.aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment) |  |

