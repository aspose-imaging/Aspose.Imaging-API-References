---
title: "StreamReadException"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La excepción de lectura de flujo."
type: docs
weight: 25
url: /es/java/com.aspose.imaging.coreexceptions/streamreadexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.imaging.coreexceptions.FrameworkException](../../com.aspose.imaging.coreexceptions/frameworkexception)
```
public class StreamReadException extends FrameworkException
```

La excepción de lectura de flujo. Se produce cuando la lectura del flujo falla debido a una solicitud de desplazamiento y recuento de bytes incorrectos.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [StreamReadException(String message)](#StreamReadException-java.lang.String-) | Inicializa una nueva instancia de la clase `StreamReadException`. |
| [StreamReadException(String message, Throwable innerException)](#StreamReadException-java.lang.String-java.lang.Throwable-) | Inicializa una nueva instancia de la clase `StreamReadException`. |
| [StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount)](#StreamReadException-java.lang.String-java.lang.Throwable-int-int-) | Inicializa una nueva instancia de la clase `StreamReadException`. |
| [StreamReadException(String message, int expectedReadCount, int actualReadCount)](#StreamReadException-java.lang.String-int-int-) | Inicializa una nueva instancia de la clase `StreamReadException`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getExpectedReadCount()](#getExpectedReadCount--) | Obtiene el recuento de bytes de lectura esperado. |
| [getActualReadCount()](#getActualReadCount--) | Obtiene el recuento de bytes de lectura real. |
### StreamReadException(String message) {#StreamReadException-java.lang.String-}
```
public StreamReadException(String message)
```


Inicializa una nueva instancia de la clase `StreamReadException`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mensaje | java.lang.String | El mensaje. |

### StreamReadException(String message, Throwable innerException) {#StreamReadException-java.lang.String-java.lang.Throwable-}
```
public StreamReadException(String message, Throwable innerException)
```


Inicializa una nueva instancia de la clase `StreamReadException`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mensaje | java.lang.String | El mensaje. |
| innerException | java.lang.Throwable | La excepción interna. |

### StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount) {#StreamReadException-java.lang.String-java.lang.Throwable-int-int-}
```
public StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount)
```


Inicializa una nueva instancia de la clase `StreamReadException`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mensaje | java.lang.String | El mensaje. |
| innerException | java.lang.Throwable | La excepción interna. |
| expectedReadCount | int | El recuento de lectura esperado. |
| actualReadCount | int | El recuento de lectura real. |

### StreamReadException(String message, int expectedReadCount, int actualReadCount) {#StreamReadException-java.lang.String-int-int-}
```
public StreamReadException(String message, int expectedReadCount, int actualReadCount)
```


Inicializa una nueva instancia de la clase `StreamReadException`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mensaje | java.lang.String | El mensaje. |
| expectedReadCount | int | El recuento de lectura esperado. |
| actualReadCount | int | El recuento de lectura real. |

### getExpectedReadCount() {#getExpectedReadCount--}
```
public int getExpectedReadCount()
```


Obtiene el recuento de bytes de lectura esperado.

**Returns:**
int - El recuento de bytes de lectura esperado.
### getActualReadCount() {#getActualReadCount--}
```
public int getActualReadCount()
```


Obtiene el recuento de bytes de lectura real.

**Returns:**
int - El recuento de bytes de lectura real.
