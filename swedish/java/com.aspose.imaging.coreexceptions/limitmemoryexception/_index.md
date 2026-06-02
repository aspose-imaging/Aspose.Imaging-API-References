---
title: "LimitMemoryException"
second_title: "Aspose.Imaging för Java API-referens"
description: "Undantaget för minnesgräns."
type: docs
weight: 21
url: /sv/java/com.aspose.imaging.coreexceptions/limitmemoryexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Error, java.lang.VirtualMachineError, java.lang.OutOfMemoryError, com.aspose.ms.System.OutOfMemoryException
```
public class LimitMemoryException extends System.OutOfMemoryException
```

Minnesbegränsningsundantaget. Förekommer när minnesanvändning bör minskas.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [LimitMemoryException(String message)](#LimitMemoryException-java.lang.String-) | Initierar en ny instans av klassen `LimitMemoryException`. |
| [LimitMemoryException(String message, Throwable innerException)](#LimitMemoryException-java.lang.String-java.lang.Throwable-) | Initierar en ny instans av klassen `LimitMemoryException`. |
| [LimitMemoryException(String message, long reduceMemoryFactor)](#LimitMemoryException-java.lang.String-long-) | Initierar en ny instans av klassen `LimitMemoryException`. |
| [LimitMemoryException(String message, Throwable innerException, int reduceMemoryFactor)](#LimitMemoryException-java.lang.String-java.lang.Throwable-int-) | Initierar en ny instans av klassen `LimitMemoryException`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getReduceMemoryFactor()](#getReduceMemoryFactor--) | Hämtar eller anger minnesreduceringsfaktorn. |
| [setReduceMemoryFactor(long value)](#setReduceMemoryFactor-long-) | Hämtar eller anger minnesreduceringsfaktorn. |
### LimitMemoryException(String message) {#LimitMemoryException-java.lang.String-}
```
public LimitMemoryException(String message)
```


Initierar en ny instans av klassen `LimitMemoryException`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meddelande | java.lang.String | Undantagsmeddelandet. |

### LimitMemoryException(String message, Throwable innerException) {#LimitMemoryException-java.lang.String-java.lang.Throwable-}
```
public LimitMemoryException(String message, Throwable innerException)
```


Initierar en ny instans av klassen `LimitMemoryException`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meddelande | java.lang.String | Undantagsmeddelandet. |
| innerException | java.lang.Throwable | Det inre undantaget. |

### LimitMemoryException(String message, long reduceMemoryFactor) {#LimitMemoryException-java.lang.String-long-}
```
public LimitMemoryException(String message, long reduceMemoryFactor)
```


Initierar en ny instans av klassen `LimitMemoryException`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meddelande | java.lang.String | Undantagsmeddelandet. |
| reduceMemoryFactor | long | Minnesreduceringsfaktorn. |

### LimitMemoryException(String message, Throwable innerException, int reduceMemoryFactor) {#LimitMemoryException-java.lang.String-java.lang.Throwable-int-}
```
public LimitMemoryException(String message, Throwable innerException, int reduceMemoryFactor)
```


Initierar en ny instans av klassen `LimitMemoryException`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meddelande | java.lang.String | Undantagsmeddelandet. |
| innerException | java.lang.Throwable | Det inre undantaget. |
| reduceMemoryFactor | int | Minnesreduceringsfaktorn. |

### getReduceMemoryFactor() {#getReduceMemoryFactor--}
```
public long getReduceMemoryFactor()
```


Hämtar eller anger minnesreduceringsfaktorn.

Värde: Den reducerade minnesfaktorn.

**Returns:**
long
### setReduceMemoryFactor(long value) {#setReduceMemoryFactor-long-}
```
public void setReduceMemoryFactor(long value)
```


Hämtar eller anger minnesreduceringsfaktorn.

Värde: Den reducerade minnesfaktorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

