---
title: "FileOpenSource"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar en filkälla för öppning."
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.sources/fileopensource/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.Source](../../com.aspose.imaging/source), [com.aspose.imaging.sources.FileSource](../../com.aspose.imaging.sources/filesource)
```
public final class FileOpenSource extends FileSource
```

Representerar en filkälla för öppning.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FileOpenSource(String filePath)](#FileOpenSource-java.lang.String-) | Initierar en ny instans av klassen `FileOpenSource` . |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFilePath()](#getFilePath--) | Hämtar filvägen för att öppna. |
| [isTemporal()](#isTemporal--) | Hämtar ett värde som indikerar om filen kommer att vara temporär. |
| [getStreamContainer()](#getStreamContainer--) | Hämtar strömbehållaren. |
### FileOpenSource(String filePath) {#FileOpenSource-java.lang.String-}
```
public FileOpenSource(String filePath)
```


Initierar en ny instans av klassen `FileOpenSource` .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen att öppna. |

### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Hämtar filvägen för att öppna.

Värde: Filvägen att öppna.

**Returns:**
java.lang.String
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


Hämtar ett värde som indikerar om filen kommer att vara temporär.

Värde: `true` om filen kommer att vara temporär; annars `false`.

**Returns:**
boolean
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


Hämtar strömbehållaren.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - the stream container.

Använd med försiktighet. Du måste avyttra strömbehållaren efter hämtning.
