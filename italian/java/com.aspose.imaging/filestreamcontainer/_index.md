---
title: "FileStreamContainer"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Classe di supporto per l'elaborazione del flusso di file."
type: docs
weight: 46
url: /it/java/com.aspose.imaging/filestreamcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.StreamContainer](../../com.aspose.imaging/streamcontainer)
```
public final class FileStreamContainer extends StreamContainer
```

Classe di supporto per l'elaborazione del flusso di file.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [to_Stream(FileStreamContainer fileStreamContainer)](#to-Stream-com.aspose.imaging.FileStreamContainer-) | Esegue una conversione esplicita da `com.aspose.imaging.FileStreamContainer` a `System.IO.Stream`. |
| [to_FileStream(FileStreamContainer fileStreamContainer)](#to-FileStream-com.aspose.imaging.FileStreamContainer-) | Esegue una conversione esplicita da `com.aspose.imaging.FileStreamContainer` a `System.IO.FileStream`. |
| [createFileStream(String fileLocation, boolean isTemporal)](#createFileStream-java.lang.String-boolean-) | Crea un nuovo stream di file. |
| [openFileStream(String fileLocation)](#openFileStream-java.lang.String-) | Apre un stream di file esistente. |
| [isTemporal()](#isTemporal--) | Ottiene o imposta un valore che indica se lo stream è temporale. |
| [setTemporal(boolean value)](#setTemporal-boolean-) | Imposta un valore che indica se lo stream è temporale. |
| [isCreated()](#isCreated--) | Ottiene un valore che indica se lo stream è stato creato esplicitamente. |
| [getFilePath()](#getFilePath--) | Ottiene il percorso del file. |
### to_Stream(FileStreamContainer fileStreamContainer) {#to-Stream-com.aspose.imaging.FileStreamContainer-}
```
public static System.IO.Stream to_Stream(FileStreamContainer fileStreamContainer)
```


Esegue una conversione esplicita da `com.aspose.imaging.FileStreamContainer` a `System.IO.Stream`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) | Il contenitore del file stream. |

**Returns:**
com.aspose.ms.System.IO.Stream - Il risultato della conversione.
### to_FileStream(FileStreamContainer fileStreamContainer) {#to-FileStream-com.aspose.imaging.FileStreamContainer-}
```
public static System.IO.FileStream to_FileStream(FileStreamContainer fileStreamContainer)
```


Esegue una conversione esplicita da `com.aspose.imaging.FileStreamContainer` a `System.IO.FileStream`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) | Il contenitore del file stream. |

**Returns:**
com.aspose.ms.System.IO.FileStream - Il risultato della conversione.
### createFileStream(String fileLocation, boolean isTemporal) {#createFileStream-java.lang.String-boolean-}
```
public static FileStreamContainer createFileStream(String fileLocation, boolean isTemporal)
```


Crea un nuovo stream di file.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileLocation | java.lang.String | La posizione del file. |
| isTemporal | boolean | Se impostato su `true` il contenitore del flusso file è temporale. |

**Returns:**
[FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) - The file stream container.
### openFileStream(String fileLocation) {#openFileStream-java.lang.String-}
```
public static FileStreamContainer openFileStream(String fileLocation)
```


Apre un flusso file esistente. Se il flusso file non esiste viene lanciata l'eccezione appropriata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileLocation | java.lang.String | La posizione del file. |

**Returns:**
[FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) - The file stream container.
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


Ottiene o imposta un valore che indica se lo stream è temporale.

**Returns:**
boolean - `true` se il flusso è temporale; altrimenti, `false`.

Un flusso temporale si rimuoverà da solo quando viene eliminato. Se il flusso è basato su memoria questa proprietà non ha effetto. Il flusso può essere contrassegnato come temporale o persistente nel caso sia stato creato esplicitamente, altrimenti viene lanciata l'eccezione appropriata.
### setTemporal(boolean value) {#setTemporal-boolean-}
```
public void setTemporal(boolean value)
```


Imposta un valore che indica se lo stream è temporale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | `true` se il flusso è temporale; altrimenti, `false`. |

Un flusso temporale si rimuoverà da solo quando viene eliminato. Se il flusso è basato su memoria questa proprietà non ha effetto. Il flusso può essere contrassegnato come temporale o persistente nel caso sia stato creato esplicitamente, altrimenti viene lanciata l'eccezione appropriata. |

### isCreated() {#isCreated--}
```
public boolean isCreated()
```


Ottiene un valore che indica se lo stream è stato creato esplicitamente.

**Returns:**
boolean - `true` se il flusso è stato creato esplicitamente; altrimenti, `false`.
### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Ottiene il percorso del file.

**Returns:**
java.lang.String - Il percorso del file.
