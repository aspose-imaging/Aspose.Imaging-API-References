---
title: "TiffImageException"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Tiff-Bildausnahme"
type: docs
weight: 21
url: /de/java/com.aspose.imaging.coreexceptions.imageformats/tiffimageexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.imaging.coreexceptions.ImageException](../../com.aspose.imaging.coreexceptions/imageexception)
```
public class TiffImageException extends ImageException
```

Die Tiff-Bildausnahme
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TiffImageException(String message)](#TiffImageException-java.lang.String-) | Initialisiert eine neue Instanz der `TiffImageException`-Klasse. |
| [TiffImageException(String message, Throwable innerException)](#TiffImageException-java.lang.String-java.lang.Throwable-) | Initialisiert eine neue Instanz der `TiffImageException`-Klasse. |
| [TiffImageException(String message, int error)](#TiffImageException-java.lang.String-int-) | Initialisiert eine neue Instanz der `TiffImageException`-Klasse. |
| [TiffImageException(int error)](#TiffImageException-int-) | Initialisiert eine neue Instanz der `TiffImageException`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getOptionsError()](#getOptionsError--) | Ermittelt den TIFF-Optionen-Fehler. |
### TiffImageException(String message) {#TiffImageException-java.lang.String-}
```
public TiffImageException(String message)
```


Initialisiert eine neue Instanz der `TiffImageException`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Nachricht | java.lang.String | Die Ausnahmemeldung. |

### TiffImageException(String message, Throwable innerException) {#TiffImageException-java.lang.String-java.lang.Throwable-}
```
public TiffImageException(String message, Throwable innerException)
```


Initialisiert eine neue Instanz der `TiffImageException`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Nachricht | java.lang.String | Die Meldung. |
| innerException | java.lang.Throwable | Die innere Ausnahme. |

### TiffImageException(String message, int error) {#TiffImageException-java.lang.String-int-}
```
public TiffImageException(String message, int error)
```


Initialisiert eine neue Instanz der `TiffImageException`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Nachricht | java.lang.String | Die Meldung. |
| Fehler | int | Der Fehler. |

### TiffImageException(int error) {#TiffImageException-int-}
```
public TiffImageException(int error)
```


Initialisiert eine neue Instanz der `TiffImageException`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fehler | int | Der Fehler. |

### getOptionsError() {#getOptionsError--}
```
public int getOptionsError()
```


Ermittelt den TIFF-Optionen-Fehler.

Wert: Der TIFF-Optionen-Fehler.

**Returns:**
int
