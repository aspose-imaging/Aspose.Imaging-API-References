---
title: "LimitMemoryException"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Speicher‑Grenzwert‑Ausnahme."
type: docs
weight: 21
url: /de/java/com.aspose.imaging.coreexceptions/limitmemoryexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Error, java.lang.VirtualMachineError, java.lang.OutOfMemoryError, com.aspose.ms.System.OutOfMemoryException
```
public class LimitMemoryException extends System.OutOfMemoryException
```

Die Speicherbegrenzungs‑Ausnahme. Tritt auf, wenn die Speichernutzung reduziert werden sollte.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [LimitMemoryException(String message)](#LimitMemoryException-java.lang.String-) | Initialisiert eine neue Instanz der `LimitMemoryException` Klasse. |
| [LimitMemoryException(String message, Throwable innerException)](#LimitMemoryException-java.lang.String-java.lang.Throwable-) | Initialisiert eine neue Instanz der `LimitMemoryException` Klasse. |
| [LimitMemoryException(String message, long reduceMemoryFactor)](#LimitMemoryException-java.lang.String-long-) | Initialisiert eine neue Instanz der `LimitMemoryException` Klasse. |
| [LimitMemoryException(String message, Throwable innerException, int reduceMemoryFactor)](#LimitMemoryException-java.lang.String-java.lang.Throwable-int-) | Initialisiert eine neue Instanz der `LimitMemoryException` Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getReduceMemoryFactor()](#getReduceMemoryFactor--) | Liest oder setzt den ReduzierSpeicher‑Faktor. |
| [setReduceMemoryFactor(long value)](#setReduceMemoryFactor-long-) | Liest oder setzt den ReduzierSpeicher‑Faktor. |
### LimitMemoryException(String message) {#LimitMemoryException-java.lang.String-}
```
public LimitMemoryException(String message)
```


Initialisiert eine neue Instanz der `LimitMemoryException` Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Nachricht | java.lang.String | Die Ausnahmemeldung. |

### LimitMemoryException(String message, Throwable innerException) {#LimitMemoryException-java.lang.String-java.lang.Throwable-}
```
public LimitMemoryException(String message, Throwable innerException)
```


Initialisiert eine neue Instanz der `LimitMemoryException` Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Nachricht | java.lang.String | Die Ausnahmemeldung. |
| innerException | java.lang.Throwable | Die innere Ausnahme. |

### LimitMemoryException(String message, long reduceMemoryFactor) {#LimitMemoryException-java.lang.String-long-}
```
public LimitMemoryException(String message, long reduceMemoryFactor)
```


Initialisiert eine neue Instanz der `LimitMemoryException` Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Nachricht | java.lang.String | Die Ausnahmemeldung. |
| reduceMemoryFactor | long | Der ReduzierSpeicher‑Faktor. |

### LimitMemoryException(String message, Throwable innerException, int reduceMemoryFactor) {#LimitMemoryException-java.lang.String-java.lang.Throwable-int-}
```
public LimitMemoryException(String message, Throwable innerException, int reduceMemoryFactor)
```


Initialisiert eine neue Instanz der `LimitMemoryException` Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Nachricht | java.lang.String | Die Ausnahmemeldung. |
| innerException | java.lang.Throwable | Die innere Ausnahme. |
| reduceMemoryFactor | int | Der ReduzierSpeicher‑Faktor. |

### getReduceMemoryFactor() {#getReduceMemoryFactor--}
```
public long getReduceMemoryFactor()
```


Liest oder setzt den ReduzierSpeicher‑Faktor.

Wert: Der reduzierte Speicherfaktor.

**Returns:**
long
### setReduceMemoryFactor(long value) {#setReduceMemoryFactor-long-}
```
public void setReduceMemoryFactor(long value)
```


Liest oder setzt den ReduzierSpeicher‑Faktor.

Wert: Der reduzierte Speicherfaktor.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

