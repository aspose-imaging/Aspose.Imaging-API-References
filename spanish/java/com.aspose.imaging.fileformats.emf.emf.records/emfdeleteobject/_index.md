---
title: "EmfDeleteObject"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_DELETEOBJECT elimina un objeto gráfico que se especifica por su índice en la tabla de objetos EMF sección 3.1.1.1."
type: docs
weight: 43
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public final class EmfDeleteObject extends EmfRecord
```

El registro EMR\_DELETEOBJECT elimina un objeto gráfico, que se especifica por su índice en la Tabla de Objetos EMF (sección 3.1.1.1).
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfDeleteObject(EmfRecord record)](#EmfDeleteObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfDeleteObject`. |
| [EmfDeleteObject()](#EmfDeleteObject--) | Inicializa una nueva instancia de la clase `EmfDeleteObject`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getObjectHandle()](#getObjectHandle--) | Obtiene o establece un entero sin signo de 32 bits que especifica ya sea el índice de un objeto gráfico en la tabla de objetos EMF o el índice de un objeto predeterminado de la enumeración StockObject. |
| [setObjectHandle(int value)](#setObjectHandle-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica ya sea el índice de un objeto gráfico en la tabla de objetos EMF o el índice de un objeto predeterminado de la enumeración StockObject. |
### EmfDeleteObject(EmfRecord record) {#EmfDeleteObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfDeleteObject(EmfRecord record)
```


Inicializa una nueva instancia de la clase `EmfDeleteObject`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El registro. |

### EmfDeleteObject() {#EmfDeleteObject--}
```
public EmfDeleteObject()
```


Inicializa una nueva instancia de la clase `EmfDeleteObject`.

### getObjectHandle() {#getObjectHandle--}
```
public int getObjectHandle()
```


Obtiene o establece un entero sin signo de 32 bits que especifica ya sea el índice de un objeto gráfico en la tabla de objetos EMF o el índice de un objeto predeterminado de la enumeración StockObject.

**Returns:**
int
### setObjectHandle(int value) {#setObjectHandle-int-}
```
public void setObjectHandle(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica ya sea el índice de un objeto gráfico en la tabla de objetos EMF o el índice de un objeto predeterminado de la enumeración StockObject.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

