---
title: "StreamReadException"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'exception de lecture du flux."
type: docs
weight: 25
url: /fr/java/com.aspose.imaging.coreexceptions/streamreadexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.imaging.coreexceptions.FrameworkException](../../com.aspose.imaging.coreexceptions/frameworkexception)
```
public class StreamReadException extends FrameworkException
```

L'exception de lecture du flux. Causée lorsque la lecture du flux a échoué en raison d'un décalage incorrect et d'une demande de nombre d'octets.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [StreamReadException(String message)](#StreamReadException-java.lang.String-) | Initialise une nouvelle instance de la classe `StreamReadException`. |
| [StreamReadException(String message, Throwable innerException)](#StreamReadException-java.lang.String-java.lang.Throwable-) | Initialise une nouvelle instance de la classe `StreamReadException`. |
| [StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount)](#StreamReadException-java.lang.String-java.lang.Throwable-int-int-) | Initialise une nouvelle instance de la classe `StreamReadException`. |
| [StreamReadException(String message, int expectedReadCount, int actualReadCount)](#StreamReadException-java.lang.String-int-int-) | Initialise une nouvelle instance de la classe `StreamReadException`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getExpectedReadCount()](#getExpectedReadCount--) | Obtient le nombre d'octets attendus à lire. |
| [getActualReadCount()](#getActualReadCount--) | Obtient le nombre d'octets réellement lus. |
### StreamReadException(String message) {#StreamReadException-java.lang.String-}
```
public StreamReadException(String message)
```


Initialise une nouvelle instance de la classe `StreamReadException`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Le message. |

### StreamReadException(String message, Throwable innerException) {#StreamReadException-java.lang.String-java.lang.Throwable-}
```
public StreamReadException(String message, Throwable innerException)
```


Initialise une nouvelle instance de la classe `StreamReadException`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Le message. |
| innerException | java.lang.Throwable | L'exception interne. |

### StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount) {#StreamReadException-java.lang.String-java.lang.Throwable-int-int-}
```
public StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount)
```


Initialise une nouvelle instance de la classe `StreamReadException`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Le message. |
| innerException | java.lang.Throwable | L'exception interne. |
| expectedReadCount | int | Le nombre de lectures attendu. |
| actualReadCount | int | Le nombre de lectures réel. |

### StreamReadException(String message, int expectedReadCount, int actualReadCount) {#StreamReadException-java.lang.String-int-int-}
```
public StreamReadException(String message, int expectedReadCount, int actualReadCount)
```


Initialise une nouvelle instance de la classe `StreamReadException`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Le message. |
| expectedReadCount | int | Le nombre de lectures attendu. |
| actualReadCount | int | Le nombre de lectures réel. |

### getExpectedReadCount() {#getExpectedReadCount--}
```
public int getExpectedReadCount()
```


Obtient le nombre d'octets attendus à lire.

**Returns:**
int - Le nombre d'octets attendus à lire.
### getActualReadCount() {#getActualReadCount--}
```
public int getActualReadCount()
```


Obtient le nombre d'octets réellement lus.

**Returns:**
int - Le nombre d'octets réellement lus.
