---
title: "FileOpenSource"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta una sorgente file per l'apertura."
type: docs
weight: 11
url: /it/java/com.aspose.imaging.sources/fileopensource/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.Source](../../com.aspose.imaging/source), [com.aspose.imaging.sources.FileSource](../../com.aspose.imaging.sources/filesource)
```
public final class FileOpenSource extends FileSource
```

Rappresenta una sorgente file per l'apertura.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FileOpenSource(String filePath)](#FileOpenSource-java.lang.String-) | Inizializza una nuova istanza della classe `FileOpenSource`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFilePath()](#getFilePath--) | Ottiene il percorso del file da aprire. |
| [isTemporal()](#isTemporal--) | Ottiene un valore che indica se il file sarà temporaneo. |
| [getStreamContainer()](#getStreamContainer--) | Ottiene il contenitore di flusso. |
### FileOpenSource(String filePath) {#FileOpenSource-java.lang.String-}
```
public FileOpenSource(String filePath)
```


Inizializza una nuova istanza della classe `FileOpenSource`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file da aprire. |

### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Ottiene il percorso del file da aprire.

Valore: Il percorso del file da aprire.

**Returns:**
java.lang.String
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


Ottiene un valore che indica se il file sarà temporaneo.

Valore: `true` se il file sarà temporaneo; altrimenti, `false`.

**Returns:**
boolean
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


Ottiene il contenitore di flusso.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - the stream container.

Usare con cautela. Sarà necessario eliminare il contenitore di flusso dopo il recupero.
