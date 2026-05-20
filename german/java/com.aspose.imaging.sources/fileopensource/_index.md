---
title: "FileOpenSource"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt eine Dateiquelle zum Öffnen dar."
type: docs
weight: 11
url: /de/java/com.aspose.imaging.sources/fileopensource/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.Source](../../com.aspose.imaging/source), [com.aspose.imaging.sources.FileSource](../../com.aspose.imaging.sources/filesource)
```
public final class FileOpenSource extends FileSource
```

Stellt eine Dateiquelle zum Öffnen dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FileOpenSource(String filePath)](#FileOpenSource-java.lang.String-) | Initialisiert eine neue Instanz der `FileOpenSource`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFilePath()](#getFilePath--) | Ruft den Dateipfad zum Öffnen ab. |
| [isTemporal()](#isTemporal--) | Ruft einen Wert ab, der angibt, ob die Datei temporär ist. |
| [getStreamContainer()](#getStreamContainer--) | Ruft den Stream‑Container ab. |
### FileOpenSource(String filePath) {#FileOpenSource-java.lang.String-}
```
public FileOpenSource(String filePath)
```


Initialisiert eine neue Instanz der `FileOpenSource`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad zum Öffnen. |

### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Ruft den Dateipfad zum Öffnen ab.

Wert: Der Dateipfad zum Öffnen.

**Returns:**
java.lang.String
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


Ruft einen Wert ab, der angibt, ob die Datei temporär ist.

Wert: `true`, wenn die Datei temporär ist; andernfalls `false`.

**Returns:**
boolean
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


Ruft den Stream‑Container ab.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - the stream container.

Vorsichtig verwenden. Der Stream‑Container muss nach dem Abrufen freigegeben werden.
