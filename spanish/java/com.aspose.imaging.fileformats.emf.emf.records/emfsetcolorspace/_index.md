---
title: "EmfSetColorSpace"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_SETCOLORSPACE define el objeto de espacio de color lógico actual para operaciones gráficas."
type: docs
weight: 123
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetcolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfSetColorSpace extends EmfObjectManipulationRecordType
```

El registro EMR\_SETCOLORSPACE define el objeto de espacio de color lógico actual para operaciones gráficas.

El objeto de espacio de color lógico definido por este registro DEBE usarse en operaciones de dibujo que se especifican en registros EMF posteriores, hasta que se especifique un objeto de espacio de color lógico diferente mediante otro registro EMR\_SETCOLORSPACE, o el objeto sea eliminado mediante un registro EMR\_DELETECOLORSPACE.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfSetColorSpace(EmfRecord source)](#EmfSetColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfSetColorSpace`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getIhCS()](#getIhCS--) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice de un objeto de espacio de color lógico en la tabla de objetos EMF (sección 3.1.1.1). |
| [setIhCS(int value)](#setIhCS-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice de un objeto de espacio de color lógico en la tabla de objetos EMF (sección 3.1.1.1). |
### EmfSetColorSpace(EmfRecord source) {#EmfSetColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetColorSpace(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfSetColorSpace`.

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

