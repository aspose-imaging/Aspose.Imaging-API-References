---
title: "FileStreamContainer"
second_title: "Aspose.Imaging för Java API-referens"
description: "Hjälparklass för filströmshantering."
type: docs
weight: 46
url: /sv/java/com.aspose.imaging/filestreamcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.StreamContainer](../../com.aspose.imaging/streamcontainer)
```
public final class FileStreamContainer extends StreamContainer
```

Hjälparklass för filströmshantering.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [to_Stream(FileStreamContainer fileStreamContainer)](#to-Stream-com.aspose.imaging.FileStreamContainer-) | Utför en explicit konvertering från `com.aspose.imaging.FileStreamContainer` till `System.IO.Stream`. |
| [to_FileStream(FileStreamContainer fileStreamContainer)](#to-FileStream-com.aspose.imaging.FileStreamContainer-) | Utför en explicit konvertering från `com.aspose.imaging.FileStreamContainer` till `System.IO.FileStream`. |
| [createFileStream(String fileLocation, boolean isTemporal)](#createFileStream-java.lang.String-boolean-) | Skapar en ny filström. |
| [openFileStream(String fileLocation)](#openFileStream-java.lang.String-) | Öppnar en befintlig filström. |
| [isTemporal()](#isTemporal--) | Hämtar eller anger ett värde som indikerar om strömmen är temporär. |
| [setTemporal(boolean value)](#setTemporal-boolean-) | Anger ett värde som indikerar om strömmen är temporär. |
| [isCreated()](#isCreated--) | Hämtar ett värde som indikerar om strömmen skapades explicit. |
| [getFilePath()](#getFilePath--) | Hämtar filsökvägen. |
### to_Stream(FileStreamContainer fileStreamContainer) {#to-Stream-com.aspose.imaging.FileStreamContainer-}
```
public static System.IO.Stream to_Stream(FileStreamContainer fileStreamContainer)
```


Utför en explicit konvertering från `com.aspose.imaging.FileStreamContainer` till `System.IO.Stream`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) | Filströmbehållaren. |

**Returns:**
com.aspose.ms.System.IO.Stream - Resultatet av konverteringen.
### to_FileStream(FileStreamContainer fileStreamContainer) {#to-FileStream-com.aspose.imaging.FileStreamContainer-}
```
public static System.IO.FileStream to_FileStream(FileStreamContainer fileStreamContainer)
```


Utför en explicit konvertering från `com.aspose.imaging.FileStreamContainer` till `System.IO.FileStream`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) | Filströmbehållaren. |

**Returns:**
com.aspose.ms.System.IO.FileStream - Resultatet av konverteringen.
### createFileStream(String fileLocation, boolean isTemporal) {#createFileStream-java.lang.String-boolean-}
```
public static FileStreamContainer createFileStream(String fileLocation, boolean isTemporal)
```


Skapar en ny filström.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileLocation | java.lang.String | Filplatsen. |
| isTemporal | boolean | Om den är inställd på `true` är filströmbehållaren temporär. |

**Returns:**
[FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) - The file stream container.
### openFileStream(String fileLocation) {#openFileStream-java.lang.String-}
```
public static FileStreamContainer openFileStream(String fileLocation)
```


Öppnar en befintlig filström. Om filströmmen inte finns kastas lämpligt undantag.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileLocation | java.lang.String | Filplatsen. |

**Returns:**
[FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) - The file stream container.
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


Hämtar eller anger ett värde som indikerar om strömmen är temporär.

**Returns:**
boolean - `true` om strömmen är temporär; annars `false`.

En temporär ström tar bort sig själv när den frigörs. Om strömmen är minnesbaserad har denna egenskap ingen effekt. Strömmen kan markeras som temporär eller beständig om den skapades explicit, annars kastas lämpligt undantag.
### setTemporal(boolean value) {#setTemporal-boolean-}
```
public void setTemporal(boolean value)
```


Anger ett värde som indikerar om strömmen är temporär.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | `true` om strömmen är temporär; annars `false`. |

En temporär ström tar bort sig själv när den frigörs. Om strömmen är minnesbaserad har denna egenskap ingen effekt. Strömmen kan markeras som temporär eller beständig om den skapades explicit, annars kastas lämpligt undantag. |

### isCreated() {#isCreated--}
```
public boolean isCreated()
```


Hämtar ett värde som indikerar om strömmen skapades explicit.

**Returns:**
boolean - `true` om strömmen skapades explicit; annars `false`.
### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Hämtar filsökvägen.

**Returns:**
java.lang.String - Filens sökväg.
