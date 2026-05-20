---
title: "StreamReadException"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'eccezione di lettura del flusso."
type: docs
weight: 25
url: /it/java/com.aspose.imaging.coreexceptions/streamreadexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.imaging.coreexceptions.FrameworkException](../../com.aspose.imaging.coreexceptions/frameworkexception)
```
public class StreamReadException extends FrameworkException
```

L'eccezione di lettura del flusso. Si verifica quando la lettura del flusso fallisce a causa di un offset errato e di una richiesta di conteggio dei byte.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [StreamReadException(String message)](#StreamReadException-java.lang.String-) | Inizializza una nuova istanza della classe `StreamReadException`. |
| [StreamReadException(String message, Throwable innerException)](#StreamReadException-java.lang.String-java.lang.Throwable-) | Inizializza una nuova istanza della classe `StreamReadException`. |
| [StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount)](#StreamReadException-java.lang.String-java.lang.Throwable-int-int-) | Inizializza una nuova istanza della classe `StreamReadException`. |
| [StreamReadException(String message, int expectedReadCount, int actualReadCount)](#StreamReadException-java.lang.String-int-int-) | Inizializza una nuova istanza della classe `StreamReadException`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getExpectedReadCount()](#getExpectedReadCount--) | Restituisce il conteggio dei byte di lettura previsto. |
| [getActualReadCount()](#getActualReadCount--) | Restituisce il conteggio dei byte di lettura effettivo. |
### StreamReadException(String message) {#StreamReadException-java.lang.String-}
```
public StreamReadException(String message)
```


Inizializza una nuova istanza della classe `StreamReadException`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| message | java.lang.String | Il messaggio. |

### StreamReadException(String message, Throwable innerException) {#StreamReadException-java.lang.String-java.lang.Throwable-}
```
public StreamReadException(String message, Throwable innerException)
```


Inizializza una nuova istanza della classe `StreamReadException`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| message | java.lang.String | Il messaggio. |
| innerException | java.lang.Throwable | L'eccezione interna. |

### StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount) {#StreamReadException-java.lang.String-java.lang.Throwable-int-int-}
```
public StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount)
```


Inizializza una nuova istanza della classe `StreamReadException`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| message | java.lang.String | Il messaggio. |
| innerException | java.lang.Throwable | L'eccezione interna. |
| expectedReadCount | int | Il conteggio di lettura previsto. |
| actualReadCount | int | Il conteggio di lettura effettivo. |

### StreamReadException(String message, int expectedReadCount, int actualReadCount) {#StreamReadException-java.lang.String-int-int-}
```
public StreamReadException(String message, int expectedReadCount, int actualReadCount)
```


Inizializza una nuova istanza della classe `StreamReadException`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| message | java.lang.String | Il messaggio. |
| expectedReadCount | int | Il conteggio di lettura previsto. |
| actualReadCount | int | Il conteggio di lettura effettivo. |

### getExpectedReadCount() {#getExpectedReadCount--}
```
public int getExpectedReadCount()
```


Restituisce il conteggio dei byte di lettura previsto.

**Returns:**
int - Il conteggio dei byte di lettura previsto.
### getActualReadCount() {#getActualReadCount--}
```
public int getActualReadCount()
```


Restituisce il conteggio dei byte di lettura effettivo.

**Returns:**
int - Il conteggio dei byte di lettura effettivo.
