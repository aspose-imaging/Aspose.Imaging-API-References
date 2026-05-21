---
title: "EmfDeleteColorSpace"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_DELETECOLORSPACE elimina un objeto de espacio de color lógico."
type: docs
weight: 42
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfdeletecolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfDeleteColorSpace extends EmfObjectManipulationRecordType
```

El registro EMR\_DELETECOLORSPACE elimina un objeto de espacio de color lógico.

Se DEBE usar un registro EMR\_DELETEOBJECT en lugar de EMR\_DELETECOLORSPACE para eliminar un objeto de espacio de color lógico.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfDeleteColorSpace(EmfRecord source)](#EmfDeleteColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfDeleteColorSpace`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getIhCS()](#getIhCS--) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice de un objeto de espacio de color lógico en la tabla de objetos EMF (sección 3.1.1.1). |
| [setIhCS(int value)](#setIhCS-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice de un objeto de espacio de color lógico en la tabla de objetos EMF (sección 3.1.1.1). |
### EmfDeleteColorSpace(EmfRecord source) {#EmfDeleteColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfDeleteColorSpace(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfDeleteColorSpace`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### getIhCS() {#getIhCS--}
```
public int getIhCS()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el índice de un objeto de espacio de color lógico en la tabla de objetos EMF (sección 3.1.1.1).

Este objeto es un objeto WMF LogColorSpace o LogColorSpaceW ([MS-WMF] secciones 2.2.2.11 y 2.2.2.12, respectivamente).

**Returns:**
int
### setIhCS(int value) {#setIhCS-int-}
```
public void setIhCS(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el índice de un objeto de espacio de color lógico en la tabla de objetos EMF (sección 3.1.1.1).

Este objeto es un objeto WMF LogColorSpace o LogColorSpaceW ([MS-WMF] secciones 2.2.2.11 y 2.2.2.12, respectivamente).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

