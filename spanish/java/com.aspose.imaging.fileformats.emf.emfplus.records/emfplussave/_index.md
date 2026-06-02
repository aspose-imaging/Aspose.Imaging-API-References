---
title: "EmfPlusSave"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusSave guarda el estado gráfico identificado por un índice especificado en una pila de estados gráficos guardados."
type: docs
weight: 51
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussave/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusSave extends EmfPlusStateRecordType
```

El registro EmfPlusSave guarda el estado gráfico, identificado por un índice especificado, en una pila de estados gráficos guardados.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusSave(EmfPlusRecord source)](#EmfPlusSave-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusSave`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Obtiene o establece un entero sin signo de 32 bits que especifica un nivel para asociarlo con el estado gráfico. |
| [setStackIndex(int value)](#setStackIndex-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica un nivel para asociarlo con el estado gráfico. |
### EmfPlusSave(EmfPlusRecord source) {#EmfPlusSave-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSave(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusSave`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Obtiene o establece un entero sin signo de 32 bits que especifica un nivel para asociarlo con el estado gráfico. El valor de nivel puede ser usado por un registro EmfPlusRestore posterior (sección 2.3.7.4) para recuperar el estado gráfico.

Valor: El índice de la pila.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica un nivel para asociarlo con el estado gráfico. El valor de nivel puede ser usado por un registro EmfPlusRestore posterior (sección 2.3.7.4) para recuperar el estado gráfico.

Valor: El índice de la pila.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

