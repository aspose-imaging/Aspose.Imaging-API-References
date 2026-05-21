---
title: "StreamReadException"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Stream‑Lese‑Ausnahme."
type: docs
weight: 25
url: /de/java/com.aspose.imaging.coreexceptions/streamreadexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.imaging.coreexceptions.FrameworkException](../../com.aspose.imaging.coreexceptions/frameworkexception)
```
public class StreamReadException extends FrameworkException
```

Die Ausnahme beim Lesen des Streams. Tritt auf, wenn das Lesen des Streams aufgrund einer falschen Offset‑ und Byte‑Zählungsanforderung fehlgeschlagen ist.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [StreamReadException(String message)](#StreamReadException-java.lang.String-) | Initialisiert eine neue Instanz der `StreamReadException`‑Klasse. |
| [StreamReadException(String message, Throwable innerException)](#StreamReadException-java.lang.String-java.lang.Throwable-) | Initialisiert eine neue Instanz der `StreamReadException`‑Klasse. |
| [StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount)](#StreamReadException-java.lang.String-java.lang.Throwable-int-int-) | Initialisiert eine neue Instanz der `StreamReadException`‑Klasse. |
| [StreamReadException(String message, int expectedReadCount, int actualReadCount)](#StreamReadException-java.lang.String-int-int-) | Initialisiert eine neue Instanz der `StreamReadException`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getExpectedReadCount()](#getExpectedReadCount--) | Gibt die erwartete Anzahl gelesener Bytes zurück. |
| [getActualReadCount()](#getActualReadCount--) | Gibt die tatsächliche Anzahl gelesener Bytes zurück. |
### StreamReadException(String message) {#StreamReadException-java.lang.String-}
```
public StreamReadException(String message)
```


Initialisiert eine neue Instanz der `StreamReadException`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Nachricht | java.lang.String | Die Meldung. |

### StreamReadException(String message, Throwable innerException) {#StreamReadException-java.lang.String-java.lang.Throwable-}
```
public StreamReadException(String message, Throwable innerException)
```


Initialisiert eine neue Instanz der `StreamReadException`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Nachricht | java.lang.String | Die Meldung. |
| innerException | java.lang.Throwable | Die innere Ausnahme. |

### StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount) {#StreamReadException-java.lang.String-java.lang.Throwable-int-int-}
```
public StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount)
```


Initialisiert eine neue Instanz der `StreamReadException`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Nachricht | java.lang.String | Die Meldung. |
| innerException | java.lang.Throwable | Die innere Ausnahme. |
| expectedReadCount | int | Die erwartete Lesemenge. |
| actualReadCount | int | Die tatsächliche Lesemenge. |

### StreamReadException(String message, int expectedReadCount, int actualReadCount) {#StreamReadException-java.lang.String-int-int-}
```
public StreamReadException(String message, int expectedReadCount, int actualReadCount)
```


Initialisiert eine neue Instanz der `StreamReadException`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Nachricht | java.lang.String | Die Meldung. |
| expectedReadCount | int | Die erwartete Lesemenge. |
| actualReadCount | int | Die tatsächliche Lesemenge. |

### getExpectedReadCount() {#getExpectedReadCount--}
```
public int getExpectedReadCount()
```


Gibt die erwartete Anzahl gelesener Bytes zurück.

**Returns:**
int – Die erwartete Anzahl gelesener Bytes.
### getActualReadCount() {#getActualReadCount--}
```
public int getActualReadCount()
```


Gibt die tatsächliche Anzahl gelesener Bytes zurück.

**Returns:**
int – Die tatsächliche Anzahl gelesener Bytes.
