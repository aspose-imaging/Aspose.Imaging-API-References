---
title: "EmfPlusEndContainer"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusEndContainer cierra un contenedor de estado gráfico que fue previamente abierto por una operación de inicio de contenedor."
type: docs
weight: 30
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusEndContainer extends EmfPlusStateRecordType
```

El registro EmfPlusEndContainer cierra un contenedor de estado gráfico que fue previamente abierto por una operación de inicio de contenedor.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusEndContainer(EmfPlusRecord source)](#EmfPlusEndContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusEndContainer`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice de un contenedor de estado gráfico. |
| [setStackIndex(int value)](#setStackIndex-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice de un contenedor de estado gráfico. |
### EmfPlusEndContainer(EmfPlusRecord source) {#EmfPlusEndContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusEndContainer(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusEndContainer`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el índice de un contenedor de estado gráfico. El índice DEBE coincidir con el valor asociado a un contenedor de estado gráfico abierto por un registro EmfPlusBeginContainer (sección 2.3.7.1) o EmfPlusBeginContainerNoParams (sección 2.3.7.2).

Valor: El índice de la pila.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el índice de un contenedor de estado gráfico. El índice DEBE coincidir con el valor asociado a un contenedor de estado gráfico abierto por un registro EmfPlusBeginContainer (sección 2.3.7.1) o EmfPlusBeginContainerNoParams (sección 2.3.7.2).

Valor: El índice de la pila.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

