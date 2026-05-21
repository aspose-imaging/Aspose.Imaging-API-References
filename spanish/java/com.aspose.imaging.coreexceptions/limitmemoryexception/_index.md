---
title: "LimitMemoryException"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La excepción de límite de memoria."
type: docs
weight: 21
url: /es/java/com.aspose.imaging.coreexceptions/limitmemoryexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Error, java.lang.VirtualMachineError, java.lang.OutOfMemoryError, com.aspose.ms.System.OutOfMemoryException
```
public class LimitMemoryException extends System.OutOfMemoryException
```

La excepción de límite de memoria. Ocurre cuando se debe reducir el uso de memoria.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [LimitMemoryException(String message)](#LimitMemoryException-java.lang.String-) | Inicializa una nueva instancia de la clase `LimitMemoryException`. |
| [LimitMemoryException(String message, Throwable innerException)](#LimitMemoryException-java.lang.String-java.lang.Throwable-) | Inicializa una nueva instancia de la clase `LimitMemoryException`. |
| [LimitMemoryException(String message, long reduceMemoryFactor)](#LimitMemoryException-java.lang.String-long-) | Inicializa una nueva instancia de la clase `LimitMemoryException`. |
| [LimitMemoryException(String message, Throwable innerException, int reduceMemoryFactor)](#LimitMemoryException-java.lang.String-java.lang.Throwable-int-) | Inicializa una nueva instancia de la clase `LimitMemoryException`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getReduceMemoryFactor()](#getReduceMemoryFactor--) | Obtiene o establece el factor de reducción de memoria. |
| [setReduceMemoryFactor(long value)](#setReduceMemoryFactor-long-) | Obtiene o establece el factor de reducción de memoria. |
### LimitMemoryException(String message) {#LimitMemoryException-java.lang.String-}
```
public LimitMemoryException(String message)
```


Inicializa una nueva instancia de la clase `LimitMemoryException`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mensaje | java.lang.String | El mensaje de la excepción. |

### LimitMemoryException(String message, Throwable innerException) {#LimitMemoryException-java.lang.String-java.lang.Throwable-}
```
public LimitMemoryException(String message, Throwable innerException)
```


Inicializa una nueva instancia de la clase `LimitMemoryException`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mensaje | java.lang.String | El mensaje de la excepción. |
| innerException | java.lang.Throwable | La excepción interna. |

### LimitMemoryException(String message, long reduceMemoryFactor) {#LimitMemoryException-java.lang.String-long-}
```
public LimitMemoryException(String message, long reduceMemoryFactor)
```


Inicializa una nueva instancia de la clase `LimitMemoryException`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mensaje | java.lang.String | El mensaje de la excepción. |
| reduceMemoryFactor | long | El factor de reducción de memoria. |

### LimitMemoryException(String message, Throwable innerException, int reduceMemoryFactor) {#LimitMemoryException-java.lang.String-java.lang.Throwable-int-}
```
public LimitMemoryException(String message, Throwable innerException, int reduceMemoryFactor)
```


Inicializa una nueva instancia de la clase `LimitMemoryException`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mensaje | java.lang.String | El mensaje de la excepción. |
| innerException | java.lang.Throwable | La excepción interna. |
| reduceMemoryFactor | int | El factor de reducción de memoria. |

### getReduceMemoryFactor() {#getReduceMemoryFactor--}
```
public long getReduceMemoryFactor()
```


Obtiene o establece el factor de reducción de memoria.

Valor: El factor de reducción de memoria.

**Returns:**
long
### setReduceMemoryFactor(long value) {#setReduceMemoryFactor-long-}
```
public void setReduceMemoryFactor(long value)
```


Obtiene o establece el factor de reducción de memoria.

Valor: El factor de reducción de memoria.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

