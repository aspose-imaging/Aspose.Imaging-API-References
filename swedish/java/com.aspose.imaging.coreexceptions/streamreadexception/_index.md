---
title: "StreamReadException"
second_title: "Aspose.Imaging för Java API-referens"
description: "Undantaget för strömläsning."
type: docs
weight: 25
url: /sv/java/com.aspose.imaging.coreexceptions/streamreadexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.imaging.coreexceptions.FrameworkException](../../com.aspose.imaging.coreexceptions/frameworkexception)
```
public class StreamReadException extends FrameworkException
```

Strömavläsningsundantaget. Orsakat när strömavläsning misslyckades på grund av felaktig förskjutning och begäran om byteantal.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [StreamReadException(String message)](#StreamReadException-java.lang.String-) | Initierar en ny instans av klassen `StreamReadException`. |
| [StreamReadException(String message, Throwable innerException)](#StreamReadException-java.lang.String-java.lang.Throwable-) | Initierar en ny instans av klassen `StreamReadException`. |
| [StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount)](#StreamReadException-java.lang.String-java.lang.Throwable-int-int-) | Initierar en ny instans av klassen `StreamReadException`. |
| [StreamReadException(String message, int expectedReadCount, int actualReadCount)](#StreamReadException-java.lang.String-int-int-) | Initierar en ny instans av klassen `StreamReadException`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getExpectedReadCount()](#getExpectedReadCount--) | Hämtar det förväntade antalet lästa byte. |
| [getActualReadCount()](#getActualReadCount--) | Hämtar det faktiska antalet lästa byte. |
### StreamReadException(String message) {#StreamReadException-java.lang.String-}
```
public StreamReadException(String message)
```


Initierar en ny instans av klassen `StreamReadException`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meddelande | java.lang.String | Meddelandet. |

### StreamReadException(String message, Throwable innerException) {#StreamReadException-java.lang.String-java.lang.Throwable-}
```
public StreamReadException(String message, Throwable innerException)
```


Initierar en ny instans av klassen `StreamReadException`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meddelande | java.lang.String | Meddelandet. |
| innerException | java.lang.Throwable | Det inre undantaget. |

### StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount) {#StreamReadException-java.lang.String-java.lang.Throwable-int-int-}
```
public StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount)
```


Initierar en ny instans av klassen `StreamReadException`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meddelande | java.lang.String | Meddelandet. |
| innerException | java.lang.Throwable | Det inre undantaget. |
| expectedReadCount | int | Det förväntade läsantalet. |
| actualReadCount | int | Det faktiska läsantalet. |

### StreamReadException(String message, int expectedReadCount, int actualReadCount) {#StreamReadException-java.lang.String-int-int-}
```
public StreamReadException(String message, int expectedReadCount, int actualReadCount)
```


Initierar en ny instans av klassen `StreamReadException`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meddelande | java.lang.String | Meddelandet. |
| expectedReadCount | int | Det förväntade läsantalet. |
| actualReadCount | int | Det faktiska läsantalet. |

### getExpectedReadCount() {#getExpectedReadCount--}
```
public int getExpectedReadCount()
```


Hämtar det förväntade antalet lästa byte.

**Returns:**
int - Det förväntade antalet lästa byte.
### getActualReadCount() {#getActualReadCount--}
```
public int getActualReadCount()
```


Hämtar det faktiska antalet lästa byte.

**Returns:**
int - Det faktiska antalet lästa byte.
