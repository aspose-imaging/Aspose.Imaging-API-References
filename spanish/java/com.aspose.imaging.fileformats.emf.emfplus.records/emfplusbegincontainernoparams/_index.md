---
title: "EmfPlusBeginContainerNoParams"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusBeginContainerNoParams abre un nuevo contenedor de estado gráfico."
type: docs
weight: 11
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusBeginContainerNoParams extends EmfPlusStateRecordType
```

El registro EmfPlusBeginContainerNoParams abre un nuevo contenedor de estado gráfico.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusBeginContainerNoParams(EmfPlusRecord source)](#EmfPlusBeginContainerNoParams-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusBeginContainerNoParams`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Obtiene o establece un entero sin signo de 32 bits que especifica un índice para asociar con el contenedor de estado gráfico. |
| [setStackIndex(int value)](#setStackIndex-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica un índice para asociar con el contenedor de estado gráfico. |
### EmfPlusBeginContainerNoParams(EmfPlusRecord source) {#EmfPlusBeginContainerNoParams-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusBeginContainerNoParams(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusBeginContainerNoParams`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Obtiene o establece un entero sin signo de 32 bits que especifica un índice para asociar con el contenedor de estado gráfico. El índice DEBE ser referenciado por un registro EmfPlusEndContainer posterior (sección 2.3.7.3) para cerrar el contenedor de estado gráfico.

Valor: El índice de la pila.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica un índice para asociar con el contenedor de estado gráfico. El índice DEBE ser referenciado por un registro EmfPlusEndContainer posterior (sección 2.3.7.3) para cerrar el contenedor de estado gráfico.

Valor: El índice de la pila.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

