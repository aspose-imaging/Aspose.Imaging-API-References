---
title: "FileStreamContainer"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Hilfsklasse für die Verarbeitung von Dateistreams."
type: docs
weight: 46
url: /de/java/com.aspose.imaging/filestreamcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.StreamContainer](../../com.aspose.imaging/streamcontainer)
```
public final class FileStreamContainer extends StreamContainer
```

Hilfsklasse für die Verarbeitung von Dateistreams.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [to_Stream(FileStreamContainer fileStreamContainer)](#to-Stream-com.aspose.imaging.FileStreamContainer-) | Führt eine explizite Konvertierung von `com.aspose.imaging.FileStreamContainer` zu `System.IO.Stream` durch. |
| [to_FileStream(FileStreamContainer fileStreamContainer)](#to-FileStream-com.aspose.imaging.FileStreamContainer-) | Führt eine explizite Konvertierung von `com.aspose.imaging.FileStreamContainer` zu `System.IO.FileStream` durch. |
| [createFileStream(String fileLocation, boolean isTemporal)](#createFileStream-java.lang.String-boolean-) | Erstellt einen neuen Dateistream. |
| [openFileStream(String fileLocation)](#openFileStream-java.lang.String-) | Öffnet einen vorhandenen Dateistream. |
| [isTemporal()](#isTemporal--) | Liest oder setzt einen Wert, der angibt, ob der Stream temporär ist. |
| [setTemporal(boolean value)](#setTemporal-boolean-) | Setzt einen Wert, der angibt, ob der Stream temporär ist. |
| [isCreated()](#isCreated--) | Liest einen Wert, der angibt, ob der Stream explizit erstellt wurde. |
| [getFilePath()](#getFilePath--) | Liest den Dateipfad. |
### to_Stream(FileStreamContainer fileStreamContainer) {#to-Stream-com.aspose.imaging.FileStreamContainer-}
```
public static System.IO.Stream to_Stream(FileStreamContainer fileStreamContainer)
```


Führt eine explizite Konvertierung von `com.aspose.imaging.FileStreamContainer` zu `System.IO.Stream` durch.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) | Der Dateistream-Container. |

**Returns:**
com.aspose.ms.System.IO.Stream - Das Ergebnis der Konvertierung.
### to_FileStream(FileStreamContainer fileStreamContainer) {#to-FileStream-com.aspose.imaging.FileStreamContainer-}
```
public static System.IO.FileStream to_FileStream(FileStreamContainer fileStreamContainer)
```


Führt eine explizite Konvertierung von `com.aspose.imaging.FileStreamContainer` zu `System.IO.FileStream` durch.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) | Der Dateistream-Container. |

**Returns:**
com.aspose.ms.System.IO.FileStream - Das Ergebnis der Konvertierung.
### createFileStream(String fileLocation, boolean isTemporal) {#createFileStream-java.lang.String-boolean-}
```
public static FileStreamContainer createFileStream(String fileLocation, boolean isTemporal)
```


Erstellt einen neuen Dateistream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileLocation | java.lang.String | Der Dateistandort. |
| isTemporal | boolean | Wenn auf `true` gesetzt, ist der Dateistream-Container temporär. |

**Returns:**
[FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) - The file stream container.
### openFileStream(String fileLocation) {#openFileStream-java.lang.String-}
```
public static FileStreamContainer openFileStream(String fileLocation)
```


Öffnet einen vorhandenen Dateistream. Wenn der Dateistream nicht existiert, wird die entsprechende Ausnahme ausgelöst.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileLocation | java.lang.String | Der Dateistandort. |

**Returns:**
[FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) - The file stream container.
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


Liest oder setzt einen Wert, der angibt, ob der Stream temporär ist.

**Returns:**
boolean - `true`, wenn der Stream temporär ist; andernfalls `false`.

Ein temporärer Stream entfernt sich selbst, wenn er freigegeben wird. Wenn der Stream speicherbasiert ist, hat diese Eigenschaft keine Wirkung. Der Stream kann als temporär oder persistent markiert werden, falls er explizit erstellt wurde; andernfalls wird die entsprechende Ausnahme ausgelöst.
### setTemporal(boolean value) {#setTemporal-boolean-}
```
public void setTemporal(boolean value)
```


Setzt einen Wert, der angibt, ob der Stream temporär ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | `true`, wenn der Stream temporär ist; andernfalls `false`. |

Ein temporärer Stream entfernt sich selbst, wenn er freigegeben wird. Wenn der Stream speicherbasiert ist, hat diese Eigenschaft keine Wirkung. Der Stream kann als temporär oder persistent markiert werden, falls er explizit erstellt wurde; andernfalls wird die entsprechende Ausnahme ausgelöst. |

### isCreated() {#isCreated--}
```
public boolean isCreated()
```


Liest einen Wert, der angibt, ob der Stream explizit erstellt wurde.

**Returns:**
boolean - `true`, wenn der Stream explizit erstellt wurde; andernfalls `false`.
### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Liest den Dateipfad.

**Returns:**
java.lang.String - Der Dateipfad.
