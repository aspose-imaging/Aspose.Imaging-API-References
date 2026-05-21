---
title: "EmfPlusRestore"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusRestore restaura el estado gráfico identificado por un índice especificado de una pila de estados gráficos guardados."
type: docs
weight: 49
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusRestore extends EmfPlusStateRecordType
```

El registro EmfPlusRestore restaura el estado gráfico, identificado por un índice especificado, de una pila de estados gráficos guardados.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusRestore(EmfPlusRecord source)](#EmfPlusRestore-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusRestore`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Obtiene o establece un entero sin signo de 32 bits que especifica el nivel asociado a un estado gráfico. |
| [setStackIndex(int value)](#setStackIndex-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el nivel asociado a un estado gráfico. |
### EmfPlusRestore(EmfPlusRecord source) {#EmfPlusRestore-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRestore(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusRestore`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el nivel asociado a un estado gráfico. El valor de nivel fue asignado al estado gráfico por un registro EmfPlusSave anterior (sección 2.3.7.5).

Valor: El índice de la pila.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el nivel asociado a un estado gráfico. El valor de nivel fue asignado al estado gráfico por un registro EmfPlusSave anterior (sección 2.3.7.5).

Valor: El índice de la pila.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

