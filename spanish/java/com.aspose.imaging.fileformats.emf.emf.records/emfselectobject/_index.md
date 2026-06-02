---
title: "EmfSelectObject"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_SELECTOBJECT agrega un objeto gráfico al contexto de dispositivo de reproducción del metafile actual."
type: docs
weight: 116
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfselectobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public final class EmfSelectObject extends EmfRecord
```

El registro EMR\_SELECTOBJECT agrega un objeto gráfico al contexto de dispositivo de reproducción del metafile actual. El objeto se especifica ya sea por su índice en la tabla de objetos EMF (sección 3.1.1.1) o por su valor de la enumeración StockObject (sección 2.1.31).
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfSelectObject(EmfRecord record)](#EmfSelectObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfSelectObject`. |
| [EmfSelectObject()](#EmfSelectObject--) | Inicializa una nueva instancia de la clase `EmfSelectObject`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getObjectHandle()](#getObjectHandle--) | Obtiene o establece un entero sin signo de 32 bits que especifica ya sea el índice de un objeto gráfico en la tabla de objetos EMF o el índice de un objeto predefinido de la enumeración `Consts.EmfStockObject`. |
| [setObjectHandle(int value)](#setObjectHandle-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica ya sea el índice de un objeto gráfico en la tabla de objetos EMF o el índice de un objeto predefinido de la enumeración `Consts.EmfStockObject`. |
### EmfSelectObject(EmfRecord record) {#EmfSelectObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSelectObject(EmfRecord record)
```


Inicializa una nueva instancia de la clase `EmfSelectObject`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El registro. |

### EmfSelectObject() {#EmfSelectObject--}
```
public EmfSelectObject()
```


Inicializa una nueva instancia de la clase `EmfSelectObject`.

### getObjectHandle() {#getObjectHandle--}
```
public int getObjectHandle()
```


Obtiene o establece un entero sin signo de 32 bits que especifica ya sea el índice de un objeto gráfico en la tabla de objetos EMF o el índice de un objeto predefinido de la enumeración `Consts.EmfStockObject`.

**Returns:**
int
### setObjectHandle(int value) {#setObjectHandle-int-}
```
public void setObjectHandle(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica ya sea el índice de un objeto gráfico en la tabla de objetos EMF o el índice de un objeto predefinido de la enumeración `Consts.EmfStockObject`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

