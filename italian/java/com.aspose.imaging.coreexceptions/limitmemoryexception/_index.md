---
title: "LimitMemoryException"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'eccezione di memoria limitata."
type: docs
weight: 21
url: /it/java/com.aspose.imaging.coreexceptions/limitmemoryexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Error, java.lang.VirtualMachineError, java.lang.OutOfMemoryError, com.aspose.ms.System.OutOfMemoryException
```
public class LimitMemoryException extends System.OutOfMemoryException
```

L'eccezione di memoria limitata. Si verifica quando l'uso della memoria dovrebbe essere ridotto.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [LimitMemoryException(String message)](#LimitMemoryException-java.lang.String-) | Inizializza una nuova istanza della classe `LimitMemoryException`. |
| [LimitMemoryException(String message, Throwable innerException)](#LimitMemoryException-java.lang.String-java.lang.Throwable-) | Inizializza una nuova istanza della classe `LimitMemoryException`. |
| [LimitMemoryException(String message, long reduceMemoryFactor)](#LimitMemoryException-java.lang.String-long-) | Inizializza una nuova istanza della classe `LimitMemoryException`. |
| [LimitMemoryException(String message, Throwable innerException, int reduceMemoryFactor)](#LimitMemoryException-java.lang.String-java.lang.Throwable-int-) | Inizializza una nuova istanza della classe `LimitMemoryException`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getReduceMemoryFactor()](#getReduceMemoryFactor--) | Ottiene o imposta il fattore di riduzione della memoria. |
| [setReduceMemoryFactor(long value)](#setReduceMemoryFactor-long-) | Ottiene o imposta il fattore di riduzione della memoria. |
### LimitMemoryException(String message) {#LimitMemoryException-java.lang.String-}
```
public LimitMemoryException(String message)
```


Inizializza una nuova istanza della classe `LimitMemoryException`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| message | java.lang.String | Il messaggio dell'eccezione. |

### LimitMemoryException(String message, Throwable innerException) {#LimitMemoryException-java.lang.String-java.lang.Throwable-}
```
public LimitMemoryException(String message, Throwable innerException)
```


Inizializza una nuova istanza della classe `LimitMemoryException`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| message | java.lang.String | Il messaggio dell'eccezione. |
| innerException | java.lang.Throwable | L'eccezione interna. |

### LimitMemoryException(String message, long reduceMemoryFactor) {#LimitMemoryException-java.lang.String-long-}
```
public LimitMemoryException(String message, long reduceMemoryFactor)
```


Inizializza una nuova istanza della classe `LimitMemoryException`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| message | java.lang.String | Il messaggio dell'eccezione. |
| reduceMemoryFactor | long | Il fattore di riduzione della memoria. |

### LimitMemoryException(String message, Throwable innerException, int reduceMemoryFactor) {#LimitMemoryException-java.lang.String-java.lang.Throwable-int-}
```
public LimitMemoryException(String message, Throwable innerException, int reduceMemoryFactor)
```


Inizializza una nuova istanza della classe `LimitMemoryException`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| message | java.lang.String | Il messaggio dell'eccezione. |
| innerException | java.lang.Throwable | L'eccezione interna. |
| reduceMemoryFactor | int | Il fattore di riduzione della memoria. |

### getReduceMemoryFactor() {#getReduceMemoryFactor--}
```
public long getReduceMemoryFactor()
```


Ottiene o imposta il fattore di riduzione della memoria.

Valore: Il fattore di riduzione della memoria.

**Returns:**
long
### setReduceMemoryFactor(long value) {#setReduceMemoryFactor-long-}
```
public void setReduceMemoryFactor(long value)
```


Ottiene o imposta il fattore di riduzione della memoria.

Valore: Il fattore di riduzione della memoria.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

